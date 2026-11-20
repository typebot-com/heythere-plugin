# Heythere

Heythere runs a business's WhatsApp number. This plugin gives your agent two things:

- **The Heythere connector**, Heythere's remote MCP server at `https://app.heythere.io/api/mcp`. You sign in with your Heythere account the first time your agent uses it, and it then acts as you, within the workspaces you can access: it reads and writes automations, contacts, conversations, message templates and broadcasts.
- **The `build-whatsapp-automation` skill**, which teaches your agent how to build an automation that your customers find natural and your team can review: checking what you believe Heythere does on its own against its documentation, listing who can write to the number and what each of them needs, briefing an agent step rather than scripting it, and telling you what it verified and what it assumed.

## Install

In Claude Code 2.1.275 or later:

```
/plugin install heythere --marketplace typebot-com/heythere-plugin
```

Then type `/mcp`, choose the Heythere server and sign in with your Heythere account.

## What it runs, sends and fetches

The plugin runs no code on your machine. Your agent calls the connector, which sends your requests to Heythere's API with the access you approved, and reads Heythere's public documentation at `https://heythere.io/docs`. An automation your agent drafts reaches no customer until a member of your workspace publishes it, but a broadcast it sends or a reply it writes in a conversation reaches the customer at once.

## Learn more

- [Docs](https://heythere.io/docs): what each concept of Heythere is for.
- [Connect your agent](https://heythere.io/docs/concepts/api-access): how the connection works and how to take it back.
- Support: support@heythere.io
