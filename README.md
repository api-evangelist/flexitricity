# Flexitricity (flexitricity)

Flexitricity Limited is an Edinburgh-based energy flexibility aggregator and licensed electricity supplier operating what it describes as the first, largest and most advanced demand response portfolio in Great Britain — a virtual power plant exceeding 1GW. Founded in 2004 by Dr Alastair Martin, acquired by Alpiq in 2014, merged with Quinbrook's Velox Power in 2022, and per the company's own timeline acquired by Drax in 2026, it sits in the value chain between commercial, industrial and aggregated domestic energy assets and the GB wholesale and balancing markets. It routes customer assets — batteries, standby generation, industrial load, hydrogen electrolysers, co-located sites and, through its FlexGO product, residential EV charging — into the Balancing Mechanism, Capacity Market, frequency response, reserve services, the Demand Flexibility Service, DNO flexibility markets and wholesale trading. Its API posture is closed: Flexitricity publishes no developer portal, no documented public API, no OpenAPI, and no open market data of its own. The developer-facing subdomains developer., developers., docs., api. and data. do not resolve; the only interactive surface is portal.flexitricity.com, which requires a customer account. The United Kingdom has no consumer data-portability mandate comparable to Australia's Consumer Data Right, so nothing compels Flexitricity to expose customer usage data through an API. The open, machine-readable data about Flexitricity is published by Elexon, not by Flexitricity — its 63 registered BM Units under lead party FLEXTRCY are retrievable anonymously from the Elexon BMRS Insights API. Open on the regulator's side, closed on its own: that split is the finding.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flexitricity/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flexitricity/refs/heads/main/apis.yml)

## Tags

- Energy
- United Kingdom
- Utilities
- Electricity
- Demand Response
- Energy Markets
- Grid
- DER
- Battery Storage
- Virtual Power Plant
- Flexibility
- EV Charging

## Timestamps

- **Created:** 2026-07-27
- **Modified:** 2026-07-27

## APIs

No public, documented APIs were found. Flexitricity publishes no developer portal, no API reference, and no machine-readable API contract of any kind. See [review.yml](review.yml) for the full probe log.

## Energy Data Posture

- **Home market:** United Kingdom
- **Mandate regime:** `smart-meter-infrastructure` — Great Britain mandated infrastructure and market machinery, not a consumer data right. There is no GB equivalent of the Australian Consumer Data Right for energy.
- **Mandate status:** `live-implemented` — but read the qualifier. The infrastructure obligation is verifiably live: Flexitricity Limited appears in the Elexon BMRS register (lead party `FLEXTRCY`) with 63 BM Units across 12 GSP groups, retrieved anonymously on 2026-07-27. That register is **Elexon's** implementation of **Elexon's** publication duty. Flexitricity itself publishes no endpoint, and nothing obliges it to.
- **Data standard:** No API data standard reference found. No Green Button/ESPI, no CDR Consumer Data Standards, no OpenADR, no IEEE 2030.5, no IEC CIM, no OCPP/OCPI. The company operates under GB market codes (BSC, Capacity Market rules, Grid Code) — market codes, not API standards.
- **Consumer data API:** No. There is no documented route for a third party to obtain an individual customer's usage or settlement data.
- **Open market data:** No — not from Flexitricity. Its market activity is published openly and in detail by Elexon and NESO instead.
- **Access gate:** `customer-account-required` — the only credentialed surface is `portal.flexitricity.com`, reachable only after signing a commercial contract. There is no self-serve signup, no application form for API access, and no sandbox.
- **Auth model:** None documented. No API key, OAuth 2.0, OpenID Connect, mTLS or accreditation scheme is published; no OIDC discovery document is served.

## Properties

- [Website](https://www.flexitricity.com/)
- [About](https://www.flexitricity.com/about)
- [Our Story](https://www.flexitricity.com/about/our-story)
- [Team](https://www.flexitricity.com/about/our-team)
- [Services](https://www.flexitricity.com/services)
- [Portal](https://portal.flexitricity.com/)
- [Login](https://portal.flexitricity.com/login)
- [Blog](https://www.flexitricity.com/blog)
- [Resources](https://www.flexitricity.com/resources/brochures-white-papers)
- [Videos](https://www.flexitricity.com/videos)
- [Privacy Policy](https://www.flexitricity.com/legal/privacy-policy)
- [Terms of Service](https://www.flexitricity.com/legal/terms-conditions)
- [Licence Conditions](https://www.flexitricity.com/legal/license-conditions)
- [LinkedIn](https://www.linkedin.com/company/flexitricity/)
- [YouTube](https://www.youtube.com/user/FlexitricityLtd)
- [GitHub Organization](https://github.com/Flexitricity) — exists, zero public repositories

## A note for harvesters

`www.flexitricity.com` and `flexgo.energy` both return **HTTP 200 for arbitrary paths**. `/openapi.json`, `/swagger.json`, `/api-docs`, `/robots.txt` and `/sitemap.xml` all return 200 with the same Next.js marketing shell. Status codes alone are meaningless on these hosts — content inspection is mandatory. Nothing here was saved as a specification.

## Maintainers

- Kin Lane — kin@apievangelist.com
