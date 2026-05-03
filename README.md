# Sound Transit

Sound Transit is a regional transit authority serving the Seattle-Puget Sound area of Washington State, operating light rail (1 Line, 2 Line, T Line), commuter rail, and ST Express bus services. The Sound Transit Open Transit Data (OTD) program provides GTFS static and real-time data feeds, OneBusAway API access, and GTFS-RT service alerts for transit application developers and researchers.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sound-transit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Transit, Transportation, GTFS, Real-Time, Public Transit, Government, Seattle

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### Sound Transit OneBusAway API

The Sound Transit OneBusAway API provides access to real-time and scheduled transit data for the Puget Sound region. Supports route information, stop locations, real-time arrivals and departures, vehicle positions, and trip details.

**Human URL:** [https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd](https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd)
**Base URL:** `https://api.pugetsound.onebusaway.org/api/where`

#### Tags

Transit, GTFS, Real-Time, Routes, Stops, Vehicles

#### Properties

- [Documentation](https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd)
- [Reference](http://developer.onebusaway.org/)
- [GTFS Downloads](https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/otd-downloads)
- [OpenAPI](openapi/sound-transit-onebusaway-openapi.yml)

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| Sound Transit OneBusAway API | [openapi/sound-transit-onebusaway-openapi.yml](openapi/sound-transit-onebusaway-openapi.yml) |

### Spectral Rules

| Ruleset | File |
|---------|------|
| Sound Transit Rules | [rules/sound-transit-rules.yml](rules/sound-transit-rules.yml) |

### Naftiko Capabilities

**Shared Definitions:**

| API | File |
|-----|------|
| Sound Transit OneBusAway | [capabilities/shared/sound-transit-onebusaway.yaml](capabilities/shared/sound-transit-onebusaway.yaml) |

**Workflow Capabilities:**

| Workflow | File | Description |
|----------|------|-------------|
| Transit Data | [capabilities/transit-data.yaml](capabilities/transit-data.yaml) | Real-time and scheduled transit data for trip planning |

### JSON Schemas

| Schema | File |
|--------|------|
| Stop | [json-schema/sound-transit-stop-schema.json](json-schema/sound-transit-stop-schema.json) |
| Arrival And Departure | [json-schema/sound-transit-arrival-schema.json](json-schema/sound-transit-arrival-schema.json) |

### JSON Structures

| Structure | File |
|-----------|------|
| Arrivals Response | [json-structure/sound-transit-arrivals-structure.json](json-structure/sound-transit-arrivals-structure.json) |

### JSON-LD Contexts

| Context | File |
|---------|------|
| Sound Transit | [json-ld/sound-transit-context.jsonld](json-ld/sound-transit-context.jsonld) |

### Examples

| Example | File |
|---------|------|
| Get Arrivals | [examples/sound-transit-get-arrivals-example.json](examples/sound-transit-get-arrivals-example.json) |

### Vocabulary

| Vocabulary | File |
|------------|------|
| Sound Transit | [vocabulary/sound-transit-vocabulary.yml](vocabulary/sound-transit-vocabulary.yml) |

## Common Properties

- [Portal](https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd)
- [Website](https://www.soundtransit.org/)
- [GTFS-RT Service Alerts (JSON)](https://s3.amazonaws.com/st-service-alerts-prod/alerts_pb.json)
- [GTFS-RT Service Alerts (Proto)](https://s3.amazonaws.com/st-service-alerts-prod/alerts.pb)
- [Transitland Feed](https://www.transit.land/feeds/f-c23-soundtransit)
- [Terms of Use](https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/transit-data-terms-use)
- [API Key Request](mailto:oba_api_key@soundtransit.org)
- [Support](mailto:open_transit_data@soundtransit.org)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
