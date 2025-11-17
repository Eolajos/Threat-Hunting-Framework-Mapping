# Threat-Hunting-Framework-Mapping: Energy & Utilities Sector Using MITRE ATT&CK

## Overview
This project demonstrates proactive threat hunting for the Energy & Utilities sector using the MITRE ATT&CK framework. It maps Advanced Persistent Threat (APT) groups to Tactics, Techniques, and Procedures (TTPs) and visualizes them in MITRE ATT&CK Navigator.

APT groups analyzed:
- **APT28 (Red)**
- **APT29 (Orange)**
- **APT10 (Yellow)**
- **BITTER (Green)**

Key techniques observed include **account compromise, phishing, credential forging, and command/script execution**.

---

## Tools & Resources
- [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/)
- SOCRadar Labs
- OSINT research

---

## Usage
1. Open MITRE ATT&CK Navigator.
2. Load the JSON layer files (if included in `/layers`).
3. Visualize techniques with assigned colors:
   - Red – APT28
   - Orange – APT29
   - Yellow – APT10
   - Green – BITTER

---

## Findings
- Common techniques across APTs: account compromise, phishing, credential forging, command/script execution.
- Persistent techniques such as scheduled tasks and remote services are frequently used.
- Navigator visualiz
