# Authenticity and Sanitization

## Evidence statement

The portfolio fixture uses pre-existing excerpts of real historical public
facts. No replacement network collection or synthetic record generation was
used to assemble the included examples.

The selected facts retain official reference links and portfolio-only digests.
The public bundle is a bounded historical exhibit, not a current source feed
or a production archive.

## Historical cutoff

The examples use records effective on or before `2021-12-31`:

| Source family | Selected records | Effective date range |
| --- | ---: | --- |
| Macroeconomic indicators | 24 | 2020-12-31 to 2021-12-31 |
| Completed public awards | 4 | 2015-09-25 to 2021-09-30 |
| Vulnerability metadata | 42 | 2005-06-01 to 2021-12-03 |

The exhibit also contains one repeated capture so the supplied decision record
can show how repeated observations are handled. The final public result is 70
unique events.

## Integrity evidence

The included manifest, source registry, evidence snapshots, exports, and
quality summary carry matching portfolio-level digests and counts. These
artifacts make the sample internally reviewable without exposing the private
collection system that produced the original excerpts.

## Removed material

- Personal names used as owner or operator identifiers, personal email,
  phone, and address fields.
- Raw response bodies and unused source fields.
- Current or future-effective records.
- Private hostnames, network addresses, credentials, customer records, archive
  paths, and operational timestamps.
- Collection inventory, orchestration, deployment detail, and proprietary
  processing logic.

## Public review boundary

Source terms, attribution requirements, rate limits, and downstream commercial
delivery rights must be reviewed again before any new collection or customer
delivery. This repository documents a sanitized exhibit and does not grant
rights to the underlying sources or to the private systems.
