---
name: Resolve and verify a member identity
description: Resolve a contributor to a CDP member and attach/verify a platform identity.
api: openapi/crowddev-cdp-public-openapi.yml
operations: [resolveMember, createMember, getMemberIdentities, createMemberIdentity, verifyMemberIdentity]
---

# Resolve and verify a member identity (LFX Community Data Platform)

Use the CDP Public API (`https://cm.lfx.dev/api/v1`) to find or create a member and manage their identities.

## Auth
Send an OAuth 2.0 client-credentials bearer token (Auth0) or a static API key as a bearer token.
Scopes needed: `read:members`, `write:members`, `read:member-identities`, `write:member-identities`.

## Steps
1. `resolveMember` — POST `/members/resolve` with a known identity (platform + value) to find an existing member.
2. If none, `createMember` — POST `/members` with one or more identities to create the profile.
3. `getMemberIdentities` — GET `/members/{memberId}/identities` to review linked identities.
4. `createMemberIdentity` — POST `/members/{memberId}/identities` to attach a new platform identity.
5. `verifyMemberIdentity` — PATCH `/members/{memberId}/identities/{identityId}` to mark it verified.

## Rules
- A `409 Conflict` on `createMemberIdentity` means the identity already belongs to another member — resolve first.
- Errors return `{ "error": { "code", "message" } }` (application/json); handle `401`/`403` by checking token scopes.
- No idempotency key is supported; guard creates with a prior `resolveMember`.
