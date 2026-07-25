---
name: Look up contributor affiliations by GitHub handle
description: Resolve one or many GitHub handles to their organization affiliations via CDP.
api: openapi/crowddev-cdp-public-openapi.yml
operations: [getBulkAffiliations, getAffiliationByHandle]
---

# Contributor affiliation lookup (LFX Community Data Platform)

Use the CDP Public API (`https://cm.lfx.dev/api/v1`) to map GitHub contributors to organizations.

## Auth
OAuth 2.0 client-credentials bearer token or static API key. Scopes: `read:members`, `read:organizations`, `read:project-affiliations`.

## Steps
1. Single handle — `getAffiliationByHandle` — GET `/affiliations/{githubHandle}`.
2. Many handles — `getBulkAffiliations` — POST `/affiliations` with a batch of GitHub handles.

## Rules
- Unknown handles return `404 Not Found`.
- Paginate large result sets with `page` / `pageSize`; sort with `sortBy` / `sortDir`.
- Errors use the `{ "error": { "code", "message" } }` envelope.
