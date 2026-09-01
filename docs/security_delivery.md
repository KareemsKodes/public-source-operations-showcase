# Security and Delivery Model (Public View)

The platform is presented around a default-deny customer boundary. A successful
sign-in establishes identity; it does not, by itself, grant access to a paid
product.

## Authorization behavior

Each protected request checks the identity, requested product, customer scope,
term, and applicable usage boundary before returning a result. The same
decision applies to dashboard views, API calls, MCP tool calls, and downloads.

## Lifecycle behavior

| Event | Customer-visible result |
| --- | --- |
| Account created | Identity exists; paid products remain closed. |
| Payment or explicit grant confirmed | The selected product scope becomes eligible. |
| Subscription cancellation requested | Service continues through the already-paid term. |
| Paid term ends | The product scope closes across every delivery surface. |
| Grant expires or is revoked | The granted scope closes on the next protected request. |
| Account deletion completes | Customer sessions and access records are invalidated. |

## Data handling boundary

- Credentials and customer data are kept out of public bundles and public
  examples.
- Public demonstrations use old, bounded records rather than current feeds.
- Customer files are presented as private, authorized results rather than
  permanent public links.
- The public portfolio records control behavior and evidence status, not
  customer payloads or private operational state.

This is a public case-study description, not a claim that every possible
enterprise connector or customer configuration is deployed in this repository.
