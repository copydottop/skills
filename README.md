# copy.top skills

Agent skills for [copy.top](https://copy.top): live signals, trader intel and alerts from top traders on fomo, pump.fun and hyperliquid.

```
npx skills add copydottop/skills
```

The skill uses the public copy.top MCP server (`https://copy.top/mcp`), read-only, no key needed.

| Skill | What it does |
|---|---|
| `copytop-signals` | what smart traders are buying, vetting a trader or a coin, leaderboards, alerts by cursor |

Figures are data, not advice.

## Without the skill

Connect the MCP server directly:

```
claude mcp add --transport http copytop https://copy.top/mcp
```

Docs: https://copy.top/mcp
