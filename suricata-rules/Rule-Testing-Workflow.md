# 🧪 Suricata Rule Testing Workflow

Steps to validate and tune Suricata rules.

---

## 1. Prepare

- enable rule in local rules file  
- assign unique SID and rev  
- restart/reload Suricata

📸 Placeholder: rules file screenshot.

---

## 2. Test

- replay PCAP (tcpreplay) or generate traffic  
- confirm alert fired  
- review eve.json logs

📸 Placeholder: alert log.

---

## 3. Tune

- adjust content/offset/depth  
- refine flow directions  
- reduce false positives

📸 Placeholder: before/after rule.

---
