# Kioptrix Level 3 – Penetration Testing Walkthrough

A practical penetration-testing walkthrough of Kioptrix Level 3 from VulnHub, documenting the complete assessment process from initial reconnaissance to root access.

## Machine Information

| Category | Details |
|---|---|
| Machine | Kioptrix Level 3 |
| Platform | VulnHub |
| Difficulty | Beginner / Intermediate |
| Target OS | Linux |
| Attacker OS | Kali Linux |
| Focus | Web Security & Linux Privilege Escalation |

## Attack Surface & Techniques

- Network Reconnaissance
- Nmap Service Enumeration
- Web Application Enumeration
- Directory Discovery using DIRB and Nikto
- LotusCMS Vulnerability Research
- SQL Injection Detection and Exploitation
- Database Enumeration using SQLmap
- Password Hash Analysis and Cracking
- SSH Authentication
- Linux Post-Exploitation
- Sudo Misconfiguration
- HT Editor Privilege Escalation
- Kernel Exploit Investigation

## Attack Paths

### Path 1 – SQL Injection

SQL Injection → Database Enumeration → Credential Extraction → Password Cracking → SSH Access → Linux Privilege Escalation.

### Path 2 – LotusCMS RCE

LotusCMS Vulnerability → Remote Code Execution → Reverse Shell → Post-Exploitation → Linux Privilege Escalation.

## Tools Used

- Kali Linux
- Nmap
- DIRB
- Nikto
- SearchSploit
- Metasploit
- SQLmap
- John the Ripper
- Netcat
- SSH

## Key Learning Outcomes

- Identifying potential web application attack surfaces.
- Understanding SQL Injection and database enumeration.
- Investigating publicly documented software vulnerabilities.
- Understanding credential reuse and password hash cracking.
- Performing Linux post-exploitation enumeration.
- Identifying excessive sudo permissions.
- Exploiting privileged application misconfigurations.

## Documentation

The complete walkthrough includes the methodology, commands, explanations, screenshots, findings, and lessons learned.

**Medium Article:** [Insert your published Medium article URL here]

## Disclaimer

This documentation is intended strictly for educational purposes and authorized penetration-testing environments.

All testing was performed against an intentionally vulnerable virtual machine in an isolated lab environment.
