# IT Support Lab

This repository contains my hands-on IT support and system administration learning projects.

## Project Goals
- Learn networking fundamentals
- Practice troubleshooting commands
- Document technical work
- Build a professional portfolio

## Completed Labs

### Day 1 - Network Basics
- Used `ipconfig` to view network configuration
- Used `ping google.com` to test internet connectivity
- Used `tracert google.com` to trace the route to Google
- Documented findings and observations

## Skills Practiced
- Network troubleshooting
- Command-line tools
- Technical documentation
- Git and GitHub

## Tools Used
- Windows PowerShell
- Git
- GitHub
- VS Code

## Day 2 - Windows Troubleshooting Basics

- Used systeminfo to gather system details
- Used hostname to identify the computer
- Used whoami to identify the logged-in user
- Practiced documenting troubleshooting activities

### Day 3 - Windows Services

Commands Used:
- Get-Service
- Get-Service | findstr DHCP
- Get-Service | findstr DNS
- Get-Service | findstr Spooler

Skills Learned:
- Windows service management
- Service monitoring
- Troubleshooting background processes

## Day 4 – Users, Groups and NTFS Permissions

Topics covered:

* Local users
* Local groups
* Administrator membership
* File creation
* NTFS permissions
* Access Control Lists (ACLs)

Detailed notes are available in:

`Day4-Users-NTFS.md`

# Day 5 - Windows Process Management with PowerShell

## Objective

The objective of this exercise was to learn how to monitor running processes in Windows using PowerShell. Understanding processes helps system administrators identify resource usage, troubleshoot performance issues, and monitor system health.

---

## Commands Executed

### Display all running processes

```powershell
Get-Process
