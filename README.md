# Task-1-
# 🛡️ Cyber Security Internship – Task 1

## 🔍 Objective
Scan the local network to identify devices and their open TCP ports to understand potential security exposure.

## 🛠️ Tools Used
- **Kali Linux**
- **Nmap** v7.95

## 🌐 Network Details
- **Scanner IP**: 192.168.153.129
- **Scanned Range**: 192.168.153.0/24

## 📊 Scan Summary

**Command used**:
```bash
nmap -sS 192.168.153.0/24 -oN scan_results.txt
