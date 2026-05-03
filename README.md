# TECO Energy (teco-energy)

TECO Energy is an energy holding company and subsidiary of Emera Inc., operating Tampa Electric (electric utility serving west central Florida) and Peoples Gas (natural gas utility serving Florida). Tampa Electric serves approximately 800,000 customers across the Tampa Bay area. TECO Energy provides a developer portal powered by Azure API Management at developer.tecoenergy.com, exposing APIs for outage management, account services, energy usage, billing, and grid operations.

**URL:** [https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/teco-energy/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Fortune:** Fortune 1000

## Tags:

 - Energy, Utilities, Electric, Natural Gas, Smart Grid, Tampa Bay

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### Tampa Electric API Management

Tampa Electric provides a developer portal powered by Azure API Management at developer.tecoenergy.com.

**Human URL:** [https://developer.tecoenergy.com/](https://developer.tecoenergy.com/)

#### Properties

- [Documentation](https://developer.tecoenergy.com/)
- [DeveloperPortal](https://developer.tecoenergy.com/)

### Tampa Electric Outage API

Power outage reporting, tracking, and map data for the Tampa Electric service territory.

**Human URL:** [https://account.tecoenergy.com/Outage/Outagemap](https://account.tecoenergy.com/Outage/Outagemap)

#### Tags:

 - Electric Utility, Grid Operations, Outage, Reliability

#### Properties

- [Documentation](https://account.tecoenergy.com/Outage/Outagemap)
- [OpenAPI](openapi/teco-energy-outage-openapi.yml)
- [JSONSchema](json-schema/teco-energy-outage-schema.json)

### Tampa Electric Account API

Customer account management including billing, energy usage, payments, and service requests.

**Human URL:** [https://account.tecoenergy.com/](https://account.tecoenergy.com/)

#### Tags:

 - Account Management, Billing, Customer Service, Energy Usage

#### Properties

- [Documentation](https://account.tecoenergy.com/)
- [OpenAPI](openapi/teco-energy-account-openapi.yml)
- [JSONSchema](json-schema/teco-energy-account-schema.json)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [teco-energy-outage-openapi.yml](openapi/teco-energy-outage-openapi.yml) | Outage management API - list, report, and track power outages |
| [teco-energy-account-openapi.yml](openapi/teco-energy-account-openapi.yml) | Account API - billing, usage, payments, service requests |

### JSON Schemas

| File | Description |
|---|---|
| [teco-energy-outage-schema.json](json-schema/teco-energy-outage-schema.json) | Schema for Tampa Electric outage event objects |
| [teco-energy-account-schema.json](json-schema/teco-energy-account-schema.json) | Schema for Tampa Electric customer account objects |

### JSON Structure

| File | Description |
|---|---|
| [teco-energy-outage-structure.json](json-structure/teco-energy-outage-structure.json) | Field-level documentation for outage objects |

### JSON-LD Context

| File | Description |
|---|---|
| [teco-energy-context.jsonld](json-ld/teco-energy-context.jsonld) | Linked data context mapping TECO Energy terms to schema.org |

### Examples

| File | Description |
|---|---|
| [teco-energy-list-outages-example.json](examples/teco-energy-list-outages-example.json) | Example request/response for listing outages |
| [teco-energy-get-usage-example.json](examples/teco-energy-get-usage-example.json) | Example request/response for energy usage history |

### Spectral Rules

| File | Description |
|---|---|
| [teco-energy-rules.yml](rules/teco-energy-rules.yml) | Spectral ruleset for Tampa Electric API conventions |

### Naftiko Capabilities

| File | Description |
|---|---|
| [capabilities/utility-operations.yaml](capabilities/utility-operations.yaml) | Utility operations workflow - outage + account management (9 MCP tools) |
| [capabilities/shared/outage-api.yaml](capabilities/shared/outage-api.yaml) | Shared Tampa Electric Outage API consumed definition |
| [capabilities/shared/account-api.yaml](capabilities/shared/account-api.yaml) | Shared Tampa Electric Account API consumed definition |

### Vocabulary

| File | Description |
|---|---|
| [teco-energy-vocabulary.yml](vocabulary/teco-energy-vocabulary.yml) | Domain vocabulary for Tampa Electric utility operations |

## Common Properties

- [Website](https://www.tecoenergy.com)
- [DeveloperPortal](https://developer.tecoenergy.com/)
- [Tampa Electric Website](https://www.tampaelectric.com/)
- [Account Portal](https://account.tecoenergy.com/)
- [Outage Map](https://account.tecoenergy.com/Outage/Outagemap)
- [LinkedIn](https://www.linkedin.com/company/teco-energy)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
