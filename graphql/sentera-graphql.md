# Sentera FieldAgent GraphQL API

Sentera's FieldAgent API is a **GraphQL** API, not a resource-oriented REST API.
There is a single HTTP endpoint that fronts the entire GraphQL schema.

## Endpoint

```
POST https://api.sentera.com/graphql
```

- All queries and mutations are sent to this one endpoint, regardless of the
  resource being read or written.
- `GET` is also supported, with the `query` and optional `variables` passed as
  URL-encoded query-string parameters.
- Accepts `application/json` and `application/x-www-form-urlencoded`.

## Authentication

GraphQL requests require a Sentera `auth_token` supplied as a Bearer token:

```
Authorization: Bearer <auth_token>
```

Tokens are obtained per Sentera's Authentication and Authorization
documentation. The public reference docs are open, but a token requires a
Sentera/FieldAgent account, so live use is effectively customer/partner-gated.

## Operation surface (from the published GraphQL reference)

Queries (30+) include, among others:

- `field`, `fields`, `survey`, `surveys`, `task`, `tasks`
- `analytic`, `catalog`, `order`, `orders`, `deals`
- `organization`, `organizations`, `selected_organization`, `user`
- `sync_*` operations (e.g. sync images, files, orders, surveys)

Mutations (80+) include, among others:

- `create_field`, `update_field`, `delete_field`, `share_fields`
- `create_orders`, `place_order`, `update_order`, `cancel_orders`
- `upsert_*` bulk operations
- File / image management and webhook subscription mutations
- Contact and crop-season management

## Example request

```bash
curl https://api.sentera.com/graphql \
  -H "Authorization: Bearer $SENTERA_AUTH_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"query":"query { fields(owner_id: \"ORG_SENTERA_ID\") { results { id name } } }"}'
```

## Notes

- GraphQL returns HTTP `200` even when the body contains field-level `errors`.
- The companion `openapi/sentera-openapi.yml` models only this one real HTTP
  transport endpoint; the full typed object graph lives in the GraphQL schema.

## Reference

- Getting started: https://api.sentera.com/api/getting_started/introduction.html
- Query reference: https://api.sentera.com/api/docs/operation/query/index.html
- Examples: https://api.sentera.com/api/examples/user_mutations
