1.	What MITRE ATT&CK tactic was used for initial access?  
A: T1566
Explanation:
- Go to the Exchange logs
- Find the email from CNN
- Grab the malicious IP and filter for it in Wireshark
- Go down and see that 10.0.2.3 reached out to the same malicious IP, going to cnnn.com
- See that 10.0.2.3 then downloaded edge_update.hta
- All of this shows that Spearphishing succeeded, and helps explain how to find some of the following questions.

2.  What was the subject of the e-mail?  
A: Election Cycle! (ELECTION CYCLE also valid)

3.  Who was the sender of the email?  
A: cnn_news_team@cnn.com

4.	What e-mail addresses was the e-mail sent to? Your answer should be in alphabetical order and comma separated with no spaces. For example: bob@domain.com,jane@domain.com,joe@domain.com  
A: allen_justice@cecilio.local,galen_wilkinson@cecilio.local,jeffry_diaz@cecilio.local,reid_hopper@cecilio.local,roberto_beck@cecilio.local  

5.  Was the e-mail successful in phishing someone If so, what was the domain that was visited by the user? Answer should be in the format: google.com. If you think it was unsuccessful, put in the answer: NA  
A: cnnn.com

6.  You successfully identified that someone at least clicked the link in the phishing e-mail. However, the e-mail was from cnn.com, and the domain was cnnn.com. This is typically done to circumvent people's phishing training by making it look so similar. What is this technique known as? Alternatively, put in the MITRE ATT&CK technique number (TXXXX)  
A: typosquatting | URL Hijacking | T1328 | 1328 | Buy Domain Name  
Explanation: The malicious domain was cnnn.com, an off by one domain to help trick people that it is a legitimate site, and also to get people who typo the domain.  

7.  Did the user download a file from cnnn.com? If so, what is the file name? Otherwise, answer: N/A  
A: edge_update.hta

8.  What is the IP address and hostname of the box that was compromised? Answer format: IP,hostname   
A: 10.0.2.3,WIN10-FIN-001.cecilio.local

9.	 Based off the intel report just provided, and that a computer interacted with the website cnnn.com, which user actually clicked the e-mail?  
	A: allen_justice  
Explanation: The intel provided a hint that HTAs should be searched for, and only one user downloaded edge_update.hta. This user was allen_justice.

10.  What is the best match for the MITRE ATT&CK tactic that was used for Execution?  
	A: T1204  
Explanation: Based off the inject and finding who executed the file, you have to find the best fitting MITRE ATT&CK tactic. This is T1218.005, formerly known as 1204.  

11.	What MITRE ATT&CK tactic was used for Discovery? 
A: T1046  
Explanation: This requires searching a bit, and finding evidence of a nmap scan. Remember this can be seen with SYNs being sntn with no response, or SYN then RST / RST,ACK. Once you find evidence of a nmap scan, then you find the matching technique, which is T1046.

12.	What ports were scanned? List the ports in ascending order separated by commas with no spaces.  
A: 21,22,139,445,3306  
Explanation: This can be a bit confusing as there are multiple nmap scans that occur, but you have to find the correct one for this chain. To find this, you could do a filter in wireshark for tcp.port == 22 (or another commonly scanned port), and find it. Alternatively, you could look for SYNs or RSTs. To find this answer, do ip.src == 10.0.4.2, and analyze the first scan.

13.	What MITRE ATT&CK tactic was used for Collection?   
A: T1005
Explanation: This one is a bit complicated to realize until you further inspect what happened. Please see the answers below - but note this MITRE tactic best fits what occurs.

14.	In order to collect the data the attacker was interested in, they dropped a file onto Allen's box. What is the name of the file, providing the full path? 
A: C:\Users\allen_justice\Downloads\mysql-shell-8.0.21-windows-x86-64bit\mysql-shell-8.0.21-windows-x86-64bit\bin\mysqlsh.exe  
Explanation: You would need to inspect the windows logs provided in the large CSV, and look at allen's box (who was earlier identified as the victim). You will randomly see a mysql client on the box - which is a hint that something strange is going on. Grabbing this exe is the answer.

15. What was the parent process of the executable?  
A: powershell.exe  
Explanation: Look at the CSV of the logs and notice how mysqlsh.exe is executed, with powershell as the parent. This answers the question, and helps solidify this is probably unusual.

16.	What MITRE ATT&CK tactic was used for Command and Control?  
A: T1573  
Explanation: All C&C occurs over 443, therefore fitting this tactic.

17.	What MITRE ATT&CK tactic was used for Exfiltration?  
A: T1041  
Explanation: All exfil occurred over the same C&C, and we are unable to see what happens due to it being encrypted. This technique best fits.

18.	What port was used for Command and Control and Exfiltration?  
A: 443  
Explanation: Look for ip.src == 10.0.2.3 && tcp.port == 443.

19.	What was the name of the file that was likely exfiltrated?  
A: db_dump.db  
Explanation: Again, this requires some logic due to the answer not being directly in the windows logs, and the C&C channel being encrypted. However, you can see through the mysql client, some enumeration occurred and then a dump to this file. This was most likely done by the attacker, and was most likely taken back. 

20. What APT was responsible for this attack?  
A: APT MimiSec  
Explanation: This requires looking at the intel documents, process of elimination will help you here.
- APT EAGLE EYE is most likely not the APT - there is no evidence of RDP connections being used in the network, and a malicious office document, or an executable disguised as a document was not found in this chain.
- APT SKYSABER is most likely not the APT - there was no evidence of use of LaZanga, Mimikatz, or ProcDump. Additionally, there is no proof that a scheduled task was created to execute a .vbe file.
- APT HAMMERFALL is most likely not the APT. This attack chain relied on spearphishing and user execution, rather than a system being vulnerable to MS17-010. Additionally, no extra payload were downloaded other than the initial HTA. 
- APT HAUNTEDHOUSE is most likely not the APT - while we do not know the nation of this attack and we do see evidence of powershell, there is no proof of AdFind.exe being used. Additionally, powershell was not used to download anymore malware - instead, this attack chain relied on the user to download & execute the HTA.
- APT Mimisec IS the answer. A database was targeted (the mysql database), and user interaction was utilized rather than the exploitation of existing software. 

21. What is the IP of the sql database?  
A: 10.0.2.7  
Explanation: All of the following MYSQL questions can be answered via the windows logs, and the command line parameters used to connect to the mysql server.

22. What is the name of the database that was accessed?  
  A: crm

23. What was the query used to dump the table accessed?  
A: select * from customers

24. How many customer accounts were compromised during the attack?  
A: 1000

25. What encryption algorithm are the customer's passwords stored in?  
A: MD5 Crypt | MD5  
Explanation: When the SQL dump occurs, you can see the hashed passwords. It'll start with $1$, which indicates MD5 was utilized.

26. What was the username that accessed the mysql database?  
A: root  

27. What was the password used for the account?  
A: P@ssw0rd

