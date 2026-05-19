# MCP Risk Ledger MCP

Paid remote MCP for server intake risk reports, tool review, approvals, and readiness.

## Connect

- Website: https://mcpriskledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://mcpriskledger.clauxel.com/mcp
- Server card: https://mcpriskledger.clauxel.com/.well-known/mcp/server-card.json
- Official Registry name: `com.clauxel.mcpriskledger/mcpriskledger-mcp`

This is a hosted Streamable HTTP MCP server. It requires an Authorization bearer token issued after checkout and token claim.

## What It Does

MCP Risk Ledger MCP exposes a fixed, read-only tool surface for MCP risk review. It is designed for agent workflows that need a hosted MCP endpoint with explicit auth, public discovery metadata, and clear data boundaries.

## Authentication

Send the paid MCP token as:

```http
Authorization: Bearer <token>
```

The token is issued by the product checkout and MCP token claim flow. Do not put tokens in issues, pull requests, logs, or screenshots.

## Files

- [server.json](./server.json) - MCP Registry descriptor.
- [Usage guide](./docs/usage.md) - setup and request examples.
- [Security notes](./docs/security.md) - auth, data boundaries, and safe-use expectations.
- [llms.txt](./llms.txt) - short machine-readable discovery summary.

## Related Workflow

- [OpenHuman Online](https://openhuman.online/?utm_source=github&utm_medium=readme&utm_campaign=openhuman_public_repos&utm_content=mcp_risk_ledger) is useful when this MCP rollout also needs human-readable source memory, meeting notes, or approval context outside the server.

## Status

This public repository is a docs-only distribution package for directory review and MCP discovery. The hosted server runs at https://mcpriskledger.clauxel.com/mcp.
