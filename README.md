# Middesk

Middesk is a business identity and verification platform providing API-first infrastructure for KYB (Know Your Business) compliance, EIN/TIN validation, business registration verification, UBO and officer research, sanctions screening, and ongoing business monitoring. Used by fintechs, lenders, banks, and marketplaces to automate customer onboarding and compliance workflows.

**Website:** https://www.middesk.com
**Developer Docs:** https://docs.middesk.com
**API Reference:** https://docs.middesk.com/reference
**Status:** https://status.middesk.com
**Blog:** https://www.middesk.com/blog
**GitHub:** https://github.com/middesk
**LinkedIn:** https://www.linkedin.com/company/middesk
**X:** https://x.com/middeskhq

## API

Middesk exposes a REST API with JSON responses over HTTPS. Two environments are available:

- **Production:** `https://api.middesk.com/v1/`
- **Sandbox:** `https://api-sandbox.middesk.com/v1/`

Authentication uses HTTP Basic Auth or Bearer token with API keys (prefixed `mk_live` for production, `mk_test` for sandbox). Keys are managed in the Middesk Dashboard under Settings > Developer > Credentials.

## Key Products

- Business verification (KYB) — Secretary of State registration, EIN/TIN validation, address verification
- Owner and officer verification
- Sanctions and OFAC screening
- Adverse media and PEP screening
- Web presence and industry analysis
- Ongoing business monitoring with webhook notifications
- Lien search and management
- Entity management for payroll tax registration
- Business autocomplete and smart populate (prefill)
- Agentic compliance workflows

## Repository Contents

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/middesk-plans-pricing.yml` — Pricing plans and tiers
- `rate-limits/middesk-rate-limits.yml` — Rate limiting and authentication details
- `finops/middesk-finops.yml` — FinOps guidance and cost optimization strategies
