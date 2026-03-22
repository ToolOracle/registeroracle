# 📋 registerOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/register/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "registeroracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/register/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_provider` | Add or update an ICT third-party provider in the DORA Register of Information (A |
| `list_providers` | List all ICT third-party providers in the Register of Information with optional  |
| `get_provider` | Get full details, risk flags, and ITS completeness of a specific provider. |
| `validate_roi` | Validate entire Register of Information against DORA ITS requirements.  |
| `concentration_risk` | Analyze ICT concentration risks across providers, countries, cloud types.  |
| `ctpp_check` | Assess if a provider might qualify as Critical Third-Party Provider (CTPP)  |
| `export_its` | Export Register of Information in ITS-compliant format for supervisory reporting |
| `gap_analysis` | Identify gaps in the Register — missing fields, incomplete entries,  |
| `register_stats` | Dashboard summary: provider counts, criticality distribution,  |
| `health_check` | Server and data status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

registerOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/register/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
