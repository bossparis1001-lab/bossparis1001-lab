# TryHackMe – Kenobi

## Overview

Room-kan waxaan ku bartay enumeration, SMB analysis, iyo privilege escalation.

## Objective

Goal-ku wuxuu ahaa in la helo user access kadibna root privilege la gaaro.

## Tools Used

* Nmap
* SMBClient
* SSH

## Enumeration

### Nmap Scan

bash
nmap -sC -sV -A <TARGET-IP>


### Findings

Ports-ka muhiimka ah:

* 21 FTP
* 22 SSH
* 80 HTTP
* 111 RPC

## Exploitation

Waxaan helay weak configuration oo ii oggolaatay inaan helo access.

bash
smbclient -L //<TARGET-IP>/


## Privilege Escalation

Privilege escalation waxaa lagu gaaray misconfiguration.

## Lessons Learned

* Enumeration waa tallaabada ugu muhiimsan.
* SMB mar walba si qoto dheer u baar.
* Linux privilege escalation pathways waa muhiim.

## Skills Demonstrated

* Network Enumeration
* Linux Privilege Escalation
* Service Enumeration
