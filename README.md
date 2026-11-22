# Lordevo Shop

Lordevo Shop is a remote MCP server of website, DNS, email, SEO and data-check tools for AI agents and developers.

- Server: `https://shop.lordevo.com/mcp` (Streamable HTTP)
- No account and no API key.
- Free tools: `list_services`, `get_sample_output`, `preflight`, plus a small daily trial on cheaper tools.
- Other tools are paid per call, from $0.003, in USDC on Base using the x402 protocol.
- Results are automated; no ranking, traffic or security outcome is promised.

## Use in Cursor

Add this to your `.mcp.json`:

```json
{
  "mcpServers": {
    "lordevo-shop": {
      "type": "streamable-http",
      "url": "https://shop.lordevo.com/mcp"
    }
  }
}
```

Support: lordevo.shop@gmail.com
