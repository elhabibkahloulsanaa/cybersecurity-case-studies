# cybersecurity-case-studies

# Cisco Networking Academy – CyberOps Associate

# Author: SANAA EL HABIB KAHLOUL

# Field: Computer Networks and Cybersecurity

# Training: Cisco Networking Academy – CyberOps Associate

# Project Type: Cybersecurity Research and Incident Analysis

# Language: English
________________________________________
### Project Overview

This repository contains research and analysis of major cybersecurity incidents as part of the Cisco Networking Academy CyberOps Associate 

training program.

The purpose of this project is to understand how cyberattacks occur, identify the systems and organizations targeted, examine the techniques 

used by attackers, and evaluate the consequences of security incidents.

# Objectives; 

•	Research major cybersecurity incidents.

•Identify attack methods and techniques.

•	Understand malware, unauthorized access, and data breaches.

•	Analyze the impact of cyberattacks on organizations and individuals.

•	Develop cybersecurity research and incident analysis skills.

# Case Studies

The following cybersecurity incidents are covered:

No.	Cybersecurity Incident	Main Category

01     	Stuxnet	Industrial Malware

02	Marriott Data Breach	Data Breach

03	United Nations Data Breach	Network 

04	Microsoft Customer Support Database Exposure	Security Misconfiguration

05	LifeLabs Data Breach	Ransomware and Data Theft

## Detailed Analysis


The Marriott data breach was selected for an in-depth investigation.

## The analysis covers:
•	Victims of the attack

•	Tools and technologies involved

•	Attack timeline

•	Targeted systems

•	Attackers' motivations

•	Consequences and security impact

### Skills and Knowledge Developed

•	Cybersecurity fundamentals

•	Malware analysis concepts

•	Network security

•	Security incident investigation

•	Data breach analysis

•	Credential theft awareness

•	Threat identification

•	Technical research and documentation

## References

The research is based on technical reports, official cybersecurity publications, government investigations, and trusted news sources.
________________________________________
File 2 — case-study-marriott.md
Case Study: Marriott Data Breach (2018)
1. Introduction
The Marriott data breach is one of the major cybersecurity incidents involving the hospitality industry.
On November 30, 2018, Marriott International announced unauthorized access to the Starwood Hotels guest reservation database.
The attackers had maintained access to the Starwood network since 2014, before Marriott acquired Starwood in September 2016.
This incident highlights the importance of network monitoring, access control, credential protection, and database security.
2. Attack Analysis
A. Who were the victims?
The victims were customers who had made reservations at Starwood Hotels properties.
According to the Office of the Privacy Commissioner of Canada, up to approximately 339 million guest records were affected worldwide. This figure represents records and may include multiple records belonging to the same individual.
B. What tools and technologies were used?
The investigation identified several tools used by the attackers:
•	Web Shell: Installed on a Starwood web server to provide remote access and enable further malicious activity.
•	Remote Access Trojans (RATs): Three different RATs were used to maintain remote access to the Starwood network.
•	Mimikatz: A credential-harvesting program used to obtain usernames and passwords from system memory.
•	VPN Tool: An open-source VPN tool was used to access the Starwood network remotely.
These tools enabled the attackers to obtain legitimate credentials, including some administrator accounts, and access sensitive database information.
C. When did the attack occur?
The intrusion timeline was as follows:
•	July 29, 2014: The attacker gained access to a Starwood web server and installed a web shell.
•	July 2018: The attacker used a VPN tool to remotely access the Starwood network.
•	September 7, 2018: A security alert was triggered.
•	September 8, 2018: Marriott received notification of the suspicious activity.
•	November 30, 2018: Marriott publicly announced the data breach.
•	December 11, 2018: Marriott completed the migration of reservation data to its own systems and decommissioned the Starwood database.
D. Which systems were targeted?
The attackers targeted several components of Starwood's IT infrastructure:
•	External-facing web server.
•	Internal network infrastructure.
•	Systems containing user credentials.
•	Starwood Guest Reservation Database.
•	Database tables containing guest profiles, contact information, and reservation details.
The guest reservation database was particularly sensitive because it contained personal and payment-related information.
E. What was the attackers' motivation?
The exact identity and motivation of the attackers have not been officially established.
However, the attackers sought unauthorized access to sensitive customer information and took steps to copy and prepare database information for removal from the Starwood network.
The investigation did not definitively establish the full extent of successful data exfiltration.
F. What were the consequences?
The breach affected up to approximately 339 million guest records worldwide.
The compromised information included:
•	Guest names.
•	Postal addresses.
•	Email addresses.
•	Telephone numbers.
•	Reservation information.
•	Passport details for some customers.
•	Encrypted payment card information for some customers.
The incident resulted in significant privacy risks, reputational damage, regulatory investigations, and additional cybersecurity costs.
Marriott removed the malicious tools, strengthened security monitoring, improved access controls, and migrated the reservation database to its own systems.
3. Cybersecurity Lessons Learned
This incident demonstrates several important cybersecurity lessons:
1.	Continuous Monitoring: Organizations must continuously monitor their networks to detect suspicious activities.
2.	Access Control: Administrator privileges should be restricted and monitored.
3.	Credential Protection: Passwords and authentication credentials must be protected against theft.
4.	Network Security: Network segmentation and proper security controls can limit unauthorized access.
5.	Incident Response: Early detection and rapid incident response are essential to reducing the impact of cyberattacks.
6.	Third-Party Risk Management: Organizations must assess the security of acquired companies and inherited IT infrastructure.
4. Conclusion
The Marriott data breach demonstrates how attackers can remain undetected inside an organization's network for several years.
The incident emphasizes the importance of strong cybersecurity policies, continuous monitoring, effective access management, and proper protection of sensitive customer information.
It also shows that cybersecurity must be considered during business acquisitions and IT infrastructure integration.
5. Main Reference
Office of the Privacy Commissioner of Canada (2022).
Hotel chain discovers breach of customer database following acquisition of a competitor.
https://www.priv.gc.ca/en/opc-actions-and-decisions/investigations/investigations-into-businesses/2022/pipeda-2022-005/
File 3 — sources.md
Sources and References
This file contains the main references used for the cybersecurity case studies.
1. Stuxnet
•	European Union Agency for Cybersecurity (ENISA): Stuxnet Analysis
https://www.enisa.europa.eu/news/enisa-news/stuxnet-analysis
•	Institute for Science and International Security: Stuxnet Malware and Natanz
https://isis-online.org/isis-reports/stuxnet-malware-and-natanz-update-of-isis-december-22-2010-reportsupa-href1
2. Marriott Data Breach
•	Office of the Privacy Commissioner of Canada (2022): Hotel chain discovers breach of customer database following acquisition of a competitor.
https://www.priv.gc.ca/en/opc-actions-and-decisions/investigations/investigations-into-businesses/2022/pipeda-2022-005/
•	Federal Trade Commission (2024): FTC Takes Action Against Marriott and Starwood Over Multiple Data Breaches.
https://www.ftc.gov/news-events/news/press-releases/2024/10/ftc-takes-action-against-marriott-starwood-over-multiple-data-breaches
3. United Nations Data Breach
•	United Nations Digital Library: Report A/75/156
https://digitallibrary.un.org/record/3883078
•	The New Humanitarian (2020): The cyber attack the UN tried to keep under wraps.
https://www.thenewhumanitarian.org/fr/node/261135
4. Microsoft Customer Support Database Exposure
•	Microsoft Security Response Center (January 22, 2020): Access Misconfiguration for Customer Support Database.
https://www.microsoft.com/en-us/msrc/blog/2020/01/access-misconfiguration-for-customer-support-database/
5. LifeLabs Data Breach
•	Information and Privacy Commissioner of Ontario: LifeLabs Privacy Breach.
https://www.ipc.on.ca/en/media-centre/news-releases/statement-office-information-and-privacy-commissioner-ontario-and-office-information-and-privacy
•	Information and Privacy Commissioner of Ontario (2024): Investigation Report into LifeLabs Privacy Breach.
https://www.ipc.on.ca/en/media-centre/news-releases/commissioners-publish-2020-investigation-report-lifelabs-privacy-breach-affecting-millions-canadians
________________________________________

