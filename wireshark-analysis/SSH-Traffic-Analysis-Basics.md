# 🔑 SSH Traffic Analysis Basics

This document explains SSH traffic patterns and indicators useful in SOC cases.

---

## 📘 1. SSH Overview

- encrypted remote shell  
- default port 22/tcp (may vary)

📸 Placeholder: SSH session metadata.

---

## 🔍 2. Suspicious Indicators

- many short connections (brute force)  
- login success after many failures  
- SSH on non-standard ports  
- odd client versions/user-agents

📸 Placeholder: connection timeline.

---

## 🧭 3. Tips in Wireshark

- filter: tcp.port == 22  
- analyze packet lengths and timings  
- correlate with auth logs on the host

📸 Placeholder: Wireshark filter bar.

---

## 📝 4. Notes

Deeper SSH case studies will be added later.

---
