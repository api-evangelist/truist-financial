# Truist Financial

Truist Financial Corporation is a purpose-driven financial services company headquartered in Charlotte, North Carolina, formed by the merger of BB&T and SunTrust Banks in 2019. As one of the ten largest commercial banks in the United States, Truist offers a comprehensive suite of developer APIs through its Developer Center, enabling financial institutions, fintech companies, and enterprise clients to integrate banking capabilities into their applications.

The platform covers personal and small business banking, commercial accounts, transactions, open banking, and association services. Truist launched FDX-compliant open banking in February 2026, partnering with Mastercard and Plaid to enable secure, tokenized financial data sharing for consumers and businesses.

**Developer Center:** [developer.truist.com](https://developer.truist.com/)
**Open Banking Portal:** [truist-1132.my.site.com/truist/s/](https://truist-1132.my.site.com/truist/s/)

---

## APIs

### Personal and Small Business Accounts API
Access consumer and small business deposit account details, types, and balances.
- [Overview](https://developer.truist.com/api/personal-and-small-business-accounts/overview)
- [OpenAPI Spec](openapi/truist-personal-small-business-accounts-openapi.yml)

### Personal and Small Business Transactions API
Retrieve transaction history for personal and small business accounts with date range and status filtering.
- [Overview](https://developer.truist.com/api/personal-and-small-business-transactions/overview)
- [OpenAPI Spec](openapi/truist-personal-small-business-transactions-openapi.yml)

### Personal and Small Business Client Contact API
Access and manage client contact information for personal and small business accounts.
- [Overview](https://developer.truist.com/api/personal-and-small-business-client-contact/overview)

### Commercial Accounts API
Access commercial deposit account details, balances, and consolidated summaries for corporate clients.
- [Overview](https://developer.truist.com/api/commercial-accounts/overview)
- [OpenAPI Spec](openapi/truist-commercial-accounts-openapi.yml)

### Commercial Account Transactions API
Retrieve commercial transaction history including ACH, wire transfers, checks, and book transfers.
- [Overview](https://developer.truist.com/api/commercial-account-transactions/overview)
- [OpenAPI Spec](openapi/truist-commercial-account-transactions-openapi.yml)

### Commercial Account Transaction Image API
Access check images and transaction document images for commercial account transactions.
- [Overview](https://developer.truist.com/api/commercial-account-transaction-image/overview)

### Open Banking API
FDX-compliant open banking access with client-permissioned data sharing via Mastercard and Plaid partnerships.
- [Portal](https://truist-1132.my.site.com/truist/s/)

### Association Services API
Banking and payment capabilities for associations, non-profits, and membership organizations.
- [Overview](https://developer.truist.com/categories/association-services)

---

## Artifacts

### OpenAPI Specifications
| Spec | Description |
|---|---|
| [truist-personal-small-business-accounts-openapi.yml](openapi/truist-personal-small-business-accounts-openapi.yml) | Personal and Small Business Accounts API |
| [truist-personal-small-business-transactions-openapi.yml](openapi/truist-personal-small-business-transactions-openapi.yml) | Personal and Small Business Transactions API |
| [truist-commercial-accounts-openapi.yml](openapi/truist-commercial-accounts-openapi.yml) | Commercial Accounts API |
| [truist-commercial-account-transactions-openapi.yml](openapi/truist-commercial-account-transactions-openapi.yml) | Commercial Account Transactions API |

### Spectral Rules
| File | Description |
|---|---|
| [truist-financial-rules.yml](rules/truist-financial-rules.yml) | Spectral ruleset enforcing Truist API conventions |

### Naftiko Capabilities

#### Shared Definitions
| File | API |
|---|---|
| [shared/personal-accounts.yaml](capabilities/shared/personal-accounts.yaml) | Personal and Small Business Accounts API |
| [shared/personal-transactions.yaml](capabilities/shared/personal-transactions.yaml) | Personal and Small Business Transactions API |
| [shared/commercial-accounts.yaml](capabilities/shared/commercial-accounts.yaml) | Commercial Accounts API |
| [shared/commercial-transactions.yaml](capabilities/shared/commercial-transactions.yaml) | Commercial Account Transactions API |

#### Workflow Capabilities
| File | Description | APIs |
|---|---|---|
| [personal-banking.yaml](capabilities/personal-banking.yaml) | Personal and small business banking data access | Personal Accounts + Transactions |
| [commercial-banking.yaml](capabilities/commercial-banking.yaml) | Commercial treasury management and transaction reporting | Commercial Accounts + Transactions |

### JSON Schema
| File | Description |
|---|---|
| [truist-financial-account-schema.json](json-schema/truist-financial-account-schema.json) | Truist deposit account schema |
| [truist-financial-transaction-schema.json](json-schema/truist-financial-transaction-schema.json) | Truist banking transaction schema |

### JSON Structure
| File | Description |
|---|---|
| [truist-financial-account-structure.json](json-structure/truist-financial-account-structure.json) | Account field structure documentation |
| [truist-financial-transaction-structure.json](json-structure/truist-financial-transaction-structure.json) | Transaction field structure documentation |

### JSON-LD Context
| File | Description |
|---|---|
| [truist-financial-context.jsonld](json-ld/truist-financial-context.jsonld) | JSON-LD context mapping Truist vocabulary to schema.org and FIBO ontologies |

### Examples
| File | Description |
|---|---|
| [truist-list-personal-accounts-example.json](examples/truist-list-personal-accounts-example.json) | List personal accounts |
| [truist-get-personal-account-balances-example.json](examples/truist-get-personal-account-balances-example.json) | Get account balances |
| [truist-list-personal-transactions-example.json](examples/truist-list-personal-transactions-example.json) | List personal transactions |
| [truist-list-commercial-accounts-example.json](examples/truist-list-commercial-accounts-example.json) | List commercial accounts |
| [truist-list-commercial-transactions-example.json](examples/truist-list-commercial-transactions-example.json) | List commercial transactions |

### Vocabulary
| File | Description |
|---|---|
| [truist-financial-vocabulary.yml](vocabulary/truist-financial-vocabulary.yml) | Domain vocabulary for Truist banking APIs |

---

## Authentication

Truist APIs use OAuth 2.0 authentication:
- **Personal banking APIs**: Authorization Code flow (consumer-permissioned)
- **Commercial banking APIs**: Client Credentials flow (server-to-server)
- **Open Banking**: FDX-compliant OAuth 2.0 with tokenized consent management

[Authentication Guide](https://developer.truist.com/api/working-with-truist)

---

## Links

- [Website](https://www.truist.com)
- [Developer Center](https://developer.truist.com/)
- [Open Banking Portal](https://truist-1132.my.site.com/truist/s/)
- [Investor Relations](https://investor.truist.com/)
- [Privacy Policy](https://www.truist.com/privacy-security)
- [Terms of Service](https://www.truist.com/about-truist/terms-conditions)
- [GitHub](https://github.com/truistbank)
- [LinkedIn](https://www.linkedin.com/company/truistfinancial)
- [X (Twitter)](https://twitter.com/Truist)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
