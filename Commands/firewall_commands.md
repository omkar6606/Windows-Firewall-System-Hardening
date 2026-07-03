\# Windows Firewall Configuration Commands



This file contains all PowerShell and Command Prompt commands used during the Windows Firewall Configuration and System Hardening project.



\---



\# System Information



```cmd

hostname

```



Displays the computer hostname.



\---



```cmd

whoami

```



Displays the currently logged-in user.



\---



```cmd

ipconfig /all

```



Displays complete network configuration.



\---



\# Windows Firewall



```powershell

Get-NetFirewallProfile

```



Displays the status of Domain, Private, and Public firewall profiles.



\---



```powershell

Get-NetFirewallRule

```



Lists all firewall rules.



\---



```powershell

Get-NetFirewallRule | Where-Object {$\_.DisplayName -like "CG\_\*"} | Format-Table DisplayName, Enabled, Direction, Action

```



Displays all custom firewall rules created during this project.



\---



```cmd

netsh advfirewall firewall show rule name=all

```



Displays all configured Windows Firewall rules.



\---



\# Microsoft Defender



```powershell

Get-MpComputerStatus

```



Displays Microsoft Defender Antivirus status.



\---



```powershell

Get-MpComputerStatus | Select AntivirusEnabled,RealTimeProtectionEnabled,AMServiceEnabled

```



Verifies antivirus, real-time protection, and Defender service status.



\---



\# Secure Boot



```powershell

Confirm-SecureBootUEFI

```



Verifies whether Secure Boot is enabled.



\---



\# Firewall Verification



```powershell

Get-NetFirewallProfile | Format-Table Name, Enabled

```



Verifies that all firewall profiles are enabled.



\---



\# User Account Verification



```cmd

net user

```



Lists all local user accounts.



\---



```cmd

net user Guest

```



Displays the status of the Guest account.



\---



\# Windows Security Verification



The following Windows Security features were manually verified using the Windows Security application:



\- Microsoft Defender Antivirus

\- Windows Defender Firewall

\- Core Isolation

\- Memory Integrity

\- Local Security Authority Protection

\- Device Encryption

\- Windows Update

\- User Account Control (UAC)



\---



\# Custom Firewall Rules Implemented



| Rule Name | Protocol | Port | Action |

|------------|----------|------|--------|

| CG\_HTTP\_Allow | TCP | 80 | Allow |

| CG\_HTTPS\_Allow | TCP | 443 | Allow |

| CG\_SSH\_Allow | TCP | 22 | Allow |

| CG\_FTP\_Block | TCP | 21 | Block |

| CG\_Telnet\_Block | TCP | 23 | Block |



\---



\# Project Outcome



The Windows system was successfully hardened by:



\- Enabling Windows Defender Firewall

\- Configuring secure inbound firewall rules

\- Blocking insecure network services

\- Verifying Microsoft Defender Antivirus

\- Confirming Secure Boot status

\- Enabling Device Encryption

\- Verifying Windows Security protections

\- Disabling Guest Account

\- Maintaining Windows Update configuration

