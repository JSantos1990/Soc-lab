# 🔐 TLS Basics for SOC Analysts

This document introduces TLS concepts relevant for network investigations and packet analysis.

---

## 📘 1. What Is TLS?

TLS (Transport Layer Security) provides encrypted communication and server authentication.

- replaces SSL  
- used in HTTPS, IMAPS, SMTPS, VPNs  

📸 Placeholder: TLS handshake diagram.

---

## 🔍 2. Why TLS Matters in SOC

- encrypted traffic can hide malicious activity  
- certificate details may reveal anomalies  
- SNI and JA3 fingerprints can aid detection  

📸 Placeholder: Wireshark TLS details pane.

---

## 🧭 3. Investigation Tips

- check SNI (server name)  
- inspect certificate issuer/validity  
- look for unusual ports using TLS  
- analyze flow metadata (size/frequency)

📸 Placeholder: certificate info screenshot.

---

## 📝 4. Notes

Advanced TLS hunting examples will be added later.

---
