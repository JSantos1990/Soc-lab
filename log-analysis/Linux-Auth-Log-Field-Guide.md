# 🔐 Linux Auth Log Field Guide

Quick reference for analyzing `/var/log/auth.log`.

---

## 📘 1. Common Entries

- Failed password for <user> from <ip>  
- Accepted password for <user>  
- Invalid user <name>  
- sudo: <user> : TTY=... ; PWD=... ; COMMAND=...  

📸 Placeholder: auth.log snippet.

---

## 🔍 2. What to Watch

- many failures from one IP  
- logins for non-existent users  
- sudo usage spikes  
- root logins (if allowed)

---

## 🧭 3. Useful Commands

- `grep "Failed password" /var/log/auth.log`  
- `grep "sudo" /var/log/auth.log`  
- `last -a`

📸 Placeholder: command output.

---
