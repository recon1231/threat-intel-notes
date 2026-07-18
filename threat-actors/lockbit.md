# LockBit (Ransomware-as-a-Service)

**Aliases:** LockBit, LockBit 2.0/3.0
**Suspected Origin/Attribution:** Operators and affiliates publicly linked to multiple countries; law enforcement action (Operation Cronos, 2024) disrupted core infrastructure
**Active Since:** At least 2019, per public reporting
**Primary Motivation:** Financial (ransomware extortion)
**Last Updated:** 2026-07-18

## Sources
- CISA/FBI/NCA joint advisories, including Operation Cronos disclosures
- MITRE ATT&CK Groups database
- Multiple incident response vendor reports (post-disclosure case studies)

## Summary
One of the most prolific Ransomware-as-a-Service (RaaS) operations publicly documented, operating an affiliate model where independent actors use LockBit's tooling and infrastructure in exchange for a revenue split. Known for double-extortion tactics — encrypting data and threatening to leak it publicly.

## TTPs (MITRE ATT&CK Mapping)
| Tactic | Technique | ID |
|---|---|---|
| Initial Access | Exploitation of public-facing applications | T1190 |
| Lateral Movement | Use of legitimate remote access tools | T1219 |
| Impact | Data encryption for extortion | T1486 |
| Exfiltration | Data staged and exfiltrated before encryption (double extortion) | T1567 |

## Notable Campaigns
- Widespread attacks against organizations across healthcare, education, and critical infrastructure sectors, per joint law enforcement advisories
- Publicly disclosed law enforcement disruption (Operation Cronos) revealed operational details about the affiliate structure

## My Notes
Good case study for understanding the RaaS business model itself, not just the malware — the affiliate/operator split is what makes this threat class scale so effectively compared to a single actor group.

---
*Compiled entirely from public sources. No original incident data.*
