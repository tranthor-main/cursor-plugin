# Tranthor

Official Cursor and Grok Bot plugin for [Tranthor](https://tranthor.com).

Connect one Tranthor workspace to work in it in plain language:
- **Read:** your segments, journeys, broadcasts and message templates, and the last 30 days of revenue, orders and messages.
- **Make changes:** save draft segments, journeys, broadcasts and message templates, pause and resume journeys, see what needs you, and ask the Supervisor.
- **Send:** send a draft broadcast or start a journey that never ran, only after you approve its preview and type its number of customers yourself.

## Install

1. Open **Cursor Settings → Plugins** (or Grok Bot connectors).
2. Search for **Tranthor** and click **Install**.
3. Sign in to Tranthor, choose your workspace, and approve the access you want to grant.

Or run `/add-plugin tranthor` in chat.

## MCP

```json
{
  "mcpServers": {
    "tranthor": {
      "type": "http",
      "url": "https://api.tranthor.com/mcp"
    }
  }
}
```

## License

MIT
