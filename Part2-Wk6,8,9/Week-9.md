Workshop Activities
---
Readings:
1.	https://www.cyber.gov.au/publications/cloud-computing-security-for-cloud-service-providers
2.	https://www.cyber.gov.au/publications/cloud-computing-security-for-tenants

Activity 1: Assuming KH has moved all their systems to the cloud, identify the relevant cybersecurity risk and mitigation techiniques required.

Answer:

Using the framework found in the Australian Signals Directorate's "Cloud Computing Security for Tenants", the following list of relevant risks and mitigations were developed.

|Risk|Reference|Mitigation|
|---|---|---|
|Overarching failure to maintain the confidentiality, integrity, and availability of patient data|1- General|Use a cloud service that is assessed by an assessor every 24 months, addressing mitigations in the Cloud Computing Security publication. Ensure senior management directs security activities. Test KH's incident response plan annually, covering patient data breaches.|
|Compromise of patient data during transit by malicious actors|4 - General|Use strong TLS/IPsec encryption for securing patient data, such as appointment booking, video consultations, and the transmition of test results.|
|Cloud service credentials (e.g. doctor's access details) compromised by a malicious third party|6 - General|Enforce multi-factor authentication for KH staff accessing patient data or systems. Avoid exposing sensitive passwords and API keys for telehealth pathology, and pharmacy services.|
|Patient data compromised by malicious cloud service provider (CSP) staff|9 - General|Regularly review access logs from KH cloud based systems to detect any suspicious activity or unauthorised access.|
|Data compromised by another tenant|11 - General|Use the cloud provider's multi-tenancy controls to ensure medical records, test results, etc are isolated from other tenants.|
|Patient data unavailable due to corruption, deletion, or cloud service termination|12 - General|Perform encrypted backups of current patient medical records, and store them securely at a secondary cloud service.|
|Cloud service unavailable due to CSP error or unplanned outage|15 - General|Ensure KH selects a cloud provider with high availabilit guarantees and implement a backup plan to access telehealth and medical records during outages.|
|System unavailable due to network connectivity issues|14 - General|Ensure reliable, high-speed internet access for KH staff to maintain smooth telehealth appointments and remote pathology operations. Consider investing in a secondary fail-over network connection.|
|Tenant's VMs are compromised by a malicious third party|1 - IaaS|Secure KH virtual machines with firewalls, intrusion detection, and regular updates to protect patient health data and KH records, and prevent unauthorised access to the system.|
|KH systems compromised by malware or other vulnerabilities in SaaS applications|1 - SaaS|Encrypt all sensitive health information stored in cloud-based telehealth, pathology and pharmacy systems to protect patient data even if the SaaS platform is compromised.|
|Cloud service unavailable due to geniune spike in demand or denial of service|2 - SaaS|Implement DDoS mitigation and use scalable resources to ensure uninterupted services during peak periods.|
|Financial consequences of genuine spike in demand or bandwidth/CPU DDos attack|17 - General|Monitor cloud usage and set reasonable spending limits for telehealth and pathology systems to avoid unexpected costs from spikes in demand or DDoS attacks.|

Australian Signals Directorate 2024, _Cloud computing secrity for tenants_, viewed 9 September 2024, https://www.cyber.gov.au/resources-business-and-government/maintaining-devices-and-systems/cloud-security-guidance/cloud-computing-security-tenants/

Whitman, M. E. & Mattord, J. J., 2018. Management of Information Security. 6th ed, s.l.:Cengage.
