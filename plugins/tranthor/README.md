# Tranthor

Official Cursor and Grok Bot plugin for [Tranthor](https://tranthor.com).

Connect one Tranthor workspace to work in it in plain language:
- **Read:** your segments, journeys, broadcasts and message templates, the last 30 days of revenue, orders and messages, and what is waiting for you in Needs you.
- **Make changes:** save draft segments, journeys, broadcasts and message templates, pause and resume journeys, and ask the Supervisor.
- **Send:** send a draft broadcast or start a journey that never ran, only after you approve its preview and type its number of customers yourself.

## Install

1. Run `/add-plugin tranthor` in chat, or open **Cursor Settings → Plugins** (or Grok Bot connectors) and install **Tranthor** once it is listed.
2. Sign in to Tranthor when asked, choose your workspace, and approve the access you want to grant.
3. Ask in plain language, for example "How did my last broadcast perform?".

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

## Support, privacy and terms

- Help: [support@tranthor.com](mailto:support@tranthor.com)
- [Privacy policy](https://tranthor.com/privacy)
- [Terms of service](https://tranthor.com/terms)
- [MCP server reference](https://docs.tranthor.com/guide/mcp-server)

The plugin itself is free and open source. Using it needs a Tranthor account, and what it can do in a workspace depends on the person's role and on the access they allow when they connect. They can revoke it at any time in Tranthor under Settings, AI Agents.

## License

MIT
