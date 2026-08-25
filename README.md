[Cybersecurity Home Lab.md](https://github.com/user-attachments/files/31441675/Cybersecurity.Home.Lab.md)

# Cybersecurity Home Lab

A hands-on cybersecurity home lab focused on building practical experience with **Active Directory, SIEM monitoring, security event investigation, detection, troubleshooting, and defensive security**.

This repository documents the lab as it develops, including configuration decisions, security testing, troubleshooting, and evidence collected during each project.

## Current Environment

- Windows Server 2022 Active Directory
- Windows 10 domain-joined endpoints
- Wazuh SIEM
- Ubuntu Server
- VMware Workstation
- Raspberry Pi / Linux security workstation

## Projects

### 01 — Active Directory Security Monitoring with Wazuh

Built centralized security monitoring for an Active Directory environment using Wazuh.

The project included:

- Wazuh agent deployment and endpoint enrollment
- Active Directory account creation monitoring
- Security group membership monitoring
- Successful and failed authentication analysis
- Kerberos pre-authentication failure monitoring
- Windows Advanced Audit Policy configuration
- Event correlation between a workstation and domain controller
- Troubleshooting and resolving a security-monitoring visibility gap

**[View the full project →](projects/01-active-directory-wazuh/README.md)**

## Lab Direction

Future phases of the lab will continue expanding into areas such as:

- SOC detection and investigation
- Network monitoring and IDS
- Active Directory attack and defense
- Security hardening
- Cloud security
- Azure and Entra ID
- Hybrid on-premises and cloud monitoring

## Purpose

The goal of this lab is not simply to install security tools, but to understand how security telemetry is generated, collected, analyzed, correlated, and investigated in an environment designed to resemble real-world enterprise infrastructure.
