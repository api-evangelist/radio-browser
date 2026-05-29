# Radio Browser (radio-browser)

Radio Browser is a free, community-driven directory of internet radio stations. The project publishes a public REST API exposing the full catalog of stations along with category aggregates (countries, states, languages, tags, codecs), click counting, voting, and station submission. Mirrors are discovered through a round-robin DNS pool (all.api.radio-browser.info) and the canonical server software (radiobrowser-api-rust) is released under AGPL-3.0, so anyone can self-host an additional mirror.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/radio-browser/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Music, Radio, Streaming, Open Source, Open Data, Community, Public APIs, AGPL

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### Radio Browser API

Public REST API exposing internet radio stations, category aggregates (countries, states, languages, tags, codecs), click counting, voting, station submission, mirror discovery, and service statistics. Response formats include JSON, XML, CSV, M3U, PLS, XSPF, and TTL.

**Human URL:** [https://api.radio-browser.info/](https://api.radio-browser.info/)

#### Tags:

 - Music, Radio, Streaming

#### Properties

- [Documentation](https://api.radio-browser.info/)
- [APIReference](https://docs.radio-browser.info/)
- [OpenAPI](openapi/radio-browser-openapi.yml)
- [JSONSchema (Station)](json-schema/radio-browser-station-schema.json)
- [JSONSchema (Category)](json-schema/radio-browser-category-schema.json)
- [JSONSchema (Stats)](json-schema/radio-browser-stats-schema.json)
- [JSONStructure (Station)](json-structure/radio-browser-station-structure.json)
- [JSONStructure (Category)](json-structure/radio-browser-category-structure.json)
- [JSON-LD](json-ld/radio-browser-context.jsonld)
- [Example: List Stations](examples/radio-browser-list-stations-example.json)
- [Example: Search Stations](examples/radio-browser-search-stations-example.json)
- [Example: List Countries](examples/radio-browser-list-countries-example.json)
- [Example: List Tags](examples/radio-browser-list-tags-example.json)
- [Example: Click Station](examples/radio-browser-click-station-example.json)
- [Example: Vote Station](examples/radio-browser-vote-station-example.json)
- [Example: Stats](examples/radio-browser-get-stats-example.json)
- [Authentication](https://docs.radio-browser.info/) — No auth required; descriptive User-Agent header is mandatory.
- [RateLimits](rate-limits/radio-browser-rate-limits.yml)

## Common Properties

- [Website](https://www.radio-browser.info/)
- [Documentation](https://api.radio-browser.info/)
- [APIReference](https://docs.radio-browser.info/)
- [GitHubOrganization](https://github.com/segler-alex)
- [GitHubRepository: radiobrowser-api-rust (archived mirror)](https://github.com/segler-alex/radiobrowser-api-rust)
- [SourceCode: GitLab (canonical AGPL-3.0 server)](https://gitlab.com/radiobrowser/radiobrowser-api-rust)
- [HelmCharts](https://gitlab.com/radiobrowser/helm-charts)
- [License: AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html)
- [SpectralRules](rules/radio-browser-rules.yml)
- [Vocabulary](vocabulary/radio-browser-vocabulary.yml)
- [NaftikoCapability: Stations](capabilities/radio-browser-stations.yaml)
- [NaftikoCapability: Categories](capabilities/radio-browser-categories.yaml)
- [NaftikoCapability: Interactions](capabilities/radio-browser-interactions.yaml)
- [Plans](plans/radio-browser-plans-pricing.yml)
- [RateLimits](rate-limits/radio-browser-rate-limits.yml)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- SDK: [ivandotv/radio-browser-api (JS/TS)](https://github.com/ivandotv/radio-browser-api)
- SDK: [andreztz/pyradios (Python)](https://github.com/andreztz/pyradios)
- SDK: [sfuhrm/radiobrowser4j (Java)](https://github.com/sfuhrm/radiobrowser4j)
- SDK: [nepodev/radio-browser (Node.js)](https://github.com/nepodev/radio-browser)
- SDK: [tomassasovsky/radio-browser-api.dart (Dart)](https://github.com/tomassasovsky/radio-browser-api.dart)
- SDK: [adinan-cenci/radio-browser (PHP)](https://github.com/adinan-cenci/radio-browser)
- SDK: [RadioBrowser (Elixir)](https://hexdocs.pm/radio_browser/)

## Features

| Name | Description |
|------|-------------|
| Round-Robin Mirror Pool | Servers discovered via DNS resolution of all.api.radio-browser.info; clients pick a healthy mirror and fall back as needed. |
| Multiple Response Formats | JSON, XML, CSV, M3U, PLS, XSPF, and TTL output for nearly every read endpoint. |
| Faceted Browse | List stations by country, country code, state, language, tag, or codec with station counts per facet. |
| Continuous Stream Health Checks | Stations are automatically pinged to verify their stream is reachable; results power lastcheckok and broken-station endpoints. |
| Community Curation | Anyone can submit a station via POST /json/add; clicks and votes feed station popularity rankings. |
| Open Source Server (AGPL-3.0) | The radiobrowser-api-rust server is open source; operators can self-host an additional mirror. |
| Geo Coordinates | Stations carry optional geo_lat/geo_long for map-based discovery. |
| Prometheus Metrics | Each mirror exposes /metrics in Prometheus exposition format for operational observability. |

## Use Cases

| Name | Description |
|------|-------------|
| Internet Radio Player Apps | Power desktop, mobile, and web players that let users browse the directory and play streams. |
| Voice Assistant Skills | Back Alexa/Google/Home Assistant skills that play "play jazz radio from France" requests by searching the directory. |
| Smart Speaker Integrations | Embedded firmware (e.g. AirMusic, Hama, internet radio hardware) ships Radio Browser as a station source. |
| Music Discovery Research | Researchers analyze the catalog to study global radio programming, language distribution, and genre tagging. |
| Streaming Health Dashboards | Use the /json/checks data to build dashboards showing global radio stream uptime. |
| Editorial Curation | Editors use vote/click data to surface trending stations by country, language, or genre. |

## Integrations

| Name | Description |
|------|-------------|
| Home Assistant | Multiple custom components and the built-in Radio Browser integration use the API for station selection. |
| VLC / Media Players | Media player extensions consume the API to populate radio station catalogs. |
| Self-Hosted Mirrors | Operators run radiobrowser-api-rust to add to the all.api.radio-browser.info pool. |
| Public APIs Directory | Listed in public-apis/public-apis under the Music category. |

## Solutions

| Name | Description |
|------|-------------|
| Hosted Community API | The free, hosted, AGPL-licensed Radio Browser mirror network — the default for most apps. |
| Self-Hosted Mirror | Run radiobrowser-api-rust on your own infrastructure for guaranteed throughput, isolated data, or private catalogs. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Radio Browser OpenAPI](openapi/radio-browser-openapi.yml)

### JSON Schema

- [Station](json-schema/radio-browser-station-schema.json)
- [Category](json-schema/radio-browser-category-schema.json)
- [Service Stats](json-schema/radio-browser-stats-schema.json)

### JSON Structure

- [Station](json-structure/radio-browser-station-structure.json)
- [Category](json-structure/radio-browser-category-structure.json)

### JSON-LD

- [Radio Browser Context](json-ld/radio-browser-context.jsonld)

### Examples

- [List Stations](examples/radio-browser-list-stations-example.json)
- [Search Stations](examples/radio-browser-search-stations-example.json)
- [List Countries](examples/radio-browser-list-countries-example.json)
- [List Tags](examples/radio-browser-list-tags-example.json)
- [Click Station](examples/radio-browser-click-station-example.json)
- [Vote Station](examples/radio-browser-vote-station-example.json)
- [Service Stats](examples/radio-browser-get-stats-example.json)

## Capabilities

Naftiko capabilities covering the Radio Browser surface area.

| Capability | Purpose | MCP Tools |
|------------|---------|-----------|
| [Stations](capabilities/radio-browser-stations.yaml) | Search, browse, and rank stations | 5 |
| [Categories](capabilities/radio-browser-categories.yaml) | List countries, languages, tags, codecs, states | 6 |
| [Interactions](capabilities/radio-browser-interactions.yaml) | Click counting, voting, station submission | 3 |

## Vocabulary

- [Radio Browser Vocabulary](vocabulary/radio-browser-vocabulary.yml) — Controlled vocabulary for stations, facets, interaction events, and service metadata.

## Rules

- [Radio Browser Spectral Rules](rules/radio-browser-rules.yml) — 7 rules enforcing operationId casing, summary Title Case, station tagging, UUID format, User-Agent documentation, AGPL licensing, and mirror pool declaration.

## Plans

- [Radio Browser Plans](plans/radio-browser-plans-pricing.yml) — Single free community plan (AGPL-3.0) with per-interaction throttles.

## Rate Limits

- [Radio Browser Rate Limits](rate-limits/radio-browser-rate-limits.yml) — Per-interaction throttles (1 vote per 10 min per IP per station; 1 click per 24h per IP per station) plus mirror-operator discretion.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
