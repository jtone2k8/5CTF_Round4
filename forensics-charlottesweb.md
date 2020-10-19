>>>
1. What is the domain of the local network?

![image](uploads/6bfeba79071afdc53e8df8d295f526bf/image.png)

flag: PASCALPIG
>>>
2. What is the name of the Domain Controller?

![image](uploads/4dcee6f86fd16b1cb6c9baa76dbc1f33/image.png)

flag: pascalpig-dc
>>>
3. What was the computer name of the client that got infected?

![image](uploads/18f77d95d0771da422ca595d1026c1a2/image.png)

flag: DESKTOP-M1JC4XX
>>>
4. What is the sha1 hash of the downloaded executable?

![image](uploads/fb099c526617c2ee02f701302a0ecdfb/image.png)

![image](uploads/b351f1e70e68c1830f3bdf18e7d92727/image.png)

flag: 1e4b7d7868d25071db67da87392fd5dafab344a9fa6dc040f7afb0699152fc13
>>>
5. What IP was this downloaded from?

![image](uploads/a6ce8d83d707ebf35b0eaae5de8b277b/image.png)

flag: 198.12.66.108
>>>
6. This executable is malicious, what is the name of the malware given to it by AegisLab?

![image](uploads/b133d0d167be287f7b93d4e91561a12a/image.png)

flag: Trojan.MSIL.Agensla.i!c
>>>
7. What is the Digicert Thumbprint of the Executable?

![image](uploads/e2915b1025dfe01ce91782a19c57d535/image.png)

![image](uploads/c2da860efd755d196722ba48bc3a8416/image.png)

flag: 3BA63A6E4841355772DEBEF9CDCF4D5AF353A297
>>>
8. What is the Pastebin like domain that was contacted? (subdomain.domain.tld)

![image](uploads/32ee30f011c5721bcd565d0bcb6796c2/image.png)

flag: paste.nrecom.net
>>>
9. Data was being exfiltrated from the network. What Protocol was being used?

![image](uploads/1cd467cd9e70647276839bec4baf7b4a/image.png)

flag: SMTP
>>>
10. What user account was compromised?

![image](uploads/15b5190bce33754ae4ea3e14aa7748f5/image.png)

flag: ronaldo.paccione
>>>
11. what email was the exfiltrated data being sent to?

![image](uploads/f4a45134840c03541f3424fbe6f2841d/image.png)

flag: joj@big3.icu
>>>
12. What password was used to send the data?

![image](uploads/5d373cc27ae79e7f4cab6967544c937b/image.png)

![image](uploads/df27f41b48306e9d9a04b5dd57f365fa/image.png)

![image](uploads/70a3e0c237cab12af08d4e347fe3d4b2/image.png)

flag: 5ySP+R071(){#DV9Iu
>>>
13. How may emails were sent out of the network to jojo@big3.icu?

![image](uploads/5049cfe9b5ee961506c3b8e8cbc5f4c0/image.png)

flag: 5
>>>
14. In the emails that were exfiltrated, there was a file that contained passwords. What was the password for ronaldo.paccione@outlook.com?

![image](uploads/b0e75713da4e445fbdbf3b38c38f1e68/image.png)

flag: P@ssw0rd987654e21$
>>>
15. There were some screenshots taken from the computer also. What is the desktop a picture of?

![image](uploads/910486438c37f257f72f3b280fd4b2ea/image.png)

flag: spiderweb
Pick either of the SC_ files and base64 decode and open the jfif file.
>>>
16. The Trojan also captured keystrokes. What was the password for AOL?

![image](uploads/afde33f31d7f02e9516d1caf2e6821f8/image.png)

![image](uploads/20c3099376cce32b5cb23bc4d30bd364/image.png)

flag: dkk3jjfh5hjkd!!!!!
>>>
17. We know that PW_ was for passwords; SC_ was for screenshots; KL_ was for a keylogger. What does the CO_ file represent?

You b64 decode the CO_file to find a .zip

![image](uploads/3c7b6e1d6e6d89f52ba6d2caf6292dce/image.png)

![image](uploads/954ee5e5d0143a1cd03d2862faa2ba57/image.png)

![image](uploads/bfea800c277ae84f119341af4050ae35/image.png)

![image](uploads/c9e69477ef5264ece888b4cf9ac89667/image.png)

![image](uploads/179600ce4a757264c24a76a600c45085/image.png)

![image](uploads/955d612b534d43ae129626ea84b61c58/image.png)

flag: cookies
>>>