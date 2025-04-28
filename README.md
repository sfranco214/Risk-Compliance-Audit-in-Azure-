# Enterprise Cloud Audit: Penetration Testing, Security Hardening, and NIST Compliance in Azure

![Enterprise Cloud Audit Screenshot](https://github.com/user-attachments/assets/ab50c86a-2ad3-45a9-9dd7-d360370521fd)

## Introduction

This project is a comprehensive simulation of a real-world cybersecurity consulting engagement. I designed, secured, and audited a cloud-based enterprise network using Microsoft Azure and Kali Linux, following best practices in offensive security, cloud configuration, and compliance mapping to the NIST Cybersecurity Framework (CSF).

This project demonstrates capabilities in risk assessment, vulnerability testing, cloud security hardening, compliance auditing, and professional reporting, aligned to the expectations of a cybersecurity consultant role.

## Project Objectives

- Deploy a simulated enterprise environment in Microsoft Azure
- Conduct penetration testing using Kali Linux tools
- Harden cloud and endpoint systems with Azure-native security features
- Audit compliance against NIST CSF standards
- Deliver technical documentation, dashboards, and executive-level reporting

## Phase 1: Azure Environment Deployment

- Built an isolated Azure Resource Group dedicated to testing and auditing
- Deployed a segmented Virtual Network (VNet) including:
  - Management Subnet: Kali Linux VM and Jump Box
  - Server Subnet: Windows Server 2022 Domain Controller
  - Client Subnet: Windows 10 Client and Ubuntu Web Server
- Configured Network Security Groups (NSGs) to control and restrict traffic
- Joined Windows 10 Client to Active Directory domain
- Secured remote access by limiting RDP and SSH connections to static IPs
- Applied Microsoft Security Baselines to harden virtual machines

## Phase 2: Offensive Testing with Kali Linux

Performed controlled penetration testing activities using a dedicated Kali Linux machine:

| Tool          | Purpose                                 |
|---------------|-----------------------------------------|
| nmap          | Network discovery and port scanning    |
| Nessus        | Vulnerability assessment               |
| Nikto, wpscan, sqlmap | Web application and database testing |
| Metasploit    | Proof-of-con



