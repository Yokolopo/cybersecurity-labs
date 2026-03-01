# WinRM Service Exploitation Using Metasploit

## Objective
Fingerprint the Windows Remote Management (WinRM) service and exploit it to gain Meterpreter access on the target system.

---

## Lab Environment
- Attacker Machine: Kali Linux
- Target Machine: demo.ine.local
- Environment: INE Cybersecurity Lab

---

## Tools Used
- Nmap
- Metasploit Framework

---

## Methodology

### 1. Service Discovery
Performed network scanning to identify open ports and running services.

### 2. WinRM Fingerprinting
Identified Windows Remote Management (WinRM) service running on the target host.

### 3. Vulnerability Exploitation
Used Metasploit exploit and auxiliary modules targeting WinRM.

### 4. Meterpreter Access
Successfully obtained a Meterpreter session on the target machine.

### 5. Flag Retrieval
Navigated system directories and retrieved the lab flag.

---

## Findings
- WinRM service exposed externally
- Weak configuration allowed remote exploitation
- Remote command execution achieved

---

## Security Recommendations
- Restrict WinRM exposure
- Enforce strong authentication
- Limit remote management access via firewall
- Monitor WinRM activity in SIEM solutions

---

## Skills Demonstrated
- Network Enumeration
- Service Fingerprinting
- Metasploit Exploitation
- Post-Exploitation
- Remote Access Techniques
