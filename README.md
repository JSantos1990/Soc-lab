# 🛡️ SOC Lab – Security Operations & Network Analysis

This repository contains my hands-on SOC (Security Operations Center) laboratory.  
It includes network traffic analysis, custom IDS/IPS rules, incident reports, and log investigation exercises.

The goal of this lab is to build and demonstrate skills in:
- Network and packet inspection  
- Threat detection and alert investigation  
- Writing IDS/IPS signatures  
- Log analysis  
- Creating SOC-style incident reports  
- Understanding attacker behavior and MITRE ATT&CK techniques  

---

## 📂 Repository Structure

### 📁 `wireshark-analysis`
PCAP investigations performed using Wireshark.  
Content includes:
- Protocol breakdown  
- Suspicious traffic identification  
- Session reconstruction  
- Attack traffic examples  

---

### 📁 `suricata-rules`
Custom Suricata IDS/IPS signatures built for detection engineering practice.  
Examples include:
- Port scan detection  
- Brute-force attempts  
- Malware-like C2 patterns  
- Suspicious protocol behavior  

---

### 📁 `incident-reports`
Simulated SOC incident reports following a professional format:  
- Incident summary  
- Indicators of Compromise (IoCs)  
- Log analysis  
- Timeline  
- Containment and remediation  
- Lessons learned  

---

### 📁 `log-analysis`
Log investigation exercises using:
- Syslog  
- Windows Event Logs  
- Web server logs  
- Authentication activity  
- Firewall/IDS events  

Includes detection logic, queries, and findings.

---

## 🔧 Tools & Technologies Used

- **Wireshark** – packet analysis  
- **Suricata** – IDS/IPS rule creation and testing  
- **Zeek** – network event analysis (optional)  
- **Elastic Stack / Kibana** – log visualization  
- **Linux tools** – tcpdump, ss, journalctl, netstat  
- **Python** – log parsing and automation  

---

## 🧭 Future Content Roadmap

- [ ] Port-scan detection using Suricata rules  
- [ ] Malicious HTTP traffic PCAP analysis  
- [ ] SOC report: SSH brute-force investigation  
- [ ] DNS tunneling detection example  
- [ ] Windows event log analysis mapped to MITRE ATT&CK  

---

## 📌 Purpose of This Lab

This repository serves as my practical environment for developing SOC and Blue Team skills.  
All content is based on real-world scenarios that a security analyst may encounter.

---
