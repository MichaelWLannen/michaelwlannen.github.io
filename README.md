# ⚡ MICHAEL W. LANNEN
### **Cybersecurity Specialist | SecOps & Incident Response** 
📍 *Beckley, WV*  

[![Email Me](https://img.shields.io/badge/Email-Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Michael.lannen93@gmail.com) 
[![Download Master CV](https://img.shields.io/badge/Download-Master%20CV-0078D4?style=for-the-badge&logo=microsoftword&logoColor=white)](./Michael%20Lannen%20Cyber%20Security%20Analyst.pdf) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/michael-lannen-053588167/) 
[![GitHub](https://img.shields.io/badge/GitHub-Profile-24292e?style=for-the-badge&logo=github)](https://github.com/MichaelWLannen)

---

## 📖 MY STORY & JOURNEY

Hey, I'm Michael Lannen. I grew up in a small town in West Virginia. I was a late bloomer to cybersecurity, but I’ve always been drawn to computers. As a kid, I was usually taking things apart to see how they worked. My dad brought home an old clear-case Mac from my aunt's job once. I got curious, tore it completely down, and couldn't get it working again. My dad wasn't too happy about that. We didn't have much money growing up, so a replacement wasn't an option. Years later, my mom went to college and bought a computer with her grant money. That’s when I really got hooked—spending hours on AOL and in AIM chat rooms, just enjoying being online.

When it was time for college, my dad pushed me toward a traditional path. I gave Civil Engineering a shot, but it wasn't for me. I dropped out and went straight to work, moving through jobs at Walmart, pipeline construction, and eventually a call center.

Working at the call center was the turning point. I realized I could actually make a living working with technology. An older guy in the IT department took me under his wing and showed me what he could when he had time. I wanted to go back to school, but I didn't have much Pell Grant funding left from my first attempt. I needed a program that would give me an actual degree and industry certs without wasting time or money. I found West Virginia Junior College (WVJC), enrolled in their 18-month Associate degree program, and worked as hard as I could.

It was a tough stretch. My wife and I had a baby right before I started school, and money was tight. My daily schedule looked like this:
* **6:00 AM:** Get up and prep for a 35-mile commute.
* **8:00 AM – 5:00 PM:** Drop my wife at work, drop my baby at daycare, and work my full shift at the call center.
* **5:00 PM – 9:00 PM:** Pick up my baby and DoorDash with the car seat in the back to cover diapers and food.
* **10:30 PM – 1:00 AM+:** Get everyone settled for the night, then stay up studying and doing coursework.

While I was in school, my mentor at the call center passed away, so I never got to show him what I learned. Shortly after, a new IT hire came on who needed help. I stepped up on top of my regular job—imaging laptops, packing hardware, helping people on the floor with broken mice or monitor issues, and helping train new remote agents. 

Eventually, I landed a job at **FMRS Health Systems**. They needed someone for general IT support, but it quickly turned into much more than that. I learned on the fly while finishing my degree, all while continuing to DoorDash on the side. 

After graduating with Honors, I used that momentum to build out real security tools at work and in my lab: setting up Splunk and Wazuh SIEMs, running GoPhish campaigns, building local MISP pipelines for IOC enrichment, and triaging alerts in SentinelOne.

I'm still learning every day and building out new projects. Feel free to shoot me a message or check out my work below!

---

> ## 🚀 OVERVIEW
> **Cybersecurity Specialist with 2 years of hands-on SecOps experience and 6 years in broader IT roles.** Practical background in incident response, setting up SIEM logging, and automating threat intel workflows. Built a production Splunk setup across 150+ endpoints using recycled hardware, helped contain a live ransomware incident, and built local LLM/MISP integrations to speed up alert triage.

---

## 🏆 CERTIFICATIONS
⚡ `CompTIA CSAP` | `CompTIA CySA+` | `CompTIA Security+` | `CompTIA Network+` | `CompTIA ITF+`

---

## 🛠️ TECHNICAL SKILLS MATRIX

| 🛡️ Security Operations & DFIR | 🔑 Identity, Cloud & GRC | 🌐 Infrastructure & Tools |
| :--- | :--- | :--- |
| • Splunk Enterprise SIEM<br>• SentinelOne EDR<br>• Wazuh SIEM/XDR & MS Sentinel<br>• Incident Response (FEMA ICS 100)<br>• Tenable Nessus, Nmap & YARA | • Microsoft Entra ID & Intune<br>• RBAC & Least Privilege<br>• HIPAA & PCI-DSS Compliance<br>• NIST CSF / SP 800-53 Mapping<br>• Email Forensics (SPF/DKIM/DMARC) | • L2/L3 Network Segmentation<br>• Linux Admin (Ubuntu/Debian)<br>• Linux LVM Storage Management<br>• NinjaOne RMM Scripting<br>• Docker & Docker Compose |

### 🤖 AUTOMATION & SCRIPTING
* 💻 **PowerShell:** Software deployment via NinjaOne RMM (SentinelOne, Wazuh, Splunk), Active Directory scripts, and endpoint management.
* 🐧 **Bash:** Linux administration, LVM storage pool setup, system provisioning, and basic log management tasks.
* 🐍 **Python & Local AI:** Automation scripts, MISP + Splunk IOC enrichment pipelines, and local LLM setups (Ollama / Mistral) for offline alert analysis and Webhook notifications.

---

## 🗺️ INFRASTRUCTURE TOPOLOGY

![Enterprise Infrastructure Topology Map](https://quickchart.io/graphviz?format=png&graph=digraph+G+{+node+[shape=box,fontname="Helvetica",style="filled,rounded",fillcolor="%231e293b",color="%2338bdf8",fontcolor="%23f8fafc"];+edge+[color="%2394a3b8"];+bgcolor="%230f172a";+subgraph+cluster_0+{+label="Enterprise+Perimeter";+fontcolor="%2338bdf8";+color="%2338bdf8";+VLAN_Seg+[label="Advanced+L2/L3+Segmentation\n(43+Secure+VLAN+Zones)",shape=diamond,color="%2338bdf8"];+}+subgraph+cluster_1+{+label="Clinical+Footprint+(150%2B+Endpoints)";+fontcolor="%2338bdf8";+WinAD+[label="Active+Directory+Domain+Controller"];+MultiEndpoints+[label="Multi-Platform+Clinical+Nodes\n(Workstations+%26+Medical+IoT)"];+VLAN_Seg+->+WinAD;+VLAN_Seg+->+MultiEndpoints;+}+subgraph+cluster_2+{+label="Centralized+Security+Core";+fontcolor="%2338bdf8";+color="%2338bdf8";+Splunk+[label="Ubuntu+Linux+Server\nSplunk+Enterprise+SIEM",fillcolor="%232a3439",color="%2338bdf8"];+LVM+[label="1TB+Linux+LVM\nAggregated+Storage+Pool"];+Splunk+->+LVM+[dir=both,label="Log+Sync/IO"];+}+subgraph+cluster_3+{+label="Isolated+Security+Sandbox";+fontcolor="%2338bdf8";+Hypervisor+[label="VMware+Type-1+/+VirtualBox"];+LabNodes+[label="Malware+Analysis+%26+Lab+Nodes"];+Hypervisor+->+LabNodes;+}+WinAD+->+Splunk+[label="S1+API+/+Event+Logs",fontcolor="%2394a3b8"];+MultiEndpoints+->+Splunk+[label="Sysmon+/+Universal+Forwarder",fontcolor="%2394a3b8"];+})

---

## 🔬 PROJECTS & LAB WORK

* **[Local LLM & MISP Threat Intel Pipeline](https://github.com/michaelnoobz/Splunk-homelab-and-work-set-up):** Set up a local threat intel pipeline using Docker Compose. Combines MISP, Splunk, and a local LLM (Dolphin-Mistral / Mistral-7B) to enrich IOCs and send structured alert summaries to a private Discord Webhook.
* **[Production Splunk Deployment](https://github.com/michaelnoobz/Splunk-homelab-and-work-set-up):** Built a Splunk Enterprise instance on a Linux server to collect logs from 150+ endpoints. Used Linux LVM to combine spare hard drives into a 1TB storage array for indexing, and deployed forwarders via NinjaOne RMM.
* **[GoPhish Phishing Setup](https://github.com/michaelnoobz/Gophish-):** Configured GoPhish on a Linux server with custom email templates, a fake login page, and an educational landing page to run internal awareness tests.
* **[Azure Sentinel Honeypot](https://github.com/michaelnoobz/MyFirstSEIM):** Set up a public-facing Windows VM in Azure to record attack traffic. Used Microsoft Sentinel and KQL to log and map global RDP brute-force attempts in real time.
* **[DRP Table-Top Exercises](https://github.com/michaelnoobz/DRP-Table-Tops):** Created Disaster Recovery tabletop exercise templates for internal security reviews based on NIST standards.
* **[Malware & Email Analysis Lab](https://github.com/michaelnoobz/Pico-CTF-Python-Automation):** Analyzed suspicious email headers and attachments, pulled IOCs (IPs, domains, hashes), and wrote YARA rules for detection.
* **[Nessus Vulnerability Assessment Lab](https://github.com/michaelnoobz/Pico-CTF-Python-Automation):** Ran authenticated and unauthenticated Nessus scans across a small lab network to find missing patches and misconfigurations, then drafted remediation reports.

---

## 💼 WORK EXPERIENCE

### Cybersecurity and IT Specialist
**FMRS Health Systems** | Beckley, WV | *Nov 2024 – Present*
* **Ransomware Response:** Responded to an active ransomware incident following a 3-month adversary dwell time. Used FEMA ICS 100 principles to isolate infected endpoints, coordinate restoration, and prevent clinical downtime.
* **Splunk SIEM Setup:** Built and configured a Splunk Enterprise server on Ubuntu to collect logs across 150+ endpoints. Configured Linux LVM to merge spare drives into a 1TB array dedicated to log storage.
* **Threat Intel & LLM Pipeline:** Built an automated pipeline linking MISP, Splunk, and a local LLM in Docker Compose to auto-enrich incoming alerts and send summaries via Discord Webhook.
* **Software Deployment:** Wrote PowerShell scripts to roll out SentinelOne, Wazuh, and Splunk agents across 150+ workstations via NinjaOne RMM.
* **Network & GRC:** Managed 43 separate VLANs to keep clinical, guest, and server traffic isolated for HIPAA/PCI compliance. Wrote Disaster Recovery Plans, AUPs, and SOPs that helped raise audit scores by 20%.
* **Phishing Awareness:** Ran internal phishing tests using GoPhish with automatic redirects to training pages, lowering company-wide click rates by 20%.

### Engineering Analyst (Contract)
**Alpha Engineering Services** | Mabscott, WV | *Oct 2023 – Feb 2024*
* **Data Analysis:** Processed and sorted technical airflow data to optimize ventilation systems while ensuring compliance with safety standards.

### Production Support Specialist
**Ibex Global Solutions** | Beckley, WV | *May 2019 – Nov 2024*
* **Identity & Data Security:** Handled user access requests and enforced HIPAA/PCI-DSS data restrictions across support environments.
* **Issue Escalation:** Investigated recurring system issues, improving support documentation and reducing escalation tickets by 30%.

---

## 🎓 EDUCATION
* **A.A.S. in Cybersecurity (Honors)** | *West Virginia Junior College*

---

## 🤝 COMMUNITY WORK
* **Infrastructure Support:** Set up basic network hardware and website configurations for local non-profit and healthcare setups.
* **Community Drives:** Used 3D printers to manufacture small items and resources for local children's charity initiatives.
