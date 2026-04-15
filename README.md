# mcp-yesterdays-number

yesterdays-number MCP — wraps StupidAPIs (requires X-API-Key)

Part of the [Pipeworx](https://pipeworx.io) open MCP gateway.

## Tools

| Tool | Description |
|------|-------------|
| `yesterdays_number_get` | A random number, aged 24 hours for smoothness. Some numbers are better with time. This one is fine. |

## Quick Start

Add to your MCP client config:

```json
{
  "mcpServers": {
    "yesterdays-number": {
      "url": "https://gateway.pipeworx.io/yesterdays-number/mcp"
    }
  }
}
```

Or use the CLI:

```bash
npx pipeworx use yesterdays-number
```

## License

MIT
