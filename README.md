# ⚡ MICHAEL W. LANNEN
### **Cybersecurity Analyst | SecOps & Incident Response** 
📍 *Meadow Bridge, WV* 

[![Email Me](https://img.shields.io/badge/Email-Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Michael.lannen93@gmail.com) 
[![Download Master CV](https://img.shields.io/badge/Download-Master%20CV-0078D4?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](./Michael%20Lannen%20Cyber%20Security.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/michael-lannen-053588167/) 
[![GitHub](https://img.shields.io/badge/GitHub-Profile-24292e?style=for-the-badge&logo=github)](https://michaelwlannen.github.io)

---
> ## 🚀 OVERVIEW
> **Security Professional** with direct hands-on experience in real-world ransomware remediation and a focus on **Digital Forensics and Incident Response (DFIR)**. Combines 2 years of dedicated cybersecurity operations with 6 years of technical IT experience. Proven track record containing live threat actors, architecting Splunk log pipelines, and conducting forensic email/payload analysis across 150+ endpoints.
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

After graduating with Honors, I used that momentum to build out real security tools at work and in my lab:setting up Splunk and Wazuh SIEMs, running GoPhish campaigns, building local MISP pipelines for IOC enrichment, and triaging alerts in SentinelOne.

I'm still learning every day and building out new projects. Feel free to shoot me a message or check out my work below!

---

## 🏆 CERTIFICATIONS
⚡ `CompTIA CSAP` | `CompTIA CySA+` | `CompTIA Security+` | `CompTIA Network+` | `CompTIA ITF+`

---

## 🛠️ TECHNICAL SKILLS MATRIX

| 🛡️ Security Operations & DFIR | 🔑 Cloud, Identity & GRC | 🌐 Infrastructure, Networking & Scripting |
| :--- | :--- | :--- |
| • Microsoft Sentinel & Splunk SIEM<br>• SentinelOne EDR & Wazuh SIEM<br>• Incident Response & Triage<br>• GoPhish Phishing Simulations<br>• VirusTotal, AlienVault OTX & YARA | • Entra ID, Active Directory & Intune<br>• RBAC, MFA & Least Privilege<br>• HIPAA & PCI-DSS Compliance<br>• NIST CSF / SP 800-53 Mapping<br>• Email Forensics (SPF/DKIM/DMARC) | • pfSense, WireGuard, Firewalls & VPNs<br>• L2/L3 VLAN Management<br>• Scripting: PowerShell, Python, Bash<br>• NinjaOne RMM Automation<br>• Linux Systems Admin & Docker |

---

## 🗺️ INFRASTRUCTURE TOPOLOGY

![Enterprise Infrastructure Topology Map](https://quickchart.io/graphviz?format=png&graph=digraph+G+{+node+[shape=box,fontname="Helvetica",style="filled,rounded",fillcolor="%231e293b",color="%2338bdf8",fontcolor="%23f8fafc"];+edge+[color="%2394a3b8"];+bgcolor="%230f172a";+subgraph+cluster_0+{+label="Enterprise+Perimeter";+fontcolor="%2338bdf8";+color="%2338bdf8";+VLAN_Seg+[label="pfSense+Firewall+%26+WireGuard\n(Secure+VLAN+Segmentation)",shape=diamond,color="%2338bdf8"];+}+subgraph+cluster_1+{+label="Clinical+Footprint+(150%2B+Endpoints)";+fontcolor="%2338bdf8";+WinAD+[label="Entra+ID+/+Active+Directory"];+MultiEndpoints+[label="Multi-Platform+Endpoints\n(NinjaOne+%26+SentinelOne)"];+VLAN_Seg+->+WinAD;+VLAN_Seg+->+MultiEndpoints;+}+subgraph+cluster_2+{+label="Centralized+Security+Core";+fontcolor="%2338bdf8";+color="%2338bdf8";+Splunk+[label="Ubuntu+Linux+Server\nSplunk+Enterprise+SIEM",fillcolor="%232a3439",color="%2338bdf8"];+LVM+[label="1TB+Linux+LVM\nAggregated+Storage+Pool"];+Splunk+->+LVM+[dir=both,label="Log+Sync/IO"];+}+subgraph+cluster_3+{+label="Threat+Intel+%26+Automation";+fontcolor="%2338bdf8";+MISP+[label="MISP+Pipeline"];+LLM+[label="Local+LLM+/+Discord+Alerts"];+MISP+->+LLM;+}+WinAD+->+Splunk+[label="S1+API+/+Event+Logs",fontcolor="%2394a3b8"];+MultiEndpoints+->+Splunk+[label="Sysmon+/+Universal+Forwarder",fontcolor="%2394a3b8"];+})

---

## 🔬 PROJECTS & LAB WORK

* **Local LLM & MISP Threat Intelligence Pipeline:** Built an automated threat intelligence framework integrating MISP, Splunk, and a local LLM to ingest IOCs and post real-time AI-analyzed threat alerts to Discord.
* **GoPhish Phishing Simulation Setup:** Practical phishing simulation setup using GoPhish to improve security awareness. Includes custom phishing email templates, a mock Microsoft login page, and an educational landing page. Hosted on a Linux server and designed to help organizations identify and train users against phishing attacks.
* **Azure Free Tier Honeypot + Microsoft Sentinel Logging:** Deployed an exposed cloud honeypot environment to capture live adversary telemetry and built custom KQL queries in Microsoft Sentinel to analyze attack trends and IP origins.
* **Email Security & Malware Analysis Lab:** Conducted static/dynamic forensic analysis on malicious email payloads and extracted IOCs to author custom YARA detection rules.
* **Enterprise Vulnerability Management & Nessus Lab:** Deployed and configured Nessus Professional in an isolated lab environment to execute authenticated and unauthenticated vulnerability scans across Windows and Linux hosts; analyzed scan telemetry to identify critical CVEs, misconfigurations, and missing patches, authoring prioritized remediation reports based on CVSS scoring and risk context.
* **Infrastructure Modernization:** Built and deployed modern web infrastructure and network configurations for local small businesses and non-profit organizations.
* **Community Outreach:** Organized and participated in technical charitable initiatives, utilizing 3D printing workflows to manufacture custom resources for children in need.

---

## 💼 WORK EXPERIENCE

### Cybersecurity and IT Specialist
**FMRS Health Systems** | Beckley, WV | *Nov 2024 – Present*
* **Incident Response & Triage:** Mitigated a live ransomware outbreak following a 3-month adversary dwell time; applied FEMA ICS 100 principles to isolate compromised hosts, coordinate system restoration, and prevent clinical downtime.
* **Email Security & Threat Analysis:** Conducted detailed header and payload forensics (SPF/DKIM/DMARC, link sandboxing) on user reports, neutralizing 30+ phishing campaigns and updating email gateway controls to block credential harvesting.
* **SIEM & Storage Architecture:** Architected a production Splunk SIEM on custom Linux hardware, building a 1TB LVM storage pool from repurposed drives to ingest logs across 150+ endpoints, cutting detection times by 35% and saving $10k+.
* **Endpoint & Agent Automation:** Engineered custom PowerShell deployment scripts executed via NinjaOne RMM to automate fleet-wide rollouts of security agents across 150+ endpoints, reducing agent deployment times to under 4 hours and lowering MTTR by 40%.
* **Identity & Access Management (IAM):** Hardened organizational posture by enforcing Least Privilege and Role-Based Access Control (RBAC) for 300+ users in Entra ID, accelerating identity attack detection by 3x and neutralizing unauthorized escalation risks.
* **Security Awareness & Phishing Mitigation:** Reduced organizational phishing susceptibility by 20% by designing targeted GoPhish simulations and engineering automated remedial training workflows featuring custom HTML redirects.
* **Governance, Risk, & Compliance (GRC):** Spearheaded accreditation readiness by authoring Disaster Recovery Plans (DRP), Acceptable Use Policies (AUP), and healthcare SOPs, securing a 10% funding increase and raising compliance audit scores by 15%.
* **Vulnerability Management & Threat Intel:** Led end-to-end vulnerability triage and threat hunting using SentinelOne, Splunk, VirusTotal, and AlienVault OTX, accelerating overall threat triage and remediation speed by 25% for critical security flaws.

### Engineering Analyst
**Alpha Engineering Services** | Mabscott, WV | *Oct 2023 – Feb 2024*
* **Data Parsing & Compliance:** Parsed, sorted, and analyzed complex technical datasets to optimize airflow metrics, maintaining strict alignment with regulatory compliance and safety standards.

### Production Support
**Ibex Global** | Beckley, WV | *May 2019 – Oct 2023, Feb 2024 – Nov 2024*
* **Privacy & IAM:** Enforced PCI-DSS and HIPAA data protection controls across sensitive PII/PHI environments; managed user access controls and identity provisioning across enterprise and hybrid infrastructures.
* **Root-Cause Analysis:** Conducted root-cause investigations on complex system escalations, streamlining operational workflows and reducing recurring incidents by 30%.

---

## 🎓 EDUCATION
* **A.A.S. in Cybersecurity (Honors)** | *West Virginia Junior College*
