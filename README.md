<img src="assets/logo.svg" width="56" alt="Pagehive">

# Pagehive for Cursor

Live pages, run by your agent.

This plugin connects Cursor to [Pagehive](https://pagehive.io). Your agent builds pages, keeps data in tables and publishes sites through 90+ MCP tools. No CLI, no SDK, no local setup.

## What's inside
- **MCP server** – the remote Pagehive server at `https://pagehive.io/mcp`. You sign in once with OAuth. No keys go in this repo or your config.
- **Skill** – a short guide that shows your agent how to build a site, store data and publish safely.

## Install
Install Pagehive from the Cursor marketplace or [cursor.directory](https://cursor.directory). Or add the server to `~/.cursor/mcp.json` by hand:

```json
{
  "mcpServers": {
    "pagehive": { "url": "https://pagehive.io/mcp" }
  }
}
```

Cursor opens the Pagehive sign-in the first time your agent uses a tool. A Free account is enough to start.

## You stay in control
Every edit goes to a draft. Nothing goes live until you publish, and your agent asks you first.

## Links
- Website: [pagehive.io](https://pagehive.io)
- Guide for agents: [pagehive.io/llms.txt](https://pagehive.io/llms.txt)

## License
MIT
