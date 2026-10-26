# Flexitricity (flexitricity)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
- [Contact](https://www.flexitricity.com/contact)
- [FlexGO](https://flexgo.energy/) — product site
- [GitHub Organization](https://github.com/Flexitricity) — exists, zero public repositories

## Artifacts

- [security/flexitricity-domain-security.yml](security/flexitricity-domain-security.yml) — TLS/HSTS/DNSSEC/CAA/SPF/DMARC across every Flexitricity host. TLS 1.3 everywhere, HSTS on portal/CMS/FlexGO but not on `www`, no DNSSEC, no CAA, DMARC at `quarantine`. Records one **dangling CNAME**: `trading.flexitricity.com` points at a CloudFront distribution that no longer resolves.
- [well-known/flexitricity-well-known.yml](well-known/flexitricity-well-known.yml) — evidenced negative for the `/.well-known/` surface. Zero documents on any host; every HTTP 200 is the soft-404 shell.
- [llms/flexitricity-llms.txt](llms/flexitricity-llms.txt) — generated agent-facing index, including the explicit warning that no API exists and that Elexon, not Flexitricity, is where the machine-readable data lives.

No `openapi/`, `packages/`, `mcp/`, `skills/`, `asyncapi/`, `conventions/` or `errors/` directories exist, because there is no specification and no published developer surface to ground them in. A registry sweep (npm, PyPI, RubyGems, Packagist, crates.io, NuGet) returned zero results.

## A note for harvesters

`www.flexitricity.com` and `flexgo.energy` both return **HTTP 200 for arbitrary paths**. `/openapi.json`, `/swagger.json`, `/api-docs`, `/robots.txt` and `/sitemap.xml` all return 200 with the same Next.js marketing shell. Status codes alone are meaningless on these hosts — content inspection is mandatory. Nothing here was saved as a specification.

## Maintainers

- Kin Lane — kin@apievangelist.com
