# 💼 Enterprise Cloud Audit: Penetration Testing, Security Hardening & NIST Compliance in Azure
<img width="556" alt="Screenshot 2025-04-15 at 7 53 31 PM" src="https://github.com/user-attachments/assets/ab50c86a-2ad3-45a9-9dd7-d360370521fd" />


## 👋 Introduction
Hi, I'm Sebastian, and this project is a comprehensive simulation of a real-world cybersecurity consulting engagement. I built, secured, and audited a cloud-based enterprise network using Microsoft Azure and Kali Linux, following best practices in offensive security, cloud configuration, and compliance mapping to the **NIST Cybersecurity Framework (CSF)**.

This project showcases my ability to assess risk, test vulnerabilities, and provide actionable reporting — exactly what’s expected in a cybersecurity consultant role.

## 🎯 Project Objectives
- Deploy a simulated enterprise environment in **Microsoft Azure**
- Use **Kali Linux** tools to conduct controlled penetration testing
- Harden systems and audit compliance using native **Azure security tools**
- Map findings to **NIST CSF**
- Deliver professional **risk assessment documentation**, dashboards, and a consultant-style **presentation**

## 🧱 Phase 1: Azure Environment Deployment
- Set up an **isolated Azure Resource Group** for testing
- Deployed a **Virtual Network (VNet)** with segmentation:
  - `Mgmt Subnet`: Kali + Jump Box
  - `Server Subnet`: Windows Server 2022 (DC)
  - `Client Subnet`: Windows 10 Client + Ubuntu Web Server
- Hardened access using **NSGs** and **static IPs**
- Joined Windows 10 Client to **Active Directory**
- Enabled secure **RDP/SSH** access
- Applied **Microsoft Security Baselines**

## 🛡️ Phase 2: Offensive Testing with Kali Linux
Using a dedicated **Kali Linux VM**, I performed the following:

| Tool            | Purpose                          |
|-----------------|----------------------------------|
| `nmap`          | Network discovery and port scanning |
| `OpenVAS`       | Vulnerability assessment |
| `Nikto`, `wpscan`, `sqlmap` | Web app & database testing |
| `Metasploit`    | Controlled exploitation (non-destructive) |
| `Lynis`         | Hardening audit on Linux targets |

I documented all scan results, screenshots, and findings in `/audit`.

## 🔐 Phase 3: Azure-Native Security Tools
I used **Microsoft Defender for Cloud**, **Azure Policy**, and **Log Analytics** to evaluate cloud-side security:

- 📊 **Defender for Cloud**: Captured security recommendations and compliance score
- 📜 **Azure Policy**: Enforced rules like "block RDP from public IPs" and assessed compliance
- 🔍 **Log Analytics + KQL**: Queried VM logs and created dashboards to surface potential threats

These outputs directly fed into my reporting & remediation analysis.

## 📋 Phase 4: Documentation & Client-Style Reporting
I created all standard consulting deliverables:

- ✅ **Executive Summary** — Key insights for leadership
- ✅ **Risk Assessment Report** — Asset & vulnerability review
- ✅ **Compliance Gap Analysis** — Mapped to NIST CSF
- ✅ **Remediation Plan** — Prioritized actions to improve security posture
- ✅ **Visual Evidence** — Screenshots, scan results, dashboards

All deliverables are stored under `/docs` or embedded in the `/presentation` pitch deck.

## ⭐ Phase 5: Enhancements & Consultant Readiness

| Asset | Description |
|-------|-------------|
| 📊 `Excel Project Tracker` | Tracked phases, tasks, notes, and timeline |
| 🖼️ `PowerPoint Pitch Deck` | Client-ready summary of findings & recommendations |
| 📄 `Word Report Template` | Structured & export-ready for delivery |
| ✅ `NIST CSF Mapping Sheet` | Compliance mapping across Identify, Protect, Detect, Respond, Recover |
| 💻 `README.md` (this file) | GitHub-facing summary for recruiters and reviewers |

## 📁 Folder Structure
