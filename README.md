### HackTheBox Academy  
### Information Gathering - Web Edition  
![Logo](./logo.png)
---  
### WHOIS  
1. Perform a WHOIS lookup against the paypal.com domain. What is the registrant Internet Assigned Numbers Authority (IANA) ID number?  
`292`  
2. What is the admin email contact for the netflix.com domain (also in-scope for the Netflix bug bounty program)?  
`nicadmin@netflix.com`  
---  
### DNS  
1. Which IP address maps to inlanefreight.com?  
`134.209.24.248`  
2. What is the first mailserver returned when querying the MX records for paypal.com?  
`mx1.paypalcorp.com`  
---  
### Active Infrastructure Identification  
1. What Apache version is running on app.inlanefreight.local? (Format: 0.0.0)  
`2.4.41`  
2. Which CMS is used on app.inlanefreight.local? (Format: word)  
`joomla`  
3. On which operating system is the dev.inlanefreight.local webserver running on? (Format: word)  
`ubuntu`  
---  
### Active Subdomain Enumeration  
1. Submit the FQDN of the nameserver for the "inlanefreight.htb" domain as the answer.  
`ns.inlanefreight.htb`  
2.  Identify how many zones exist on the target nameserver. Submit the number of found zones as the answer.  
`2`  
3.  Find and submit the contents of the TXT record as the answer.  
`ZONE_TRANSFER{87o2z3cno7zsoiedznxoi82z3o47xzhoi}`  
4.  What is the FQDN of the IP address 10.10.34.136?  
`ns2.internal.inlanefreight.htb`  
5. What FQDN is assigned to the IP address 10.10.1.5? Submit the FQDN as the answer.  
`dc3.internal.inlanefreight.htb`  
6. Which IP address is assigned to the "us.inlanefreight.htb" subdomain. Submit the IP address as the answer.  
`10.10.200.5`  
7. Submit the number of all "A" records from all zones as the answer.  
`27`  
---  
### Virtual Hosts
1. Enumerate the target and find a vHost that contains flag No. 1. Submit the flag value as your answer (in the format HTB{DATA}).  
`HTB{h8973hrpiusnzjoie7zrou23i4zhmsxi8732zjso}`  
2. Enumerate the target and find a vHost that contains flag No. 2. Submit the flag value as your answer (in the format HTB{DATA}).  
`HTB{u23i4zhmsxi872z3rn98h7nh2sxnbgriusd32zjso}`  
3. Enumerate the target and find a vHost that contains flag No. 3. Submit the flag value as your answer (in the format HTB{DATA}).  
`HTB{Fl4gF0uR_o8763tznb4xou7zhgsniud7gfi734}`  
4. Enumerate the target and find a vHost that contains flag No. 4. Submit the flag value as your answer (in the format HTB{DATA}).  
`HTB{bzghi7tghin2u76x3ghdni62higz7x3s}`  
5. Find the specific vHost that starts with the letter "d" and submit the flag value as your answer (in the format HTB{DATA}).  
`HTB{7zbnr4i3n7zhrxn347zhh3dnrz4dh7zdjfbgn6d}`  
---  
### Information Gathering - Web - Skills Assessment  
1. What is the registrar IANA ID number for the githubapp.com domain?  
`292`  
2. What is the last mailserver returned when querying the MX records for githubapp.com?  
`aspmx5.googlemail.com`  
3. Perform active infrastructure identification against the host https://i.imgur.com. What server name is returned for the host?  
`cat factory 1.0`  
4. Perform subdomain enumeration against the target githubapp.com. Which subdomain has the word 'triage' in the name?  
`data-triage-reports.githubapp.com`  