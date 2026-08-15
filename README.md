![Sentinel Owl defending a digital environment](assets/sentinel-owl-banner.png)

# KQL Detections

Welcome! This repository contains a collection of production-minded KQL (Kusto Query Language) detections for Microsoft Defender XDR Advanced Hunting and Microsoft Sentinel. It helps SOC analysts, incident responders, and detection engineers hunt for sophisticated attacks and turn useful hypotheses into tunable analytics.

## Capabilities, tables & coverage

- **Capabilities:** threat hunting queries, scheduled analytics-rule templates, ATT&CK mapping, entity mapping, practical tuning guidance, and reusable watchlist schemas.
- **Key tables:** `DeviceProcessEvents`, `DeviceEvents`, `DeviceNetworkEvents`, `DeviceRegistryEvents`, `DeviceFileEvents`, `CloudAppEvents`, `IdentityLogonEvents`, `IdentityQueryEvents`, `EmailEvents`, `UrlClickEvents`, `SigninLogs`, `SecurityEvent`, and `AzureActivity`.
- **Coverage:** Initial Access, Execution, Persistence, Privilege Escalation, Defense Evasion, Credential Access, Discovery, Lateral Movement, Command and Control, Network Events, and Exfiltration.

## Repository structure

- [`Defender-XDR/`](Defender-XDR/) — Advanced Hunting queries organized by ATT&CK-aligned behavior.
- [`Sentinel/`](Sentinel/) — scheduled analytics rules grouped by telemetry and security domain.
- [`Watchlists/`](Watchlists/) — safe, disabled-by-default CSV schemas for tenant-specific enrichment.
- [`coverage.csv`](coverage.csv) — machine-readable detection and ATT&CK coverage index.

Validate and tune every query for your environment before enabling alerting or automated response. Replace all example watchlist rows before importing them.

## Connect with me

[LinkedIn](https://www.linkedin.com/in/marshsecurity) · [Mastodon](https://infosec.exchange/@katos) · [Blog](https://marshsecurity.org) · [Microsoft Docs Tracker](https://docstracker.marshsecurity.org) · [Microsoft CVE Explorer](https://docstracker.marshsecurity.org/cve)

Contributions are welcome. See [`CONTRIBUTING.md`](CONTRIBUTING.md). 

Licensed under [MIT](LICENSE).
