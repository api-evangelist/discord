# Discord (discord)

Discord is a voice, video and text communication service used by hundreds of millions of people to hang out and talk with their communities and friends.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Chat
- Communication
- Gaming
- Messaging
- Social
- Video
- Voice

## Timestamps

- **Created:** 2024-04-14
- **Modified:** 2026-05-19

## APIs

### Discord REST API

The Discord REST API provides programmatic access to Discord resources including users, guilds, channels, messages, emojis, webhooks, and more. It is the primary interface for building bots, integrations, and applications that interact with Discord data through standard HTTP request-response operations.

- **Human URL:** [https://discord.com/developers/docs/reference](https://discord.com/developers/docs/reference)
- **Base URL:** `https://discord.com/api/v10`

#### Tags

- Channels
- Guilds
- Messaging
- REST
- Users
- Webhooks

#### Properties

- [Documentation](https://discord.com/developers/docs/reference)
- [OpenAPI](https://github.com/discord/discord-api-spec) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/discord-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/discord-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord Gateway API

The Discord Gateway API provides persistent, stateful WebSocket connections between your client and Discord servers. These connections are used for sending and receiving real-time events your client can use to track and update local state, including message creation, guild updates, presence changes, and voice state updates.

- **Human URL:** [https://discord.com/developers/docs/events/gateway](https://discord.com/developers/docs/events/gateway)

#### Tags

- Events
- Gateway
- Real-Time
- WebSocket

#### Properties

- [Documentation](https://discord.com/developers/docs/events/gateway)
- [Documentation](https://discord.com/developers/docs/events/gateway-events)
- [AsyncAPI](asyncapi/discord-gateway-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/discord-interactions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-interactions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-linked-roles-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-linked-roles-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-oauth2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-oauth2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-webhook-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-webhook-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord Interactions API

The Discord Interactions API enables applications to create and respond to application commands (slash commands), message components, and modals. It supports both Gateway-based and webhook-based interaction handling, allowing bots to build rich, interactive user experiences within Discord.

- **Human URL:** [https://discord.com/developers/docs/interactions/overview](https://discord.com/developers/docs/interactions/overview)

#### Tags

- Components
- Interactions
- Modals
- Slash Commands

#### Properties

- [Documentation](https://discord.com/developers/docs/interactions/overview)
- [Documentation](https://discord.com/developers/docs/interactions/application-commands)
- [Documentation](https://discord.com/developers/docs/interactions/receiving-and-responding)
- [OpenAPI](openapi/discord-interactions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/discord-interactions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-interactions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord OAuth2 API

The Discord OAuth2 API enables application developers to build applications that utilize authentication and data from the Discord API. Discord supports the authorization code grant, the implicit grant, client credentials, and specialized flows for bots and webhooks, allowing third-party applications to access Discord user data with proper consent.

- **Human URL:** [https://discord.com/developers/docs/topics/oauth2](https://discord.com/developers/docs/topics/oauth2)

#### Tags

- Authentication
- Authorization
- OAuth2

#### Properties

- [Documentation](https://discord.com/developers/docs/topics/oauth2)
- [OpenAPI](openapi/discord-oauth2-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/discord-oauth2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-oauth2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord Webhook Events API

The Discord Webhook Events API provides HTTP-based outgoing webhook events that allow applications to receive notifications for specific events without maintaining a persistent connection. Supported events include APPLICATION_AUTHORIZED, ENTITLEMENT_CREATE, and QUEST_USER_ENROLLMENT.

- **Human URL:** [https://discord.com/developers/docs/events/webhook-events](https://discord.com/developers/docs/events/webhook-events)

#### Tags

- Events
- Notifications
- Webhooks

#### Properties

- [Documentation](https://discord.com/developers/docs/events/webhook-events)
- [OpenAPI](openapi/discord-webhook-events-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/discord-webhook-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-webhook-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord Embedded App SDK

The Discord Embedded App SDK lets you build rich, multiplayer experiences as Activities inside Discord. It handles RPC calls between your application and Discord, enabling interactive activities like games that can run in voice channels, text channels, or DMs.

- **Human URL:** [https://discord.com/developers/docs/developer-tools/embedded-app-sdk](https://discord.com/developers/docs/developer-tools/embedded-app-sdk)

#### Tags

- Activities
- Embedded
- Games
- SDK

#### Properties

- [Documentation](https://discord.com/developers/docs/developer-tools/embedded-app-sdk)
- [Git Hub Repo](https://github.com/discord/embedded-app-sdk)
- [Postman Collection](collections/discord-interactions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-interactions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-linked-roles-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-linked-roles-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-oauth2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-oauth2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-webhook-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-webhook-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord Voice API

The Discord Voice API provides the protocol for establishing and managing voice connections between clients and Discord voice servers. It handles UDP-based voice data transmission, encryption with XSalsa20-Poly1305, and supports features like speaking indicators and voice state updates.

- **Human URL:** [https://discord.com/developers/docs/topics/voice-connections](https://discord.com/developers/docs/topics/voice-connections)

#### Tags

- Real-Time
- UDP
- Voice
- WebSocket

#### Properties

- [Documentation](https://discord.com/developers/docs/topics/voice-connections)
- [AsyncAPI](asyncapi/discord-voice-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/discord-interactions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-interactions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-linked-roles-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-linked-roles-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-oauth2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-oauth2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-webhook-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-webhook-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord Linked Roles API

The Discord Linked Roles API enables applications to associate third-party metadata with Discord users through role connection metadata. Server admins can use this metadata to configure requirements for linked roles, such as verified accounts or achievement thresholds from external platforms.

- **Human URL:** [https://discord.com/developers/docs/tutorials/configuring-app-metadata-for-linked-roles](https://discord.com/developers/docs/tutorials/configuring-app-metadata-for-linked-roles)

#### Tags

- Metadata
- OAuth2
- Roles
- Verification

#### Properties

- [Documentation](https://discord.com/developers/docs/tutorials/configuring-app-metadata-for-linked-roles)
- [OpenAPI](openapi/discord-linked-roles-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/discord-linked-roles-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-linked-roles-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Discord Social SDK

The Discord Social SDK allows game developers to add rich social features into their games across desktop, mobile, and console platforms. It supports features like account linking, rich presence, lobbies, voice chat, direct messaging, friends lists, and game invites to create connected social experiences powered by Discord.

- **Human URL:** [https://discord.com/developers/docs/discord-social-sdk/overview](https://discord.com/developers/docs/discord-social-sdk/overview)

#### Tags

- Gaming
- Rich Presence
- SDK
- Social
- Voice

#### Properties

- [Documentation](https://discord.com/developers/docs/discord-social-sdk/overview)
- [Getting Started](https://discord.com/developers/docs/discord-social-sdk/getting-started)
- [Postman Collection](collections/discord-interactions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-interactions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-linked-roles-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-linked-roles-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-oauth2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-oauth2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/discord-webhook-events-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/discord-webhook-events-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/discord)
- [Portal](https://discord.com/developers/applications)
- [Terms of Service](https://discord.com/terms)
- [Privacy Policy](https://discord.com/privacy)
- [Developer  Terms](https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service)
- [Community  Guidelines](https://discord.com/guidelines)
- [Blog](https://discord.com/blog)
- [Twitter](https://twitter.com/discord)
- [Documentation](https://discord.com/developers/docs/reference)
- [Getting Started](https://discord.com/developers/docs/quick-start/getting-started)
- [Changelog](https://discord.com/developers/docs/change-log)
- [Status Page](https://discordstatus.com/)
- [Support](https://support-dev.discord.com/hc/en-us)
- [Git Hub Org](https://github.com/discord)
- [Git Hub Repo](https://github.com/discord/discord-api-docs)
- [OpenAPI](https://github.com/discord/discord-api-spec) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rate Limits](https://discord.com/developers/docs/topics/rate-limits)
- [Permissions](https://discord.com/developers/docs/topics/permissions)
- [Authentication](https://discord.com/developers/docs/topics/oauth2)
- [Status Codes](https://discord.com/developers/docs/topics/opcodes-and-status-codes)
- [Community Resources](https://discord.com/developers/docs/developer-tools/community-resources)
- [Documentation](https://discord.com/developers/docs/topics/threads)
- [Documentation](https://discord.com/developers/docs/topics/teams)
- [Documentation](https://discord.com/developers/docs/topics/voice-connections)
- [Monetization](https://discord.com/developers/docs/monetization/overview)
- [Discovery](https://discord.com/developers/docs/discovery/overview)
- [Rich Presence](https://discord.com/developers/docs/rich-presence/overview)
- [Branding](https://discord.com/branding)
- [Community](https://discord.com/invite/discord-developers)
- [Developer Policy](https://discord.com/developers/docs/policies/developer-policy)
- [Developer Terms Of Service](https://discord.com/developers/docs/policies/developer-terms-of-service)
- [Postman Workspace](https://www.postman.com/discord-api)
- [Game  S D K](https://discord.com/developers/docs/game-sdk/sdk-starter-guide)
- [Tutorials](https://discord.com/developers/docs/tutorials/hosting-on-cloudflare-workers)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/discord)
- [YouTube](https://www.youtube.com/@Discord)
- [Safety](https://discord.com/safety)
- [Developer  Policy](https://discord.com/developers/docs/policies-and-agreements/developer-policy)
- [JSON Schema](json-schema/discord-guild-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/discord-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/discord-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/discord-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/discord-role-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/discord-emoji-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/discord-webhook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/discord-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
**Email:** support@discord.com
