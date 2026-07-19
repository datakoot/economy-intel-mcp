# Economy Intel MCP — by SelfLabbs

Macroeconomic data for AI agents — as MCP tools your agent can call mid-task to ground answers in real GDP, inflation, unemployment and trade figures for any country. No API keys.

## Tools

| Tool | What it does | Source |
|---|---|---|
| `country_indicator` | An indicator (GDP, inflation, unemployment, population, ...) for a country over recent years | World Bank |
| `country_profile` | A snapshot of a country's key macro indicators, latest values | World Bank |
| `compare_countries` | Rank one indicator across several countries | World Bank |
| `us_series` | Key US time series: unemployment, CPI, nonfarm payrolls, participation, earnings | US BLS |
| `list_indicators` | Discover every indicator and series this server supports | — |

No API keys required.

## Quick start

```
claude mcp add --transport http economy-intel https://economy.selflabbs.com/mcp
```

Or point any MCP client at `https://economy.selflabbs.com/mcp`.

## Data & attribution

Country data comes from the [World Bank Open Data](https://data.worldbank.org) API (CC-BY 4.0); US series come from the [US Bureau of Labor Statistics](https://www.bls.gov) public data API (US public domain). Informational only.

Part of [SelfLabbs](https://selflabbs.com) — keyless intelligence APIs for AI agents.
