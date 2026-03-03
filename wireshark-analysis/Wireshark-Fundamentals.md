# 🌐 Wireshark Fundamentals Overview

This document introduces the basics of Wireshark, the most widely used packet analysis tool.

---

## 📘 1. What Is Wireshark?

Wireshark is a network protocol analyzer used to:

- Inspect packets  
- Identify suspicious traffic  
- Extract metadata  
- Troubleshoot network issues  

📸 Placeholder: Wireshark main window.

---

## 🧩 2. Packet Structure Overview

A typical packet includes:

- Ethernet header  
- IP header  
- TCP/UDP header  
- Application data  

📸 Placeholder: Packet dissection screenshot.

---

## 🔍 3. Filters

Display filters:

- `http`  
- `ip.addr == 192.168.1.10`  
- `tcp.flags.syn == 1`  
- `dns`  

Capture filters:

- `port 80`  
- `host 8.8.8.8`  

📸 Placeholder: Filter bar screenshot.

---

## 🌐 4. Useful Views

- Packet list  
- Packet details  
- Packet bytes  
- Statistics → Conversations  
- Statistics → Protocol Hierarchy  

📸 Placeholder: Protocol hierarchy example.

---

## 🧭 5. Typical SOC Use Cases

- Detect port scans  
- Inspect malicious HTTP traffic  
- Analyze C2 communication  
- Identify DNS anomalies  
- Extract files from PCAPs  

📸 Placeholder: Example PCAP investigation.

---

## 📝 6. Notes

More real PCAP analysis examples will be added later.

---
