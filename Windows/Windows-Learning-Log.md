# Windows Learning Log

This document records my progress while learning Windows administration, security, and PowerShell.

---

## Entry 001 - Introduction to Windows

**Date:** 21 July 2026

**Focus:** Understanding the Windows operating system, its role in cybersecurity, and basic system information gathering.

### Topics Covered

- Windows Desktop vs Windows Server
- Evolution of Windows operating systems
- Active Directory introduction
- Windows versioning
- Windows support lifecycle
- Windows Management Instrumentation (WMI)
- PowerShell `Get-WmiObject`

### Commands Practised

- `Get-WmiObject -Class Win32_OperatingSystem | Select Version, BuildNumber` - Display the Windows version and build number.
- `Get-WmiObject -Class Win32_Process` - List running processes.
- `Get-WmiObject -Class Win32_Service` - List installed services.
- `Get-WmiObject -Class Win32_BIOS` - Display BIOS information.

### Reflection

I began learning Windows fundamentals and why they are essential for penetration testing. Since Windows is one of the most widely deployed operating systems in enterprise environments, understanding its administration, security features and common components is crucial for both attacking and defending systems.

I learned the distinction between Windows Desktop and Windows Server editions, the significance of technologies such as Active Directory, and why security professionals need to recognise supported and legacy versions of Windows. I also had my first exposure to Windows Management Instrumentation (WMI) and learned how PowerShell can be used to retrieve information about the operating system, processes, services and BIOS.

### Next Steps

- Continue the Windows Fundamentals module.
- Learn the Windows file system and directory structure.
- Become familiar with common administrative tools and PowerShell.
