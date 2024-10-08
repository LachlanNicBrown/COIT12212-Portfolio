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


3. Eradication
   
The process of eradicating the phishing threat from the network has a few steps. First, using email filtering and search-and-destroy tools to remove the identified phishing email from the university's email server and mailbox, preventing further new cases. Again, blacklisting identified senders, domains, etc. Next, using endpoint detection tools and system scans, all systems or the suspectedly contaminated systems should be thoroughly checked for evidence of infection. Any system that is heavily compromised should be wiped and rebuilt, wherever possible. It is also important to continue to monitor the network and the email systems in case of new or different attack vectors, such as continued communicatinos with a C2 server for data exfiltration.

To secure the system further, resetting affected account passwords as mentioned above, and implementing MFA on key logins would be step one. Accounts that were known to be compromised should have their activity reviewd to check if they had accessed unusual or sensitive data during the attack. If a system or device such as a server host was compromised, wiping and restoring from backup would also be advisable.


4. Recovery
   
To restore normal operations, the first step is gradual re-enabling of paused services, such as email servers and the student portal, after their security is confirmed. Then unlocking accounts after eradication and securing, with continued activity monitoring for a time. Next, it's important to communicate with important stakeholders to provide a debrief of the situation - what occured, how it was responded to, and the current situation. Then, communication with the affected users and the wider community if needed to follow up on any actions they may need to take.

To verify that the threat was dealt with, continued monitoring of systems, watching for indicators of compromise. Increasing alert mechanisms on mail servers and the student portal around failed logins. Conducting final malware scans and integrity checks on the system, now that it is back online. Further analysis of logs to ensure no further suspicious activity is present and that blacklists are functioning. Depending on the response from management, an independant security audit may be warranted, or a sustained phishing awareness campaign put in place.


5. Lessons Learned
    
Post-incident, a few steps should happen to review. The Incident Response Team should be gathered and a debriefing and documentation session should cover the timelines, decicions made, tools used, and communications sent. Analysing how the attack was able to start, progress, discovered, and contained over the timeline will help understand the key facts of the incident. Analysing the effectiveness of the response, where slow actions or unsure decicions caused response delays, and what tools and actions worked well, can help streamline the next response. Discovering where there are gaps in konwledge, securities, and tools can then allow actions to be taken to fill those gaps. Finally, getting feedback from all involved is important. The CIRT will have formal technical feedback, but also getting feedback from management and the user-body can help form future communications.

For prevention, the key points to cover would be the enhancement of email filters and anti-phishing tools. These could be a technical preventative for the future. Similarly, phishing simulations and sustained awareness and training for all users are an important social preventative. As was mentioned above, implementing MFA on logins, and a review of access levels for users will help keep important data secure going forward. Finally, better Security Information and Event Management systems could help provide better or quicker analysis and detection of a future incident.

Cichonski, P, et al 2012, _Computer security incident handling guide_, National Institute of Standards and Technology. DOI: 10.6028/NIST.SP.800-61r2

Thompson, E 2018, _Cybersecurity incident response: How to contain, eradicate, and recover from incidents_, Apress, Lisle.

Whitman, M. E. & Mattord, J. J., 2018. _Management of Information Security_. 6th ed, s.l.:Cengage.
