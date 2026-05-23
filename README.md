# Moody's Corporation

Moody's Corporation (NYSE: MCO) is a global integrated risk-assessment firm operating through two segments — **Moody's Ratings** (Moody's Investors Service / MIS) for credit ratings and research, and **Moody's Analytics** for data, software, research, and APIs spanning economic data, credit risk, KYC, ESG, climate, and catastrophe modeling.

This repository profiles Moody's Corporation as a public API provider for the [API Evangelist](https://apievangelist.com) network. The deeper Moody's Analytics API artifacts (Data Buffet, Scenario Studio, AutoCycle, ECCL, KYC) are also tracked separately at [api-evangelist/moodys](https://github.com/api-evangelist/moodys); this repo is the corporate-parent profile.

## APIs

| Aid | API | Segment | Base URL |
| --- | --- | --- | --- |
| `moodys-ratings` | Moody's Ratings | Moody's Ratings (MIS) | https://ratings.moodys.com/ |
| `developer-platform` | Moody's Analytics Developer Platform | Moody's Analytics | https://developer.moodys.com/ |
| `data-buffet-api` | Data Buffet API | Moody's Analytics | https://api.economy.com/data/v1 |
| `scenario-studio-api` | Scenario Studio API | Moody's Analytics | https://api.economy.com/scenario-studio/v2 |
| `autocycle-api` | AutoCycle API | Moody's Analytics | https://api.economy.com/autocycle/v1 |
| `eccl-api` | Expected Consumer Credit Loss API | Moody's Analytics | https://api.economy.com/eccl/v1 |
| `impairmentstudio-api` | ImpairmentStudio API | Moody's Analytics | https://api.moodys.com/impairmentstudio |
| `orbis-api` | Orbis (Bureau van Dijk) API | Moody's Analytics | https://orbis.bvdinfo.com/ |
| `kyc-api` | KYC API (Kompany / Maxsight) | Moody's Analytics | https://api.kompany.com/ |
| `passfort-api` | Passfort Lifecycle API | Moody's Analytics | https://api.passfort.com/ |
| `rms-irp-api` | RMS Intelligent Risk Platform API | Moody's Analytics | https://api.rms.com/ |
| `esg-climate-api` | ESG & Climate Solutions API | Moody's Analytics | https://api.moodys.com/esg |

## Artifacts

- `apis.yml` — APIs.json catalog of every Moody's Corporation API surface and its properties.
- `openapi/` — `moodys-analytics-developer-openapi.yml` (umbrella platform) + `moodys-data-buffet-api-openapi.yml` (Data Buffet reference).
- `capabilities/` — Naftiko capabilities for authentication, Data Buffet, ImpairmentStudio, Orbis lookup, KYC verification, and a cross-API credit onboarding workflow composition.
- `json-schema/` — JSON Schemas for credit ratings, entities, time series, and RMS catastrophe events.
- `json-structure/` — Structural definitions for the same entities.
- `json-ld/` — JSON-LD context mapping Moody's terms onto schema.org and FIBO.
- `examples/` — Representative request / response and entity examples.
- `rules/` — Spectral ruleset enforcing Moody's API conventions (Title Case, OAuth2, https).
- `vocabulary/` — Domain vocabulary covering segments, product lines, and key terms (CECL, LEI, UBO, TCFD, etc.).
- `plans/` — Commercial plans summary (enterprise-quote model).
- `rate-limits/` — Documented rate limits (Data Buffet 1 req/sec, 1 GB/month).
- `finops/` — FinOps / FOCUS-aligned cost-attribution and optimization guidance.

## Authentication

Moody's Analytics product APIs predominantly use **OAuth2 client credentials** (`POST /oauth2/token`, 1-hour bearer tokens) with **HMAC request signing** as a fallback on legacy product APIs (Data Buffet, Scenario Studio). API credentials are provisioned through the customer's Moody's Analytics account.

## GitHub Organization

[github.com/moodysanalytics](https://github.com/moodysanalytics) hosts open-source code samples and tooling, including:

- `databuffet-api-codesamples` — C# / Java / Python / R code samples for the Data Buffet API.
- `scenario-studio-api-codesamples` — Python / R client libraries and Postman collection for Scenario Studio.
- `apic` — Python CLI for Moody's Analytics APIs (currently supports ImpairmentStudio).
- `MoodysAnalytics-PassFort-CustomCheckFramework` — TypeScript starter for custom Passfort data-provider integrations.

## Notable Absences

- No public self-service developer tier or free sandbox key listed publicly.
- No published per-call USD pricing on the developer portal.
- No single OpenAPI catalog page enumerating every Moody's Analytics product API surface.
- No public status page or platform RSS feed surfaced from corporate URLs.

## Related

- API Evangelist sibling profile: [api-evangelist/moodys](https://github.com/api-evangelist/moodys) — deeper artifact set for the Moody's Analytics APIs.
- Investor relations: https://ir.moodys.com/

## License

The artifacts in this repository are released under the [API Commons](http://apicommons.org) terms. Underlying API access is governed by Moody's Analytics terms of use: https://www.moodys.com/web/en/us/about/legal/terms-of-use.html
