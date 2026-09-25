# Horse Truth Machine Intelligence MCP

Official public distribution metadata and connection documentation for the Horse Truth remote MCP server.

**Remote endpoint:** `https://horsetruth.com.au/api/v1/mcp`

Horse Truth provides derived Australian racehorse intelligence for AI agents, MCP clients, software and publishers.

## Tools

Free discovery/sample tools:

- `sandbox_preview`
- `discover_purchase_options`

Paid intelligence tools:

- `horse_intelligence`
- `horse_changes`
- `horse_rankings`
- `resolve_horse`

Direct Horse Truth machine access starts at **A$1 for 50 credits**. The Apify marketplace route is **US$0.02 per successful result** through Pay-Per-Event.

## Connect

```bash
claude mcp add --transport http horse-truth https://horsetruth.com.au/api/v1/mcp
```

Paid tools use a Horse Truth machine key as `Authorization: Bearer <key>`. Free discovery tools do not consume credits.

Developer and purchase documentation: https://horsetruth.com.au/developers

Apify marketplace: https://apify.com/crocheted_poacher/horse-truth-machine-intelligence

Official MCP Registry name: `au.com.horsetruth/machine-intelligence`

## Public metadata

- Server card: https://horsetruth.com.au/.well-known/mcp/server-card.json
- Integrations declaration: https://horsetruth.com.au/.well-known/integrations.json
- API catalog: https://horsetruth.com.au/.well-known/api-catalog
- Agent card: https://horsetruth.com.au/.well-known/agent-card.json
- LLM discovery: https://horsetruth.com.au/llms.txt

## Source boundary

This repository intentionally contains public distribution metadata and integration documentation only. Horse Truth's proprietary runtime, research pipeline, model logic and private data are not published here.

## Security

Please report security issues through the contact path published at https://horsetruth.com.au/developers rather than opening a public exploit report.
