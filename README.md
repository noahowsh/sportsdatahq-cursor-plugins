# SportsDataHQ plugins for Cursor

Nine sports data MCP servers, one per sport. Each is a hosted server: Cursor connects to the URL and asks you to sign in. Every account starts free with 500 credits a month and no card.

| Plugin | Sport | Server |
|---|---|---|
| [PuckAPI](./puckapi) | NHL | `https://mcp.puckapi.com/mcp` |
| [EndzoneAPI](./endzoneapi) | NFL | `https://mcp.endzoneapi.com/mcp` |
| [DunkAPI](./dunkapi) | NBA | `https://mcp.dunkapi.com/mcp` |
| [StrikerAPI](./strikerapi) | soccer | `https://mcp.strikerapi.com/mcp` |
| [FastballAPI](./fastballapi) | MLB | `https://mcp.fastballapi.com/mcp` |
| [AcesAPI](./acesapi) | tennis | `https://mcp.acesapi.com/mcp` |
| [BirdieAPI](./birdieapi) | golf | `https://mcp.birdieapi.com/mcp` |
| [FighterAPI](./fighterapi) | UFC | `https://mcp.fighterapi.com/mcp` |
| [YorkerAPI](./yorkerapi) | cricket | `https://mcp.yorkerapi.com/mcp` |

All tools are read-only. Each call uses credits from your account; pricing is on each site.

## Use one without the plugin

Add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "dunkapi": { "url": "https://mcp.dunkapi.com/mcp" }
  }
}
```

## License

MIT
