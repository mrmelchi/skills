# skills

Colección de skills compatibles con el estándar [SKILL.md](https://skills.sh) abiertos. Desarrollados para los cursos de IA de UCEMA.

[![skills.sh](https://skills.sh/b/gauss314/skills)](https://skills.sh/gauss314/skills)


## Skills disponibles

| # | Skill | Tipo | Costo | API Key | Descripción |
|---|-------|------|:-----:|:-------:|-------------|
| 1 | [BCRA Macro](./skills/bcra-macro/) | API | ✅ Gratis | - | 🌎AR Estadísticas Monetarias ARG v4.0 del BCRA: 638 series macroeconómicas |
| 2 | [FRED Macro](./skills/fred-macro/) | API | ✅ Gratis | Requerida | Reserva Federal: 840K+ series macro (GDP, CPI, tasas, empleo, M2, VIX) |
| 3 | [Finnhub](./skills/finnhub/) | API | ⚠️ Freemium | Requerida | Gratis: Cotizaciones, perfil empresa, earnings, recomendaciones, métricas, noticias, búsqueda (60 calls/min free) |
| 4 | [Data912](./skills/data912/) | API | ✅ Gratis | - | 🌎AR Acciones, CEDEARs, bonos, letras, MEP, CCL (live + OHLC). US live Acciones y Volatilidades |
| 5 | [Alpha Vantage](./skills/alpha-vantage/) | API | ⚠️ Freemium | Requerida | Acciones, forex, crypto, 50+ indicadores técnicos, fundamental data (25 calls/dia free) |
| 6 | [Alpaca Data](./skills/alpaca-data/) | API | ✅ Gratis | Requerida | Acciones US, crypto, opciones con historical y real-time data. Feed IEX |
| 7 | [Alpaca Trading](./skills/alpaca-trading/) | API | ✅ Gratis | Requerida | Paper trading: órdenes, posiciones, cuenta para acciones, crypto y opciones |
| 8 | [Yahoo Finance](./skills/yahoo-finance/) | Scraper | ✅ Gratis | - | Precios, históricos, fundamentales, opciones, noticias en JSON |
| 9 | [SEC Data](./skills/sec-data/) | API | ✅ Gratis | - | SEC EDGAR: financial statements (income, balance, cash flow) desde XBRL JSON |
| 10 | [Finviz](./skills/finviz/) | Scraper | ✅ Gratis | - | Datos fundamentales, técnicos, insider trading, news y screener para acciones US |
| 11 | [Macrotrends](./skills/macrotrends/) | Scraper | ✅ Gratis | - | Financial statements, ratios, employee count con 15+ años de data |
| 12 | [MarketScreener](./skills/marketscreener/) | Scraper | ✅ Gratis | - | Cotizaciones, perfil, financials (income/balance/cashflow), valuación, consenso analistas, noticias, earnings transcripts listado, insider trading, accionistas, gobierno corporativo. Cubre 20K+ acciones globales incluyendo ADRs |
| 13 | [MarketWatch](./skills/marketwatch/) | Scraper | ✅ Gratis | - | Quotes, financials, SEC filings, analyst estimates, options, historical OHLCV |
| 14 | [CompaniesMarketCap](./skills/companiesmarketcap/) | Scraper | ✅ Gratis | - | Rankings (marketcap/earnings/revenue/employees/ratios), stock history, ETF holdings |
| 15 | [SimplyWallSt](./skills/simplywallst/) | API/Scraper | ✅ Gratis | - | Snowflake scores, valuation, P/E/P/B/ROE, dividend history (19+ años), insider transactions, price targets. 78K+ listings en 106 exchanges globales |
| 16 | [EarningsWhispers](./skills/earningswhispers/) | API | ✅ Gratis | - | Earnings transcripts COMPLETOS (prepared remarks + Q&A) via API pública sin auth. 33,500+ stocks globales. Cobertura: US, Europa, Asia, LatAm |
| 17 | [Barchart](./skills/barchart/) | Scraper | ✅ Gratis | - | Quotes + fundamentals + insider summary. Estimates. Analysts 30K+ stocks US, ADRs globales |
| 18 | [Nasdaq Data](./skills/nasdaq-data/) | API | ✅ Gratis | - | Cotizaciones, short interest, financials, institutional holdings, opciones, noticias, ETFs donde el stock es Top 10 Holding via API REST interna |
| 19 | [CBOE Data](./skills/cboe-data/) | API | ✅ Gratis | - | Índices y stocks CBOE: quotes delayed, historical (HV/IV), intraday 1-min, futuros VX, market summary (equities + opciones), most-active, symbol lookup |
| 20 | [Investing.com](./skills/investing/) | Scraper | ✅ Gratis | - | 81K+ equities, 10K+ indices, 2.4K currencies, 344 commodities, 30K+ ETFs, 4K+ crypto. Quotes, historico OHLCV, fundamentals (income/balance/cashflow/ratios), dividendos, earnings, perfil. Cobertura global con auto-detección de tipo. Requiere `curl_cffi` |
| 21 | [Morningstar](./skills/morningstar/) | API | ✅ Gratis | - | Screener masivo via API JSON: 53 universes (102K+ listings, 39 paises) con 33 campos (precio, market cap, ratios, retornos 1d/1w/1m/3m/6m/12m/36m/60m/120m, deuda, dividend yield, sector, industria). CEDEARs Argentina (XBUE), NYSE, Nasdaq, B3, BMV, Tokyo, London, etc. Token universal via ingenieria inversa. Multi-universe, multi-pais, multi-currency. Salida JSON/CSV |
| 22 | [MAE](./skills/mae/) | API | ✅ Gratis | - | 🌎AR Mercado Abierto Electrónico: renta fija, cauciones, REPO, FOREX mayorista, dólar diferido (DDF), índice ARS-MAE, licitaciones primarias, comunicados institucionales, flujo de fondos para curvas TIR/MD. 17 endpoints |
| 23 | [BYMA](./skills/byma/) | API | ✅ Gratis | - | 🌎AR Bolsas y Mercados Argentinos: paneles de acciones líderes, CEDEARs, bonos soberanos + LECAPs/BONCAPs, ONs corporativas, cauciones, opciones y SENEBI. Históricos OHLCV de instrumentos e índices (MERVAL, BURCAP). 9 endpoints |
| 24 | [CAFCI](./skills/cafci/) | API | ✅ Gratis | - | 🌎AR Fondos comunes de inversión argentinos (1152 fondos, 4615 clases): catálogo completo con honorarios/fees, snapshot diario (VCP, patrimonio, market share, variaciones día/mes/YTD/12m), ficha individual con rendimientos TNA, composición de cartera (top activos). 4 endpoints + cache local diario |

### Instalación

Instalar todas las skills globalmente: `npx skills add gauss314/skills -g` 
Tambien se pueden instalar solo las necesarias individualmente con los comandos de la tabla:

| # | Skill | Comando |
|---|-------|---------|
| 1 | BCRA Macro | `npx skills add gauss314/skills --skill bcra-macro` |
| 2 | FRED Macro | `npx skills add gauss314/skills --skill fred-macro` |
| 3 | Finnhub | `npx skills add gauss314/skills --skill finnhub` |
| 4 | Data912 | `npx skills add gauss314/skills --skill data912` |
| 5 | Alpha Vantage | `npx skills add gauss314/skills --skill alpha-vantage` |
| 6 | Alpaca Data | `npx skills add gauss314/skills --skill alpaca-data` |
| 7 | Alpaca Trading | `npx skills add gauss314/skills --skill alpaca-trading` |
| 8 | Yahoo Finance | `npx skills add gauss314/skills --skill yahoo-finance` |
| 9 | SEC Data | `npx skills add gauss314/skills --skill sec-data` |
| 10 | Finviz | `npx skills add gauss314/skills --skill finviz` |
| 11 | Macrotrends | `npx skills add gauss314/skills --skill macrotrends` |
| 12 | MarketScreener | `npx skills add gauss314/skills --skill marketscreener` |
| 13 | MarketWatch | `npx skills add gauss314/skills --skill marketwatch` |
| 14 | CompaniesMarketCap | `npx skills add gauss314/skills --skill companiesmarketcap` |
| 15 | SimplyWallSt | `npx skills add gauss314/skills --skill simplywallst` |
| 16 | EarningsWhispers | `npx skills add gauss314/skills --skill earningswhispers` |
| 17 | Barchart | `npx skills add gauss314/skills --skill barchart` |
| 18 | Nasdaq Data | `npx skills add gauss314/skills --skill nasdaq-data` |
| 19 | CBOE Data | `npx skills add gauss314/skills --skill cboe-data` |
| 20 | Investing.com | `npx skills add gauss314/skills --skill investing` |
| 21 | Morningstar | `npx skills add gauss314/skills --skill morningstar` |
| 21 | MAE | `npx skills add gauss314/skills --skill mae` |
| 22 | BYMA | `npx skills add gauss314/skills --skill byma` |
| 23 | CAFCI | `npx skills add gauss314/skills --skill cafci` |

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
