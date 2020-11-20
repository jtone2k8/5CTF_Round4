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

4.	What e-mail addresses was the e-mail sent to? Your answer should be in alphabetical order and comma separated with no spaces. For example: bob@domain.com,jane@domain.com,joe@domain.com (validated)
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
Explanation: The intel provided a hint that HTAs should be searched for, and only one user downloaded edge_update.hta. This user was allen_justice

10.  What is the best match for the MITRE ATT&CK tactic that was used for Execution?
	A: T1204
Explanation: Based off the inject and finding who executed the file, you have to find the best fitting MITRE ATT&CK tactic. This is T1218.005, formerly known as 1204.

11.	What MITRE ATT&CK tactic was used for Discovery? 
A: T1046 
Explanation: This requires searching a bit, and finding evidence of a nmap scan. 
12.	What ports were scanned? List the ports in ascending order separated by commas with no spaces. (Validated)
	Prereq: #10
	A: 22,139,445,3306
13.	What MITRE ATT&CK tactic was used for Collection? (Validate)
	Prereq: #11-12
	A: T1005
14.	In order to collect the data the attacker was interested in, they dropped a file onto Allen's box. What is the name of the file, providing the full path? (Validated)
	Prereq: #13
	A: C:\Users\allen_justice\Downloads\mysql-shell-8.0.21-windows-x86-64bit\mysql-shell-8.0.21-windows-x86-64bit\bin\mysqlsh.exe
15. What was the parent process of the executable?
	Prereq: #14
	A: powershell.exe
16.	What MITRE ATT&CK tactic was used for Command and Control? (Validated)
	Prereq: #15
	T1573
17.	What MITRE ATT&CK tactic was used for Exfiltration? (Validated)
	Prereq: #16
	T1041
18.	What port was used for Command and Control and Exfiltration? (Validated)
	Prereq: #16
	A: 443
19.	What was the name of the file that was likely exfiltrated?  
	Prereq: #17-18
	A: db_dump.db
20. What APT was responsible for this attack?
	Prereq: #19
	A: APT MimiSec
~SQL QUESTIONS~
21. What is the IP of the sql database? (Validated)
	Prereq: #19
	A: 10.0.2.7
22. What is the name of the database that was accessed? (Validated)
	Prereq: #21
	A: crm
23. What was the query used to dump the table accessed? (Validated)
	Prereq: #22
	A: select * from customers
24. How many customer accounts were compromised during the attack? (Validated)
	Prereq: #23
	A: 1000
25. What encryption algorithim are the customer's passwords stored in? (Validated)
	Prereq: #24
	A: MD5 Crypt | MD5
26. What was the username that accessed the mysql database? (Validated)
	Prereq: #22
	A: root
27. What was the password used for the account? (Validated)
	Prereq: #22
	A: P@ssw0rd

