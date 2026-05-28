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
## Exploitation
The SMB service was analyzed and misconfigurations were identified which allowed further access.

## Privilege Escalation
System misconfigurations were used to escalate privileges to root.

## Lessons Learned
- Enumeration is the most important phase in penetration testing
- SMB misconfigurations can lead to unauthorized access
- Proper privilege escalation requires careful system analysis
