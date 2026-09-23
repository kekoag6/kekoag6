<div align="center">

# Kekoa Giron 🔐

<a href="https://github.com/kekoag6">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=620&lines=Threat+Hunting+%7C+Incident+Response;Detection+Engineering+%7C+Digital+Forensics;KQL+%E2%80%A2+Microsoft+Sentinel+%E2%80%A2+Defender;Vulnerability+Management+%7C+STIG+Remediation;M.S.+Cybersecurity+%E2%80%A2+CySA%2B+%E2%80%A2+PenTest%2B+%E2%80%A2+Security%2B" alt="Typing banner: Threat Hunting, Incident Response, Detection Engineering, Digital Forensics, KQL, Vulnerability Management" />
</a>

<a href="https://www.linkedin.com/in/kekoagiron/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://www.instagram.com/kekoagiron"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
<img src="https://img.shields.io/badge/Honolulu%2C%20HI-555555?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Based in Honolulu, HI" />

</div>

---

## 👋 About Me

I'm a cybersecurity practitioner who learns by doing. These projects cover the full defensive cycle: finding and fixing vulnerabilities, hunting for attackers in real telemetry, and turning what I find into detections. Each repository includes the queries, scripts, and evidence behind the work.

Across all of it I try to hold one standard: **separate what the telemetry proves from what it can't show, and say which is which.** "No evidence of exfiltration" and "no visibility into exfiltration" are different findings, and only one of them lets you close an incident.

- 🎓 **Education:** M.S. Cybersecurity and Information Assurance (WGU) · BBA in Management, University of Hawaiʻi at Mānoa (Shidler College of Business)
- 🛡️ **Certifications:** CompTIA CySA+, PenTest+, Security+ · ISC2 CC · Google Cybersecurity
- 🔎 **Focus areas:** threat hunting, incident response, detection engineering, digital forensics, vulnerability management
- 🛠️ **Side project:** building **Rosterborn**, a fantasy football app, with AI-assisted development
- 🏃 **Outside of work:** running, volleyball, fantasy football, and gaming (mostly retired)

---

## 🚨 Threat Hunting and Incident Response

| Project | What it shows |
|---|---|
| **[TideGlass: AI Agent Intrusion Investigation](https://github.com/kekoag6/Threat-Hunting-Scenario-TideGlass)** | Traced an AI-agent attack across 8 log sources in Microsoft Sentinel, from exploit to AWS credential theft, lateral movement, and exfiltration of 2.8M customer records — 52 minutes end to end. Every KQL query, MITRE ATT&CK and ATLAS mapping, 37 evidence panels, and 8 detection rules. |
| **[MySQL Ransomware — Honeynet Investigation](https://github.com/kekoag6/Honeynet-MySQL-Ransomware-Incident)** | **Real intrusion activity** against a honeynet I built and instrumented. 12 external sources brute-forced an exposed MySQL service, enumerated every schema, issued 35 `DROP` statements, and left a Bitcoin ransom demand. Full timeline, IOC extraction with negative validation, and an explicit account of what the logs could not establish. |
| **[Cryptojacking via Spoofed Vendor Update](https://github.com/kekoag6/Incident-Response-Cryptojacking)** | Three helpdesk tickets about a slow application traced to an XMRig miner on a file server, installed through a spoofed vendor email after Defender was disabled by Group Policy. Wazuh correlation, containment, and the detection gaps that cost five hours. |

## 🔬 Digital Forensics

| Project | What it shows |
|---|---|
| **[Endpoint Forensic Triage — Defender Live Response](https://github.com/kekoag6/Endpoint-Forensic-Triage-MDE)** | Triage of a Windows 11 endpoint that surfaced an **active Tor circuit** — four established relay connections and a local SOCKS proxy, from a portable browser that left no uninstall entry. Four artifact classes corroborate it; decoded registry FILETIMEs reconstruct the download → extract → execute → connect chain to the second. |

## 📡 Detection Engineering

| Project | What it shows |
|---|---|
| **[Sentinel SOC Visibility Workbooks](https://github.com/kekoag6/Sentinel-SOC-Visibility-Workbooks)** | Four deployable Microsoft Sentinel workbooks turning Defender and flow telemetry into geographic triage views: inbound authentication origins, outbound C2 fan-in, exfiltration by byte volume, and allowed inbound traffic matched against threat intelligence. Commented KQL, deduplicated TI joins, companion grids for every map. |

## ⚠️ Vulnerability Management and Hardening

| Project | What it shows |
|---|---|
| **[Risk-Based Vulnerability Management Program](https://github.com/kekoag6/Vulnerability-Management-Program)** | A full scan → prioritize → remediate → verify cycle. Six remediation rounds took a Windows host from **2 Critical / 8 High / 12 Medium to 0 / 0 / 2** — an 87% reduction in actionable findings — with three residual risks formally accepted rather than suppressed. Ships the remediations as idempotent PowerShell, each script carrying the Tenable plugin ID it clears so the automation reconciles against the scan evidence. Includes API-driven Linux scanning. |
| **[Windows 11 DISA STIG Remediation](https://github.com/kekoag6/Windows-11-STIG-Remediation)** | Ten idempotent, self-validating PowerShell scripts remediating Windows 11 STIG controls — three CAT I, plus Azure Trusted Launch with Secure Boot and vTPM. Each documents both the registry and Group Policy path and reads the value back to confirm it landed. Ships with a read-only compliance checker covering all ten. |

## 📋 Governance, Risk, and Compliance

| Project | What it shows |
|---|---|
| **[Security Control Gap Assessments](https://github.com/kekoag6/Security-Control-Gap-Assessments)** | Three assessments across healthcare, retail, and federal-contractor cloud migration. NIST SP 800-53 control ratings with the reasoning behind why two controls in the same family rate differently, PCI DSS and GDPR mapped to shared controls, and cloud security planning under an active audit deadline. |

---

## 🧰 Toolkit

<p>
  <img src="https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=flat-square" alt="Microsoft Sentinel" />
  <img src="https://img.shields.io/badge/Defender%20for%20Endpoint-0078D4?style=flat-square" alt="Microsoft Defender for Endpoint" />
  <img src="https://img.shields.io/badge/KQL-0078D4?style=flat-square" alt="KQL" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square" alt="Azure" />
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square" alt="AWS" />
  <img src="https://img.shields.io/badge/Tenable-00A5B5?style=flat-square" alt="Tenable" />
  <img src="https://img.shields.io/badge/Wazuh-005C8A?style=flat-square" alt="Wazuh" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square" alt="PowerShell" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=flat-square" alt="MITRE ATT&CK" />
  <img src="https://img.shields.io/badge/MITRE%20ATLAS-C8102E?style=flat-square" alt="MITRE ATLAS" />
  <img src="https://img.shields.io/badge/DISA%20STIGs-4B5563?style=flat-square" alt="DISA STIGs" />
  <img src="https://img.shields.io/badge/NIST%20SP%20800--53-4B5563?style=flat-square" alt="NIST SP 800-53" />
</p>

---

<details>
<summary><b>🏅 Certifications</b></summary>
<br>

| Certification | Issuer | Year |
|---|---|---|
| CySA+ | CompTIA | 2026 |
| PenTest+ | CompTIA | 2026 |
| Certified in Cybersecurity (CC) | ISC2 | 2026 |
| Security+ | CompTIA | 2025 |
| Google Cybersecurity Certificate | Google | 2025 |
| Google Project Management Certificate | Google | 2024 |

</details>

<details>
<summary><b>🗂️ Other repositories</b></summary>
<br>

| Repository | Contents |
|---|---|
| **[cyber-projects](https://github.com/kekoag6/cyber-projects)** | Original submission reference for the STIG remediation scripts. Documented in full at [Windows-11-STIG-Remediation](https://github.com/kekoag6/Windows-11-STIG-Remediation). |

</details>

<div align="center">

**📫 Open to conversations about SOC, threat hunting, and incident response roles.**<br>
<a href="https://www.linkedin.com/in/kekoagiron/">Connect on LinkedIn</a>

</div>
