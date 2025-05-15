# Final-Project-DEPI-
# Penetration Testing Reports

This repository contains detailed penetration testing reports for various systems, machines, and web applications. It documents vulnerabilities discovered during testing, proof-of-concept exploits, and remediation strategies to enhance security.

## Overview

This project demonstrates comprehensive penetration testing methodologies applied to various targets, including virtual machines, web applications, and services. The findings highlight security weaknesses and provide actionable recommendations for remediation.

---

### **Included Reports**
1. **Kioptrix Levels 3 & 4**
   - **Vulnerabilities**: SQL Injection, Privilege Escalation.
   - **Tools Used**: SQLmap, manual MySQL exploitation.
   - **Impact**: Unauthorized data access and system compromise.

2. **MR-Robot Machine**
   - **Vulnerabilities**: WordPress misconfigurations, Reverse Shell, SUID exploitation.
   - **Tools Used**: WPScan, reverse shell scripts, privilege escalation techniques.
   - **Impact**: Gained root access.

3. **Stapler 1 and VulnOS 2**
   - **Vulnerabilities**: Anonymous FTP login, SSH brute force, SQL injection.
   - **Tools Used**: Hydra, SQLmap.
   - **Impact**: Exposed sensitive data and credentials.

4. **OWASP Juice Shop Report**
   - **Vulnerabilities**: Cross-Site Scripting (XSS), Insecure Direct Object References (IDOR), SQL Injection.
   - **Tools Used**: Burp Suite, browser-based manual testing.
   - **Impact**: Compromised web application functionality and sensitive data.

5. **PermX Graduation Project**
   - **Vulnerabilities**: Weak ACL settings, exposed subdomains, symlink abuse.
   - **Tools Used**: LinPEAS, enumeration scripts.
   - **Impact**: Unauthorized access and privilege escalation.

---

### **Methodology**
The penetration testing process involves:
1. **Enumeration**: Identifying open ports, services, and potential entry points.
2. **Vulnerability Assessment**: Analyzing misconfigurations, outdated software, and security loopholes.
3. **Exploitation**: Leveraging discovered vulnerabilities to demonstrate system compromise.
4. **Post-Exploitation**: Gaining further access, privilege escalation, and sensitive data extraction.
5. **Reporting**: Documenting findings with proof-of-concept exploits and recommendations.

---

### **Tools Used**
- **Enumeration**: Nmap, Gobuster, WPScan, LinPEAS.
- **Exploitation**: Metasploit, SQLmap, custom scripts.
- **Post-Exploitation**: Reverse shell techniques, privilege escalation methods.
- **Analysis**: Burp Suite, manual verification.

---

### **Findings and Impact**
The reports emphasize:
- Identification of critical vulnerabilities like SQL Injection, Privilege Escalation, and Anonymous FTP access.
- Practical exploitation examples with proof-of-concept scripts and screenshots.
- High-level severity assessments to prioritize remediation efforts.

---

### **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone https://github.com/Moaaz104/penetration-testing-reports.git
