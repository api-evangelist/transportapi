# TransportAPI

TransportAPI is a managed data service provider for UK public transport, offering real-time and scheduled bus, rail, and multimodal transport data via REST and WebSocket APIs to power apps, websites, analytics, and data-mining workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/transportapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Public Transit, Transport, UK, Real-Time, Journey Planning, Bus, Rail

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-03

## APIs

### TransportAPI
UK public transport data API with real-time bus and rail departures, multimodal journey planning, performance analytics, and transport places lookup across Great Britain.

**Human URL:** [https://developer.transportapi.com/](https://developer.transportapi.com/)

**Base URL:** `https://transportapi.com/v3/uk`

#### Tags

Public Transit, Transport, UK, Real-Time, Journey Planning, Bus, Rail

#### Properties

- [Documentation](https://developer.transportapi.com/docs/)
- [OpenAPI](openapi/transportapi-openapi.yml)
- [JSON Structure](json-structure/transportapi-departure-structure.json)
- [JSON-LD Context](json-ld/transportapi-context.jsonld)
- [Spectral Rules](rules/transportapi-rules.yml)
- [Naftiko Capabilities](capabilities/uk-transport-information.yaml)
- [Vocabulary](vocabulary/transportapi-vocabulary.yml)
- [Sign Up](https://developer.transportapi.com/)

## Managed Services

| Service | Description |
|---|---|
| TAPI Journey Planner | Multimodal journey planning across bus, train, metro, tram, cycle, car, ferry, and taxi |
| TAPI Bus Information | Real-time and scheduled bus departures via REST or WebSocket |
| TAPI Bus Performance | Fleet punctuality and Traffic Commissioner performance analytics |
| TAPI Rail Information | Real-time and scheduled rail departures nationwide |
| TAPI Rail Performance | Historical rail lateness and cancellation data for delay-repay |
| TAPI Places | Bus stops, train stations, and transport access points across Great Britain |

## OpenAPI Specifications

| API | File |
|---|---|
| TransportAPI | [openapi/transportapi-openapi.yml](openapi/transportapi-openapi.yml) |

## Capabilities

### Workflow Capabilities

| Workflow | Description |
|---|---|
| [UK Transport Information](capabilities/uk-transport-information.yaml) | Unified bus/rail departures, journey planning, and places for UK transport apps |

### Shared Definitions

| API | File |
|---|---|
| [TransportAPI](capabilities/shared/transportapi.yaml) | Core TransportAPI consumed definitions |

## Examples

| Example | Description |
|---|---|
| [Get Bus Stop Live Departures](examples/transportapi-get-bus-stop-live-departures-example.json) | Get live bus departures for a UK bus stop |
| [Plan Journey](examples/transportapi-plan-journey-example.json) | Plan a multimodal UK journey |

## Rules

| Ruleset | Description |
|---|---|
| [transportapi-rules.yml](rules/transportapi-rules.yml) | Spectral ruleset for TransportAPI conventions |

## JSON Structures

| Structure | Description |
|---|---|
| [transportapi-departure-structure.json](json-structure/transportapi-departure-structure.json) | UK transport departure fields |

## JSON-LD

| Context | Description |
|---|---|
| [transportapi-context.jsonld](json-ld/transportapi-context.jsonld) | Linked data context for UK transport |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [transportapi-vocabulary.yml](vocabulary/transportapi-vocabulary.yml) | UK public transport domain vocabulary |

## Common Properties

- [Website](https://www.transportapi.com/)
- [Documentation](https://developer.transportapi.com/)
- [Sign Up](https://developer.transportapi.com/)
- [GitHub](https://github.com/transportapi)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
