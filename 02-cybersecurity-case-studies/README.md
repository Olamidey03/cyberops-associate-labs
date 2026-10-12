# Lab: Cybersecurity Case Studies

## Overview

This lab explores five high-profile cybersecurity incidents to understand how attacks happen, what information or systems are affected, and how organisations can improve their security.

## Objectives

- Research and analyse real-world cybersecurity incidents.
- Identify victims, attack timelines, affected systems, and possible motivations.
- Understand the impact of data breaches and malware.
- Recommend security controls based on lessons from each incident.

## Case Study 1: Stuxnet

**Who:** Industrial control systems associated with Iran's nuclear programme were a major known target.

**What:** Stuxnet was a sophisticated worm designed to interfere with industrial processes involving Siemens control systems.

**When:** It became publicly known in 2010.

**Where:** Iran, particularly the Natanz uranium-enrichment facility.

**Why:** Its apparent purpose was to disrupt or delay uranium enrichment. Public evidence does not conclusively establish every party responsible.

**Security lesson:** Critical infrastructure requires layered protection, including controls for removable media, system isolation, and industrial network monitoring.

## Case Study 2: Marriott / Starwood Data Breach

**Who:** Guests whose information was stored in Starwood's reservation database.

**What:** Attackers gained unauthorised access to the reservation database and copied guest information.

**When:** The intrusion began around 2014. Marriott detected suspicious activity in September 2018 and announced the incident on November 30, 2018.

**Where:** Starwood's network and guest reservation database.

**Why:** The attackers' precise motivation has not been conclusively established publicly.

**Security lesson:** Organisations need effective access controls, network segmentation, multifactor authentication, patch management, and monitoring.

## Case Study 3: United Nations Data Breach

**Who:** The UN and people whose information was held in affected systems, including staff.

**What:** Attackers compromised dozens of servers. Reporting described potential exposure of staff records, health-insurance information, and commercial contract data.

**When:** The attack began in July 2019.

**Where:** UN systems in Geneva and Vienna.

**Why:** The attackers' precise motivation has not been conclusively established publicly.

**Security lesson:** Prompt patching, network segmentation, restricted access, and effective monitoring help prevent compromise or limit its spread.

## Case Study 4: Microsoft Customer Support Database Exposure

**Who:** Microsoft customers whose support records were present in the affected database.

**What:** A misconfigured network security rule exposed an internal customer-support analytics database to unauthorised access. Microsoft reported no evidence of malicious use in its investigation.

**When:** The issue was corrected on December 31, 2019, and Microsoft announced the investigation on January 22, 2020.

**Where:** Microsoft's internal customer-support analytics database.

**Why:** A configuration error left the database exposed.

**Security lesson:** Organisations should audit security configurations, restrict database access, detect misconfigurations, and minimise stored personal information.

## Case Study 5: LifeLabs Data Breach

**Who:** LifeLabs, a Canadian medical laboratory company, and customers whose information was potentially affected.

**What:** A cyberattack resulted in unauthorised access to customer information. LifeLabs reported that information associated with approximately 15 million customers could have been affected.

**When:** The breach was publicly announced on December 17, 2019.

**Where:** LifeLabs' computer systems in Canada.

**Why:** Attackers demanded a ransom, according to LifeLabs. Their full motivation has not been independently established here.

**Security lesson:** Healthcare organisations must protect sensitive personal and medical information through strong access controls, monitoring, incident response, and appropriate data protection.

## Detailed Analysis: Marriott / Starwood Breach

### A. Who were the victims?

Guests whose information was stored in Starwood's reservation database were affected. Marriott acquired Starwood in 2016 while the intrusion was ongoing.

### B. What technologies or tools were used?

Investigators reported that attackers compromised an internet-facing server, installed malware, collected privileged credentials, and moved through the internal network. Reported malware included keyloggers, memory-scraping malware, and remote-access trojans. The exact initial exploit tool has not been conclusively established in the sources used for this report.

### C. When did the attack happen?

- Around July 2014: Initial compromise.
- September 2018: Suspicious activity involving the reservation database was detected.
- November 19, 2018: Marriott's investigation determined that unauthorised access had occurred.
- November 30, 2018: Marriott publicly announced the incident.

### D. What systems were targeted?

The attackers accessed Starwood's internal network and guest reservation database. The investigation found malware across hundreds of systems.

### E. What was the motivation?

The attackers copied guest information and attempted to remove data from the network. Their precise identity and motivation have not been conclusively established publicly.

### F. What was the outcome?

Approximately 339 million guest records worldwide were affected. Exposed information included names, contact details, reservation information, and passport numbers. The investigation reported approximately 5.25 million unencrypted passport numbers.

### Recommended Security Improvements

1. **Intrusion Detection Systems (IDS):** Detect suspicious activity and alert security teams.
2. **Intrusion Prevention Systems (IPS):** Block certain detected malicious traffic.
3. **Multifactor Authentication (MFA):** Reduce the risk posed by stolen passwords.
4. **Least privilege:** Restrict each account to the access it needs.
5. **Network segmentation:** Limit movement between compromised systems and sensitive databases.
6. **Monitoring and logging:** Help identify unusual logins, access patterns, and data transfers.
7. **Patch management:** Address known vulnerabilities promptly.
8. **Security awareness:** Help employees recognise phishing and social engineering.

## Key Concepts Learned

- Defence in depth
- Vulnerabilities and exploits
- Confidentiality, integrity, and availability (CIA triad)
- Authentication and authorisation
- Network segmentation
- Intrusion detection and prevention
- Security awareness
- Incident response

## Sources

- [Microsoft Security Response Center — Customer Support Database Exposure](https://www.microsoft.com/en-us/msrc/blog/2020/01/access-misconfiguration-for-customer-support-database/)
- [LifeLabs — Customer Notification](https://www.lifelabs.com/customer-notification/)
- [The New Humanitarian — UN Cyberattack Investigation](https://www.thenewhumanitarian.org/investigation/2020/01/29/united-nations-cyber-attack)
- [Marriott — November 2018 Incident Announcement](https://news.marriott.com/news/2018/11/30/marriott-announces-starwood-guest-reservation-database-security-incident)
- [US Federal Trade Commission — Marriott/Starwood Matter](https://www.ftc.gov/legal-library/browse/cases-proceedings/192-3058-marriott-international-inc)

## Reflection

This lab demonstrated that cybersecurity incidents can result from malware, exploited software vulnerabilities, weak security configurations, and insufficient controls. Effective defence combines technology, secure processes, monitoring, and informed employees.
