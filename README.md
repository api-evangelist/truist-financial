# Truist Financial (truist-financial)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Truist Financial Corporation is a purpose-driven financial services company headquartered in Charlotte, North Carolina, formed by the merger of BB&T and SunTrust Banks in 2019. As one of the ten largest commercial banks in the United States, Truist offers a comprehensive suite of developer APIs through its Developer Center, enabling financial institutions, fintech companies, and enterprise clients to integrate banking capabilities into their applications. The platform covers personal and small business banking, commercial accounts, transactions, open banking, and association services, with OAuth 2.0 and API key authentication. Truist launched FDX-compliant open banking in 2026, partnering with Mastercard and Plaid to enable secure, tokenized financial data sharing for consumers and businesses.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Banking
- Financial Services
- Open Banking
- Commercial Banking
- Personal Banking
- Payments
- Accounts
- Transactions
- Fortune 500

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Truist Personal and Small Business Accounts API

The Truist Personal and Small Business Accounts API provides programmatic access to consumer and small business deposit account information, including account details, balances, account types, and ownership information. Developers can retrieve account lists for authenticated clients, access individual account details, and retrieve balance information for checking, savings, and money market accounts. The API supports OAuth 2.0 authentication and is designed for fintech integrations, account aggregation platforms, and personal finance management applications.

- **Human URL:** [https://developer.truist.com/api/personal-and-small-business-accounts/overview](https://developer.truist.com/api/personal-and-small-business-accounts/overview)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Accounts
- Personal Banking
- Small Business
- Banking

#### Properties

- [Documentation](https://developer.truist.com/api/personal-and-small-business-accounts/overview)
- [Documentation](https://developer.truist.com/api/personal-and-small-business-accounts/documentation)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-accounts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truist Personal and Small Business Transactions API

The Truist Personal and Small Business Transactions API enables retrieval of transaction history for personal and small business accounts. Developers can access posted and pending transactions, filter by date range, and retrieve transaction details including merchant information, amounts, and transaction categories. The API supports OAuth 2.0 authentication and is suitable for personal finance management tools, accounting integrations, and expense tracking applications.

- **Human URL:** [https://developer.truist.com/api/personal-and-small-business-transactions/overview](https://developer.truist.com/api/personal-and-small-business-transactions/overview)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Transactions
- Personal Banking
- Small Business
- Banking

#### Properties

- [Documentation](https://developer.truist.com/api/personal-and-small-business-transactions/overview)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-transactions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truist Personal and Small Business Client Contact API

The Truist Personal and Small Business Client Contact API provides access to client contact information associated with personal and small business accounts, including address, phone number, and email address data. This API enables authorized applications to retrieve and manage contact details for authenticated Truist clients, supporting CRM integrations and account management workflows.

- **Human URL:** [https://developer.truist.com/api/personal-and-small-business-client-contact/overview](https://developer.truist.com/api/personal-and-small-business-client-contact/overview)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Client Management
- Personal Banking
- Small Business
- Contact Information
- Banking

#### Properties

- [Documentation](https://developer.truist.com/api/personal-and-small-business-client-contact/overview)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truist Commercial Accounts API

The Truist Commercial Accounts API provides programmatic access to commercial deposit account information, including account balances, account details, and account summary data for commercial and corporate clients. The API supports treasury management integrations, ERP system connectivity, and cash management platforms. It enables real-time balance reporting, account hierarchy retrieval, and integration with commercial banking operations. OAuth 2.0 and API key authentication are supported.

- **Human URL:** [https://developer.truist.com/api/commercial-accounts/overview](https://developer.truist.com/api/commercial-accounts/overview)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Accounts
- Commercial Banking
- Treasury
- Banking

#### Properties

- [Documentation](https://developer.truist.com/api/commercial-accounts/overview)
- [Documentation](https://developer.truist.com/api/commercial-accounts/documentation)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-accounts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truist Commercial Account Transactions API

The Truist Commercial Account Transactions API enables programmatic retrieval of commercial account transaction data including ACH credits and debits, wire transfers, checks, and other payment types. The API supports filtering by date range and transaction type, enabling ERP integrations, cash flow reconciliation, and automated accounting workflows. It is designed for treasury teams, corporate finance applications, and commercial banking integrations.

- **Human URL:** [https://developer.truist.com/api/commercial-account-transactions/overview](https://developer.truist.com/api/commercial-account-transactions/overview)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Transactions
- Commercial Banking
- Treasury
- Banking

#### Properties

- [Documentation](https://developer.truist.com/api/commercial-account-transactions/overview)
- [Documentation](https://developer.truist.com/api/commercial-account-transactions/documentation)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-account-transactions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truist Commercial Account Transaction Image API

The Truist Commercial Account Transaction Image API provides access to check images and transaction document images associated with commercial account transactions. Developers can retrieve front and back images of checks, deposit slips, and other payment documents by transaction reference. The API supports document archiving, audit workflows, and automated reconciliation integrations for commercial banking clients.

- **Human URL:** [https://developer.truist.com/api/commercial-account-transaction-image/overview](https://developer.truist.com/api/commercial-account-transaction-image/overview)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Transactions
- Check Images
- Commercial Banking
- Documents
- Banking

#### Properties

- [Documentation](https://developer.truist.com/api/commercial-account-transaction-image/overview)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truist Open Banking API

The Truist Open Banking API provides secure, FDX-compliant (Financial Data Exchange) access to consumer and small business financial data, enabling authorized fintech applications to retrieve account balances, transaction history, and payment information with client consent. Launched in February 2026 in partnership with Mastercard's open finance platform, the API replaces credential sharing with tokenized, permission-based access. Truist expanded the program through a Plaid data-access agreement in March 2026, enabling clients to manage and revoke third-party data access through a centralized consent portal. The API supports account information, transaction data, investment data, and loan data per FDX standards.

- **Human URL:** [https://truist-1132.my.site.com/truist/s/](https://truist-1132.my.site.com/truist/s/)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Open Banking
- FDX
- Financial Data Exchange
- Accounts
- Banking

#### Properties

- [Portal](https://truist-1132.my.site.com/truist/s/)
- [Documentation](https://truist-1132.my.site.com/truist/s/subscriptions)
- [Announcement](https://www.prnewswire.com/news-releases/truist-launches-secure-open-banking-experience-302685248.html)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Truist Association Services API

The Truist Association Services API provides banking and payment capabilities tailored for associations, non-profit organizations, and community groups. The API supports dues collection, payment processing, member account management, and reporting for trade associations, homeowners associations, and membership organizations that bank with Truist. It enables integration of banking workflows into association management platforms and member portals.

- **Human URL:** [https://developer.truist.com/categories/association-services](https://developer.truist.com/categories/association-services)
- **Base URL:** `https://api.truist.com/v1`

#### Tags

- Association Services
- Community Banking
- Banking
- Payments

#### Properties

- [Documentation](https://developer.truist.com/categories/association-services)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [Postman Collection](collections/truist-commercial-account-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-account-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-commercial-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-commercial-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/truist-personal-small-business-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truist-personal-small-business-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.truist.com)
- [Portal](https://developer.truist.com/)
- [Getting Started](https://developer.truist.com/api/working-with-truist)
- [Authentication](https://developer.truist.com/api/working-with-truist)
- [Portal](https://truist-1132.my.site.com/truist/s/)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/rules/truist-financial-rules.yml)
- [Investor Relations](https://investor.truist.com/)
- [About](https://www.truist.com/about-truist)
- [Blog](https://ir.truist.com/news-releases)
- [LinkedIn](https://www.linkedin.com/company/truistfinancial)
- [X (Twitter)](https://twitter.com/Truist)
- [Git Hub](https://github.com/truistbank)
- [Privacy Policy](https://www.truist.com/privacy-security)
- [Terms of Service](https://www.truist.com/about-truist/terms-conditions)
- [Features](undefined)
- [L L Ms Txt](https://developer.truist.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
