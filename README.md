# Basic Pentesting: 1 – Exploitation Walkthrough

This repository contains my personal penetration-testing practice report for the
*Basic Pentesting: 1* VulnHub machine.  
The goal of this project was to identify exposed services, analyze 
misconfigurations, and perform a safe proof-of-concept exploitation inside a
controlled lab environment.

## ⚡ Objective
- Enumerate the target system using Nmap  
- Identify the vulnerable ProFTPD 1.3.3c service  
- Use Nmap NSE scripts to verify the backdoor vulnerability  
- Exploit the service using Metasploit  
- Gain shell access and validate successful compromise  

## 🛠 Tools & Requirements
- Kali Linux (Attacker)
- Basic Pentesting: 1 VM (Victim)
- Nmap for scanning and script execution
- Metasploit Framework for exploitation
- Screenshots stored in /screenshots/ directory

## 📂 Documentation Structure
- *01–07* screenshots demonstrating scanning, script usage, exploit selection,
  payload configuration, execution, and final shell access.
- *notes.txt* contains all commands used during enumeration and exploitation.

## ⚠ Legal Notice
This project was performed ONLY in a private, isolated lab environment for
learning purposes.  
Do *not* use these techniques on systems without explicit authorization.
