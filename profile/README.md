<p align="center">
  <a href="https://fxapis.com"><img src="https://raw.githubusercontent.com/FXapis/.github/main/profile/banner.png" alt="fxapis — the MetaTrader 5 API, with market intelligence built in" width="100%"></a>
</p>

**fxapis** is a hosted MetaTrader 5 API with market intelligence built in. Connect an MT5
account with its login, password and server, from any broker, then trade it from code,
TradingView alerts, n8n or an AI agent. MarketLabs adds the economic calendar, positioning
data and a daily cited research brief for your pairs. There is no terminal, VPS or EA on
your side.

### Trade MetaTrader 5
- **REST API** — accounts, live prices, price history, orders, positions and deal history over HTTPS
- **Multi-account orders** — one trade on many accounts at once, then close or retry it the same way
- **TradingView alerts** — secret webhook URLs that turn alerts into orders on your accounts
- **Webhooks** — order, position and account events as they happen

### MarketLabs — market intelligence *(beta, on every plan)*
- **Today for you** — your open positions and orders against the next events and the last 24 hours
- **Economic calendar** — official releases and rate decisions, with forecast, actual and previous figures
- **Positioning and sessions** — CFTC positioning and the trading sessions for each pair
- **Daily research** — a cited brief for each watchlist pair, scored for accuracy afterwards

MarketLabs is research, never trading advice, and it never places a trade.

### For AI agents
A hosted MCP server at `https://api.fxapis.com/mcp` lets Claude, ChatGPT, Cursor or any MCP
client read accounts and MarketLabs, and place orders only if you allow it. Sign-in is OAuth,
and the first consent is read-only. A read-only server is at `https://api.fxapis.com/mcp/insights`.
Both are in the official MCP Registry as `com.fxapis/mt5` and `com.fxapis/mt5-insights`.

### Repositories

| | |
|---|---|
| **SDKs** | [Python](https://github.com/FXapis/fxapis-python) (`pip install fxapis`) · [TypeScript](https://github.com/FXapis/fxapis-typescript) (`npm install fxapis`) |
| **AI agents** | [MCP examples](https://github.com/FXapis/fxapis-mcp-examples) · [Claude plugin](https://github.com/FXapis/fxapis-claude-plugins) |
| **Automation** | [n8n node](https://github.com/FXapis/fxapis-n8n) · [TradingView, Postman and n8n templates](https://github.com/FXapis/fxapis-integrations) |
| **Start here** | [Examples](https://github.com/FXapis/fxapis-examples) · [Next.js starter](https://github.com/FXapis/fxapis-nextjs-starter) |

**Links:** [Website](https://fxapis.com) · [Docs](https://docs.fxapis.com) · [MarketLabs](https://fxapis.com/marketlabs) · [MCP](https://fxapis.com/mcp) · Support: support@fxapis.com
