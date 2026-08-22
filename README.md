# Sage (sage)

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

Sage provides cloud-based ERP, accounting, payroll, and HR software for businesses worldwide. The Sage Developer program provides APIs for integrating with Sage products including Sage Accounting (Business Cloud), Sage Intacct, Sage 200, Sage X3, and Sage 50. APIs support OAuth 2.0 authentication and cover contacts, invoices, payments, ledger accounts, bank accounts, products, and financial reporting. Sage Accounting API v3.1 is the current supported REST version with daily limits of 1,296,000 requests per app.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sage/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Accounting
- Business Management
- Cloud Software
- ERP
- Payroll
- HR

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-30

## APIs

### Sage Accounting API

Sage Accounting API (v3.1) is a RESTful web service that connects software to Sage's cloud accounting platform. Supports contacts, sales invoices, purchase invoices, payments, bank accounts, ledger accounts, products/services, and financial reports. Uses OAuth 2.0 for authentication. Covers Sage Business Cloud Accounting and Sage Business Cloud Start products.

- **Human URL:** [https://developer.sage.com/accounting](https://developer.sage.com/accounting)

#### Tags

- Accounting
- ERP
- REST
- OAuth 2.0

#### Properties

- [Documentation](https://developer.sage.com/accounting/reference)
- [Getting Started](https://developer.sage.com/accounting/guides/concepts/overview)
- [OpenAPI](openapi/sage-accounting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage Intacct API

Sage Intacct provides both REST and XML APIs for advanced financial management including multi-entity consolidations, project accounting, revenue recognition, and advanced reporting. The REST API uses OAuth 2.0 for authorization. Targeted at mid-market and enterprise finance teams.

- **Human URL:** [https://developer.sage.com/intacct/](https://developer.sage.com/intacct/)

#### Tags

- Accounting
- ERP
- REST
- XML
- OAuth 2.0

#### Properties

- [Documentation](https://developer.intacct.com/api/)
- [Authentication](https://developer.sage.com/intacct/docs/1/sage-intacct-rest-api/authorization-and-security/oauth2)
- [Postman Collection](collections/sage-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage X3 API

Sage X3 provides a GraphQL API offering flexible data access for ERP operations including manufacturing, distribution, procurement, finance, and CRM. Supports SOAP API for legacy integrations. Targeted at enterprise and manufacturing organizations.

- **Human URL:** [https://developer.sage.com/x3/](https://developer.sage.com/x3/)

#### Tags

- ERP
- GraphQL
- Manufacturing
- Distribution

#### Properties

- [Documentation](https://developer.sage.com/x3/)
- [Postman Collection](collections/sage-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage 200 API

Sage 200 API provides REST access to Sage 200 Standard and Professional business management data including customers, suppliers, stock, sales orders, purchase orders, nominal ledger, bank reconciliation, and financial reporting for UK and Ireland mid-size businesses.

- **Human URL:** [https://developer.sage.com/sage-200/](https://developer.sage.com/sage-200/)

#### Tags

- Accounting
- ERP
- REST

#### Properties

- [Documentation](https://developer.sage.com/sage-200/)
- [Postman Collection](collections/sage-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage 50 Accounts API

Sage 50 Accounts API enables desktop accounting integration for UK small businesses. Provides access to accounts, transactions, customers, suppliers, products, and financial data within Sage 50 Accounts software.

- **Human URL:** [https://developer.sage.com/sage-50-accounts/](https://developer.sage.com/sage-50-accounts/)

#### Tags

- Accounting
- Desktop
- REST

#### Properties

- [Documentation](https://developer.sage.com/sage-50-accounts/)
- [Postman Collection](collections/sage-accounting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-accounting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sage-software)
- [Portal](https://developer.sage.com/)
- [Documentation](https://developer.sage.com/)
- [Authentication](https://developer.sage.com/accounting/guides/concepts/authentication)
- [Sandbox](https://developer.sage.com/accounting/guides/test-drive/)
- [Website](https://www.sage.com/)
- [Support](https://developer.sage.com/support/)
- [Blog](https://www.sage.com/en-us/blog/)
- [GitHub Organization](https://github.com/Sage)
- [OpenAPI](openapi/sage-accounting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/sage-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Spectral Rules](rules/sage-rules.yml)
- [JSON Schema](json-schema/sage-contact-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sage-invoice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sage-contact-structure.json)
- [JSON Structure](json-structure/sage-invoice-structure.json)
- [J S O N L D Context](json-ld/sage-context.jsonld)
- [Vocabulary](vocabulary/sage-vocabulary.yml)
- [Capabilities](capabilities/accounting-and-finance.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
