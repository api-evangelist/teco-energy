# TECO Energy (teco-energy)

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

TECO Energy is an energy holding company and subsidiary of Emera Inc., operating Tampa Electric (electric utility serving west central Florida) and Peoples Gas (natural gas utility serving Florida). TECO Energy provides a developer portal powered by Azure API Management at developer.tecoenergy.com, exposing APIs for outage management, account services, energy usage, billing, and grid operations. Tampa Electric serves approximately 800,000 customers across the Tampa Bay area and parts of central Florida.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Energy
- Utilities
- Electric
- Natural Gas
- Smart Grid
- Tampa Bay

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Tampa Electric API Management

Tampa Electric provides a developer portal powered by Azure API Management at developer.tecoenergy.com. The portal enables developers to discover APIs, review documentation, try APIs interactively, and sign up for API keys. APIs likely include outage management, account services, energy usage data, billing, and grid operations. Authentication is required to access the full API catalog.

- **Human URL:** [https://developer.tecoenergy.com/](https://developer.tecoenergy.com/)
- **Base URL:** `https://developer.tecoenergy.com`

#### Tags

- Electric Utility
- Energy
- API Management
- Azure
- Tampa Electric

#### Properties

- [Documentation](https://developer.tecoenergy.com/)
- [Developer Portal](https://developer.tecoenergy.com/)
- [Postman Collection](collections/teco-energy-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teco-energy-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/teco-energy-outage.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teco-energy-outage.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tampa Electric Outage API

Tampa Electric exposes outage reporting and outage map data through its customer portal and API infrastructure. The outage map at account.tecoenergy.com/Outage/Outagemap enables customers to report and track power outages, serving as the foundation for utility outage management APIs covering outage creation, status, restoration times, and affected customer counts.

- **Human URL:** [https://account.tecoenergy.com/Outage/Outagemap](https://account.tecoenergy.com/Outage/Outagemap)
- **Base URL:** `https://account.tecoenergy.com`

#### Tags

- Outage
- Electric Utility
- Grid Operations
- Reliability

#### Properties

- [Documentation](https://account.tecoenergy.com/Outage/Outagemap)
- [OpenAPI](openapi/teco-energy-outage-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teco-energy-outage.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teco-energy-outage.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/teco-energy-outage-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Tampa Electric Account API

Tampa Electric provides customer account management services including bill payment, usage history, paperless billing enrollment, service transfers, and energy audit tools. These customer-facing services are backed by account APIs enabling programmatic access to billing data, account status, payment history, and energy efficiency recommendations for residential and commercial customers.

- **Human URL:** [https://account.tecoenergy.com/](https://account.tecoenergy.com/)
- **Base URL:** `https://account.tecoenergy.com`

#### Tags

- Account Management
- Billing
- Energy Usage
- Customer Service

#### Properties

- [Documentation](https://account.tecoenergy.com/)
- [OpenAPI](openapi/teco-energy-account-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/teco-energy-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/teco-energy-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/teco-energy-account-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [Website](https://www.tecoenergy.com)
- [Developer Portal](https://developer.tecoenergy.com/)
- [Website](https://www.tampaelectric.com/)
- [Portal](https://account.tecoenergy.com/)
- [Status Page](https://account.tecoenergy.com/Outage/Outagemap)
- [LinkedIn](https://www.linkedin.com/company/teco-energy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
