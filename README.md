# ⚡ MICHAEL W. LANNEN
### **Cybersecurity Specialist | SecOps & Incident Response** 
📍 *Beckley, WV*  

[![Email Me](https://img.shields.io/badge/Email-Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Michael.lannen93@gmail.com) 
[![Download Master CV](https://img.shields.io/badge/Download-Master%20CV-0078D4?style=for-the-badge&logo=microsoftword&logoColor=white)](./Michael_Lannen_CV.pdf) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/michael-lannen-053588167/) 
[![GitHub](https://img.shields.io/badge/GitHub-Profile-24292e?style=for-the-badge&logo=github)](https://github.com/MichaelWLannen)

---

> ## 🚀 PROFESSIONAL PROFILE
> **Tactical Security Operations Specialist with 2 years of dedicated Cybersecurity operations management and 6 years of core Enterprise IT experience.**[cite: 1] Experienced in frontline threat containment, greenfield SIEM engineering, and automated threat intelligence pipelines[cite: 1]. Proven track record architecting Splunk log ingestion across 150+ endpoints, mitigating live ransomware incidents, and implementing localized AI workflows to drastically accelerate alert triage and response times[cite: 1].

---

## 🏆 CERTIFICATIONS (COMPTIA STACK)
⚡ `CompTIA CSAP` | `CompTIA CySA+` | `CompTIA Security+` | `CompTIA Network+` | `CompTIA ITF+`[cite: 1]

---

## 🛠️ CORE TECHNICAL SKILLS MATRIX

| 🛡️ Security Operations (SecOps & DFIR) | 🔑 Cloud, Identity & GRC (IAM) | 🌐 Infrastructure & Systems |
| :--- | :--- | :--- |
| • Greenfield Splunk SIEM Architecture[cite: 1]<br>• SentinelOne EDR & Threat Containment[cite: 1]<br>• Wazuh SIEM/XDR & Microsoft Sentinel[cite: 1]<br>• Incident Response (FEMA ICS 100)[cite: 1]<br>• Tenable Nessus, Nmap & YARA Analysis[cite: 1] | • Microsoft Entra ID (Azure AD) & Intune[cite: 1]<br>• RBAC & Least Privilege Enforcement[cite: 1]<br>• Regulatory Compliance (HIPAA, PCI-DSS)[cite: 1]<br>• NIST Framework Mapping (CSF / SP 800-53)[cite: 1]<br>• Email Forensics (SPF/DKIM/DMARC)[cite: 1] | • 43-Zone L2/L3 Network Segmentation[cite: 1]<br>• Linux Systems Admin (Ubuntu/Debian)[cite: 1]<br>• Linux LVM Storage Aggregation[cite: 1]<br>• NinjaOne RMM Automated Rollouts[cite: 1]<br>• Docker Compose Lab Orchestration |

### 🤖 AUTOMATION, SCRIPTING & AI INTEGRATION
* 💻 **PowerShell:** Fleet-wide RMM agent deployment wrappers (SentinelOne, Wazuh, Splunk)[cite: 1], automated AD querying, and endpoint compliance workflows[cite: 1].
* 🐧 **Bash & Linux Admin:** Command-line storage engineering (Linux LVM storage pools)[cite: 1], system provisioning, and custom cron-job log rotation protocols[cite: 1].
* 🐍 **Python & Local LLM Automation:** SecOps logic execution, automated IOC enrichment pipelines (MISP + Splunk)[cite: 1], and local LLM integration (Ollama / Dolphin-Mistral)[cite: 1] for secure, air-gapped threat report generation via Webhooks[cite: 1].

---

## 🗺️ LIVE INFRASTRUCTURE TOPOLOGY

![Enterprise Infrastructure Topology Map](https://quickchart.io/graphviz?format=png&graph=digraph+G+{+node+[shape=box,fontname="Helvetica",style="filled,rounded",fillcolor="%231e293b",color="%2338bdf8",fontcolor="%23f8fafc"];+edge+[color="%2394a3b8"];+bgcolor="%230f172a";+subgraph+cluster_0+{+label="Enterprise+Perimeter";+fontcolor="%2338bdf8";+color="%2338bdf8";+VLAN_Seg+[label="Advanced+L2/L3+Segmentation\n(43+Secure+VLAN+Zones)",shape=diamond,color="%2338bdf8"];+}+subgraph+cluster_1+{+label="Clinical+Footprint+(150%2B+Endpoints)";+fontcolor="%2338bdf8";+WinAD+[label="Active+Directory+Domain+Controller"];+MultiEndpoints+[label="Multi-Platform+Clinical+Nodes\n(Workstations+%26+Medical+IoT)"];+VLAN_Seg+->+WinAD;+VLAN_Seg+->+MultiEndpoints;+}+subgraph+cluster_2+{+label="Centralized+Security+Core";+fontcolor="%2338bdf8";+color="%2338bdf8";+Splunk+[label="Ubuntu+Linux+Server\nSplunk+Enterprise+SIEM",fillcolor="%232a3439",color="%2338bdf8"];+LVM+[label="1TB+Linux+LVM\nAggregated+Storage+Pool"];+Splunk+->+LVM+[dir=both,label="Log+Sync/IO"];+}+subgraph+cluster_3+{+label="Isolated+Security+Sandbox";+fontcolor="%2338bdf8";+Hypervisor+[label="VMware+Type-1+/+VirtualBox"];+LabNodes+[label="Malware+Analysis+%26+Lab+Nodes"];+Hypervisor+->+LabNodes;+}+WinAD+->+Splunk+[label="S1+API+/+Event+Logs",fontcolor="%2394a3b8"];+MultiEndpoints+->+Splunk+[label="Sysmon+/+Universal+Forwarder",fontcolor="%2394a3b8"];+})

---

## 💼 PROFESSIONAL EXPERIENCE

### 🔺 Cybersecurity and IT Specialist
**FMRS Health Systems** | *Nov 2024 – Present*[cite: 1]
* **Ransomware Mitigation & Incident Containment:** Served as frontline incident responder during a live enterprise ransomware incident following a 3-month adversary dwell time; utilized FEMA ICS 100 principles to contain threat vectors, isolate endpoints, and restore systems with zero clinical downtime[cite: 1].
* **Enterprise SIEM Architecture:** Architected and deployed a production **Splunk Enterprise SIEM** instance on custom Linux hardware to monitor 150+ endpoints[cite: 1]. Aggregated scavenged hardware via **Linux LVM** to build a high-velocity 1TB storage backend dedicated to log indexing[cite: 1].
* **Automated Threat Intelligence & LLM Pipeline:** Engineered an automated SOC pipeline integrating MISP, Splunk, Docker Compose, and local LLMs (Mistral-7B) to enrich IOC queries and stream real-time threat reports to a secure Discord Webhook[cite: 1].
* **Automated Endpoint Security Deployment:** Automated fleet-wide agent rollouts using custom PowerShell scripts via NinjaOne RMM, deploying SentinelOne, Wazuh, and Splunk to 150+ clinical endpoints to drastically lower MTTR[cite: 1].
* **Network Segmentation & GRC Compliance:** Maintained **43 distinct Layer-2/Layer-3 VLAN zones** to enforce HIPAA, PHI, PII, and PCI-DSS isolation[cite: 1]. Authored DRPs, AUPs, and SOPs that boosted compliance audit scores by 20% and secured a 10% funding increase[cite: 1].
* **Phishing Simulation & Awareness Training:** Designed custom GoPhish campaigns with automated HTML remedial training redirects, achieving a **20% reduction** in organizational phishing susceptibility[cite: 1].

### 🔸 Engineering Analyst (Contract)
**Alpha Engineering Services** | *Oct 2023 – Feb 2024*[cite: 1]
* **Data Parsing & Compliance:** Parsed, sorted, and analyzed complex technical datasets to optimize ventilation airflow metrics while maintaining strict alignment with environmental safety standards[cite: 1].

### 🔹 Production Support Specialist
**Ibex Global Solutions** | *May 2019 – Nov 2024*[cite: 1]
* **Identity Management & Data Privacy:** Enforced strict PCI-DSS and HIPAA data boundary protections across sensitive PII/PHI environments; managed user identity provisioning across hybrid infrastructure[cite: 1].
* **Root-Cause Analysis:** Conducted root-cause investigations on complex system escalations, streamlining operational workflows and reducing recurring escalation tickets by **30%**[cite: 1].

---

## 🎓 EDUCATION
* **Associate of Applied Science (A.A.S.) in Cybersecurity (Honors)** | *West Virginia Junior College*[cite: 1]

---

## 🤝 COMMUNITY & PROJECTS
* **Local Security Projects:** Developed modern network infrastructure and web setups for regional healthcare and non-profit initiatives[cite: 1].
* **Community Outreach:** Organized technical initiatives using 3D printing workflows to manufacture custom resources for children in need[cite: 1].

