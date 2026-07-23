# Texas Capital Bank (texas-capital-bank)

Texas Capital Bank, National Association is the banking subsidiary of Texas Capital Bancshares, Inc. (NASDAQ: TCBI), a Dallas-headquartered full-service financial services firm founded in 1998 with roughly $31.5 billion in assets (FYE 2025). It serves businesses, entrepreneurs, and institutions across Texas and the United States with commercial and business banking, treasury management, mortgage/warehouse finance, and investment banking.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/texas-capital-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/texas-capital-bank/refs/heads/main/apis.yml)

## Open Finance & API Posture

Texas Capital Bank is relationship-first, not developer-first. It markets treasury and ERP API integrations, but arranges them through partner onboarding with dedicated bankers rather than a public self-serve developer portal.

- **No public first-party developer portal.** `developer.texascapitalbank.com` and `developers.texascapitalbank.com` do not resolve; `api.texascapitalbank.com` exists but returns HTTP 403 (an internal/gated gateway host, not public documentation).
- **No downloadable OpenAPI/Swagger** and **no self-serve API signup** are published.
- **Documented, partner-gated integrations:** ConnectNow embedded banking for Sage and NetSuite, direct platform integrations, custom APIs, and SFTP (XChange) file transfer, described on the bank's Application Programming Interface (API) product page.
- **Consumer data access is aggregator-only:** permissioned account and transaction data is shared through the Finicity (Mastercard) aggregator, not a first-party API.
- **US open-finance context:** participation is voluntary and fragmented under CFPB Section 1033 and the industry FDX standard; no direct FDX-conformant first-party data-access API or published 1033 posture was found for this institution.

Note: the third-party "developer portal" URL sometimes attributed to Texas Capital Bank (`/who-we-serve/business/homebuilders-developers`) is a customer-segment page for real-estate homebuilders and property developers, not a software developer portal.

## Tags

- Financial Services
- Banking
- United States
- Commercial Banking
- Treasury Management
- Regional Bank
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Texas Capital Bank Treasury & ERP Integration APIs

Relationship-based, partner-onboarded API and integration options for treasury and ERP connectivity — ConnectNow embedded banking for Sage and NetSuite, direct platform integrations, custom APIs, and SFTP (XChange) file transfer. No public developer portal or downloadable specification.

- **Human URL:** [https://texascapitalbank.com/commercial-banking/products-solutions/application-programming-interface](https://texascapitalbank.com/commercial-banking/products-solutions/application-programming-interface)

#### Tags

- Treasury
- ERP Integration
- Payments

#### Properties

- [Documentation](https://texascapitalbank.com/commercial-banking/products-solutions/application-programming-interface)

### Consumer Data Access (Aggregator)

Consumer-permissioned account and transaction data made available to third parties through the Finicity (Mastercard) data aggregator rather than a first-party Texas Capital Bank API.

- **Human URL:** [https://fintable.io/coverage/banks/United%20States/848_texas-capital-bank](https://fintable.io/coverage/banks/United%20States/848_texas-capital-bank)

#### Tags

- Open Finance
- Data Aggregation
- Finicity

#### Properties

- [Documentation](https://fintable.io/coverage/banks/United%20States/848_texas-capital-bank)

## Common Properties

- [Website](https://texascapitalbank.com/)
- [LinkedIn](https://www.linkedin.com/company/texas-capital-bank)
- [Blog](https://texascapitalbank.com/insights)
- [Privacy Policy](https://texascapitalbank.com/online-privacy-policy-url)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
