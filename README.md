# Radio Browser (radio-browser)

Radio Browser is a free, community-driven directory of internet radio stations. The project publishes a public REST API exposing the full catalog of stations along with category aggregates (countries, states, languages, tags, codecs), click counting, voting, and station submission. Mirrors are discovered through a round-robin DNS pool (all.api.radio-browser.info) and the canonical server software (radiobrowser-api-rust) is released under AGPL-3.0, so anyone can self-host an additional mirror.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/radio-browser/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/radio-browser/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Music
- Radio
- Streaming
- Open Source
- Open Data
- Community
- Public APIs
- AGPL

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### Radio Browser API

Public REST API exposing internet radio stations, category aggregates (countries, states, languages, tags, codecs), click counting, voting, station submission, mirror discovery, and service statistics. Response formats include JSON, XML, CSV, M3U, PLS, XSPF, and TTL.

- **Human URL:** [https://api.radio-browser.info/](https://api.radio-browser.info/)
- **Base URL:** `https://de1.api.radio-browser.info`

#### Tags

- Music
- Radio
- Streaming

#### Properties

- [Documentation](https://api.radio-browser.info/)
- [API Reference](https://docs.radio-browser.info/)
- [OpenAPI](openapi/radio-browser-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radio-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radio-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/radio-browser-station-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/radio-browser-category-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/radio-browser-stats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/radio-browser-station-structure.json)
- [JSON Structure](json-structure/radio-browser-category-structure.json)
- [J S O N- L D](json-ld/radio-browser-context.jsonld)
- [Example](examples/radio-browser-list-stations-example.json)
- [Example](examples/radio-browser-search-stations-example.json)
- [Example](examples/radio-browser-list-countries-example.json)
- [Example](examples/radio-browser-list-tags-example.json)
- [Example](examples/radio-browser-click-station-example.json)
- [Example](examples/radio-browser-vote-station-example.json)
- [Example](examples/radio-browser-get-stats-example.json)
- [Authentication](https://docs.radio-browser.info/)
- [Rate Limits](rate-limits/radio-browser-rate-limits.yml)

## Common Properties

- [Website](https://www.radio-browser.info/)
- [Documentation](https://api.radio-browser.info/)
- [API Reference](https://docs.radio-browser.info/)
- [GitHub Organization](https://github.com/segler-alex)
- [GitHub Repository](https://github.com/segler-alex/radiobrowser-api-rust)
- [Source Code](https://gitlab.com/radiobrowser/radiobrowser-api-rust)
- [Helm Charts](https://gitlab.com/radiobrowser/helm-charts)
- [License](https://www.gnu.org/licenses/agpl-3.0.html)
- [Spectral Rules](rules/radio-browser-rules.yml)
- [Vocabulary](vocabulary/radio-browser-vocabulary.yml)
- [Plans](plans/radio-browser-plans-pricing.yml)
- [Rate Limits](rate-limits/radio-browser-rate-limits.yml)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [SDK](https://github.com/ivandotv/radio-browser-api)
- [SDK](https://github.com/andreztz/pyradios)
- [SDK](https://github.com/sfuhrm/radiobrowser4j)
- [SDK](https://github.com/nepodev/radio-browser)
- [SDK](https://github.com/tomassasovsky/radio-browser-api.dart)
- [SDK](https://github.com/adinan-cenci/radio-browser)
- [SDK](https://hexdocs.pm/radio_browser/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
