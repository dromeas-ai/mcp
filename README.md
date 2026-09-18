# Dromeas MCP

Connect [Dromeas](https://dromeas.ai) — agentic AI code review (PR + trunk) and release management — to Claude, Cursor, Copilot, or any MCP client.

**Remote server:** `https://mcp.dromeas.ai/mcp`  
**Docs:** https://dromeas.ai/mcp

## What you get

OAuth 2.1 (PKCE) and 60+ tools for:

- Code Map (search + call graphs)
- Multi-analyst review (security, quality, compliance, bug tracing)
- Release management, docs, testing, and instrumentation
- RBAC-gated fixes, approvals, and releases

## Quick install

### Cursor

Add to MCP settings / `mcp.json`:

```json
{
  "mcpServers": {
    "dromeas": {
      "url": "https://mcp.dromeas.ai/mcp"
    }
  }
}
```

Or open the [Dromeas MCP install guide](https://dromeas.ai/mcp).

### Claude / Claude Code

Use the Dromeas remote MCP URL with OAuth:

`https://mcp.dromeas.ai/mcp`

See https://dromeas.ai/mcp for the current Claude Desktop / Claude Code steps.

### VS Code / Copilot

```json
{
  "servers": {
    "dromeas": {
      "url": "https://mcp.dromeas.ai/mcp",
      "type": "http"
    }
  }
}
```

## Agent skills

Playbooks for coding loops, code review, and release workflows: https://dromeas.ai/agent-tools

## License

MIT — this repository is a public connector listing / install stub. The Dromeas service itself is hosted by Dromeas.
