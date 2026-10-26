# Texas Capital Bank (texas-capital-bank)

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
