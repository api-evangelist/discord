# Discord (discord)

Discord is a voice, video and text communication service used by hundreds of millions of people to hang out and talk with their communities and friends.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/discord/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Chat, Communication, Gaming, Messaging, Social, Video, Voice

## Timestamps

- **Created:** 2024-04-14
- **Modified:** 2026-03-16

## APIs

### Discord REST API
The Discord REST API provides programmatic access to Discord resources including users, guilds, channels, messages, emojis, webhooks, and more. It is the primary interface for building bots, integrations, and applications that interact with Discord data through standard HTTP request-response operations.

- **Human URL:** [https://discord.com/developers/docs/reference](https://discord.com/developers/docs/reference)
- **Base URL:** https://discord.com/api/v10
- [Documentation](https://discord.com/developers/docs/reference)
- [OpenAPI](openapi/discord-rest-api-openapi.yml)

### Discord Gateway API
The Discord Gateway API provides persistent, stateful WebSocket connections between your client and Discord servers, used for sending and receiving real-time events including message creation, guild updates, presence changes, and voice state updates.

- **Human URL:** [https://discord.com/developers/docs/events/gateway](https://discord.com/developers/docs/events/gateway)
- [AsyncAPI](asyncapi/discord-gateway-api-asyncapi.yml)

### Discord Interactions API
The Discord Interactions API enables applications to create and respond to application commands (slash commands), message components, and modals. It supports both Gateway-based and webhook-based interaction handling.

- **Human URL:** [https://discord.com/developers/docs/interactions/overview](https://discord.com/developers/docs/interactions/overview)
- [OpenAPI](openapi/discord-interactions-api-openapi.yml)

### Discord OAuth2 API
The Discord OAuth2 API enables application developers to build applications that utilize authentication and data from Discord. Supports the authorization code grant, implicit grant, client credentials, and specialized flows for bots and webhooks.

- **Human URL:** [https://discord.com/developers/docs/topics/oauth2](https://discord.com/developers/docs/topics/oauth2)
- [OpenAPI](openapi/discord-oauth2-api-openapi.yml)

### Discord Webhook Events API
HTTP-based outgoing webhook events that allow applications to receive notifications without a persistent connection. Supported events include APPLICATION_AUTHORIZED, ENTITLEMENT_CREATE, and QUEST_USER_ENROLLMENT.

- **Human URL:** [https://discord.com/developers/docs/events/webhook-events](https://discord.com/developers/docs/events/webhook-events)
- [OpenAPI](openapi/discord-webhook-events-api-openapi.yml)

### Discord Embedded App SDK
The Discord Embedded App SDK lets developers build rich, multiplayer Activities inside Discord. Handles RPC calls between application and Discord for interactive activities in voice channels, text channels, or DMs.

- **Human URL:** [https://discord.com/developers/docs/developer-tools/embedded-app-sdk](https://discord.com/developers/docs/developer-tools/embedded-app-sdk)
- [GitHub](https://github.com/discord/embedded-app-sdk)

### Discord Voice API
The Discord Voice API provides the protocol for establishing and managing voice connections between clients and Discord voice servers. Handles UDP-based voice data, encryption with XSalsa20-Poly1305, speaking indicators, and voice state updates.

- **Human URL:** [https://discord.com/developers/docs/topics/voice-connections](https://discord.com/developers/docs/topics/voice-connections)
- [AsyncAPI](asyncapi/discord-voice-api-asyncapi.yml)

### Discord Linked Roles API
The Discord Linked Roles API enables applications to associate third-party metadata with Discord users through role connection metadata. Server admins can use this metadata to configure requirements for linked roles.

- **Human URL:** [https://discord.com/developers/docs/tutorials/configuring-app-metadata-for-linked-roles](https://discord.com/developers/docs/tutorials/configuring-app-metadata-for-linked-roles)
- [OpenAPI](openapi/discord-linked-roles-api-openapi.yml)

### Discord Social SDK
The Discord Social SDK adds rich social features into games across desktop, mobile, and console: account linking, rich presence, lobbies, voice chat, direct messaging, friends lists, and game invites.

- **Human URL:** [https://discord.com/developers/docs/discord-social-sdk/overview](https://discord.com/developers/docs/discord-social-sdk/overview)

## Common Properties

- [Portal](https://discord.com/developers/applications)
- [Documentation](https://discord.com/developers/docs/reference)
- [Getting Started](https://discord.com/developers/docs/quick-start/getting-started)
- [Change Log](https://discord.com/developers/docs/change-log)
- [Status](https://discordstatus.com/)
- [Support](https://support-dev.discord.com/hc/en-us)
- [GitHub Org](https://github.com/discord)
- [Rate Limits](https://discord.com/developers/docs/topics/rate-limits)
- [Permissions](https://discord.com/developers/docs/topics/permissions)
- [Authentication (OAuth2)](https://discord.com/developers/docs/topics/oauth2)
- [Terms of Service](https://discord.com/terms)
- [Privacy Policy](https://discord.com/privacy)
- [Developer Terms](https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service)
- [Community Guidelines](https://discord.com/guidelines)
- [Postman Workspace](https://www.postman.com/discord-api)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/discord)
- [YouTube](https://www.youtube.com/@Discord)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

**Name:** Discord Inc.

**Email:** support@discord.com
