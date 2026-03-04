# 🌐 Web Server Logs Cheat Sheet

Basics for Apache/Nginx access/error logs.

---

## 📘 1. Access Log Fields

- IP, timestamp, method, path, status, bytes, referrer, user-agent

📸 Placeholder: access log line.

---

## 🔍 2. Suspicious Patterns

- many 404/401 from same IP  
- long/encoded URLs  
- unusual methods (PUT/DELETE)  
- scanning for `/admin`, `/phpmyadmin`

📸 Placeholder: grep results.

---

## 🧭 3. Useful Commands

- `awk '{print $1}' access.log | sort | uniq -c | sort -nr | head`  
- `grep -i "wp-admin" access.log`

---
