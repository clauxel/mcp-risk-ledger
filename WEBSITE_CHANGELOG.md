# Website Changelog
## 2026-06-17 - Hotword overlay split

- Added independent Cloudflare Worker + Assets hotword pages for mcpriskledger.clauxel.com.
- Routes are scoped to the new intent pages plus sitemap, robots, and llms so existing homepage, checkout, API, and MCP behavior remain with the current production Worker.
- New pages: /mcp-risk-assessment/, /mcp-server-risk-ledger/, /mcp-tool-approval/.

