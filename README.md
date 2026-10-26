# Abacus (abacus)

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

Abacus (now part of Emburse Spend) is an expense management platform that allows businesses to streamline expense reporting, receipts, and reimbursements. The Abacus API is available to partners and enterprise customers, providing programmatic access to member management and expense operations using OAuth 2.0 authentication.

**URL:** [https://www.abacus.com/](https://www.abacus.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=abacus-api-evangelist&utm_content=repo)

## Tags:

 - Accounting, Expense Management, Finance, Reimbursement

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Abacus API
The Abacus API provides programmatic access to expense management functionality, including inviting and suspending members, listing and retrieving expense reports, and integrating with third-party platforms. Available to partners and enterprise customers using OAuth 2.0 client credentials.

**Human URL:** [https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API](https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API)

#### Tags:

 - Expenses, Finance, Members, Reimbursement

#### Properties

- [Documentation](https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API)
- [OpenAPI](openapi/abacus-api-openapi.yaml)
- [JSONSchema - Member](json-schema/abacus-member-schema.json)
- [JSONSchema - Expense](json-schema/abacus-expense-schema.json)
- [JSONSchema - Invite Member Request](json-schema/abacus-invite-member-request-schema.json)
- [JSONSchema - Update Member Request](json-schema/abacus-update-member-request-schema.json)
- [JSONSchema - Member List Response](json-schema/abacus-member-list-response-schema.json)
- [JSONSchema - Expense List Response](json-schema/abacus-expense-list-response-schema.json)
- [JSONSchema - OAuth Token Request](json-schema/abacus-oauth-token-request-schema.json)
- [JSONSchema - OAuth Token Response](json-schema/abacus-oauth-token-response-schema.json)

## Common Properties

- [Website](https://www.abacus.com/)
- [Documentation](https://support.abacus.com/hc/en-us/articles/12493681200269-Abacus-API)
- [Support](https://support.abacus.com/)
- [PrivacyPolicy](https://legal.emburse.com/)
- [TrustCenter](https://trust.emburse.com/)
- [SpectralRules](rules/abacus-spectral-rules.yml)
- [Vocabulary](vocabulary/abacus-vocabulary.yaml)
- [NaftikoCapability](capabilities/expense-management.yaml)
- [JSONLD](json-ld/abacus-api-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Member Management | Invite, update, and suspend organization members programmatically |
| Expense Tracking | Retrieve and filter expense reports by status, member, and date range |
| OAuth 2.0 Authentication | Secure API access using client credentials grant flow |
| Receipt Management | Link receipts to expense reports via URL references |
| Multi-category Expenses | Categorize expenses across meals, travel, lodging, office supplies, and software |
| Paginated Results | Paginated API responses with configurable page sizes |

## Use Cases

| Name | Description |
|------|-------------|
| Employee Onboarding | Automatically invite new employees to the expense platform via API |
| Employee Offboarding | Programmatically suspend departed employees from expense access |
| Expense Reconciliation | Retrieve and reconcile expense reports for accounting integration |
| Spend Analytics | Pull expense data by category, member, or date range for reporting |
| Third-party Integration | Connect Abacus expense data with ERP and accounting systems |

## Integrations

| Name | Description |
|------|-------------|
| QuickBooks | Sync expense data with QuickBooks for accounting reconciliation |
| Xero | Integrate with Xero for automated expense accounting |
| NetSuite | Connect expense reports with NetSuite ERP |
| Sage Intacct | Sync expenses with Sage Intacct for financial management |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Abacus API](openapi/abacus-api-openapi.yaml)

### JSON Schema

- [abacus-member-schema.json](json-schema/abacus-member-schema.json)
- [abacus-invite-member-request-schema.json](json-schema/abacus-invite-member-request-schema.json)
- [abacus-update-member-request-schema.json](json-schema/abacus-update-member-request-schema.json)
- [abacus-member-list-response-schema.json](json-schema/abacus-member-list-response-schema.json)
- [abacus-expense-schema.json](json-schema/abacus-expense-schema.json)
- [abacus-expense-list-response-schema.json](json-schema/abacus-expense-list-response-schema.json)
- [abacus-oauth-token-request-schema.json](json-schema/abacus-oauth-token-request-schema.json)
- [abacus-oauth-token-response-schema.json](json-schema/abacus-oauth-token-response-schema.json)

### JSON Structure

- [abacus-member-structure.json](json-structure/abacus-member-structure.json)
- [abacus-invite-member-request-structure.json](json-structure/abacus-invite-member-request-structure.json)
- [abacus-update-member-request-structure.json](json-structure/abacus-update-member-request-structure.json)
- [abacus-member-list-response-structure.json](json-structure/abacus-member-list-response-structure.json)
- [abacus-expense-structure.json](json-structure/abacus-expense-structure.json)
- [abacus-expense-list-response-structure.json](json-structure/abacus-expense-list-response-structure.json)
- [abacus-oauth-token-request-structure.json](json-structure/abacus-oauth-token-request-structure.json)
- [abacus-oauth-token-response-structure.json](json-structure/abacus-oauth-token-response-structure.json)

### JSON-LD

- [abacus-api-context.jsonld](json-ld/abacus-api-context.jsonld)

### Examples

- [abacus-member-example.json](examples/abacus-member-example.json)
- [abacus-invite-member-request-example.json](examples/abacus-invite-member-request-example.json)
- [abacus-update-member-request-example.json](examples/abacus-update-member-request-example.json)
- [abacus-member-list-response-example.json](examples/abacus-member-list-response-example.json)
- [abacus-expense-example.json](examples/abacus-expense-example.json)
- [abacus-expense-list-response-example.json](examples/abacus-expense-list-response-example.json)
- [abacus-oauth-token-request-example.json](examples/abacus-oauth-token-request-example.json)
- [abacus-oauth-token-response-example.json](examples/abacus-oauth-token-response-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Abacus API](capabilities/shared/abacus-api.yaml) — 7 operations for expense management and member administration

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Expense Management](capabilities/expense-management.yaml) | Abacus API | 7 | Finance Administrator, HR Manager |

## Vocabulary

- [Abacus Vocabulary](vocabulary/abacus-vocabulary.yaml) — Unified taxonomy mapping 2 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Abacus Spectral Rules](rules/abacus-spectral-rules.yml) — 42 rules across 13 categories enforcing Abacus API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
