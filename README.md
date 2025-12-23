# Rekall Penetration Test Report

This repository contains a comprehensive penetration testing engagement conducted
against Rekall Corporation systems, including web applications, Linux and Windows hosts,
and internal network services.

## Contents

- Full penetration testing report (PDF)
- Exploit evidence screenshots
- Network, web, and system-level attack demonstrations

## Report

The complete assessment report is available here:
 **[Open Full Penetration Test Report](report/Rekall-Penetration-Test-Report.pdf)**

## Screenshots

Selected screenshots demonstrating confirmed vulnerabilities and successful exploitation
can be found here:
**[Open Screenshots Folder](screenshots/)**


## Skills Demonstrated

- Web application penetration testing (XSS, SQLi, LFI, RCE)
- Network reconnaissance and enumeration
- Exploitation using Metasploit and manual payloads
- Post-exploitation and credential dumping
- Security reporting, analysis, and documentation

## Key Findings 

- **Critical** – SQL Injection allowing authentication bypass
- **Critical** – Remote Code Execution via Apache Tomcat
- **High** – Stored and Reflected Cross-Site Scripting (XSS)
- **High** – Local File Inclusion exposing system files
- **High** – Credential dumping via post-exploitation tooling

## Tools & Techniques

- Nmap – network discovery and service enumeration
- Metasploit – exploitation and post-exploitation
- Burp Suite – web application testing
- Manual payload crafting (XSS, SQLi, LFI, command injection)
- Credential dumping and privilege escalation techniques


**All testing done for educational purposes only.**
