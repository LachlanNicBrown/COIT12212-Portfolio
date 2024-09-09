Workshop Activities
---
Activity 1: Research online templates for incident response, disaster recovery, and business continuity plans. 

Answer:
There are many resources available of templates for Incident Response (IR), Disaster Recovery (DR), and Business Continuity (BC) Plans. 

One thorough example of an Incident Reponse Plan is the "Cyber Incident Reponse Plan" from the Australian Cyber Security Centre. It provides a full guide on the steps to be taken, the roles that people should step into, and a full breakdown of the entire cyber IR plan. 
- Australian Cyber Security Centre 2024, _Cyber incident response plan_, viewed 3 September 2024, https://www.cyber.gov.au/sites/default/files/2023-03/ACSC%20Cyber%20Incident%20Response%20Plan%20Guidance_A4.pdf

A useful Disaster Recovery Plan is provided by IBM, and breaks down the steps, important considerations, and goals of a disaster recovery plan.
- IBM 2024, _Example: Disaster recovery plan_, viewed 3 September 2024, https://www.ibm.com/docs/en/i/7.5?topic=system-example-disaster-recovery-plan

The Qld Government, via Business Queensland, provides a template document for Business Continuity. It provides a framework for Business Impact Analysis, Recovery, and more. 
- Queensland Government 2023, _Business continuity planning template_, viewed 3 September 2024, https://www.publications.qld.gov.au/dataset/business-continuity-planning-template/resource/63f7d2dc-0f40-4abb-b75f-7e6acfeae8f3

For the case study below, the Incident Response Plan template that will be used is provided by the National Institute of Standards and Technology.
- National Institute of Standards and Technology (NIST) 2021, _NIST SP 800-61, Revision 2, Computer Security Incident Handling Guide_, viewed 4 September 2024, https://www.nist.gov/privacy-framework/nist-sp-800-61

---
Case Study:
Design a brief incident response plan for Koala Health, in response to a virus attack, power failure, fire, employee error, and ISP failure.

Answer:

Virus Attack
| | |
|---|---|
| |Detection and Analysis|
|1.|Determine if a virus is present in any of KH's systems.|
|1.1|Analyse unusual behaviour or alerts from antivirus software.|
|1.2|Cross-check data logs for signs of infection across connected systems (app, telehealth, pathology, pharmacy).|
|1.3|Perform searches in databases or security resources such as NIST for the virus signature.|
|1.4|Begin documenting all actions, evidence, and impacted systems.|
|2.|Prioritise based on the affected systems and patiend data risk.|
|3.|Report to internal IT, Koala Health leadership, and external cybersec consultants if necessary.|
| |Containment, Eradication, and Recovery|
|4.|Secure system logs and affected devices for investigation.|
|5.|Contain the virus by isolating affected systems (e.g. quarantine the telehealth app server).|
|6.|Remove the virus and restore affected systems.|
|6.1|Patch vulnerabilities in the telehealth or other systems.|
|6.2|Eliminate the virus and any left over components.|
|6.3|If more systems are found, repeat detection and containment.|
|7.|Restore system operations.|
|7.1|Return systems to full operation.|
|7.2 |Check all systems work as expected post-restoration.|
|7.3|Set up extra monitoring for future signs of infection.|
| |Post-Incident Activity|
|8.|Write an incident report documenting the attack and resolution.|
|9.|Hold a debrief meeting to gather insights and improve future incident handling.|

Power Failure
| | |
|---|---|
| |Detection and Analysis|
|1.|Identify whether a power failure was the cause of a systems outage.|
|1.1|If possible, access system logs and external evidence (e.g. power company outage notifications).|
|1.2|Check for similar outages across the connected systems.|
|1.3|Research the cause (i.e. is it a planned outage, damage to the power grid, etc.).|
|1.4|Begin documenting all actions, evidence, and impacted systems.|
|2.|Prioritise based on the affected systems and patient care impact.|
|3.|Report to internal IT, Koala Health leadership, facilities management, and power company.|
| |Containment, Eradication, and Recovery|
|4.|Secure uptime logs and evidence related to the power failure's impact.|
|5.|Contain damage by shifting to backup power systems (generator, UPS).|
|6.|Eliminate any technical problems caused by the outage.|
|6.1|Solve power-related vulnerabilities, such as fluctuating or unstable power supplies if possible.|
|6.2|Restore systems taken offline by the outage.|
|6.3|If more systems fail during recovery, repeat backup power options where possible.|
|7.|Recover critical services and systems.|
|7.1|Restore power and return systems to normal operations.|
|7.2 |Check that all systems are functioning normally post-outage.|
|7.3|Implement monitoring to detect and automatically cover for future power risks.|
| |Post-Incident Activity|
|8.|Create a report listing the power failure's effects and recovery steps.|
|9.|Hold a debrief meeting to gather insights and improve future incident handling (e.g. better power backup options).|

Fire
| | |
|---|---|
| |Detection and Analysis|
|1.|Confirm the fire has caused system issues or damage.|
|1.1|Check which systems may be affected by the fire, physical damage, etc.|
|1.2|Cross check system outage with the fire-affected areas.|
|1.3|Research how fire, smoke, or heat affects servers, and other equpiment.|
|1.4|Begin documenting all actions, evidence, and impacted systems.|
|2.|Prioritise based on the affected systems and patient care impact.|
|3.|Report to internal IT, Koala Health leadership, facilities management,fire services.|
| |Containment, Eradication, and Recovery|
|4.|Secure and log evidence of damaged equipment.|
|5.|Contain the impact by shutting down systems at risk of further damage from smoke, etc.|
|6.|Eradicate potential hazards (e.g. smoke or fire damaged equipment).|
|6.1|Identify areas requiring backups or other recovery steps.|
|6.2|Remove damaged equipment and replace critical hardware.|
|6.3|If further systems fail during recovery, repeat detection and containment steps.|
|7.|Recover critical infrastructure and systems.|
|7.1|Restore systems using backup or replacement hardware and date recovery backups.|
|7.2 |Test restored systems for normal functionality.|
|7.3|Implement monitoring to prevent future fire risks and review fire prevention options.|
| |Post-Incident Activity|
|8.|Create a report listing the fire's effects and recovery steps.|
|9.|Hold a debrief meeting to gather insights and improve future incident prevention and handling (e.g. fireproofing or better data backups).|

Employee Error
| | |
|---|---|
| |Detection and Analysis|
|1.|Identify whether an employee error has caused a system issue or data breach.|
|1.1|Check logs, user activity, and reports of unusual system behaviour.|
|1.2|Look for confirming information related to the error (e.g. incorrect data or unauthorised access).|
|1.3|Research the scope and porential impact of the error (e.g. misconfigured settings, incorrect permissions).|
|1.4|Document the incident, detailing the employee action and affected systems.|
|2.|Prioritise based on the severity of the error (e.g. data exposure, service disruption).|
|3.|Report to internal IT, Koala Health leadership, and compliance bodies if sinsitive data was affected.|
| |Containment, Eradication, and Recovery|
|4.|Preserve and document evidence of the error.|
|5.|Contain the error by rolling back improper changes, restricting access to systems, or recalling data.|
|6.|Eradicate any remaining issues caused by the error.|
|6.1|Identify vulnerabilities that allowed the error to occur.|
|6.2|Revert improper configurations and or incorrect data.|
|6.3|If further issues or errors are found, repeat detection and containment steps.|
|7.|Recover systems or data impacted by the employee error.|
|7.1|Restore systems to a functional state.|
|7.2|Verify all systems are operating correctly post recovery.|
|7.3|Implement additional safeguards, such as training or access control.|
| |Post-Incident Activity|
|8.|Create a report listing the error, recovery, and preventative actions taken.|
|9.|Hold a debrief meeting to gather insights and improve future incident prevention and handling.|

ISP Failure
| | |
|---|---|
| |Detection and Analysis|
|1.|Determine if an ISP failure is causing system outages.|
|1.1|Check network connections and issues, including LAN versus WAN connections, network downtime, and network logs.|
|1.2|Check information from different systems to confirm the extent of the network outage.|
|1.3|Contact the ISP for outage reposrts or research other factors that could be affecting the connection.|
|1.4|Document the ISP failure and the impact on affected systems.|
|2.|Prioritise based on the extent of the service disruption (e.g. telehealth consultations, prescription orders).|
|3.|Report to internal IT, Koala Health leadership, and escalate to the ISP for resolution.|
| |Containment, Eradication, and Recovery|
|4.|Preserve evidence of the ISP failure, such as connection logs and ISP comms.|
|5.|Contain the impact by switching to backup internet solutions, such as secondary ISP failovers, or mobile data connections.|
|6.|Eliminate dependancy on, or ensure restoration of ISP connection if possible.|
|6.1|Ensure failover to alternative connection is successful.|
|6.2|Check that critical systems are operating through alternative connections.|
|6.3|If problems continue, repeat detection and containment on alternative connections.|
|7.|Recover services as the ISP resolves the issue.|
|7.1|Restore original connectivity and resume regular operations.|
|7.2|Confirm all systems are fully online after being reconnected.|
|7.3|Implement monitoring to detect future ISP failure and determine if stronger failover options are needed.|
| |Post-Incident Activity|
|8.|Create a report detailing the outage, impact, and recovery actions.|
|9.|Hold a debrief meeting to gather insights and improve future incident prevention and handling.|

National Institute of Standards and Technology (NIST) 2021, _NIST SP 800-61, Revision 2, Computer Security Incident Handling Guide_, viewed 4 September 2024, https://www.nist.gov/privacy-framework/nist-sp-800-61
(https://www.cyber.gov.au/resources-business-and-government/governance-and-user-education/incident-response/cyber-security-incident-response-planning-practitioner-guidance) (Whitman, M. E. & Mattord, J. J., 2018. Management of Information Security. 6th ed, s.l.:Cengage.)
