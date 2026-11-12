# DelegAIze MCP server

DelegAIze connects AI assistants to the systems a company already works with — CRM, mail, calendar, ERP and accounting — through AI agents that prepare the work and let a person approve it. Hosted in the EU.

This repository holds the public listing for the remote MCP server **`io.github.toasternet/delegaize`** in the [official MCP Registry](https://registry.modelcontextprotocol.io). The server itself is operated as a hosted service by Innov-AI-tive GmbH; its source code is not published here.

## Connect

Remote server (Streamable HTTP):

```
https://callpilotai.cf-innov-ai-tive.de/api/sb/functions/v1/mcp-server
```

- **Claude Code:** `claude mcp add --transport http delegaize https://callpilotai.cf-innov-ai-tive.de/api/sb/functions/v1/mcp-server`
- **claude.ai / other clients:** add it as a custom connector with the URL above.

`initialize`, `ping` and `tools/list` work without signing in, so you can see every tool before connecting. Every tool call requires sign-in via OAuth (or an API key issued in DelegAIze).

## More

- Website: https://delegaize.cf-innov-ai-tive.de/mcp
- Registry metadata: [`server.json`](server.json)

## Contact

Innov-AI-tive GmbH, Erlangen, Germany — info@innov-ai-tive.de
