# Security

## Reporting a vulnerability

Please do not open a public issue for a security problem.

- Use GitHub's **Report a vulnerability** button on this repository's Security tab (private vulnerability reporting), or
- email [support@tranthor.com](mailto:support@tranthor.com) with "Security" in the subject.

Include what you found, where, and how to reproduce it. We acknowledge reports as soon as we can and tell you when it is fixed.

## Scope

This repository holds the Tranthor plugin for Cursor: a manifest, two skills and a link to the Tranthor MCP server (`https://api.tranthor.com/mcp`). It contains no code that runs on your machine and no credentials. Sign-in to Tranthor happens through OAuth in Cursor, and what the plugin can do in a workspace is limited by the person's role and the access they choose when they connect.

Problems in the Tranthor service itself can be reported the same way.
