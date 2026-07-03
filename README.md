# 🛡️ Windows Firewall Configuration & System Hardening

> A practical cybersecurity project demonstrating Windows Defender Firewall configuration, operating system hardening, and endpoint security using native Windows 11 security features.

![Windows](https://img.shields.io/badge/Platform-Windows%2011-blue?style=for-the-badge)
![PowerShell](https://img.shields.io/badge/PowerShell-5.1+-5391FE?style=for-the-badge)
![Firewall](https://img.shields.io/badge/Firewall-Windows%20Defender-red?style=for-the-badge)
![Security](https://img.shields.io/badge/Cybersecurity-System%20Hardening-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

# 📌 Project Overview

This project demonstrates the implementation of Windows Defender Firewall Configuration and Windows System Hardening using native Microsoft Windows security features. The project focuses on improving endpoint security by configuring custom firewall rules, verifying Windows security controls, and applying system hardening best practices. It was completed as part of the Cognetix Technology Cyber Security Internship, showcasing practical skills in Windows administration, endpoint protection, and security hardening.

---

# 🎯 Objectives

- Configure Windows Defender Firewall
- Create custom inbound firewall rules
- Allow secure network services
- Block insecure network services
- Verify firewall configuration using PowerShell
- Implement Windows System Hardening
- Verify built-in Windows Security Features
- Improve overall endpoint security

---

# 🛠️ Technologies & Tools

- Windows 11
- Windows Defender Firewall
- Windows Security
- Windows PowerShell
- Command Prompt
- Microsoft Defender Antivirus
- Secure Boot
- Trusted Platform Module (TPM)
- Device Encryption
- User Account Control (UAC)

---

# 🔥 Firewall Rules Implemented

| Rule Name | Port | Protocol | Action |
|-----------|------|----------|--------|
| CG_HTTP_Allow | 80 | TCP | Allow |
| CG_HTTPS_Allow | 443 | TCP | Allow |
| CG_SSH_Allow | 22 | TCP | Allow |
| CG_FTP_Block | 21 | TCP | Block |
| CG_Telnet_Block | 23 | TCP | Block |

---

# 🔒 Windows Security Features Verified

- ✅ Microsoft Defender Antivirus
- ✅ Windows Defender Firewall
- ✅ Secure Boot
- ✅ Trusted Platform Module (TPM)
- ✅ Core Isolation
- ✅ Memory Integrity
- ✅ Device Encryption
- ✅ Windows Update
- ✅ User Account Control (UAC)
- ✅ Guest Account Disabled

---

# 📂 Project Structure

```
Windows-Firewall-System-Hardening/
│
├── README.md
├── LICENSE
│
├── report/
│   └── Windows_Firewall_Configuration_and_System_Hardening_Report.pdf
│
├── screenshots/
│   ├── 01_Baseline_Assessment/
│   ├── 02_Firewall_Status/
│   ├── 03_Firewall_Configuration/
│   ├── 04_System_Hardening/
│   └── 05_Firewall_Testing/
│
├── commands/
│   └── firewall_commands.md
│
└── assets/
```

---

# 📸 Project Screenshots

## Windows Security Dashboard

---

## Firewall Configuration


---

## Firewall Verification


---

## Windows System Hardening



---

# 💻 Commands Used

```powershell
hostname

whoami

ipconfig /all

netsh advfirewall firewall show rule name=all

Get-NetFirewallRule

Get-NetFirewallPortFilter

Get-NetFirewallProfile

Get-MpComputerStatus

Confirm-SecureBootUEFI

net user Guest
```

---

# 📊 Results

The project successfully implemented multiple Windows security controls, including custom firewall rules and operating system hardening measures.

### Security Improvements

- Improved endpoint security
- Reduced attack surface
- Blocked insecure services
- Verified firewall configuration
- Enhanced malware protection
- Enabled hardware-backed security
- Improved operating system resilience

---

# 📖 Learning Outcomes

Through this project, I gained practical experience in:

- Windows Firewall Administration
- Windows Endpoint Security
- PowerShell Administration
- Windows Security Configuration
- System Hardening
- Security Documentation
- Cybersecurity Best Practices

---

# 🚀 Future Enhancements

- Microsoft Defender for Endpoint
- Windows Event Log Monitoring
- SIEM Integration (Splunk / Microsoft Sentinel)
- Automated PowerShell Hardening Scripts
- Firewall Log Analysis
- Vulnerability Assessment
- Security Compliance Auditing

---

# 📚 References

- Microsoft Learn
- Microsoft Security Documentation
- NIST Cybersecurity Framework (CSF)
- CIS Windows Benchmarks
- OWASP Security Guidelines

---

# 👨‍💻 Author

**Omkar Shinde**

Cybersecurity Enthusiast | SOC Analyst | Security Engineer

- GitHub: https://github.com/omkar6606
- LinkedIn: https://www.linkedin.com/in/omkar-shinde-aa928721b

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ If you found this project useful, consider giving it a Star!
