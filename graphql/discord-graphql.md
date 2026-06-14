# Discord GraphQL

## Description

Discord does not expose a native public GraphQL API. Its developer platform is built on a REST API (discord.com/api/v10), a WebSocket Gateway for real-time events, and an HTTP Webhook Events endpoint. No GraphQL endpoint is documented or publicly available as of June 2026.

## Schema Source

The schema in `discord-schema.graphql` is a **conceptual GraphQL schema** derived from the Discord REST API object model documented at https://discord.com/developers/docs/reference. It is suitable for tooling, catalog enrichment, code generation, and federation use cases where a typed graph representation of Discord resources is needed.

## Endpoint

None. Discord does not provide a GraphQL endpoint.

## Documentation

- REST API reference: https://discord.com/developers/docs/reference
- GitHub API spec (OpenAPI): https://github.com/discord/discord-api-spec
- Gateway events: https://discord.com/developers/docs/events/gateway-events
- Interactions: https://discord.com/developers/docs/interactions/overview
