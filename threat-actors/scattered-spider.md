# Scattered Spider

**Aliases:** UNC3944, Muddled Libra, Octo Tempest, Starfraud
**Suspected Origin/Attribution:** Publicly reported as a loosely organized, primarily English-speaking cybercriminal collective (not state-linked)
**Active Since:** At least 2022, per public reporting
**Primary Motivation:** Financial (extortion, data theft, ransomware affiliate operations)
**Last Updated:** 2026-07-18

## Sources
- Microsoft Threat Intelligence (Octo Tempest reporting)
- Mandiant (UNC3944 reporting)
- CISA advisories on Scattered Spider TTPs

## Summary
A financially motivated group publicly known for exceptionally effective social engineering — particularly vishing (voice phishing) and help-desk impersonation to bypass MFA and gain initial access, rather than relying primarily on technical exploits. Publicly linked to high-profile breaches of large enterprises via targeting IT help desks directly.

## TTPs (MITRE ATT&CK Mapping)
| Tactic | Technique | ID |
|---|---|---|
| Initial Access | Phishing via SMS (smishing) and voice calls (vishing) | T1566 |
| Initial Access | Help-desk social engineering for MFA reset/credential access | T1656 |
| Defense Evasion | SIM swapping to intercept MFA codes | T1111 |
| Impact | Ransomware deployment via affiliate partnerships with RaaS operators | T1486 |

## Notable Campaigns
- Publicly documented breaches of major enterprises via help-desk impersonation, per Microsoft and Mandiant reporting
- Affiliate collaboration with ransomware operators for post-access monetization, per public reporting

## My Notes
Directly relevant to OSINT work — this group's core skill is building a convincing enough pretext (using publicly available employee info) to fool a live human on the phone, not exploiting a technical vulnerability. Strong example of why OSINT hygiene matters as much as technical patching.

---
*Compiled entirely from public sources. No original incident data.*
