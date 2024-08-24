Workshop Activities
---
Scenario: Phishing Attack on CQ University Network

Answer:

1. Identification
  There are a few important indicators to watch out for in this sort of situation. Unusual login patterns, such as unexpected IP addresses, multiple failed login attempts, and successful logins from unexpected locations can all point to suspicious activity. Then, monitoring reports from users around sucpicous emails, being unexpectedly locked out, and unplanned system outages can all help to understand the scope of the attack and any breaches.
  A number of logs and data sources could help determine the scope of the breach. Email server logs can help discover how many users received the phishing email/s and who interacted with them. Web server logs could show a period of sustained failed login attempts. Then, analysing firewall logs, endpoint security logs, and general network traffic may be able to identify data exfiltration, malware or unauthorised software on the system, or connections to know malicious IP addresses or phishing campaign domains.

2. Containment
   There are a number of important steps to take as soon as possible to contain the attack. First, communicating with the rest of the incident response team quickly will get a containment reaction off the ground as quickly as possible. Next, identifying compromised accounts and active sessions of suspicous accounts and immediately locking or disabling their activity will help slow continued access. Then, identifying and blocking IP addresses and domains known to be related to the phishing emails and related activity with firewall rules and DNS filtering should reduce future attacks from that source. If particular devices, such as servers or workstations are found to be compromised, it's important to quarantine them from the network to stop the spread of any malware, etc. If the extent of the incident is still unknown or quite large, temporarily suspending email services might be necessary until all problematic emails can be found and deleted.
    Immediately locking known affected accounts, and resetting compromised passwords would be step one in isolating the issue. Implementing a form of 2FA would add another security layer for the future. If equipment is suspected or found to be compromised, air-gapping at first, and perhaps segmenting on a different VLAN until certain, would prevet the spread of any installed malware. It's also important to communicate with affected users to ensure they are all understanding of why they may be locked out temporarily.

4. Eradication

5. Recovery

6. Lessons Learned
