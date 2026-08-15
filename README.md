![Sentinel Owl defending a digital environment](assets/sentinel-owl-banner.png)

# KQL Detections

Welcome! This repository contains a collection of production-minded KQL (Kusto Query Language) detections for Microsoft Defender XDR Advanced Hunting and Microsoft Sentinel. It helps SOC analysts, incident responders, and detection engineers hunt for sophisticated attacks and turn useful hypotheses into tunable analytics.

## Capabilities, tables & coverage

- **Capabilities:** threat hunting queries, scheduled analytics-rule templates, ATT&CK mapping, entity mapping, and practical tuning guidance.
- **Key tables:** `DeviceProcessEvents`, `DeviceEvents`, `DeviceNetworkEvents`, `DeviceRegistryEvents`, `DeviceFileEvents`, `IdentityLogonEvents`, `IdentityQueryEvents`, `EmailEvents`, `UrlClickEvents`, `SigninLogs`, `SecurityEvent`, and `AzureActivity`.
- **Coverage:** Initial Access, Execution, Persistence, Privilege Escalation, Defense Evasion, Credential Access, Discovery, Lateral Movement, Command and Control, and Network Events.

Start in [`detections/`](detections/) for Defender XDR hunts or [`sentinel-analytics/`](sentinel-analytics/) for deployable Sentinel rule templates. Validate and tune every rule for your environment before enabling automated response.

## Connect with me

Replace `YOUR_PROFILE` / `YOUR_DOMAIN` before publishing: [LinkedIn](https://www.linkedin.com/in/marshsecurity) · [Mastodon](https://infosec.exchange/@katos) · [Blog](https://marshsecurity.org) · [Microsoft Docs Tracker](https:/docstracker.marshsecurity.org) · [Microsoft CVE Explorer](https://docstracker.marshsecurity.org/cve)

Contributions are welcome—see [`CONTRIBUTING.md`](CONTRIBUTING.md). Licensed under [MIT](LICENSE).
