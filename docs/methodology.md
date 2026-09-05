# Methodology

## Objective
Document a repeatable, privacy-aware process for passive wireless-security observation and analysis.

## Scope Definition
Before each session, record:
- General observation area: TODO
- Date/time window: TODO
- Equipment used: TODO
- Software used: TODO
- Research purpose: TODO

## Collection Principles
- Prefer passive observation.
- Do not attempt authentication to networks without permission.
- Do not transmit disruptive frames.
- Do not capture or publish private user content.
- Collect only metadata necessary for the stated research goal.

## Suggested Fields
| Field | Purpose |
|---|---|
| Timestamp | Observation timing |
| Security type | Compare WPA/WPA2/WPA3/open trends |
| Channel | Analyze channel utilization |
| Frequency band | Compare 2.4/5/6 GHz environments where supported |
| Signal category | Approximate relative signal presence |
| Sanitized network ID | Track repeated observations without exposing identifiers |
| Broad area label | Compare locations while protecting privacy |

## Sanitization Workflow
1. Remove credentials or sensitive notes.
2. Replace identifying SSIDs with categories or pseudonyms.
3. Hash or remove BSSIDs/MAC addresses if not required.
4. Generalize precise coordinates to broader areas.
5. Review screenshots manually for accidental disclosures.
6. Publish aggregate findings rather than raw identifiable records when possible.

## Analysis Workflow
1. Import sanitized observations.
2. Normalize security labels and frequency bands.
3. Calculate aggregate counts and percentages.
4. Review channel utilization and signal categories.
5. Create privacy-safe charts/tables.
6. Document limitations and defensive takeaways.
