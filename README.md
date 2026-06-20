# Sentera (sentera)

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
