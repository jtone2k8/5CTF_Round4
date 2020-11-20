1.	What MITRE ATT&CK tactic was used for initial access? 
	A: T1566
2.	What e-mail addresses was the e-mail sent to? Your answer should be in alphabetical order and comma separated with no spaces. For example: bob@domain.comjane@domain.com,joe@domain.com
    Prereq: #1
	A: allen_justice@cecilio.local,galen_wilkinson@cecilio.local,jeffry_diaz@cecilio.local,reid_hopper@cecilio.local,roberto_beck@cecilio.local
3.	What is the best match for the MITRE ATT&CK tactic that was used for Execution?
    Prereq: #1
	A: T1204
4.	Who actually clicked the e-mail?
    Prereq: #3
    A: galen_wilkinson
5. What is the malicious hostname used for this attack?
    Prereq: #4
	A: hackkerrank.com
6. What web Browser was used to access hackkerrank.com?
    Prereq: #5
	A: Microsoft Edge
7.	What MITRE ATT&CK tactic was used for Defense Evasion?
    Prereq: #6
	T1078 | T1218
8.	What MITRE ATT&CK tactic was used for Discovery? 
    Prereq: #6  
    a.	T1046 
9.	What MITRE ATT&CK tactic was used for Collection?
    Prereq: #6
    a.	A: T1041
10. What is the file downloaded from the malicious hostname? Additionally, this file resulted in another file being created. What is the full path for these two files? Answer format: C:\Location\To\File1,C:\Location\To\File2 
    Prereq: #7-9
	A: C:\Users\galen_wilkinson\Downloads\update.zip,C:\Users\galen_wilkinson\Downloads\update\update.hta
11.	What is the full path for the file that was dropped on the victims box?
    Prereq: #10
    a.	C:\Users\galen_wilkinson\Downloads\update (1)\SharpHound.exe    
12.	What box was targeted for collection? 
    Prereq: #11
    a.	10.0.2.2
13.	What information was collected?
    Prereq: #12
    a.	Active Directory, Active Directory dump, or Active Directory Enumeration. Answer should be 2-3 words    
    Hint: You probably won't see proof of this in the logs, instead research the tools used by the attacker.
14.	What ports were scanned by the attacker? 
    Prereq: #7-9
    a.	21,69
15.	What MITRE ATT&CK tactic was used for Command and Control?
    Prereq: #13, 14
    a.	T1573
16.	What MITRE ATT&CK tactic was used for Exfiltration?
    Prereq: #16
    a.	T1011
17.	When the attacker was done with Sharphound, the results were stored in a file. What is this file? Provide the full path.
    Prereq: #13
    a.	C:\Users\galen_wilkinson\Downloads\update (1)\20201021034256_BloodHound.zip
18. What time was the Sharphound results exfilled back to the attacker? Provide the time in UTC in format: MM/DD/YYYY HH:MM
    Prereq: #17
	A: 10/21/2020 03:43
19.	What protocol was used to exfil the Bloodhound file?
    Prereq: #18
		A: 80
20. Was another file exfilled?
    Prereq: #19
	A: Yes | True
21. You correctly identified another file was exfilled - but how was it collected? Provide the MITRE ATT&CK Tactic number, including subtechnique
    Prereq: #20
	A: T1074.002
22. What protocol was used for staging the data?
    Prereq: #21
	A: tftp
23. What was the source port and destination port used to exfiltrate the additional data? (format src:#####,dst:######)
    Prereq: #22
    a.	src:56223,dst:45850
24. From which host was the file exfiltrated?
    Prereq: #23
	A: 10.0.2.242
25.	What was the name of the file that was exfiltrated? 
    Prereq: #24
	A: Super_important_Docs.zip
26. What file is inside Super_important_Docs.zip?
    Prereq: #25
	A: Super_Secret_Password.txt
27.	What was the password on the zip file? 
    Prereq: #26
    a.	7rXxB$
28. What is the MD5 of the Super_Secret_Password.txt?
    Prereq: #27
	A: 2e0c429197825787e0565ed2b5cebf2b
29. What APT was responsible for this attack?
    Prereq: #28
    A: APT MimiSec
30. BONUS: Sharphound created an additional file - what is the extension of this file? (.bin)
    Prereq: #29
		A: .bin | bin
31. What is the purpose of this file? Answer is one word.
    Prereq: 30
	HINT: https://blog.cptjesus.com/posts/newbloodhoundingestor (Take half points for this)
	A: Cache | Caching