# Programmatic API Onboarding — Discord

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Discord: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`discord-api-auth.mjs`](discord-api-auth.mjs)
- Run `node discord-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/08/27/discord-dashboard-only-app-registration/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
