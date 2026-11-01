# Apier.no

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

Apier.no provides machine‑verifiable Norwegian company authority data via an API. It offers status, roles, and coded signing authority directly from Brønnøysundregistrene, with source, history, and signed receipts. The service is self‑serve, with no sales call, and supports AI agents through MCP tools and OpenAPI specifications.

**Areas:** Norwegian · CompanyData · API · MCP · Verification

## Apier.no on APIs.io

Everything profiled for Apier.no is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apier-no/](https://apis.io/providers/apier-no/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Apier.no Account API](https://apis.io/apis/apier-no/apier-no-account-api/) — Consumer self-serve account management — sign-up, magic-link request, key issuance. The /api/v1/account/signup endpoint is `security: []` on purpose: an…
- [Apier.no Actions API](https://apis.io/apis/apier-no/apier-no-actions-api/) — Withdrawn (2026-10-21). The filing-action surface (`POST /api/v1/actions/execute` in dry-run and live mode, the pending-action approve / reject / status…
- [Apier.no Admin API](https://apis.io/apis/apier-no/apier-no-admin-api/) — Administrative endpoints for managing consumers and API keys. Requires ADMIN_API_KEY.
- [Apier.no Altinn API](https://apis.io/apis/apier-no/apier-no-altinn-api/) — Withdrawn (2026-10-21). The Altinn-sourced authorisation surface (acting-capacity resolution over Altinn roles and delegations) answers HTTP 410…
- [Apier.no Auth Gateway API](https://apis.io/apis/apier-no/apier-no-auth-gateway-api/) — Withdrawn (2026-10-21). The delegation endpoints that used to arrange Maskinporten and Altinn access on the consumer's behalf answer HTTP 410…
- [Apier.no Brreg API](https://apis.io/apis/apier-no/apier-no-brreg-api/) — Brønnøysund Enhetsregisteret context surface — agent-shaped company profile reads. NLOD-licensed public data; role codes only, never personal identifiers…
- [Apier.no Changes API](https://apis.io/apis/apier-no/apier-no-changes-api/) — Cross-source change archive — detected archive events from Brreg, Altinn, DigDir, Norges Bank, NAV Aa-registeret, and Skatteetaten Tier 2 sub-results…
- [Apier.no Company API](https://apis.io/apis/apier-no/apier-no-company-api/) — Reads over the Registry Engine's two-tier company model (Tier 1 public Brønnøysund data + Tier 2 gated commercial metrics).
- [Apier.no Discovery API](https://apis.io/apis/apier-no/apier-no-discovery-api/) — Agent-first discovery manifest. `/v1/capabilities` is the machine-readable menu of every callable capability; `llms.txt` and `workflows.json` are the prose…
- [Apier.no Fullmakt API](https://apis.io/apis/apier-no/apier-no-fullmakt-api/) — Withdrawn (2026-10-21). The fullmakt line (agent principals, brokered Altinn systembruker delegations, their receipts and revocation) answers HTTP 410…
- [Apier.no Infrastructure API](https://apis.io/apis/apier-no/apier-no-infrastructure-api/) — Non-product endpoints (health checks, discovery).
- [Apier.no Knowledge API](https://apis.io/apis/apier-no/apier-no-knowledge-api/) — The Knowledge Catalog — canonical, machine-readable topic records answering what an agent needs to KNOW about Norwegian company authority and…
- [Apier.no Privacy API](https://apis.io/apis/apier-no/apier-no-privacy-api/) — Zero-auth GDPR transparency endpoints — Article 15 access requests via DSR. Rate-limited per IP (10/min, lower than Category A's 1000/min) so the surface…
- [Apier.no Public API](https://apis.io/apis/apier-no/apier-no-public-api/) — Free, zero-auth endpoints. Rate-limited per-IP (soft cap 1000/min). Distribution infrastructure, not revenue — these exist so agents can discover the API…
- [Apier.no Sandbox API](https://apis.io/apis/apier-no/apier-no-sandbox-api/) — Zero-auth, deterministic, CORS-open mirrors of every Category B company endpoint. Returns synthetic Norwegian company fixtures so agents can test…
- [Apier.no Subscriptions API](https://apis.io/apis/apier-no/apier-no-subscriptions-api/) — Pro-tier change-detection webhook subscriptions. Consumers register a webhook URL + filter; Apier fires HMAC-SHA256-signed deliveries when matching…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Apier No Webhooks](https://apis.io/asyncapis/apier-no/apier-no-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Apier No Agentic Access](https://apis.io/agentic-access/apier-no/apier-no-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CompanyContext](https://apis.io/schemas/apier-no/apier-no-company-context/)
- [CompanyVerification](https://apis.io/schemas/apier-no/apier-no-company-verification/)
- [ErrorCode](https://apis.io/schemas/apier-no/apier-no-error-code/)
- [SandboxMeta](https://apis.io/schemas/apier-no/apier-no-sandbox-meta/)
- [SignedReceipt](https://apis.io/schemas/apier-no/apier-no-signed-receipt/)
- [TrustMetadata](https://apis.io/schemas/apier-no/apier-no-trust-metadata/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Apier No Context](https://apis.io/jsonld/apier-no/apier-no-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Apier No Openapi Overlay](https://apis.io/overlays/apier-no/apier-no-openapi-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Apier.no API Rules](https://apis.io/rules/apier-no/apier-no-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Apier No Authentication](https://apis.io/security/apier-no/apier-no-authentication/)
- [Apier No Domain Security](https://apis.io/security/apier-no/apier-no-domain-security/)
- [Apier No Trust Center](https://apis.io/security/apier-no/apier-no-trust-center/)
- [Apier No Vulnerability Disclosure](https://apis.io/security/apier-no/apier-no-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Apier No Scopes](https://apis.io/scopes/apier-no/apier-no-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apier No Plans Pricing](https://apis.io/plans/apier-no/apier-no-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apier No Rate Limits](https://apis.io/rate-limits/apier-no/apier-no-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://apier.no/)
- [Documentation](https://www.apier.no/docs)
- [Getting started](https://www.apier.no/docs/quickstart)
- [API reference](https://www.apier.no/openapi.json)
- [Pricing](https://www.apier.no/pricing)
- [Support](https://www.apier.no/support)
- [Changelog](https://www.apier.no/docs/changelog)
- [Blog](https://www.apier.no/blog)
- [Security](https://www.apier.no/security)
- [Compliance](https://www.apier.no/trust)
- [Terms of service](https://www.apier.no/terms)
- [Privacy policy](https://www.apier.no/privacy)
- [Status](https://apier.betteruptime.com/)

## API Evangelist rating

**Kin Score 77.2** — exemplar · rubric 0.26.0 · scored 2026-11-01

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 70.9 |
| Contract governance | 79.1 |
| Operational transparency | 83.7 |
| Developer ergonomics | 61.2 |
| Access clarity | 79.5 |

**Agent readiness 74.3** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apier-no/](https://apis.io/providers/apier-no/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Apier.no: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apier-no/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
