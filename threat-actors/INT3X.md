# INT3X

**Aliases:** INT3X team/group (collective banner used by multiple individual actors)
**Suspected Origin/Attribution:** Publicly reported as an Egypt-focused cybercrime collective; not attributed to any nation-state
**Active Since:** At least early 2026, per public reporting
**Primary Motivation:** Financial (data sale/extortion) and hacktivist-style defacement
**Last Updated:** 2026-07-18

## Sources
- DeXpose (in collaboration with Buguard) — public threat actor attribution writeup, May 2026
- Public social media reporting on claimed leaks (e.g., Mansoura University data)

## Summary
INT3X is a publicly documented cybercrime collective primarily targeting Egyptian organizations across sectors including aviation, industrial/manufacturing, government infrastructure, and higher education. The group operates as a banner used by multiple collaborating individual actors rather than a single formal organization, advertising and selling stolen databases on cybercrime forums and occasionally defacing compromised websites with public messaging. One investigation publicly reported that a core member was de-anonymized through accumulated operational security failures (reused usernames, metadata leaks, and credential reuse) and referred to law enforcement.

## TTPs (MITRE ATT&CK Mapping)
| Tactic | Technique | ID |
|---|---|---|
| Initial Access | Exploitation of public-facing applications (including a claimed zero-day against a payment gateway) | T1190 |
| Collection | Bulk database exfiltration from breached systems | T1213 |
| Impact | Website defacement | T1491 |
| Exfiltration / Monetization | Sale of stolen databases on cybercrime forums | T1567 |

## Notable Campaigns (per public reporting)
- Advertised sale of an airline HR/recruitment database (~104,000 records)
- Claimed defacement of an industrial/manufacturing company website
- Claimed breach of a government roads and bridges authority's contract system
- Advertised sale of a university dataset described as containing close to 989,000 student records
- Claimed breach of a university payment gateway platform affecting multiple institutions
- Defacement of an educational institution's website with a public message

## My Notes
Strong regional case study precisely because it's local (Egypt-focused) and recent — useful for understanding how a small, informally organized group without nation-state resources can still cause large-scale exposure by targeting under-secured public-facing systems (payment gateways, university portals) rather than hardened enterprise targets. The publicly reported attribution investigation is also a good example of how OSINT/operational security failures (username reuse, Git commit metadata, credential reuse) unravel anonymity over time — relevant to both defensive awareness and my own OSINT methodology practice.

---
*Compiled from public reporting only. No original incident data, and no reproduction of any individual's identifying details beyond what is already the subject of public reporting and law enforcement referral.*
