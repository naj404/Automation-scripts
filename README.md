# SysAdmin Automation Scripts

This repository contains automation scripts used in my System Administrator home lab projects.

## Scripts

### 1. Linux Health Check Script (Bash)

File: sysinfo.sh

This script collects basic system health information including:
- Hostname
- System uptime
- Disk usage
- Memory usage

Example commands used:
hostname
uptime
df -h
free -m

### 2. Active Directory User Report Script (PowerShell)

File: ad_report.ps1

This script exports all Active Directory users to a CSV report.

Command used:
Get-ADUser -Filter * | Select Name, SamAccountName | Export-Csv

Output:
AD_Users_Report.csv

## Skills Demonstrated

- Linux administration
- Bash scripting
- Windows Server administration
- Active Directory management
- PowerShell automation
