# APT29 (Cozy Bear)

**Aliases:** Cozy Bear, The Dukes, Midnight Blizzard, NOBELIUM
**Suspected Origin/Attribution:** Publicly attributed by multiple governments and vendors to Russia's Foreign Intelligence Service (SVR)
**Active Since:** At least 2008, per public reporting
**Primary Motivation:** Espionage
**Last Updated:** 2026-07-18

## Sources
- MITRE ATT&CK Groups database (G0016)
- CISA/NCSC joint advisories
- Microsoft Threat Intelligence and Mandiant public reporting on the SolarWinds supply chain compromise

## Summary
A state-linked espionage group publicly known for long-term, stealthy intrusion campaigns against government, think tank, and technology sector targets. Widely associated with the SolarWinds supply chain compromise, one of the most significant publicly documented cyber espionage operations, notable for its patience and operational security rather than speed or destruction.

## TTPs (MITRE ATT&CK Mapping)
| Tactic | Technique | ID |
|---|---|---|
| Initial Access | Supply chain compromise | T1195 |
| Initial Access | Spearphishing attachment | T1566.001 |
| Defense Evasion | Use of legitimate cloud services to blend in with normal traffic | T1102 |
| Persistence | Valid account abuse (compromised credentials reused over long periods) | T1078 |

## Notable Campaigns
- SolarWinds supply chain compromise, publicly attributed and extensively documented by U.S. government agencies and multiple security vendors
- Long-term intrusion campaigns against diplomatic and think tank targets, per public reporting

## My Notes
Useful contrast to Lazarus/LockBit — this group prioritizes staying undetected for as long as possible over fast monetization, which changes what detection signals actually matter (long-dwell-time anomalies vs. rapid encryption/exfiltration alerts).

---
*Compiled entirely from public sources. No original incident data.*
