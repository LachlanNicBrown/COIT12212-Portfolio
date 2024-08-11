Workshop Activities
---
Activity 1: Create a table of the top five biggest cyber events in the last five years by searching on informationisbeautiful.net.

Answer:

| Incident Name and Year | Brief Event Story | Impact | Type of Atack |
|------------------------|-------------------|--------|---------------|
| Indonesian SIM Cards - 2022 | Approximately 1.3 billion SIM card registrations (including ID numbers, phone numbers, and more) were obtained in a breach of the various Governmental bodies. The Indonesian government has a history of poor coordination and security around citizen's data. | 1.3 billion SIM card registrations  | Hacking of "patchwork [...] data security". Vector unknown. |
| Shanghai Police - 2022 | A database containing ~1 billion entries for home address, ID numbers, and more were obtained with leaked credentials to a police server. | ~1 billion entries of a police database | Breach via leaked credentials and a "bug in an Elastic Search deployment". |
| Ticketmaster - 2024 | Approximately 560 million database entries containing names, addresses, partial credit card data, and more was obtained in a breach of Ticketmaster's owner Live Nation. Cloud service provider Snowflake was reported to have noticed an increase in threat activity targeting some of it's customers, such as Ticketmaster. | 560 million entries of customer information | Hacking of a cloud-based database. Vector unknown. |
| Facebook - 2021 | Approximately 530 million users' names, emails, addresses, etc. were released on a forum. The data was several years old and was from previously scraped information prior to a vulnerability patch in 2019. | 530 million entries of older user data, which could be used for phishing or social manipulation | Misuse of bots to scrape data due to an unknown vulnerability. |
| Syniverse - 2021 | An unknown amount, but possibly around 500 million users with breached call/SMS data over a period of years due to unauthorised access to an internal database/transfer environment of mobile exchange company Syniverse. Call records, user locations, and text message content could have been accessed. | Estimates of around 500 million users having their call/text data breached over a period of 5 years. | Hacking of a system that allowed access to the company's data transfer environment, without discovery over approx. 5 years. |

---
Activity 2: Research the following topics and write one paragraph about each:
- Threat Intelligence
- STIX and TAXII

Answer:
Threat intelligence is the collection, investigation, and sharing of information about current cyber threats. Understanding the tactics, techniques, vectors, etc of threat actors, the vulnerabilities in systems and the potential impacts that these vulnerabilities could have if exploited. By using the information gained and examined from threat intelligence, organisations can harden and proactively respond to attacks, or mitigate them altogether. (https://www.crowdstrike.com/cybersecurity-101/threat-intelligence/)

Structured Threat Information eXpression (STIX) and Trusted Automated eXchange of Indicator Information (TAXII) are frameworks designed to improve the shareing of cyber threat intelligence. STIX acts as a common language for cyber threat information, which allows for easier and standardised descriptions of threat actors, attack types, and other data. TAXII includes the secure and automated exchange of this data to and from different enities. (https://www.cloudflare.com/learning/security/what-is-stix-and-taxii/)

---
Activity 3: Understand what a threat model is by reading the provided article. Describe any three threat models and give an example of each.

Answer:
The threat model STRIDE was originally developed by Microsoft and helps categorise and identify potential threats. The acronym stands for:
- Spoofing: Pretending to be something or someone else to gain unauthorised access to a resource.
- Tampering: maliciously altering data or code.
- Repudiation: denying an action or transaction to escape discovery or accountability.
- Information Disclosure: leaking information to unauthorised sources.
- Denial of Service: disrupting the availability of services to legitimate users.
- Elevation of Privilege: gaining higher privileges than those orignially granted, gaining unauthorised access.
For example, in an online bank system, a spoofing threat might involve an attacker impersonating a user with social engineering and phishing to gain access to their account. A tampering threat could involve data being altered mid-transaction by an attacker to redirect funds to a different account. (https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-threats)

PnG (Persona Non Grata) is a model that identifies and manages potential attackers or unwanted entities to a digital system. This concept can be used to highlight and reduce risks associated with particular types or classes of people or entities, for example internal threat actors, or external foreign agencies. By categorising and describing these entities as PnG, security measures can be put in place in advance.
A specific example could be a previous disgrunteled internal staff member who had elevated access - the PnG profile could describe their internal access and knowledge, what credentials they had that should be changed, accounts that should be disabled, and potential threats they could pose in the future. (https://www.cisco.com/c/en/us/products/security/what-is-threat-modeling.html#~how-threat-modeling-works)

Security Cards are a physical and novel approach to discussing and identifying threats. Acting more as a brainstorming technique, security cards can be a deck of cards with each card representing a different type of threat or vector, which can be drawn and discussed with security teams and other stakeholders.
For example, a security card deck could contain cards that descrbe the impacts of a threat, the motivations behind carrying out an attack, the resources available to attackers, and the vectors that attackers may use.

---
Activity 4: Describe the following concepts in one paragraph each:
- Cyber Kill Chain
- MITRE ATT&CK

Answer:
The cyber kill chain is a framework designed by Lockheed MArtin to understand and defend against cyber threats by describing the stages of a cyber attack. There are seven steps: recon, weaponisation, delivery, exploitation, instalation, command and control, and actions on objectives. These stages represent a step in an attack's proccess, starting with gathering information about a system, implementing an exploit or social manipulation, to executing the goal of the attack. These stages can help break down and understand an attack and can help detect, prevent, or stop parts of the chain. (https://www.crowdstrike.com/cybersecurity-101/cyber-kill-chain/)

MITRE ATT&CK (Adversarial Tactics, Techniques, and Common Knowledge) is a framework that extensively lists tactics, techniques, and proceedures (TTPs) used by threat actors. It is available globally and is organised into different tactics and techniques broken down across different stages of a potential attack. MITRE ATT&CK can be used to keep up to date with current threat detection and incident response, and in assessing the security of systems. (https://www.crowdstrike.com/cybersecurity-101/mitre-attack-framework/)

