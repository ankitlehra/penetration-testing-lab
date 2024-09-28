# Penetration Testing Lab

## Description
The **Penetration Testing Lab** project simulates various penetration testing scenarios using a controlled lab environment. The lab setup consists of three virtual machines—Kali Linux (attacker machine), Metasploitable3 (vulnerable target), and a Windows Domain Controller (DC1)—designed to provide a realistic environment for practicing information gathering, vulnerability scanning, and exploitation techniques.

The main focus of the lab is to demonstrate:
- **Information Gathering** using Nmap to discover live hosts and perform OS fingerprinting.
- **Vulnerability Scanning** to identify services and potential exploits using tools like Metasploit.
- **Exploitation** of known vulnerabilities such as the MS17-010 (EternalBlue), which allows remote code execution on the target.
- **Database Enumeration** through brute-forcing credentials to access MySQL databases and extract sensitive information.
- **Service Scanning and Exploitation** using Nmap scripts to identify and exploit additional services.

The lab documents all the steps and commands used, making it an excellent resource for beginners looking to understand penetration testing workflows.

## Objectives
- Understand how to set up a virtual lab for penetration testing.
- Practice various reconnaissance and scanning techniques.
- Exploit known vulnerabilities to gain access to systems.
- Conduct database enumeration to extract information from vulnerable servers.
- Document findings and create a reusable script for automation.

## Tools & Technologies Used
- **Kali Linux** (Attacker Machine)
- **Metasploitable3** (Vulnerable Target)
- **Windows Domain Controller (DC1)** (For Active Directory testing)
- **Nmap** (Network Scanning)
- **Metasploit Framework** (Exploitation Framework)
- **MySQL** (Database Target)
- **VirtualBox**  (Virtualization Platform)

## Project Commands Script
The project commands have been consolidated into a single script file named `penetration_lab_script.sh`. This file includes all the necessary commands executed during the lab, covering:

- Information gathering using `nmap`
- Scanning for vulnerabilities using `nmap` and Metasploit
- Running exploits against identified vulnerabilities
- Performing database enumeration and extraction

## Screenshots
1. **Initial Metasploit Setup**:
   *Description*: This screenshot shows the initial setup of Metasploit, with the selected EternalBlue module.

2. **Successful Exploit Output**:
   *Description*: Demonstrates a successful execution of the MS17-010 exploit.

3. **MySQL Database Enumeration**:
   *Description*: Shows database enumeration using brute-forced credentials.
