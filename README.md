# AlgoRover Research for Cursor

Discover published strategies and inspect historical research through the hosted AlgoRover Research MCP service. This repository contains a Cursor plugin with Research instructions and a remote MCP connection.

## Installation

This plugin has been prepared for Cursor Marketplace review. Marketplace availability is not yet confirmed.

For direct MCP setup, merge the entry from [mcp.json](mcp.json) into your project's `.cursor/mcp.json`, preserving other servers. The endpoint is `https://research.algorover.ai/mcp` and uses Streamable HTTP. Ask Cursor to search AlgoRover Research strategies, then read the details of a returned strategy and exact version.

## Validation and authorization

The native Cursor MCP client discovered all 16 tools. This confirms MCP connectivity. Marketplace plugin installation, inline card rendering, browser OAuth and the complete authenticated backtest workflow remain under validation.

Public discovery and preparation do not require sign-in. Starting historical backtests and reading personal tasks or reports require Research OAuth with `research:read` and `research:run`. Use Cursor's supported browser authorization flow when available. Do not paste tokens, passwords or exchange credentials into chat or configuration. Anonymous tool discovery does not establish access to personal research.

Before running a backtest, show the actual preview and obtain confirmation. Use returned strategy references, presets and task identifiers. If the client shows text instead of a card, show the returned text and links. Report authorization failures directly.

AlgoRover Research uses public market data and supports historical analysis. It does not connect exchange accounts or place orders. Historical performance does not establish future returns.

## Publisher

Rivendell Holdings Investment Limited.

- [Website](https://www.algorover.ai/)
- [Support](https://www.algorover.ai/en/help/)
- [Privacy](https://www.algorover.ai/privacy/)
- [Terms](https://www.algorover.ai/terms/)
