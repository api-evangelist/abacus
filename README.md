# Abacus (abacus)
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
