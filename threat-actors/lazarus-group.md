# Lazarus Group

**Aliases:** Hidden Cobra, Guardians of Peace, ZINC, Diamond Sleet
**Suspected Origin/Attribution:** Publicly attributed by the U.S. and allied governments to North Korea
**Active Since:** At least 2009, per public reporting
**Primary Motivation:** Financial theft (notably cryptocurrency) and espionage
**Last Updated:** 2026-07-18

## Sources
- MITRE ATT&CK Groups database (G0032)
- U.S. Treasury/FBI/CISA joint advisories
- Chainalysis and blockchain forensics reporting on crypto theft campaigns

## Summary
A state-linked group publicly associated with large-scale cryptocurrency theft, supply chain compromise, and destructive attacks. Notable for shifting tradecraft toward financially motivated operations to generate revenue, distinguishing it from purely espionage-focused state actors.

## TTPs (MITRE ATT&CK Mapping)
| Tactic | Technique | ID |
|---|---|---|
| Initial Access | Supply chain compromise | T1195 |
| Initial Access | Social engineering via fake job offers (publicly documented recruiting-lure campaigns) | T1566 |
| Impact | Data destruction / wiper malware | T1485 |
| Exfiltration | Cryptocurrency exchange targeting | T1657 |

## Notable Campaigns
- Multiple large-scale cryptocurrency exchange breaches, publicly attributed and tracked via blockchain forensics
- Fake job-offer social engineering campaigns targeting developers, per multiple vendor reports

## My Notes
The fake job-offer lure pattern is a strong example of social engineering tailored to a specific target profile (developers) rather than generic phishing — worth studying the pretext-building technique specifically.

---
*Compiled entirely from public sources. No original incident data.*
