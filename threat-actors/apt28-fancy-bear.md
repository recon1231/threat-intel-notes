# APT28 (Fancy Bear)

**Aliases:** Fancy Bear, Sofacy, Sednit, STRONTIUM, Forest Blizzard
**Suspected Origin/Attribution:** Publicly attributed by multiple governments and vendors to Russian military intelligence (GRU)
**Active Since:** At least 2004, per public reporting
**Primary Motivation:** Espionage
**Last Updated:** 2026-07-18

## Sources
- MITRE ATT&CK Groups database (G0007)
- Multiple government joint advisories (CISA, NCSC, and allied agencies)
- Vendor reporting from Mandiant, Microsoft, and CrowdStrike

## Summary
One of the most widely tracked state-linked espionage groups, publicly associated with intelligence-gathering operations against government, military, and political targets. Known for combining spear-phishing with credential harvesting infrastructure and custom malware toolsets.

## TTPs (MITRE ATT&CK Mapping)
| Tactic | Technique | ID |
|---|---|---|
| Initial Access | Spearphishing Link | T1566.002 |
| Credential Access | Credential harvesting via fake login portals | T1556 |
| Persistence | Custom backdoors / scheduled tasks | T1053 |
| Command and Control | Encrypted C2 channels | T1071 |

## Notable Campaigns
- Long-running credential phishing campaigns targeting government and defense-adjacent organizations, per multiple joint government advisories
- Use of publicly disclosed zero-day exploits in targeted intrusion campaigns, per vendor reporting

## My Notes
Good group to study for understanding how nation-state actors blend social engineering with technical exploitation — the phishing infrastructure patterns are relevant even outside nation-state context.

---
*Compiled entirely from public sources. No original incident data.*
