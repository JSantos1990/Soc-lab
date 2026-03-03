# 🚨 Suricata Fundamentals Overview

This document introduces Suricata, a powerful IDS/IPS used for network-based threat detection.

---

## 📘 1. What Is Suricata?

Suricata is an open-source IDS/IPS that:

- Detects network threats  
- Uses signature-based rules  
- Supports multi-threading  
- Generates alerts and logs  

📸 Placeholder: Suricata alert example.

---

## 🧩 2. Suricata Rule Structure

Basic syntax:

action protocol src_ip src_port -> dst_ip dst_port (options)

Example:

alert tcp any any -> any 22 (msg:"SSH connection"; sid:10001;)

📸 Placeholder: Rule structure diagram.

---

## 🔍 3. Key Rule Options

- `msg` → description  
- `sid` → unique ID  
- `rev` → revision  
- `content` → match payload  
- `nocase` → case-insensitive  
- `pcre` → regex  

📸 Placeholder: Rule editor screenshot.

---

## 🧪 4. Suricata Use Cases

- Detect brute-force attacks  
- Identify scans  
- Flag suspicious HTTP requests  
- Monitor DNS anomalies  

📸 Placeholder: Suricata logs.

---

## 🧭 5. Notes

More custom rules and real examples will be added next.

---
