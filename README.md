# ⚡ MICHAEL W. LANNEN
### **Cybersecurity Analyst | SecOps & Incident Response** 
📍 *Meadow Bridge, WV* 

[![Email Me](https://img.shields.io/badge/Email-Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Michael.lannen93@gmail.com) 
[![Download Master CV](https://img.shields.io/badge/Download-Master%20CV-0078D4?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](./Michael%20Lannen%20Cyber%20Security.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/michael-lannen-053588167/) 
[![GitHub](https://img.shields.io/badge/GitHub-Profile-24292e?style=for-the-badge&logo=github)](https://michaelwlannen.github.io)

---
> ## 🚀 OVERVIEW
> **Cybersecurity Analyst** with hands-on experience in security operations, incident response, and defensive security engineering within healthcare environments. Experienced in investigating ransomware incidents, phishing campaigns, security alerts, and endpoint threats while deploying SIEM, EDR, and identity security solutions. Combines 2 years of cybersecurity operations experience with 6 years of technical IT experience, utilizing Splunk, Microsoft Sentinel, SentinelOne, KQL, SPL, and PowerShell automation to strengthen detection and response capabilities.
---

## 📖 MY STORY & JOURNEY

Hey, I'm Michael Lannen. I grew up in a small town in West Virginia. I was a late bloomer to cybersecurity, but I’ve always been drawn to computers. As a kid, I was usually taking things apart to see how they worked. My dad brought home an old clear-case Mac from my aunt's job once. I got curious, tore it completely down, and couldn't get it working again. My dad wasn't too happy about that. We didn't have much money growing up, so a replacement wasn't an option. Years later, my mom went to college and bought a computer with her grant money. That’s when I really got hooked—spending hours on AOL and in AIM chat rooms, just enjoying being online.

When it was time for college, my dad pushed me toward a traditional path. I gave Civil Engineering a shot, but it wasn't for me. I dropped out and went straight to work, moving through jobs at Walmart, pipeline construction, and eventually a call center.

Working at the call center was the turning point. I realized I could actually make a living working with technology. An older guy in the IT department took me under his wing and showed me what he could when he had time. 

In 2022, my daughter was born, and becoming a father really put my butt in gear. I knew I needed to build a real career and secure our future. I wanted to go back to school, but I didn't have much Pell Grant funding left from my first attempt. I needed a program that would give me an actual degree and industry certs without wasting time or money. In 2024, I enrolled in West Virginia Junior College's 18-month Associate degree program and worked as hard as I could.

It was a tough stretch, and money was tight. My daily schedule looked like this:
* **6:00 AM:** Get up and prep for a 35-mile commute.
* **8:00 AM – 5:00 PM:** Drop my wife off at work, drop my baby off at daycare, and work my full shift at the call center.
* **5:00 PM – 9:00 PM:** Pick up my daughter and DoorDash with her car seat in the back to cover diapers and food.
* **10:30 PM – 1:00 AM+:** Get everyone settled for the night, then stay up studying and doing coursework.

While I was in school, my mentor at the call center passed away, so I never got to show him what I learned. Shortly after, a new IT hire came on who needed help. I stepped up on top of my regular job—imaging laptops, packing hardware, helping people on the floor with broken mice or monitor issues, and helping train new remote agents. 

Eventually, I landed a job at **FMRS Health Systems**. They needed someone for general IT support, but it quickly turned into much more than that. I learned on the fly while finishing my degree, all while continuing to DoorDash on the side. 

After graduating with Honors, I used that momentum to build out real security tools at work and in my lab: setting up Splunk and Wazuh SIEMs, running GoPhish campaigns, building local MISP pipelines for IOC enrichment, and triaging alerts in SentinelOne.

I'm still learning every day and building out new projects. Feel free to shoot me a message or check out my work below!

---

## 🏆 CERTIFICATIONS
⚡ `CompTIA Security+` | `CompTIA Network+` | `CompTIA CySA+` | `CompTIA CSAP` | `CompTIA ITF+`

---

## 🛠️ TECHNICAL SKILLS MATRIX

| 🛡️ Security Operations & DFIR | 🔑 Cloud, Identity & GRC | 🌐 Infrastructure, Scripting & Engineering |
| :--- | :--- | :--- |
| • Microsoft Sentinel & Splunk SIEM<br>• SentinelOne EDR & Wazuh SIEM<br>• Incident Response & Triage<br>• GoPhish Phishing Simulations<br>• VirusTotal & AlienVault OTX<br>• Forensic Triage & Phishing Analysis | • Entra ID, Active Directory & Intune<br>• RBAC, MFA & Least Privilege<br>• HIPAA & PCI-DSS Compliance<br>• NIST CSF / SP 800-53 Mapping<br>• Email Forensics (SPF/DKIM/DMARC)<br>• DRP / AUP / Healthcare SOPs | • Detection Engineering: SPL, KQL, IOC Enrichment, Alert Tuning<br>• Scripting: PowerShell, Python, Bash<br>• pfSense, WireGuard, Firewalls & VPNs<br>• L2/L3 VLAN Management<br>• NinjaOne RMM Automation<br>• Linux Admin & Docker |

---

## 🗺️ INFRASTRUCTURE TOPOLOGY

![Enterprise Infrastructure Topology Map](https://quickchart.io/graphviz?format=png&graph=digraph+G+{+node+[shape=box,fontname="Helvetica",style="filled,rounded",fillcolor="%231e293b",color="%2338bdf8",fontcolor="%23f8fafc"];+edge+[color="%2394a3b8"];+bgcolor="%230f172a";+subgraph+cluster_0+{+label="Enterprise+Perimeter";+fontcolor="%2338bdf8";+color="%2338bdf8";+VLAN_Seg+[label="pfSense+Firewall+%26+WireGuard\n(Secure+VLAN+Segmentation)",shape=diamond,color="%2338bdf8"];+}+subgraph+cluster_1+{+label="Clinical+Footprint+(150%2B+Endpoints)";+fontcolor="%2338bdf8";+WinAD+[label="Entra+ID+/+Active+Directory"];+MultiEndpoints+[label="Multi-Platform+Endpoints\n(NinjaOne+%26+SentinelOne)"];+VLAN_Seg+->+WinAD;+VLAN_Seg+->+MultiEndpoints;+}+subgraph+cluster_2+{+label="Centralized+Security+Core";+fontcolor="%2338bdf8";+color="%2338bdf8";+Splunk+[label="Ubuntu+Linux+Server\nSplunk+Enterprise+SIEM",fillcolor="%232a3439",color="%2338bdf8"];+LVM+[label="1TB+Linux+LVM\nAggregated+Storage+Pool"];+Splunk+->+LVM+[dir=both,label="Log+Sync/IO"];+}+subgraph+cluster_3+{+label="Threat+Intel+%26+Automation";+fontcolor="%2338bdf8";+MISP+[label="MISP+Pipeline"];+LLM+[label="Local+LLM+/+Discord+Alerts"];+MISP+->+LLM;+}+WinAD+->+Splunk+[label="S1+API+/+Event+Logs",fontcolor="%2394a3b8"];+MultiEndpoints+->+Splunk+[label="Sysmon+/+Universal+Forwarder",fontcolor="%2394a3b8"];+})

---

## 🔬 PROJECTS & LAB WORK

* **Local LLM & MISP Threat Intelligence Pipeline:** Built an automated threat intelligence framework integrating MISP, Splunk, and a local LLM to ingest IOCs and post real-time AI-analyzed threat alerts to Discord.
* **GoPhish Phishing Simulation Setup:** Practical phishing simulation setup using GoPhish to improve security awareness. Includes custom phishing email templates, a mock Microsoft login page, and an educational landing page. Hosted on a Linux server and designed to help organizations identify and train users against phishing attacks.
* **Azure Free Tier Honeypot + Microsoft Sentinel Logging:** Deployed an exposed cloud honeypot environment to capture live adversary telemetry and built custom KQL queries in Microsoft Sentinel to analyze attack trends and IP origins.
* **Email Security & Malware Analysis Lab:** Conducted static and dynamic analysis of malicious email payloads, extracted indicators of compromise (IOCs), and documented findings to support threat investigation and detection improvements.
* **Enterprise Vulnerability Management & Nessus Lab:** Deployed and configured Nessus Professional in an isolated lab environment to execute authenticated and unauthenticated vulnerability scans across Windows and Linux hosts; analyzed scan telemetry to identify critical CVEs, misconfigurations, and missing patches, authoring prioritized remediation reports based on CVSS scoring and risk context.
* **Infrastructure Modernization:** Built and deployed modern web infrastructure and network configurations for local small businesses and non-profit organizations.
* **Community Outreach:** Organized and participated in technical charitable initiatives, utilizing 3D printing workflows to manufacture custom resources for children in need.

---

## 💼 WORK EXPERIENCE

### Cybersecurity Analyst / IT Specialist
**FMRS Health Systems** | Beckley, WV | *Nov 2024 – Present*
* **Incident Response & Triage:** Responded to a ransomware incident involving compromise of an internet-facing firewall service; performed security triage, supported endpoint isolation, analyzed indicators of compromise, and assisted recovery and remediation efforts.
* **Email Security & Threat Analysis:** Investigated and remediated 30+ phishing campaigns, analyzing headers, URLs, and payloads while extracting IOCs and improving email security controls.
* **SIEM & Storage Architecture:** Deployed and configured a production Splunk SIEM environment on Linux infrastructure, designing log ingestion pipelines across 150+ endpoints and developing centralized visibility for security monitoring and threat investigation.
* **Endpoint & Agent Automation:** Engineered custom PowerShell deployment scripts executed via NinjaOne RMM to automate fleet-wide security agent rollouts across 150+ endpoints.
* **Identity & Access Management (IAM):** Hardened identity security posture by implementing least privilege principles and RBAC controls for 300+ users in Entra ID.
* **Security Awareness & Phishing Mitigation:** Developed GoPhish simulations and automated remediation workflows using custom HTML training pages to improve employee phishing awareness.
* **Governance, Risk, & Compliance (GRC):** Supported accreditation readiness by authoring Disaster Recovery Plans (DRP), Acceptable Use Policies (AUP), and healthcare security SOPs.
* **Vulnerability Management & Threat Intel:** Conducted vulnerability triage and threat hunting using SentinelOne, Splunk, VirusTotal, and AlienVault OTX to investigate security findings and support remediation efforts.

### Engineering Analyst
**Alpha Engineering Services** | Mabscott, WV | *Oct 2023 – Feb 2024*
* **Data Parsing & Compliance:** Parsed, sorted, and analyzed complex technical datasets to optimize airflow metrics, maintaining strict alignment with regulatory compliance and safety standards.

### Production Support
**Ibex Global** | Beckley, WV | *May 2019 – Oct 2023, Feb 2024 – Nov 2024*
* **Privacy & IAM:** Enforced PCI-DSS and HIPAA data protection controls across sensitive PII/PHI environments; managed user access controls and identity provisioning across enterprise and hybrid infrastructures.
* **Root-Cause Analysis:** Conducted root-cause investigations on complex system escalations, streamlining operational workflows and reducing recurring incidents.

---

## 🎓 EDUCATION
* **A.A.S. in Cybersecurity (Honors)** | *West Virginia Junior College*
