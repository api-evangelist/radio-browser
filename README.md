# Radio Browser (radio-browser)

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
