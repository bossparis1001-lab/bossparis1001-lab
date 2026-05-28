# TryHackMe – Kenobi

## Overview
Room-kan waxaan ku bartay enumeration, SMB analysis, file sharing misconfigurations, iyo privilege escalation fundamentals.

## Objective
Goal-ku wuxuu ahaa in la helo user access kadibna root (admin) privilege la gaaro.

## Tools Used
- Nmap
- SMBClient
- Netcat
- SSH

## Enumeration

### Nmap Scan
```bash
nmap -sC -sV -A <TARGET-IP>
