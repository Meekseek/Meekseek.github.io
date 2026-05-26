---
layout: default
title: Jeremy Schoenick - Technical Resume
---
Minnesota, USA | [j.schoenick@pm.me](mailto:j.schoenick@pm.me) | [LinkedIn](https://www.linkedin.com/in/jeremy-s-93686567) | [GitHub](https://github.com/Meekseek)

### PROFESSIONAL SUMMARY
Cross-functional leader and aspiring cybersecurity professional combining 3+ years of technical operations and team leadership with advanced self-directed study. Possessing a foundational Computer Science background and holding a Google Cybersecurity Professional Certificate, I have practical experience building and defending a virtual Security Operations Center (SOC) home lab environment. Seeking an entry-level technical apprenticeship to apply cross-functional leadership, hands-on troubleshooting skills, and a strong aptitude for network defense and system integrity.

### TECHNICAL SKILLS
* **Systems & Virtualization:** Proxmox VE, Ubuntu Server, Windows 11 Enterprise Administration, Linux CLI (systemctl, LVM storage management), SSH implementation
* **Security & Monitoring:** SIEM (Wazuh, OpenSearch), Microsoft Sysmon, Log Analysis, Windows Event Auditing, Threat Mapping (MITRE ATT&CK)
* **Networking:** TCP/IP Fundamentals, SOHO Network Configuration (Xfinity), Mesh Network Deployment (Eero), Network Ingestion Pipelines
* **Development:** Python (Socket, Automation), SQL (Basic Querying), Bash Scripting, PowerShell
* **Tools:** GitHub, VS Code
* **Operational:** Inventory Management Systems (WMS), OSHA Safety Compliance, Team Training, Workflow Optimization

---

### PROJECTS

#### [Virtual Security Operations Center (SOC) | Home Lab](https://github.com/Meekseek/Home-Lab-SOC-Wazuh)
* **Virtual SOC & SIEM Deployment:** Engineered an isolated virtual network utilizing a Proxmox VE hypervisor, deploying a centralized Wazuh SIEM on Ubuntu Server to ingest and analyze endpoint telemetry across both Linux (Kali) and Windows 11 Enterprise target agents.
* **Windows Auditing & Sysmon Integration:** Configured and deployed Microsoft Sysmon on the Windows 11 target node, establishing granular host-level telemetry streams (process creation, network connections) into the SIEM pipeline to enable advanced defensive tracking.
* **Infrastructure Resilience & LVM Troubleshooting:** Diagnosed and resolved a critical 100% root partition disk exhaustion crash on the Ubuntu SIEM node; executed Linux CLI systems administration and Logical Volume Management (LVM) commands to dynamically expand partitions and restore core indexing database clusters without data loss.
* **Network Log Engineering:** Diagnosed and resolved SSH log visibility gaps on the target endpoint by configuring rsyslog pipelines, successfully routing critical security events to the SIEM.
* **Attack Simulation & Analysis:** Executed a simulated SSH brute-force attack using Hydra, utilizing OpenSearch to filter raw JSON logs, identify attacker IPs, and map the telemetry to the MITRE ATT&CK framework (T1110).
* **Automated Threat Mitigation (SOAR):** Engineered active defense capabilities using Wazuh's Active Response module; dynamically deployed endpoint firewall rules to isolate attacker IPs upon detecting SSH brute-force thresholds.

#### [Python Network Port Scanner | Personal Project](https://github.com/Meekseek/Port-Scanner)
* Engineered a CLI-based network diagnostic tool using Python's socket library to audit well-known ports (1-1024) on target devices.
* Optimized tool performance by implementing a 0.5s connection timeout, rapidly identifying open TCP services without stalling on closed ports.
* Developed robust error handling using try/except blocks to gracefully manage connection refusals and user interruptions.
* Deployed the script on a home network to verify router security configurations and identify active servers.

#### [Linux Network Hardening | Home Lab](https://github.com/Meekseek/pi-hole-deployment)
* Configured a Raspberry Pi 5 as a secure Linux server, establishing strict user permission policies (chmod/chown).
* Hardened server access by implementing SSH key-based authentication and disabling password login to simulate industry-standard practices.

---

### PROFESSIONAL EXPERIENCE

#### Warehouse Team Lead | Americold | Newport, MN | June 2024 - Present
* **Tier-1 Technical Support:** Act as the primary contact for troubleshooting and resolving hardware and connectivity issues for enterprise RF scanners, consistently minimizing operational downtime.
* **Data Integrity Management:** Managed and audited data integrity within the enterprise Warehouse Management System (WMS), actively resolving discrepancies in inventory and validating receiving logs.
* **Operations Leadership:** Directed daily workflows and ensured strict compliance with OSHA and Food Safety standards for a team of 5 associates, consistently meeting time-sensitive operational deadlines.
* **Process Optimization:** Implemented procedural and physical rack reconfigurations to enhance storage density, resulting in measurable improvements in space utilization.

---

### EDUCATION
* **Bachelor of Science, Computer Science** | University of the People, Expected Graduation: 2029
* **CompTIA Security+ (SY0-701)** | In Progress — Anticipated Completion: July 2026
* **Google Cybersecurity Professional Certificate** | Completed January 2026
* **Welding Technology Certificate** | Chippewa Valley Technical College
