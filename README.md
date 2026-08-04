# Moody's Corporation (moodys-corporation)

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

Moody's Corporation (NYSE: MCO) is a global integrated risk-assessment firm operating through two segments: Moody's Ratings (Moody's Investors Service), which publishes credit ratings and assessment services on debt obligations, and Moody's Analytics, which provides data, software, research, and APIs spanning economic data, credit risk, KYC/AML, ESG, climate, and catastrophe modeling. Moody's Analytics products are exposed through multiple developer APIs and a portal at developer.moodys.com, with deeper API surfaces published at api.economy.com (Data Buffet, Scenario Studio, AutoCycle, ECCL) and through subsidiary brands including Bureau van Dijk (Orbis), RMS (catastrophe risk), Kompany / Passfort (KYC), and Four Twenty Seven (climate).

**APIs.json:** [https://github.com/api-evangelist/moodys-corporation/blob/main/apis.yml](https://github.com/api-evangelist/moodys-corporation/blob/main/apis.yml)

## Tags

- Analytics
- Catastrophe Risk
- Climate Risk
- Compliance
- Credit Ratings
- Economic Data
- ESG
- Financial Data
- KYC
- Risk

## Timestamps

- **Modified:** 2026-05-23

## APIs


#### Tags

- Credit Ratings
- Debt
- Fixed Income
- Issuer Reference Data
- Research
- Sovereign
- Structured Finance

#### Properties

- [Portal](https://ratings.moodys.com/)
- [Terms of Service](https://www.moodys.com/web/en/us/about/legal/terms-of-use.html)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's Analytics Developer Platform

Umbrella developer platform spanning Moody's Analytics APIs across economic data, credit risk, KYC, ESG, climate, and risk modeling. Hosts API catalogs, OpenAPI specifications, authentication (OAuth2 client credentials and HMAC), sandbox keys, and code samples for downstream Moody's API products including Data Buffet, Scenario Studio, AutoCycle, ECCL, ImpairmentStudio, RMS Intelligent Risk Platform, Orbis, and Passfort.

- **Human URL:** [https://developer.moodys.com/](https://developer.moodys.com/)
- **Base URL:** `https://developer.moodys.com/`

#### Tags

- API Catalog
- Developer Portal
- OAuth2
- SDKs

#### Properties

- [Portal](https://developer.moodys.com/)
- [Hub](https://hub.moodysanalytics.com/)
- [GitHub Organization](https://github.com/moodysanalytics)
- [OpenAPI](openapi/moodys-analytics-developer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's Analytics Data Buffet API

Programmatic access to international and subnational economic, demographic, and financial time-series data and forecasts. Supports retrieval of single or multi-series, basket creation, asynchronous bulk orders, and search against the Data Buffet repository. Authentication is OAuth2 client credentials with HMAC signing; rate-limited at one request per second and a 1 GB monthly data cap per key.

- **Human URL:** [https://www.economy.com/products/tools/data-buffet](https://www.economy.com/products/tools/data-buffet)
- **Base URL:** `https://api.economy.com/data/v1`

#### Tags

- Demographics
- Economic Data
- Forecasts
- Time Series

#### Properties

- [Documentation](https://api.economy.com/data/v1/swagger)
- [GitHub Organization](https://github.com/moodysanalytics/databuffet-api-codesamples)
- [OpenAPI](openapi/moodys-data-buffet-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's Analytics Scenario Studio API

Programmatic access to the Scenario Studio macroeconomic scenario platform, enabling automatic retrieval of custom scenarios generated against the Moody's Analytics Global Macroeconomic Model. Supports OAuth and HMAC authentication and returns JSON responses; a Postman collection and Python / R client libraries ship with the published code samples.

- **Human URL:** [https://hub.moodysanalytics.com/products](https://hub.moodysanalytics.com/products)
- **Base URL:** `https://api.economy.com/scenario-studio/v2`

#### Tags

- Economic Models
- Forecasting
- Macroeconomic
- Scenarios

#### Properties

- [Documentation](https://api.economy.com/scenario-studio/v2/swagger)
- [GitHub Organization](https://github.com/moodysanalytics/scenario-studio-api-codesamples)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's AutoCycle API

Retrieves forecasts of vehicle prices from AutoCycle models, integrating Moody's Analytics economic data and scenarios for automotive residual value forecasting.

- **Human URL:** [https://hub.moodysanalytics.com/products](https://hub.moodysanalytics.com/products)
- **Base URL:** `https://api.economy.com/autocycle/v1`

#### Tags

- Automotive
- Forecasts
- Residual Value
- Vehicle Pricing

#### Properties

- [Documentation](https://api.economy.com/autocycle/v1/swagger)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's Expected Consumer Credit Loss (ECCL) API

Retrieves expected consumer credit loss forecasts under baseline and stress scenarios. Combines customer data, economic data from Moody's Analytics, and consumer credit data for credit risk modeling and CCAR / CECL workflows.

- **Human URL:** [https://hub.moodysanalytics.com/products](https://hub.moodysanalytics.com/products)
- **Base URL:** `https://api.economy.com/eccl/v1`

#### Tags

- CECL
- Consumer Credit
- Credit Loss
- Forecasts
- Risk

#### Properties

- [Documentation](https://api.economy.com/eccl/v1/swagger)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's ImpairmentStudio API

Programmatic interface to ImpairmentStudio for CECL impairment estimation. Supports importing input datasets, triggering analyses, polling job status, and downloading analysis outputs via the apic Python CLI or direct API calls.

- **Human URL:** [https://www.moodys.com/web/en/us/products/impairmentstudio.html](https://www.moodys.com/web/en/us/products/impairmentstudio.html)
- **Base URL:** `https://api.moodys.com/impairmentstudio`

#### Tags

- CECL
- Credit Loss
- Impairment
- Reserve Modeling

#### Properties

- [C L I](https://github.com/moodysanalytics/apic)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's Orbis (Bureau van Dijk) API

Access to Orbis, the Bureau van Dijk company information database covering hundreds of millions of public and private companies worldwide with ownership, financials, officers, beneficial owners, ESG, and corporate family-tree data. The Orbis API and bulk data integrations feed KYC, compliance, third-party risk, and credit workflows.

- **Human URL:** [https://www.bvdinfo.com/en-gb/our-products/data/international/orbis](https://www.bvdinfo.com/en-gb/our-products/data/international/orbis)
- **Base URL:** `https://orbis.bvdinfo.com/`

#### Tags

- Beneficial Ownership
- Company Data
- Corporate Family Tree
- Financials
- KYC
- Reference Data

#### Properties

- [Documentation](https://www.bvdinfo.com/en-gb/our-products/data/integration/apis-and-feeds)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's KYC API (Kompany / Maxsight Entity Verification)

Verifies businesses against authoritative primary-source government registers in real time, returning legal entity records, ultimate beneficial owners, registered documents, and AML / sanctions screening signals. Powers the Maxsight Entity Verification API and Kompany Live Search.

- **Human URL:** [https://www.kompany.com/kycapi/discover](https://www.kompany.com/kycapi/discover)
- **Base URL:** `https://api.kompany.com/`

#### Tags

- Anti-Money Laundering
- Compliance
- Entity Verification
- KYC
- Risk
- Sanctions Screening

#### Properties

- [Documentation](https://www.kompany.com/kycapi/console-v2)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's Passfort Lifecycle API

Customer lifecycle and KYC orchestration platform enabling onboarding, perpetual KYC, customer due diligence, and supplier risk workflows. Exposes a Custom Check Framework so integrators can plug additional data providers into Passfort's policy engine.

- **Human URL:** [https://www.passfort.com/](https://www.passfort.com/)
- **Base URL:** `https://api.passfort.com/`

#### Tags

- Customer Due Diligence
- KYC
- Onboarding
- Perpetual KYC
- Workflow

#### Properties

- [SDK](https://github.com/moodysanalytics/MoodysAnalytics-PassFort-CustomCheckFramework)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moody's RMS Intelligent Risk Platform (IRP) API

APIs for the RMS Intelligent Risk Platform covering catastrophe modeling, exposure management, and event response across natural perils (hurricane, earthquake, flood, severe convective storm, wildfire), terrorism, cyber, and life / health events for insurance and reinsurance use cases.

- **Human URL:** [https://www.rms.com/products/risk-modeler](https://www.rms.com/products/risk-modeler)
- **Base URL:** `https://api.rms.com/`

#### Tags

- Catastrophe Risk
- Cyber Risk
- Exposure Management
- Insurance
- Reinsurance
- Risk Modeling

#### Properties

- [Documentation](https://www.rms.com/products/risk-modeler)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)


#### Tags

- Climate Risk
- Controversies
- CSRD
- ESG Scores
- Physical Risk
- SFDR
- TCFD
- Transition Risk

#### Properties

- [Documentation](https://www.moodys.com/web/en/us/capabilities/esg-and-climate.html)
- [Postman Collection](collections/moodys-analytics-developer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-analytics-developer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/moodys-data-buffet-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moodys-data-buffet-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.moodys.com/)
- [Blog](https://www.moodys.com/web/en/us/insights.html)
- [Terms of Service](https://www.moodys.com/web/en/us/about/legal/terms-of-use.html)
- [Privacy Policy](https://www.moodys.com/web/en/us/about/legal/privacy-policy.html)
- [GitHub Organization](https://github.com/moodysanalytics)
- [Investor Relations](https://ir.moodys.com/)
- [Contact](https://www.moodys.com/web/en/us/about/contact.html)
- [Insights](https://www.moodys.com/web/en/us/insights/all.html)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
