# Public Exhibit Contract

This is the reviewer-facing shape of the supplied examples. The exact
production contracts and implementation details remain private.

## Evidence record

| Field category | Meaning |
| --- | --- |
| Record identifier | Stable identifier for the exhibit row. |
| Source reference | Sanitized source alias and official reference link. |
| Subject | Country, organization, vulnerability, or other public entity. |
| Event or measure | Human-readable event type or indicator. |
| Effective date | Date represented by the public fact. |
| Reported value | Value retained from the source with its unit or type. |
| Evidence digest | Digest of the sanitized portfolio record. |

## Reviewable release

The generated exhibits add event-level identifiers, source coverage, evidence
status, and repeated-capture decisions so a reviewer can trace the visible
result back to the included historical fixture.

## Publication rules

- Examples remain at or before the historical cutoff shown in the README.
- Required exhibit fields must be present.
- Evidence references use HTTPS.
- Portfolio digests and snapshot counts must agree across the included files.
- Personal contact data, raw source bodies, current feeds, and private
  operational metadata are excluded.

The public contract is intentionally smaller than the private service
contract. It demonstrates clarity and traceability without revealing the
production schema, tool implementation, or proprietary analytical methods.
