# Ad Library Intelligence for Gemini CLI

Competitor ads from the Meta, Google Ads Transparency and LinkedIn ad libraries, plus ads.txt sellers.

This extension connects Gemini CLI to the hosted MCP server [Ad Library Intelligence](https://mcpize.com/mcp/ad-library-intelligence). It reads public pages only and needs no login or cookies for the source itself.

## Install

```
gemini extensions install https://github.com/benthepythondev00/ad-library-intelligence
```

Gemini CLI asks for your MCPize API key once and keeps it in the system keychain.

## Get a key

1. Open https://mcpize.com/mcp/ad-library-intelligence and subscribe. The Free plan needs no card.
2. Copy the API key shown on the server page.

## Try it

- "Which Google ads has nike.com shown in Germany this month?"
- "Show me 20 active Meta ads that mention running shoes in the US."

## Plans

Billing runs through MCPize: Free for a small monthly allowance, Pro $9 for 1,000 calls, Business $29 for 5,000 calls. See the server page for the current numbers.

## Notes

Independent server by benthepythondev. Not affiliated with or endorsed by the sites it reads. The same data is available as Apify Actors: https://apify.com/benthepythondev
