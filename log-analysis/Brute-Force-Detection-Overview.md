# 🔐 Brute Force Detection Overview

This document explains how brute-force attacks are detected in logs and SIEM systems.

---

## 🧩 1. Indicators of Brute Force

- Many failed logons in short time
- Same username with multiple IPs
- Sequential password attempts
- Lockout events

📸 Placeholder: failed login pattern.

---

## 🔍 2. Relevant Logs

### Windows  
- Event ID 4625  
- Event ID 4624  
- Event ID 4740  

### Linux  
- /var/log/auth.log  
- "Failed password" messages  

📸 Placeholder: auth.log sample.

---

## 🧭 3. Detection Logic

- Count failed logons per minute  
- Track source IP  
- Correlate across endpoints  

---

## 📝 4. Notes

Detailed SIEM queries will be added later.

---
