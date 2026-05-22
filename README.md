# Information Security Lab Audit (OEL)

This repository documents a comprehensive security assessment and penetration testing lab, focusing on network reconnaissance, web application vulnerability testing, and defense hardening.

## 🛡 Project Overview
The primary objective of this project was to conduct a controlled security audit of an intentionally vulnerable environment (Metasploitable2/DVWA) to understand attack surfaces and implement defensive security controls.

## 🛠 Key Lab Phases
* [cite_start]**Network Reconnaissance:** Identification of live hosts and open services using Nmap[cite: 4177, 4203].
* [cite_start]**Vulnerability Analysis:** Identification of vulnerable services (e.g., vsftpd 2.3.4, Bindshell) and verification using SearchSploit[cite: 4280, 4408, 4419].
* [cite_start]**Web Security Testing:** Demonstration of SQL Injection vulnerabilities within the DVWA environment at different security levels[cite: 4624, 4699, 4776].
* [cite_start]**Social Engineering Analysis:** Controlled demonstration of email-based trust manipulation using SEToolkit[cite: 4835, 4948].
* [cite_start]**Data Protection:** Implementation of GPG encryption for secure file transfer[cite: 5014, 5085].
* [cite_start]**Firewall Hardening:** Network traffic analysis using Wireshark and firewall rule management using UFW[cite: 5225, 5474, 5508].

## 📂 Repository Structure
```text
InfoSec-OEL/
├── docs/
│   └── Ayesha_AI014_OEL_IS.pdf    # Complete security audit report
└── README.md
