# Threat Intelligence Notes

Ongoing research notes on threat actor TTPs, malware behavior, and cybercrime campaign patterns — built while working through CEH / GCIH-track / GSOC-track material and independent research.

⚠️ **Disclaimer:** All notes here are compiled from public sources (vendor threat reports, official advisories, CVE databases, MITRE ATT&CK) and cited accordingly. This repository does not contain original incident response data, private client information, or unauthorized access to any system.

---

## About

Unlike [`osint-writeups`](https://github.com/recon1231/osint-writeups-), which contains polished, publish-ready investigations, this repository is my working notebook — raw notes, references, and observations compiled while researching threat actors and malware families. Expect shorter entries, less polish, and more frequent updates.

---

## Repository Structure

```
threat-intel-notes/
├── README.md
├── malware-families/       # Notes per malware family — behavior, IOCs (public), references
├── threat-actors/            # TTP breakdowns per group, sourced from public reporting
└── resources.md               # Tools, feeds, and references I use regularly
```

---

## How Entries Are Written

Each note includes:
- **Source(s)** — where the information came from (always cited, never presented as original incident data)
- **Summary** — what the malware/actor does, in plain terms
- **TTPs** — mapped to MITRE ATT&CK where applicable
- **Notes** — my own observations, questions, or things worth researching further

---

## Threat Actors

| Actor / Group | Focus | Last Updated |
|---|---|---|
| [APT28 (Fancy Bear)](./threat-actors/apt28-fancy-bear.md) | State-linked espionage | 2026-07-18 |
| [Lazarus Group](./threat-actors/lazarus-group.md) | Financial theft / espionage | 2026-07-18 |
| [LockBit](./threat-actors/lockbit.md) | Ransomware-as-a-Service | 2026-07-18 |
| [APT29 (Cozy Bear)](./threat-actors/apt29-cozy-bear.md) | State-linked espionage | 2026-07-18 |
| [Scattered Spider](./threat-actors/scattered-spider.md) | Social-engineering-first / financial | 2026-07-18 |
| [INT3X](./threat-actors/int3x.md) | Regional cybercrime collective (Egypt-focused) | 2026-07-18 |

## Malware Families

| Family | Type | Last Updated |
|---|---|---|
| [Emotet](./malware-families/emotet.md) | Loader / Botnet | 2026-07-18 |
| [Qakbot](./malware-families/qakbot.md) | Banking Trojan / Loader | 2026-07-18 |
| [RedLine Stealer](./malware-families/redline-stealer.md) | Infostealer | 2026-07-18 |
| [Cobalt Strike (Malicious Use)](./malware-families/cobalt-strike-malicious-use.md) | Post-Exploitation / C2 Framework | 2026-07-18 |
| [Agent Tesla](./malware-families/agent-tesla.md) | RAT / Keylogger / Infostealer | 2026-07-18 |

---

## Connect

- **X (Twitter):** [@yourhandle](#)
- **LinkedIn:** [Yassin Hamada](#)
- **Writeups (polished):** [osint-writeups](https://github.com/recon1231/osint-writeups-)
- **Medium:** [link](#)

---

### About Me

Cybersecurity researcher focused on OSINT, malware analysis, and threat intelligence. Building hands-on experience through independent research, applied training, and collaborative bug bounty work.
