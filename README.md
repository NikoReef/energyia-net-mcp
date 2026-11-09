# EnergyIA.NET — MCP connector

Connect your AI assistant to **official oil, gas and mining data of America**, comparable
country by country: production by country, operator, field and mine, mining, refineries, gas
flaring, electricity, energy balance, reference prices, and the movement of energy and mining
vessels at terminals (from the public AIS signals ships broadcast; not tracking of people).
Every answer comes normalized and cited with its source and period. Argentina in detail
(fields and wells): [EnergyIA.AR](https://github.com/NikoReef/energyia-mcp).

- **Server (remote, HTTP):** `https://energyia.net/conectar-mi-ia`
- **Auth:** OAuth — sign in with the email of your EnergyIA.NET account and a 6-digit code. Nothing to install, no API keys.
- **Access:** create an account at [energyia.net](https://energyia.net).
- **Read-only:** every tool is a query; nothing writes to your data or ours.

## Install

**Grok / Cursor:** install this plugin from the marketplace, or add the server from `.mcp.json`.

**Any MCP client:** add a remote HTTP server with the URL above. Step-by-step guides: https://energyia.net/en/guias

## Data

Coverage, sources and periods: ask the `coverage` and `sources` tools. Data is informational and is not investment advice.

---

Este repositorio sólo contiene la configuración del conector (no el código del servicio). Sitio: https://energyia.net
