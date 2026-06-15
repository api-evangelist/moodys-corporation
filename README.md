# Moody's Corporation (moodys-corporation)

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

### Moody's Ratings (Moody's Investors Service)

Moody's Ratings (formerly Moody's Investors Service / MIS) publishes credit ratings, research, and risk analysis on debt obligations issued by corporations, governments, and structured finance vehicles. Ratings, research, and the issuer/instrument reference data underpin the firm's research feeds and licensed data products consumed by institutional subscribers and downstream data redistributors.

- **Human URL:** [https://ratings.moodys.com/](https://ratings.moodys.com/)
- **Base URL:** `https://ratings.moodys.com/`

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

### Moody's ESG & Climate Solutions API

ESG scores, controversies, climate physical and transition risk metrics sourced from Four Twenty Seven and Moody's ESG Solutions. Used for portfolio screening, sustainable-finance reporting, climate scenario analysis, and regulatory disclosure (TCFD / CSRD / SFDR).

- **Human URL:** [https://www.moodys.com/web/en/us/capabilities/esg-and-climate.html](https://www.moodys.com/web/en/us/capabilities/esg-and-climate.html)
- **Base URL:** `https://api.moodys.com/esg`

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
