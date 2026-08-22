# Sentera (sentera)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sentera is a precision-agriculture company building aerial imagery sensors, drones, and the FieldAgent platform for capturing, processing, and analyzing in-season field data. The FieldAgent API is a single-endpoint GraphQL interface (https://api.sentera.com/graphql) that gives customers and integration partners programmatic access to fields, surveys, flight tasks, imagery, mosaics, plot analytics, and orders. Sentera was acquired by John Deere in 2025.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sentera/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sentera/refs/heads/main/apis.yml)

## Tags

- Precision Agriculture
- Aerial Imagery
- Drones
- Sensors
- Analytics
- GraphQL

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Sentera FieldAgent GraphQL API

Single-endpoint GraphQL API (POST/GET to https://api.sentera.com/graphql) exposing the full FieldAgent object graph - fields, surveys, flight tasks, analytics, and orders - through queries and mutations authenticated with a Sentera Bearer auth_token.

- **Human URL:** [https://api.sentera.com/api/getting_started/introduction.html](https://api.sentera.com/api/getting_started/introduction.html)
- **Base URL:** `https://api.sentera.com/graphql`

#### Tags

- GraphQL
- FieldAgent
- Fields
- Surveys

#### Properties

- [Documentation](https://api.sentera.com/api/getting_started/introduction.html)
- [API Reference](https://api.sentera.com/api/docs/operation/query/index.html)
- [OpenAPI](openapi/sentera-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GraphQL](graphql/sentera-graphql.md)
- [Postman Collection](collections/sentera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sentera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sentera Imagery & Data API

Access to captured imagery, orthomosaics, and processed map layers (RGB, NDVI, NDRE) tied to surveys and flight tasks, plus imagery upload and sync operations, surfaced through the FieldAgent GraphQL endpoint.

- **Human URL:** [https://api.sentera.com/api/getting_started/introduction.html](https://api.sentera.com/api/getting_started/introduction.html)
- **Base URL:** `https://api.sentera.com/graphql`

#### Tags

- Imagery
- Mosaics
- Data
- GraphQL

#### Properties

- [Documentation](https://api.sentera.com/api/getting_started/introduction.html)
- [API Reference](https://api.sentera.com/api/docs/operation/query/index.html)
- [OpenAPI](openapi/sentera-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GraphQL](graphql/sentera-graphql.md)
- [Postman Collection](collections/sentera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sentera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sentera Plot Analytics API

Plant-level analytic results - stand/population counts, tassel counts, plot statistics, and field insights used by seed and research programs - retrievable via the analytic and catalog GraphQL queries.

- **Human URL:** [https://api.sentera.com/api/getting_started/introduction.html](https://api.sentera.com/api/getting_started/introduction.html)
- **Base URL:** `https://api.sentera.com/graphql`

#### Tags

- Analytics
- Plot Analytics
- Stand Count
- Research

#### Properties

- [Documentation](https://api.sentera.com/api/getting_started/introduction.html)
- [API Reference](https://api.sentera.com/api/docs/operation/query/index.html)
- [OpenAPI](openapi/sentera-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GraphQL](graphql/sentera-graphql.md)
- [Postman Collection](collections/sentera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sentera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sentera Orders & Organizations API

Processing-order placement and lifecycle management, organization and user administration, field sharing, and webhook subscriptions for event notifications, all exposed as FieldAgent GraphQL mutations and queries.

- **Human URL:** [https://api.sentera.com/api/getting_started/introduction.html](https://api.sentera.com/api/getting_started/introduction.html)
- **Base URL:** `https://api.sentera.com/graphql`

#### Tags

- Orders
- Organizations
- Webhooks
- GraphQL

#### Properties

- [Documentation](https://api.sentera.com/api/getting_started/introduction.html)
- [API Reference](https://api.sentera.com/api/docs/operation/query/index.html)
- [OpenAPI](openapi/sentera-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GraphQL](graphql/sentera-graphql.md)
- [Postman Collection](collections/sentera.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sentera.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sentera)
- [Website](https://sentera.com/)
- [Documentation](https://api.sentera.com/api/getting_started/introduction.html)
- [Plans](plans/sentera-plans-pricing.yml)
- [Rate Limits](rate-limits/sentera-rate-limits.yml)
- [Fin Ops](finops/sentera-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
