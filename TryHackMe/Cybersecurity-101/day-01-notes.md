# Day 01 - Cybersecurity 101

Date: May 21, 2026

## Concepts Learned

### CVE and CVSS
- CVE stands for Common Vulnerabilities and Exposures
- Every confirmed vulnerability gets a unique identifier format CVE-YEAR-NUMBER
- Acts as a universal dictionary of known vulnerabilities across organizations
- CVSS is the scoring system used to prioritize vulnerabilities
- Score ranges from 0 to 10, higher means more critical
- Score is based on impact, complexity, and availability

### SOC
- Security Operations Centre
- Security analysts play a significant role in an organisations defence
- Primary environment for entry level security roles

### Linux Permissions
- Three levels: Owner, Group, Others
- Three permission types: Read, Write, Execute
- Command to check permissions: ls -l
- ls -la includes hidden files
- Permissions are displayed as rwxrwxrwx format

### Root vs Sudo
- Root is the superuser with unrestricted full system access
- Sudo grants temporary elevated privileges for a single command
- Not all users have sudo access, controlled by the sudoers file
- Running as root full time is bad practice and considered a security risk
- Least Privilege principle: users should only have minimum access needed

### User Management
- su command switches between users
- groups command shows group membership
- id command shows current user information
- cat /etc/group shows all groups and members on the system

## Commands Learned
- ls -l : check file permissions
- ls -la : check permissions including hidden files
- su : switch users
- sudo : temporary elevated access
- groups : view group membership
- id : view current user details
- cat /etc/group : view all system groups

## Key Takeaways
- Permissions control who can read, write, or execute files
- Understanding privilege levels is foundational for both defence and offence
- Least Privilege is a core security principle used across all environments
- Privilege escalation is the process of moving from low to high access on a system
