# TryHackMe – Kenobi

## Overview
This room focused on SMB enumeration, misconfigurations, and privilege escalation techniques.

## Objective
Gain initial access and escalate privileges to root.

## Tools Used
- Nmap
- SMBClient
- Netcat
- SSH

## Enumeration

### Nmap Scan
```bash
nmap -sC -sV -A <TARGET-IP>
