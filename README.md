# Crowd.dev

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

Crowd.dev is an open-source developer data platform that centralizes community, product, and commercial data to unify contributor identities, resolve who is engaging with an open-source project, and activate that data for developer relations and community-led growth. Founded in Berlin and backed by Seedcamp, crowd.dev was acquired by the Linux Foundation in April 2024 and now powers the LFX Community Data Platform (CDP). The codebase is Apache-2.0 open source at github.com/CrowdDotDev (now linuxfoundation/crowd.dev), and the CDP Public API exposes transactional REST endpoints for member and organization profiles, identity verification, work-experience and project-affiliation management, contributor affiliation lookups, and open-source package/stewardship intelligence.

**Areas:** Company · Community · Developer Relations · Developer Data Platform · Identity Resolution · Open Source · Community Data Platform · Open Source Intelligence

## Crowd.dev on APIs.io

Everything profiled for Crowd.dev is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/crowddev/](https://apis.io/providers/crowddev/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Crowd.dev Advisories API](https://apis.io/apis/crowddev/crowddev-advisories-api/) — Security advisories for a package, split out of package detail. The draft contract gates these behind a dedicated read:advisories scope; until Auth0 issues…
- [Crowd.dev Affiliations API](https://apis.io/apis/crowddev/crowddev-affiliations-api/) — Bulk contributor affiliation lookups by GitHub handle.
- [Crowd.dev Contacts API](https://apis.io/apis/crowddev/crowddev-contacts-api/) — Security contacts for a package — includes contact PII (e.g. reporter emails). The contract gates these behind a dedicated cdp:maintainers:read scope and…
- [Crowd.dev Dashboard API](https://apis.io/apis/crowddev/crowddev-dashboard-api/) — KPI bar metrics and activity feed.
- [Crowd.dev Maintainer Roles API](https://apis.io/apis/crowddev/crowddev-maintainer-roles-api/) — Retrieve maintainer roles for a member.
- [Crowd.dev Member Affiliations API](https://apis.io/apis/crowddev/crowddev-member-affiliations-api-api/) — API endpoints for managing project affiliations, including listing and bulk updating affiliation relationships within a profile.
- [Crowd.dev Member Identities API](https://apis.io/apis/crowddev/crowddev-member-identities-api/) — Manage and verify member identities across platforms.
- [Crowd.dev Member Organizations API](https://apis.io/apis/crowddev/crowddev-member-organizations-api-api/) — API endpoints for managing work history organizations, including creating, reading, updating, and deleting organization relationships for profiles.
- [Crowd.dev Members API](https://apis.io/apis/crowddev/crowddev-members-api/) — Resolve member profiles by identity.
- [Crowd.dev Organizations API](https://apis.io/apis/crowddev/crowddev-organizations-api/) — Look up and create organizations.
- [Crowd.dev Packages API](https://apis.io/apis/crowddev/crowddev-packages-api/) — Package detail — requires read:packages and read:stewardships (see TODO above).
- [Crowd.dev Project Affiliations API](https://apis.io/apis/crowddev/crowddev-project-affiliations-api/) — View and override per-project affiliation data for a member.
- [Crowd.dev Stewardship Actions API](https://apis.io/apis/crowddev/crowddev-stewardship-actions-api/) — Admin-initiated stewardship mutations.
- [Crowd.dev Stewardship API](https://apis.io/apis/crowddev/crowddev-stewardship-api/) — Stewardship state — individual and batch.
- [Crowd.dev Stewardships API](https://apis.io/apis/crowddev/crowddev-stewardships-api/) — Open, assign, escalate, and update stewardship status.
- [Crowd.dev Work Experiences API](https://apis.io/apis/crowddev/crowddev-work-experiences-api/) — Manage and verify member work experiences (organization affiliations).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [crowddev-cdp](https://apis.io/servers/crowddev/crowddev-cdp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Crowddev Agentic Access](https://apis.io/agentic-access/crowddev/crowddev-agentic-access/)

#### Collections (16)

Postman and Open Collection request collections.

- [CDP → Akrites External Advisories API](https://apis.io/collections/crowddev/open-crowddev-advisories-api/)
- [CDP → Akrites External Advisories Affiliations API](https://apis.io/collections/crowddev/open-crowddev-affiliations-api/)
- [CDP → Akrites External Advisories Contacts API](https://apis.io/collections/crowddev/open-crowddev-contacts-api/)
- [CDP → Akrites External Advisories Dashboard API](https://apis.io/collections/crowddev/open-crowddev-dashboard-api/)
- [CDP → Akrites External Advisories Maintainer Roles API](https://apis.io/collections/crowddev/open-crowddev-maintainer-roles-api/)
- [CDP → Akrites External Advisories Member Affiliations API API](https://apis.io/collections/crowddev/open-crowddev-member-affiliations-api-api/)
- [CDP → Akrites External Advisories Member Identities API](https://apis.io/collections/crowddev/open-crowddev-member-identities-api/)
- [CDP → Akrites External Advisories Member Organizations API API](https://apis.io/collections/crowddev/open-crowddev-member-organizations-api-api/)
- [CDP → Akrites External Advisories Members API](https://apis.io/collections/crowddev/open-crowddev-members-api/)
- [CDP → Akrites External Advisories Organizations API](https://apis.io/collections/crowddev/open-crowddev-organizations-api/)
- [CDP → Akrites External Advisories Packages API](https://apis.io/collections/crowddev/open-crowddev-packages-api/)
- [CDP → Akrites External Advisories Project Affiliations API](https://apis.io/collections/crowddev/open-crowddev-project-affiliations-api/)
- [CDP → Akrites External Advisories Stewardship Actions API](https://apis.io/collections/crowddev/open-crowddev-stewardship-actions-api/)
- [CDP → Akrites External Advisories Stewardship API](https://apis.io/collections/crowddev/open-crowddev-stewardship-api/)
- [CDP → Akrites External Advisories Stewardships API](https://apis.io/collections/crowddev/open-crowddev-stewardships-api/)
- [CDP → Akrites External Advisories Work Experiences API](https://apis.io/collections/crowddev/open-crowddev-work-experiences-api/)

#### Overlays (7)

OpenAPI overlays, including conversational phrasing for each operation.

- [Crowddev Cdp Akrites External Overlay](https://apis.io/overlays/crowddev/crowddev-cdp-akrites-external-overlay/)
- [Crowddev Cdp Akrites Overlay](https://apis.io/overlays/crowddev/crowddev-cdp-akrites-overlay/)
- [Crowddev Cdp Ossprey Overlay](https://apis.io/overlays/crowddev/crowddev-cdp-ossprey-overlay/)
- [Crowddev Cdp Packages Overlay](https://apis.io/overlays/crowddev/crowddev-cdp-packages-overlay/)
- [Crowddev Cdp Public Overlay](https://apis.io/overlays/crowddev/crowddev-cdp-public-overlay/)
- [Crowddev Cdp Stewardships Overlay](https://apis.io/overlays/crowddev/crowddev-cdp-stewardships-overlay/)
- [Crowddev Cm Id Overlay](https://apis.io/overlays/crowddev/crowddev-cm-id-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Crowddev Authentication](https://apis.io/security/crowddev/crowddev-authentication/)
- [Crowddev Domain Security](https://apis.io/security/crowddev/crowddev-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Crowddev Scopes](https://apis.io/scopes/crowddev/crowddev-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Crowddev Plans Pricing](https://apis.io/plans/crowddev/crowddev-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Crowddev Rate Limits](https://apis.io/rate-limits/crowddev/crowddev-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://crowd.dev)
- [Documentation](https://docs.linuxfoundation.org/lfx/community-management)
- [Getting started](https://docs.linuxfoundation.org/lfx/community-management/quick-start-guide)
- [API reference](https://github.com/linuxfoundation/crowd.dev/tree/main/backend/src/api/public)
- [Pricing](https://docs.linuxfoundation.org/lfx/community-management)
- [Sign up](https://cm.lfx.dev/project-groups)
- [Support](https://jira.linuxfoundation.org/plugins/servlet/desk/portal/4)
- [Changelog](https://changelog.crowd.dev/)
- [Terms of service](https://www.linuxfoundation.org/legal/terms)
- [Privacy policy](https://www.linuxfoundation.org/legal/privacy-policy)
- [GitHub](https://github.com/CrowdDotDev)
- [Status](https://status.lfx.dev)

## API Evangelist rating

**Kin Score 56.4** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 52.1 |
| Contract governance | 18.2 |
| Operational transparency | 50.0 |
| Developer ergonomics | 70.8 |
| Access clarity | 52.6 |

**Agent readiness 36.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/crowddev/](https://apis.io/providers/crowddev/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Crowd.dev: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/crowddev/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
