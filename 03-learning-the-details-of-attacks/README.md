# Lab 03 — Learning the Details of Attacks

## Overview

This lab explored Internet of Things (IoT) vulnerabilities across four sectors: industry, energy systems, healthcare, and government. The objective was to understand how vulnerabilities arise, who might exploit them, why they may be targeted, and how their risks can be reduced.

## Objectives

- Research IoT vulnerabilities in different sectors.
- Identify potential threat actors and their motivations.
- Explain the causes and possible consequences of vulnerabilities.
- Recommend security controls to reduce risk.

## 1. IoT Vulnerabilities by Sector

### Industry

Industrial devices and software may contain vulnerabilities that allow unauthorized access or remote code execution. If exploited, these weaknesses could disrupt industrial operations or affect the integrity and availability of systems.

**Potential mitigation:** Apply vendor security updates, restrict network access, segment industrial control networks, and monitor suspicious activity.

### Energy Systems

Energy-sector devices and control components may be exposed through insecure configurations, weak access controls, or improperly protected remote access. Exploitation could affect device operation or the reliability of energy services.

**Potential mitigation:** Follow vendor advisories, use firewalls and network segmentation, secure remote access, and apply recommended updates.

### Healthcare

Connected medical devices, including wireless infusion pumps, can be affected by default passcodes, weak authentication, outdated software, and insecure network configurations. Unauthorized access could expose patient information or interfere with device operation.

**Potential mitigation:** Change default credentials, enforce appropriate access controls, apply manufacturer-approved updates, restrict remote access, and separate medical devices from general-purpose networks.

### Government

Connected government devices, such as surveillance cameras and building-management systems, may be at risk when credentials are weak, firmware is outdated, or devices are improperly configured. Exploitation could compromise sensitive information or disrupt services.

**Potential mitigation:** Maintain an inventory of connected devices, change default credentials, update firmware, restrict access, and monitor device activity.

*Note: These sector examples describe vulnerability types and potential risks; they do not claim that a specific incident occurred in every sector.*

## 2. Detailed Vulnerability Analysis: Healthcare IoT

### a. What is the vulnerability?

A wireless infusion pump may retain a manufacturer-default maintenance passcode or have weak authentication and access controls. If these weaknesses are not corrected, an unauthorized person may gain access to device functions or related information.

### b. Who might exploit it, and why?

A cybercriminal or other malicious actor might attempt to exploit the weakness to obtain sensitive patient information, install malicious software, or interfere with device operation. The actual motive would depend on the individual or group involved.

### c. Why does the vulnerability exist?

The vulnerability may exist because default credentials were not changed, access permissions are too broad, software is not kept updated, or remote access and network settings are inadequately secured.

### d. What could be done to limit the vulnerability?

- Change default passcodes and enforce strong authentication.
- Give users only the permissions needed for their roles.
- Apply manufacturer-approved security updates.
- Restrict and secure remote access.
- Segment medical devices from other networks.
- Monitor for suspicious activity and maintain an inventory of connected devices.

## Key Lessons Learned

- IoT connectivity improves functionality but can increase the attack surface.
- Default credentials and weak access controls can expose connected devices.
- The impact of a vulnerability depends on the device, its environment, and the access obtained.
- Security requires multiple controls, including patching, authentication, segmentation, and monitoring.
- Healthcare IoT security is particularly important because cyber incidents can affect both information privacy and patient safety.

## Sources

1. [NIST — Securing Wireless Infusion Pumps](https://www.nccoe.nist.gov/publication/1800-8/VolB/)
2. [NIST — Securing Wireless Infusion Pumps in Healthcare Delivery Organizations](https://csrc.nist.gov/pubs/sp/1800/8/final)
3. [CISA — Industrial Control Systems Advisories](https://www.cisa.gov/news-events/ics-advisories)
4. [CISA — Internet of Things and cybersecurity guidance](https://www.cisa.gov/)

## Reflection

This research improved my understanding of how IoT vulnerabilities can affect different sectors. I learned to connect a vulnerability with its possible causes, threat actors, potential impact, and practical defensive controls. It also reinforced the importance of securing connected devices throughout their lifecycle.
