1.	What MITRE ATT&CK tactic was used for initial access?   
A: T1566  
Explanation: Similar to Skyilne, this one was also started by phishing. Examining the Windows Exchange logs again would show another phishing attempt, and these logs hold the answers shown below.

2.	What e-mail addresses was the e-mail sent to? Your answer should be in alphabetical order and comma separated with no spaces. For example: bob@domain.comjane@domain.com,joe@domain.com  
A: allen_justice@cecilio.local,galen_wilkinson@cecilio.local,jeffry_diaz@cecilio.local,reid_hopper@cecilio.local,roberto_beck@cecilio.local  

3.	What is the best match for the MITRE ATT&CK tactic that was used for Execution?  
A: T1204  
Explanation: Based off the inject and finding who executed the file, you have to find the best fitting MITRE ATT&CK tactic. This is T1218.005, formerly known as 1204.

4.	Who actually clicked the e-mail?  
A: galen_wilkinson  
Explanation: Seeing who went to the same site either using the domain (or similar) in the exchange logs, or finding the malicious IP in the log and seeing who accessed it. Once upon finding the hostname/IP of the workstation, you could use the windows logs to find this hostname, and what user was using it.

5. What is the malicious hostname used for this attack?  
A: hackkerrank.com  

6. What web Browser was used to access hackkerrank.com?  
A: Microsoft Edge  
Explanation: For this one, you'd need to find the packet in wireshark. For this, you can do ip.dst == 34.70.11.100 (IP found through the exchange logs). From there, you can see 10.0.2.3 (galen) connecting to the IP. Grab the user agent which is Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/86.0.4240.80 Safari/537.36 Edg/86.0.622.43. Throwing this into google shows you this is most likely Microsoft Edge.  

7.	What MITRE ATT&CK tactic was used for Defense Evasion?  
A. T1078 | T1218  
Explanation: Again, this ends up in the download and execution of a HTA from the malicious website.

8.	What MITRE ATT&CK tactic was used for Discovery? 
A. T1046  
Explanation: Another nmap occurs, so same discovery as Skyline.

9.	What MITRE ATT&CK tactic was used for Collection?  
A: T1041  
Explanation: All exfil happens again through the C&C.

10. What is the file downloaded from the malicious hostname? Additionally, this file resulted in another file being created. What is the full path for these two files? Answer format: C:\Location\To\File1,C:\Location\To\File2  
A: C:\Users\galen_wilkinson\Downloads\update.zip,C:\Users\galen_wilkinson\Downloads\update\update.hta  
Explanation: This can be found through the windows logs if you're able to find the first file (either of them), and tracing either way (to find what resulted in the .hta if you first had the zip, or other way around).

11.	What is the full path for the file that was dropped on the victims box?  
A. C:\Users\galen_wilkinson\Downloads\update (1)\SharpHound.exe    
Explanation: This can be found through going down the event logs a bit further after the update.hta

12.	What box was targeted for collection? 
A. 10.0.2.2  
Explanation: We previously identified that 10.0.2.3 is the victim computer, and we can start seeing some traffic over SMB2 between 10.0.2.3 and 10.0.2.2. This makes sense since SharpHound is used for AD enumeration.

13.	What information was collected?  
A. Active Directory, Active Directory dump, or Active Directory Enumeration. Answer should be 2-3 words    
Explanation: This come from the same explanation above. 

14.	What ports were scanned by the attacker?  
A: 21,69  
Explanation: This can be a bit confusing as there are multiple nmap scans that occur, but you have to find the correct one for this chain. To find this, you could do a filter in wireshark for tcp.port == 21 (or another commonly scanned port), and find it. Alternatively, you could look for SYNs or RSTs. Note that the 69 is a hint for a later answer.

15.	What MITRE ATT&CK tactic was used for Command and Control?  
A. T1573  

16.	What MITRE ATT&CK tactic was used for Exfiltration?  
A. T1041 
Explanation: The initial data is exfilled over the C2 network (80), therefore T1041 is the answer.

17.	When the attacker was done with Sharphound, the results were stored in a file. What is this file? Provide the full path.  
A.	C:\Users\galen_wilkinson\Downloads\update (1)\20201021034256_BloodHound.zip  
Explanation: This can be traced through the windows event logs

18. What time was the Sharphound results exfilled back to the attacker? Provide the time in UTC in format: MM/DD/YYYY HH:MM
A: 10/21/2020 03:43   

19.	What protocol was used to exfil the Bloodhound file?  
A: 80  

 ~~20. Was another file exfilled?~~

 ~~A: Yes | True~~

21. You correctly identified another file was exfilled - but how was it collected? Provide the MITRE ATT&CK Tactic number, including subtechnique
A: T1074.002  
Explanation: Overall, the goal here is to realize another file was exfilled over TFTP, then trace down everythign regarding this. This can be found through the windows event logs & pcap

22. What protocol was used for staging the data?  
A: tftp  

23. What was the source port and destination port used to exfiltrate the additional data? (format src:#####,dst:######)  
a.src:56223,dst:45850  
Explanation: This is specifically looking for the data packet in TFTP. So you'll need to look at UDP conversations between 20.0.4.2 and 10.0.2.242, go to the data packet and find the ports.

24. From which host was the file exfiltrated?  
A: 10.0.2.242

25.	What was the name of the file that was exfiltrated?  
A: Super_important_Docs.zip  
Explanation: This can be found through wireshark -> export -> tftp

26. What file is inside Super_important_Docs.zip?  
A: Super_Secret_Password.txt  
Explanation: The zip is password protected, Use john2zip to break it (see password below), and find the file.

27.	What was the password on the zip file?  
 a. 7rXxB$  

28. What is the MD5 of the Super_Secret_Password.txt?  
A: 2e0c429197825787e0565ed2b5cebf2b

29. What APT was responsible for this attack?  
A: APT MimiSec  
1. Explanation: This requires looking at the intel documents, process of elimination will help you here.

- APT EAGLE EYE is most likely not the APT - there is no evidence of RDP connections being used in the network, and a malicious office document, or an executable disguised as a document was not found in this chain.
- APT SKYSABER is most likely not the APT - there was no evidence of use of LaZanga, Mimikatz, or ProcDump. Additionally, there is no proof that a scheduled task was created to execute a .vbe file.
- APT HAMMERFALL is most likely not the APT. This attack chain relied on spearphishing and user execution, rather than a system being vulnerable to MS17-010. Additionally, no extra payload were downloaded other than the initial HTA.
- APT HAUNTEDHOUSE is most likely not the APT - while we do not know the nation of this attack and we do see evidence of powershell, there is no proof of AdFind.exe being used. Additionally, powershell was not used to download anymore malware - instead, this attack chain relied on the user to download & execute the HTA.
- APT Mimisec IS the answer. A database was targeted (the mysql database), and user interaction was utilized rather than the exploitation of existing software.

30. BONUS: Sharphound created an additional file - what is the extension of this file? (.bin)  
A: .bin | bin  
Explanation: Dig through the windows logs a bit more between sharphound and the bloodhound events, and you can find a .bin that originally may seem suspicious. 

31. What is the purpose of this file? Answer is one word.  
HINT: https://blog.cptjesus.com/posts/newbloodhoundingestor  
A: Cache | Caching  
Explanation: As per the hint's blog, this .bin file shows that caching was done when executing Sharphound, and can be another artifact to show it was ran (although there is an option to turn off caching).