# skills

Colección de skills compatibles con el estándar [SKILL.md](https://skills.sh) abiertos. Desarrollados para los cursos de IA de UCEMA.

[![skills.sh](https://skills.sh/b/gauss314/skills)](https://skills.sh/gauss314/skills)


## Skills disponibles

| Skill | Tipo | Costo | API Key | Descripción |
|-------|------|:-----:|:-------:|-------------|
| [BCRA Macro](./skills/bcra-macro/) | API | ✅ Gratis | - | 🌎AR Estadísticas Monetarias ARG v4.0 del BCRA: 638 series macroeconómicas |
| [FRED Macro](./skills/fred-macro/) | API | ✅ Gratis | Requerida | Reserva Federal: 840K+ series macro (GDP, CPI, tasas, empleo, M2, VIX) |
| [Finnhub](./skills/finnhub/) | API | ⚠️ Freemium | Requerida | Gratis: Cotizaciones, perfil empresa, earnings, recomendaciones, métricas, noticias, búsqueda (60 calls/min free) |
| [Data912](./skills/data912/) | API | ✅ Gratis | - |  🌎AR Acciones, CEDEARs, bonos, letras, MEP, CCL (live + OHLC). �US live Acciones y Volatilidades |
| [Alpha Vantage](./skills/alpha-vantage/) | API | ⚠️ Freemium | Requerida | Acciones, forex, crypto, 50+ indicadores técnicos, fundamental data (25 calls/dia free) |
| [Alpaca Data](./skills/alpaca-data/) | API | ✅ Gratis | Requerida | Acciones US, crypto, opciones con historical y real-time data. Feed IEX |
| [Alpaca Trading](./skills/alpaca-trading/) | API | ✅ Gratis | Requerida | Paper trading: órdenes, posiciones, cuenta para acciones, crypto y opciones |
| [Yahoo Finance](./skills/yahoo-finance/) | Scraper | ✅ Gratis | - | Precios, históricos, fundamentales, opciones, noticias en JSON |
| [SEC Data](./skills/sec-data/) | API | ✅ Gratis | - | SEC EDGAR: financial statements (income, balance, cash flow) desde XBRL JSON |
| [Finviz](./skills/finviz/) | Scraper | ✅ Gratis | - | Datos fundamentales, técnicos, insider trading, news y screener para acciones US |
| [Macrotrends](./skills/macrotrends/) | Scraper | ✅ Gratis | - | Financial statements, ratios, employee count con 15+ años de data |
| [MarketScreener](./skills/marketscreener/) | Scraper | ✅ Gratis | - | Cotizaciones, perfil, financials (income/balance/cashflow), valuación, consenso analistas, noticias, earnings transcripts listado, insider trading, accionistas, gobierno corporativo. Cubre 20K+ acciones globales incluyendo ADRs |
| [MarketWatch](./skills/marketwatch/) | Scraper | ✅ Gratis | - | Quotes, financials, SEC filings, analyst estimates, options, historical OHLCV |
| [CompaniesMarketCap](./skills/companiesmarketcap/) | Scraper | ✅ Gratis | - | Rankings (marketcap/earnings/revenue/employees/ratios), stock history, ETF holdings |
| [EarningsWhispers](./skills/earningswhispers/) | API | ✅ Gratis | - | Earnings transcripts COMPLETOS (prepared remarks + Q&A) via API pública sin auth. 33,500+ stocks globales. Cobertura: US, Europa, Asia, LatAm |

### Instalación

Instalar todas las skills globalmente: `npx skills add gauss314/skills -g` 
Tambien se pueden instalar solo las necesarias individualmente con los comandos de la tabla:

| Skill | Comando |
|-------|---------|
| BCRA Macro | `npx skills add gauss314/skills --skill bcra-macro` |
| FRED Macro | `npx skills add gauss314/skills --skill fred-macro` |
| Finnhub | `npx skills add gauss314/skills --skill finnhub` |
| Data912 | `npx skills add gauss314/skills --skill data912` |
| Alpha Vantage | `npx skills add gauss314/skills --skill alpha-vantage` |
| Alpaca Data | `npx skills add gauss314/skills --skill alpaca-data` |
| Alpaca Trading | `npx skills add gauss314/skills --skill alpaca-trading` |
| Yahoo Finance | `npx skills add gauss314/skills --skill yahoo-finance` |
| SEC Data | `npx skills add gauss314/skills --skill sec-data` |
| Finviz | `npx skills add gauss314/skills --skill finviz` |
| Macrotrends | `npx skills add gauss314/skills --skill macrotrends` |
| MarketScreener | `npx skills add gauss314/skills --skill marketscreener` |
| MarketWatch | `npx skills add gauss314/skills --skill marketwatch` |
| CompaniesMarketCap | `npx skills add gauss314/skills --skill companiesmarketcap` |
| EarningsWhispers | `npx skills add gauss314/skills --skill earningswhispers` |

## Estructura

Cada skill es un directorio que sigue la estructura del estándar Agent Skills:

```
.
├── skills/
│   └── <skill-name>/
│       ├── SKILL.md           # requerido: frontmatter + instrucciones
│       ├── references/        # carpeta opcional: documentación complementaria
│       ├── scripts/           # carpeta opcional: scripts de ejemplo ejecutables
│       └── assets/            # carpeta opcional: plantillas, configs
├── README.md
├── LICENSE                    # MIT
└── .gitignore
```

## Cómo funciona

El comando `npx skills add gauss314/skills --skill bcra-macro` instala:

1. **SKILL.md** → se carga al contexto del agente cuando usás `/bcra-macro`
2. **references/** → documentación complementaria (catálogos, referencias)
3. **scripts/** → scripts ejecutables (Python, Bash, etc.)
4. **assets/** → plantillas, configs, archivos auxiliares

Los archivos en `references/`, `scripts/` y `assets/` se cargan **solo cuando el skill los necesita**, siguiendo el principio de **Progressive Disclosure** para optimizar tokens.

## Formato SKILL.md

```yaml
---
name: nombre-del-skill
description: Descripción breve (<100 caracteres)
license: MIT
---

# Skill Name

Instrucciones para el agente y contenido del SKILL...
```

**Campos obligatorios:** `name`, `description`  
**Campos opcionales:** `license`, `metadata`, `disable-model-invocation`

## Instalación

```bash
# Instalar un skill específico en el proyecto
npx skills add gauss314/skills --skill bcra-macro


# Instalar todos los skills del repo para el proyecto
npx skills add gauss314/skills --all


# Instalación global (accesible para cualquier proyecto del usuario)
npx skills add gauss314/skills --skill bcra-macro -g
```

## Compatibilidad

Probado con:

- Claude Code, Antigravity, Cursor, Windsurf, Gemini CLI
- Codex, OpenCode, CommandCode CLI, Kimi CLI, Trae

## Licencia

[MIT](./LICENSE)
