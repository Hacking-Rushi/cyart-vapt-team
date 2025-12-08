# Security Assessment & VAPT Lab on Metasploitable

Comprehensive Vulnerability Assessment and Penetration Testing (VAPT) project using open-source tools on the Metasploitable vulnerable machine.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yourusername/security-vapt-lab/blob/main/LICENSE)
[![OpenVAS](https://img.shields.io/badge/Tool-OpenVAS-green.svg)](https://www.greenbone.net/en/)
[![Nmap](https://img.shields.io/badge/Tool-Nmap-orange.svg)](https://nmap.org/)
[![Nikto](https://img.shields.io/badge/Tool-Nikto-red.svg)](https://cirt.net/Nikto2)
[![Metasploit](https://img.shields.io/badge/Tool-Metasploit-purple.svg)](https://www.metasploit.com/)

## 🎯 Project Overview

Hands-on security assessment lab demonstrating:
- **Network reconnaissance** with Nmap
- **Web vulnerability scanning** with Nikto
- **Comprehensive vulnerability assessment** with OpenVAS
- **Exploit validation** with Metasploit Framework
- **Risk assessment** using CVSS scoring
- **Compliance mapping** (ISO 27001, GDPR, HIPAA, OWASP Top 10)

## 🛠️ Tools Used

| Tool | Purpose | Key Commands |
|------|---------|-------------|
| **Nmap** | Network discovery & service enumeration | `nmap -sS -sV -O <target>` |
| **Nikto** | Web server vulnerability scanning | `nikto -h <target>` |
| **OpenVAS** | Comprehensive vulnerability scanning | Web UI scanning |
| **Metasploit** | Exploit development & validation | `msfconsole` |

## 🔍 Key Findings

### Critical Vulnerabilities Discovered
| Vulnerability | CVSS Score | Service | Risk Level |
|---------------|------------|---------|------------|
| CVE-2017-12617 (Tomcat RCE) | 9.8 | Apache Tomcat | **Critical** |
| CVE-2019-0708 (BlueKeep) | 8.1 | RDP | **High** |
| Directory Listing | 5.4 | Apache HTTP | **Medium** |

## 📋 Lab Setup Instructions

### Prerequisites
- VirtualBox or VMware
- Kali Linux VM
- Metasploitable 3 VM

### Quick Setup