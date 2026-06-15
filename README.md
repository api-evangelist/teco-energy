# TECO Energy (teco-energy)

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
