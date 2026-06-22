# Network Vulnerability Assessment Lab — Metasploitable 2

> Controlled vulnerability assessment performed in an isolated laboratory environment using Nmap, Nessus, and OpenVAS.

![Status](https://img.shields.io/badge/Status-Completed-success)
![Environment](https://img.shields.io/badge/Environment-Lab-blue)
![Platform](https://img.shields.io/badge/Target-Metasploitable2-orange)
![Tools](https://img.shields.io/badge/Tools-Nmap%20%7C%20Nessus%20%7C%20OpenVAS-lightgrey)

---

# Overview

This project demonstrates a structured **Network Vulnerability Assessment (NVA)** conducted against **Metasploitable 2**, an intentionally vulnerable Linux machine designed for cybersecurity learning and controlled security testing.

The assessment followed a professional vulnerability assessment workflow:

1. Asset Discovery
2. Network Reconnaissance
3. Service Enumeration
4. Vulnerability Identification
5. Risk Analysis
6. Prioritization
7. Remediation Recommendations

The objective was to identify exposed services, evaluate discovered vulnerabilities, assess associated risks, and propose mitigation strategies.

---

# Scope

## In Scope
- Metasploitable 2 Virtual Machine
- Internal isolated lab network
- Service discovery
- Vulnerability identification
- Risk analysis

## Out of Scope
- Exploitation
- Privilege escalation
- Persistence
- Production environments

---

# Lab Environment

| Component | Technology |
|----------|-----------|
| Attacker Machine | Kali Linux |
| Target Machine | Metasploitable 2 |
| Network Type | Internal / Host-Only |
| Scanning Tools | Nmap, Nessus, OpenVAS |
| Objective | Vulnerability Assessment |

---

# Tools Used

## Nmap

Used for reconnaissance and enumeration.

### Activities
- Host discovery
- Port scanning
- Service detection
- Version detection

Example:

```bash
nmap -sV -sC <target-ip>
```

---

## Nessus

Used for automated vulnerability identification and security assessment.

### Activities
- Vulnerability discovery
- Severity assessment
- Service misconfiguration detection
- Exposure identification

---

## OpenVAS

Used for vulnerability validation and comparative assessment.

### Activities
- Vulnerability scanning
- Detection verification
- Security posture analysis
- Risk evaluation

---

# Assessment Methodology

```text
Target Identification
        ↓
Nmap Enumeration
        ↓
Nessus Scan
        ↓
OpenVAS Scan
        ↓
Finding Validation
        ↓
Risk Prioritization
        ↓
Remediation
```

---

# Key Findings

| Category | Observation |
|----------|------------|
| Open Ports | Multiple exposed services discovered |
| Legacy Services | Outdated software versions identified |
| Weak Configuration | Security hardening opportunities identified |
| Information Exposure | Excessive service disclosure observed |

> Findings depend on scan configuration and environment.

---

# Repository Structure

```text
network-vulnerability-assessment-lab/
│
├── README.md
├── screenshots/
├── nmap/
│   └── scan-results
├── nessus/
│   └── reports
├── openvas/
│   └── reports
├── remediation/
└── final-report/
```

---

# Skills Demonstrated

- Network Reconnaissance
- Service Enumeration
- Vulnerability Assessment
- Risk Prioritization
- Security Analysis
- Technical Reporting

---

# Ethical Notice

This assessment was performed exclusively in a controlled educational environment.

No testing was conducted against unauthorized systems.

---

# Author

**iamhxmz**  
Cybersecurity | Vulnerability Assessment | Network Security
