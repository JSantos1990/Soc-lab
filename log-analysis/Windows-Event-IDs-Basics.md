# 🪟 Windows Event IDs Basics

This document summarizes important Windows Event IDs used in SOC investigations.

---

## 🔑 1. Authentication Events

- 4624 – Successful logon  
- 4625 – Failed logon  
- 4648 – Logon using explicit credentials  
- 4672 – Special privileges assigned  
- 4768 – Kerberos TGT request  
- 4769 – Kerberos service ticket request  

📸 Placeholder: Security log sample.

---

## 🔐 2. Account Management

- 4720 – User account created  
- 4722 – User enabled  
- 4723 – Password change attempted  
- 4725 – User disabled  
- 4732 – Added to local group  
- 4728 – Added to global security group  

📸 Placeholder: Event Viewer screenshot.

---

## 🌐 3. Network & RDP Events

- 1149 – RDP successful connection  
- 5156 – Allowed connection (Windows Filtering Platform)  
- 5158 – Blocked connection  

📸 Placeholder: RDP logs.

---

## 📌 4. Monitoring Recommendations

- Track failed logons  
- Monitor privileged logons  
- Track group membership changes  
- Watch for unusual service ticket requests  

---

## 📝 5. Notes

More event walkthroughs will be added later.

---
