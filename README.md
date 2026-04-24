# Hi, I'm Pashtrik Shabani

### Bug Bounty Hunter | Independent Security Researcher | CS Student

I am an offensive security researcher specializing in web application vulnerabilities, network infrastructure, and secure development. I bridge the gap between academic computer science theory and real-world cybersecurity by building custom applications, engineering isolated network environments, and executing full-chain attack simulations. 

My methodology focuses on the complete security lifecycle: **Architecting** the infrastructure, **Building** the application, **Exploiting** the vulnerabilities, and **Patching** the code.

---

## 🛠️ The Arsenal (Technical Stack)
* **Offensive Security:** Kali Linux, Nmap, Burp Suite, Hydra, SQLmap, Metasploit, Wireshark
* **Web Development:** PHP 8, MySQL / MariaDB, JavaScript, HTML5/CSS3
* **Networking & Infrastructure:** TCP/IP, Subnetting, VLANs, Virtualization (VirtualBox, Proxmox, Host-Only/NAT)
* **Defense & Remediation:** OWASP Top 10, Prepared Statements, Input Sanitization, BCrypt/Argon2 Hashing
* **Python Essentials 1** | *Cisco Networking Academy* (2026)
  * [Verify Certification](https://www.credly.com/badges/882c2934-0fb7-48db-a9dd-e2b187dddeb5/public_url)
  * Skills: Procedural Programming, Algorithmic Logic, Python Data Structures.
* **Introduction to Programming Using Java** | *UBT Professional School* (2022)
  * Credential ID: 19828/2-10 (30 Hours Training)
  * Skills: Object-Oriented Programming (OOP), Data Structures, Java Syntax.

---

## Featured Security Research & Projects

### 1. [Full-Stack Web App Penetration Testing Lab](https://github.com/pashtrik-labs/PayGearPlan-Pentest) *(The "Breaker" Phase)*
*An end-to-end offensive security audit of a custom e-commerce environment.*
* **The Exploit Chain:** Executed a 12-stage attack lifecycle starting from Nmap reconnaissance to exploiting UNION-based SQL Injection for data dumping and authentication bypass.
* **Weaponization:** Escalated a Stored XSS vulnerability into an invisible, weaponized payload to silently exfiltrate administrative session cookies (`PHPSESSID`) over the network via a Python HTTP listener, resulting in complete Account Takeover.
* **Remediation:** Authored a comprehensive Blue Team patching guide focusing on parameterized queries and output encoding.

### 2. [PayGearPlan: Secure E-Commerce Development](https://github.com/pashtrik-labs/PayGearPlan) *(The "Builder" Phase)*
*A custom PHP/MySQL web application built from scratch to serve as a vulnerable target and security hardening lab.*
* **Architecture:** Developed a dynamic storefront featuring client registration, session management, product CRUD operations, and a segregated Admin Control Panel.
* **Security Focus:** Engineered specifically to test defenses against the OWASP Top 10, focusing on mitigating Broken Access Control, Cryptographic Failures, and Injection flaws in a localized XAMPP/LAMP environment.

### 3. [Network Service Brute-Forcing & Enumeration Lab](https://github.com/pashtrik-labs/Network-Exploitation-Labs)
*A controlled, isolated infrastructure lab demonstrating network service exploitation.*
* **Environment:** Engineered a secure, Host-Only VirtualBox network isolating a Kali Linux attacker machine and a Metasploitable2 target.
* **Execution:** Conducted comprehensive service enumeration using `nmap -sV` to identify open ports (SSH, HTTP), followed by targeted, dictionary-based credential brute-forcing using `Hydra` and the `rockyou.txt` wordlist to gain unauthorized system access.

### 4. [Advanced 2-Layer Home Lab Network Architecture](https://github.com/pashtrik-labs/network-intrusion-lab)
*A hybrid physical and virtual infrastructure designed for traffic analysis and network segmentation.*
* **Infrastructure:** Combined physical hardware nodes with virtualized environments to simulate enterprise-level network complexities.
* **Simulations:** Focused on network segmentation bypassing, internal attack simulation, service enumeration, and centralized logging to analyze the traffic signatures of common exploitation tools.

---

## 🛡️ Red Team Laboratory & Adversarial Research

I maintain a high-performance, isolated virtualization environment designed for **adversarial simulation** and **security research**. This multi-node lab allows me to safely execute and analyze complex attack vectors across physical and virtual systems.

### **Multi-Node Lab Architecture**
* **Hypervisor:** **Proxmox VE** (Type-1 Hypervisor) – Dedicated server hosting a variety of "Victim" VMs, legacy Windows systems, and my custom **PayGearPlan** (PHP/MySQL) testing environment.
* **Primary Attacker (Node 1):** **HP ZBook** (Ubuntu/Kali Linux) – Optimized for high-speed network reconnaissance, vulnerability scanning, and payload delivery.
* **Secondary Attacker (Node 2):** **Dell Latitude** (Kali Linux VM) – Utilized for coordinated brute-force attacks and testing concurrent adversarial persistence.
* **Support Node:** **Toshiba Laptop** – Used for real-time monitoring, documentation, and traffic capture analysis.

### **Research & Testing Focus**
* **Coordinated Adversarial Simulations:** Utilizing the dual-node setup (HP & Dell) to simulate multi-vector attacks and distributed brute-forcing.
* **Exploitation & Malware Analysis:** Executing malicious payloads within a Proxmox sandbox to analyze execution patterns and persistence mechanisms.
* **Web Application Pentesting:** Using custom PHP/MySQL projects as targets to identify SQL Injection (SQLi) and Cross-Site Scripting (XSS).
* **Network Pivoting & Lateral Movement:** Simulating movement across segmented virtual subnets to understand how attackers escalate access within a network.
* **Traffic Analysis:** Monitoring "East-West" traffic between nodes to identify attack signatures and refine detection logic.

> [!IMPORTANT]
> **Ethics & Safety:** All activities are conducted within a strictly isolated, host-only network. This lab is used exclusively for educational purposes, skill development, and authorized white-hat security research.

---

## Current Focus & Research
* **Bug Bounty Hunting & Vulnerability Research:** Translating lab-based exploit chains into the wild. Actively hunting for high-impact, undocumented vulnerabilities in live production environments and bug bounty programs.
* **Offensive Security & Exploit Mechanics:** Intensely focused on how things can be cracked. Moving beyond automated tools to understand the core logic of how systems, authentications, and defenses are actively bypassed.
* **Infrastructure & Network Engineering:** Deeply fascinated by how networks work under the hood. Designing and building secure network architectures from the ground up to deeply understand the environment before tearing it apart.
* **Web Application Penetration Testing:** Deconstructing modern full-stack web applications to discover exactly how websites are cracked, bypassing firewalls, and weaponizing vulnerabilities for full system compromise.

---

### 🤝 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/pashtrik-shabani-93928b31b/)

