# 🛡️ TryHackMe – SOC Level 1

My notes, write-ups and progress through the [TryHackMe SOC Level 1](https://tryhackme.com/path/outline/soclevel1) learning path.

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)
![Modules](https://img.shields.io/badge/Modules-14-blue)
![Labs](https://img.shields.io/badge/Labs-65-blue)
![Est. time](https://img.shields.io/badge/Est.%20time-~65h-orange)
![Status](https://img.shields.io/badge/Status-In%20progress-yellow)

---

## 📌 About the path

SOC Level 1 is TryHackMe's beginner blue team path for aspiring junior SOC analysts. The path was rebuilt in 2025 around what an L1 analyst actually does on shift: **triage an alert → investigate → document → escalate or close**.

It moves from how a SOC works, to the core tools, to each type of telemetry (network, web, Windows, Linux), and finishes with full investigations.

> ℹ️ This repo follows the **new** path. The old version (with forensics tools like Volatility, KAPE and Autopsy) now lives on as *SOC Level 1 (legacy)*.

---

## 📊 Progress

| # | Module | Status |
| --- | -------- | :------: |
| 01 | Blue Team Introduction | ⬜ |
| 02 | SOC Team Internals | ⬜ |
| 03 | Core SOC Solutions | ⬜ |
| 04 | Cyber Defence Frameworks | ⬜ |
| 05 | Phishing Analysis | ⬜ |
| 06 | Network Traffic Analysis | ⬜ |
| 07 | Network Security Monitoring | ⬜ |
| 08 | Web Security Monitoring | ⬜ |
| 09 | Windows Security Monitoring | ⬜ |
| 10 | Linux Security Monitoring | ⬜ |
| 11 | Malware Concepts for SOC | ⬜ |
| 12 | Threat Analysis Tools | ⬜ |
| 13 | SIEM Triage for SOC | ⬜ |
| 14 | Capstone Challenges | ⬜ |

Legend: ⬜ Not started · 🟨 In progress · ✅ Completed

---

## 🗂️ Modules & rooms

### 01 – Blue Team Introduction

What a SOC does and where the junior analyst fits in.

- [ ] Junior Security Analyst Intro
- [ ] SOC Role in Blue Team
- [ ] Humans as Attack Vectors
- [ ] Systems as Attack Vectors

### 02 – SOC Team Internals

Triage workflow, reporting, workbooks and SOC metrics.

- [ ] SOC L1 Alert Triage
- [ ] SOC L1 Alert Reporting
- [ ] SOC Workbooks and Lookups
- [ ] SOC Metrics and Objectives
- [ ] SOC Simulator – Introduction to Phishing

### 03 – Core SOC Solutions

- [ ] EDR
- [ ] SIEM
- [ ] Splunk Basics
- [ ] Elastic Stack Basics
- [ ] SOAR

### 04 – Cyber Defence Frameworks

- [ ] Pyramid of Pain
- [ ] Cyber Kill Chain
- [ ] Unified Kill Chain
- [ ] MITRE
- [ ] Summit
- [ ] Eviction

### 05 – Phishing Analysis

Headers, senders, links and attachments of suspicious emails.

- [ ] *add rooms*

### 06 – Network Traffic Analysis

- [ ] Wireshark (×3 rooms)

- [ ] NetworkMiner

### 07 – Network Security Monitoring

Intrusion detection (e.g. Snort).

- [ ] *add rooms*

### 08 – Web Security Monitoring

Spotting web attacks in server and proxy logs.

- [ ] *add rooms*

### 09 – Windows Security Monitoring

Which Windows events matter and how to read them.

- [ ] *add rooms*

### 10 – Linux Security Monitoring

- [ ] *add rooms*

### 11 – Malware Concepts for SOC

Malware behaviour at triage level – not reverse engineering.

- [ ] *add rooms*

### 12 – Threat Analysis Tools

Threat intel lookups to enrich alerts.

- [ ] *add rooms*

### 13 – SIEM Triage for SOC

End-to-end alert triage in Splunk and Elastic.

- [ ] *add rooms*

### 14 – Capstone Challenges

- [ ] Tempest
- [ ] Boogeyman series
- [ ] *add rooms*

---

## 📁 Repository structure

``` text
    .
    ├── README.md
    ├── 01-blue-team-introduction/
    ├── 02-soc-team-internals/
    ├── 03-core-soc-solutions/
    ├── 04-cyber-defence-frameworks/
    ├── 05-phishing-analysis/
    ├── 06-network-traffic-analysis/
    ├── 07-network-security-monitoring/
    ├── 08-web-security-monitoring/
    ├── 09-windows-security-monitoring/
    ├── 10-linux-security-monitoring/
    ├── 11-malware-concepts/
    ├── 12-threat-analysis-tools/
    ├── 13-siem-triage/
    ├── 14-capstone/
    ├── playbooks/          # My triage playbooks per alert type
    └── cheatsheets/        # Splunk SPL, KQL, Wireshark filters, Windows Event IDs …
```

---

## 📝 Note template

Each room gets its own `.md` file using this template:

```markdown
# Room name
**Module:** XX – Module name
**Link:** https://tryhackme.com/room/...
**Completed:** YYYY-MM-DD

## Key takeaways
- …

## Tools & commands
- …

## How I'd use this as an L1 analyst
- …
```

---

## 🧰 Skills & tools covered

`SIEM` `Splunk` `Elastic / Kibana` `EDR` `SOAR` `Wireshark` `NetworkMiner` `Snort` `MITRE ATT&CK` `Cyber Kill Chain` `Pyramid of Pain` `Phishing analysis` `Windows Event Logs` `Linux logs` `Threat intelligence` `Alert triage` `Incident reporting`

---

## 🎯 Next steps

- [ ] Complete the path and download the certificate of completion
- [ ] Practice in the SOC Simulator
- [ ] Consider the **SAL1** (Security Analyst Level 1) certification

---

## ⚠️ Disclaimer

These notes are for personal learning. In line with TryHackMe's rules, this repo does **not** contain flags or direct answers – only concepts, methods and my own reflections. Only analyse systems and data you are authorised to examine.

---

## 🔗 Links

- [SOC Level 1 learning path](https://tryhackme.com/path/outline/soclevel1)
- [MITRE ATT&CK](https://attack.mitre.org/)
- My TryHackMe profile: `https://tryhackme.com/p/Paperz9`
