# Sage

Sage provides cloud-based ERP, accounting, payroll, and HR software for businesses worldwide. The Sage Developer program offers APIs for integrating with Sage products including Sage Accounting (Business Cloud), Sage Intacct, Sage 200, Sage X3, and Sage 50.

**URL:** [https://developer.sage.com/](https://developer.sage.com/)

## APIs

### Sage Accounting API
Sage Accounting API (v3.1) is a RESTful web service for Sage Business Cloud Accounting. Covers contacts, sales/purchase invoices, payments, bank accounts, ledger accounts, products, and financial reports. OAuth 2.0 authentication. Rate limit: 1,296,000 requests/day.

**Human URL:** [https://developer.sage.com/accounting](https://developer.sage.com/accounting)

#### Tags
- Accounting, ERP, REST, OAuth 2.0

#### Properties
- [Documentation](https://developer.sage.com/accounting/reference)
- [Getting Started](https://developer.sage.com/accounting/guides/concepts/overview)
- [OpenAPI](openapi/sage-accounting-openapi.yml)

### Sage Intacct API
Advanced financial management with REST and XML APIs for multi-entity consolidations, project accounting, and revenue recognition. OAuth 2.0 authorization.

**Human URL:** [https://developer.sage.com/intacct/](https://developer.sage.com/intacct/)

#### Tags
- Accounting, ERP, REST, XML, OAuth 2.0

#### Properties
- [Documentation](https://developer.intacct.com/api/)
- [Authentication](https://developer.sage.com/intacct/docs/1/sage-intacct-rest-api/authorization-and-security/oauth2)

### Sage X3 API
GraphQL API for enterprise ERP including manufacturing, distribution, procurement, finance, and CRM.

**Human URL:** [https://developer.sage.com/x3/](https://developer.sage.com/x3/)

#### Tags
- ERP, GraphQL, Manufacturing, Distribution

### Sage 200 API
REST API for Sage 200 business management data for UK and Ireland mid-size businesses.

**Human URL:** [https://developer.sage.com/sage-200/](https://developer.sage.com/sage-200/)

#### Tags
- Accounting, ERP, REST

### Sage 50 Accounts API
Desktop accounting integration API for UK small businesses using Sage 50 Accounts.

**Human URL:** [https://developer.sage.com/sage-50-accounts/](https://developer.sage.com/sage-50-accounts/)

#### Tags
- Accounting, Desktop, REST

## Common Properties

- [Portal](https://developer.sage.com/)
- [Documentation](https://developer.sage.com/)
- [Authentication](https://developer.sage.com/accounting/guides/concepts/authentication)
- [Sandbox](https://developer.sage.com/accounting/guides/test-drive/)
- [Website](https://www.sage.com/)
- [Support](https://developer.sage.com/support/)
- [Blog](https://www.sage.com/en-us/blog/)
- [GitHubOrganization](https://github.com/Sage)
- [OpenAPI](openapi/sage-accounting-openapi.yml)
- [SpectralRules](rules/sage-rules.yml)
- [JSONSchema](json-schema/sage-contact-schema.json)
- [JSONSchema](json-schema/sage-invoice-schema.json)
- [JSONLDContext](json-ld/sage-context.jsonld)
- [Vocabulary](vocabulary/sage-vocabulary.yml)
- [Capabilities](capabilities/accounting-and-finance.yaml)

## Capabilities

### Shared Definitions
- [sage-accounting](capabilities/shared/sage-accounting.yaml) — Sage Accounting API v3.1

### Workflows
- [accounting-and-finance](capabilities/accounting-and-finance.yaml) — Unified accounting and financial management workflow (14 MCP tools)

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/sage-accounting-openapi.yml](openapi/sage-accounting-openapi.yml) |
| Spectral Rules | [rules/sage-rules.yml](rules/sage-rules.yml) |
| JSON Schema | [json-schema/sage-contact-schema.json](json-schema/sage-contact-schema.json) |
| JSON Schema | [json-schema/sage-invoice-schema.json](json-schema/sage-invoice-schema.json) |
| JSON Structure | [json-structure/sage-contact-structure.json](json-structure/sage-contact-structure.json) |
| JSON-LD Context | [json-ld/sage-context.jsonld](json-ld/sage-context.jsonld) |
| Vocabulary | [vocabulary/sage-vocabulary.yml](vocabulary/sage-vocabulary.yml) |
| Examples | [examples/](examples/) |

## Maintainers

**Email:** kin@apievangelist.com
