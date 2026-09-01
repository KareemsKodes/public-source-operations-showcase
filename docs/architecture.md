# Public Showcase Architecture

This document explains the visible shape of the portfolio exhibit. It is a
communication aid, not a production blueprint. The implementation source,
private deployment design, and proprietary analytical methods are intentionally
not included in this public release.

```text
selected historical public facts
              |
              v
        publication review
              |
              v
       consistent event records
              |
              v
       quality and evidence checks
              |
       +------+----------------+
       |                       |
       v                       v
  visual report          machine-readable exhibits
```

## What a reviewer can inspect

### Evidence exhibits

Three small excerpts contain selected historical factual fields. The fixture
uses old records, official reference links, and a clearly stated date cutoff.
Raw response bodies, unused fields, personal contacts, current records, and
private archive material are excluded.

### Quality evidence

The supplied reports show source coverage, date coverage, required-field
completeness, repeated-capture handling, evidence status, and the boundary of
the published fixture. They are intended to make the result inspectable rather
than ask a buyer to trust an unexplained number.

### Delivery exhibits

The release includes HTML for human review and CSV/JSON for downstream
inspection. These are portfolio files only; they are not customer credentials,
live endpoints, or an active data-delivery channel.

## Kept private

- Collection and discovery systems.
- Production infrastructure and deployment configuration.
- Customer, payment, usage, and operational records.
- Proprietary scoring, ranking, correlation, and product-generation methods.
- Exact production contracts, internal tool names, and implementation source.
