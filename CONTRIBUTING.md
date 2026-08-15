# Contributing

Open an issue before substantial changes. Use a short-lived branch, keep one detection per pull request where practical, and explain the threat hypothesis, expected telemetry, test evidence, false positives, and ATT&CK mapping.

Every query should:

- filter time and high-volume data early;
- project analyst-useful fields;
- avoid tenant-specific values unless clearly marked;
- include tuning guidance and required data sources;
- be tested in the target portal before merge.

Never submit secrets, customer identifiers, or live indicators that should remain private.
