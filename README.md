# skills

Open-source collection of skills compatible with the [SKILL.md](https://skills.sh) standard. Developed for the AI courses at UCEMA.

[![skills.sh](https://skills.sh/b/gauss314/skills)](https://skills.sh/gauss314/skills)


## Data — Global

Skills that extract market data (quotes, historical, fundamentals, screener, etc). Multi-country / global coverage: US, Europe, Asia, and global aggregators.

| # | Skill | Type | Cost | API Key | Instruments |
|---|-------|------|:-----:|:-------:|--------------|
| 1 | [FRED Macro](./skills/fred-macro/) | API | ✅ Free | Required | macro-data |
| 2 | [Alpha Vantage](./skills/alpha-vantage/) | API | ⚠️ Freemium | Required | stocks, forex, commodities, fundamentals |
| 3 | [Yahoo Finance](./skills/yahoo-finance/) | Scraper | ✅ Free | - | stocks, forex, options, futures, fundamentals |
| 4 | [SEC Data](./skills/sec-data/) | API | ✅ Free | - | fundamentals |
| 5 | [Alpaca Data](./skills/alpaca-data/) | API | ✅ Free | Required | stocks, options |
| 6 | [Finnhub](./skills/finnhub/) | API | ⚠️ Freemium | Required | stocks, forex, fundamentals |
| 7 | [Finviz](./skills/finviz/) | Scraper | ✅ Free | - | stocks, fundamentals, screener |
| 8 | [Macrotrends](./skills/macrotrends/) | Scraper | ✅ Free | - | stocks, fundamentals |
| 9 | [MarketScreener](./skills/marketscreener/) | Scraper | ✅ Free | - | stocks, fundamentals, screener |
| 10 | [MarketWatch](./skills/marketwatch/) | Scraper | ✅ Free | - | stocks, options, futures, fundamentals |
| 11 | [CompaniesMarketCap](./skills/companiesmarketcap/) | Scraper | ✅ Free | - | stocks, etfs |
| 12 | [SimplyWallSt](./skills/simplywallst/) | API/Scraper | ✅ Free | - | stocks, fundamentals |
| 13 | [EarningsWhispers](./skills/earningswhispers/) | API | ✅ Free | - | fundamentals |
| 14 | [Barchart](./skills/barchart/) | Scraper | ✅ Free | - | stocks, futures, fundamentals |
| 15 | [Nasdaq Data](./skills/nasdaq-data/) | API | ✅ Free | - | stocks, options, fundamentals, etfs |
| 16 | [CBOE Data](./skills/cboe-data/) | API | ✅ Free | - | stocks, options, commodities, futures |
| 17 | [Investing.com](./skills/investing/) | Scraper | ✅ Free | - | stocks, forex, commodities, options, futures, etfs, screener, fundamentals |
| 18 | [Morningstar](./skills/morningstar/) | API | ✅ Free | - | screener |
| 19 | [TradingView](./skills/tradingview/) | API | ✅ Free | - | stocks, etfs, bonds, options, futures, forex, crypto, screener, fundamentals |

## Data — Regional (Argentina)

Skills specific to the Argentine market: BCRA, BCBA, MAE, CAFCI, etc.

| # | Skill | Type | Cost | API Key | Instruments |
|---|-------|------|:-----:|:-------:|--------------|
| 1 | [BCRA Macro](./skills/bcra-macro/) | API | ✅ Free | - | macro-data |
| 2 | [Data912](./skills/data912/) | API | ✅ Free | - | stocks, forex, bonds, options, etfs |
| 3 | [MAE](./skills/mae/) | API | ✅ Free | - | bonds, macro-data, forex |
| 4 | [BYMA](./skills/byma/) | API | ✅ Free | - | stocks, bonds, options, etfs |
| 5 | [CAFCI](./skills/cafci/) | API | ✅ Free | - | etfs |

---

## Brokers

Skills that allow executing real trades (orders, positions, account) on broker accounts.

| # | Skill | Type | Country | Instruments |
|---|-------|------|---------|--------------|
| 1 | [Alpaca Trading](./skills/alpaca-trading/) | REST | USA | stocks, options |
| soon | Invertironline | | | |
| soon | Portfolio Personal | | | |

---

## Tools

Calculation and financial support tools (backtesting frameworks, screeners, options and greeks calculation, etc).

| # | Skill | Concepts |
|---|-------|----------|
| soon | Portfolio Optimization | Markowitz, mean-variance, Black-Litterman, risk parity, constraints (long-only, sector caps, position limits), efficient frontier, monte carlo |
| soon | Backtesting | Walk-forward, in-sample/out-of-sample, transaction costs, slippage, sharpe/sortino/max-drawdown, equity curve, signal generation |
| soon | Option pricing | Black-Scholes, binomial/trinomial trees, Monte Carlo, greeks (delta/gamma/vega/theta/rho), implied vol, volatility surface |

---

### Installation

Install all skills globally: `npx skills add gauss314/skills -g`  
Individual skills can also be installed with the commands in the table:

| Skill | Command |
|-------|---------|
| FRED Macro | `npx skills add gauss314/skills --skill fred-macro` |
| Alpha Vantage | `npx skills add gauss314/skills --skill alpha-vantage` |
| Yahoo Finance | `npx skills add gauss314/skills --skill yahoo-finance` |
| SEC Data | `npx skills add gauss314/skills --skill sec-data` |
| Alpaca Data | `npx skills add gauss314/skills --skill alpaca-data` |
| Finnhub | `npx skills add gauss314/skills --skill finnhub` |
| Finviz | `npx skills add gauss314/skills --skill finviz` |
| Macrotrends | `npx skills add gauss314/skills --skill macrotrends` |
| MarketScreener | `npx skills add gauss314/skills --skill marketscreener` |
| MarketWatch | `npx skills add gauss314/skills --skill marketwatch` |
| CompaniesMarketCap | `npx skills add gauss314/skills --skill companiesmarketcap` |
| SimplyWallSt | `npx skills add gauss314/skills --skill simplywallst` |
| EarningsWhispers | `npx skills add gauss314/skills --skill earningswhispers` |
| Barchart | `npx skills add gauss314/skills --skill barchart` |
| Nasdaq Data | `npx skills add gauss314/skills --skill nasdaq-data` |
| CBOE Data | `npx skills add gauss314/skills --skill cboe-data` |
| Investing.com | `npx skills add gauss314/skills --skill investing` |
| Morningstar | `npx skills add gauss314/skills --skill morningstar` |
| TradingView | `npx skills add gauss314/skills --skill tradingview` |
| BCRA Macro | `npx skills add gauss314/skills --skill bcra-macro` |
| Data912 | `npx skills add gauss314/skills --skill data912` |
| MAE | `npx skills add gauss314/skills --skill mae` |
| BYMA | `npx skills add gauss314/skills --skill byma` |
| CAFCI | `npx skills add gauss314/skills --skill cafci` |
| Alpaca Trading | `npx skills add gauss314/skills --skill alpaca-trading` |

## Structure

Each skill is a directory following the Agent Skills standard structure:

```
.
├── skills/
│   └── <skill-name>/
│       ├── SKILL.md           # required: frontmatter + instructions
│       ├── references/        # optional folder: complementary documentation
│       ├── scripts/           # optional folder: executable example scripts
│       └── assets/            # optional folder: templates, configs
├── README.md
├── LICENSE                    # MIT
└── .gitignore
```

## How it works

The command `npx skills add gauss314/skills --skill bcra-macro` installs:

1. **SKILL.md** → loaded into the agent context when you use `/bcra-macro`
2. **references/** → complementary documentation (catalogs, references)
3. **scripts/** → executable scripts (Python, Bash, etc)
4. **assets/** → templates, configs, auxiliary files

Files in `references/`, `scripts/` and `assets/` are loaded **only when the skill needs them**, following the **Progressive Disclosure** principle to optimize tokens.

## SKILL.md format

```yaml
---
name: skill-name
description: Short description (<100 characters)
license: MIT
---

# Skill Name

Instructions for the agent and SKILL content...
```

**Required fields:** `name`, `description`  
**Optional fields:** `license`, `metadata`, `disable-model-invocation`

## Installation

```bash
# Install a specific skill in the project
npx skills add gauss314/skills --skill bcra-macro


# Install all skills from the repo into the project
npx skills add gauss314/skills --all


# Global install (accessible to any of the user's projects)
npx skills add gauss314/skills --skill bcra-macro -g
```

## Skill Description

#### Data — Global

**FRED Macro:** **840,000+** macroeconomic series from the Federal Reserve (GDP, CPI, rates, employment, M2, VIX, treasuries, mortgages). Historical series since **1996** with search by name/category, tags, releases, and daily/monthly/quarterly/annual frequencies. Official free API.

**Alpha Vantage:** **20+** global exchanges, **200,000+** tickers (stocks, forex, crypto, commodities). Freemium with **25 calls/day** free. Covers TIME_SERIES_INTRADAY/DAILY/WEEKLY/MONTHLY, **50+** technical indicators, fundamental overview, FX rates, crypto ratings, commodities (metals, energy, grains).

**Yahoo Finance:** global coverage — stocks, ETFs, crypto, forex, bonds, indices, options, futures, fundamentals and news. Quotes delayed **15min**, daily/intraday OHLCV, financial statements, options chains, futures on commodities and indices, news, analyst recommendations, insider transactions. Unofficial endpoints via direct HTTP requests (no wrapper).

**SEC Data:** all companies filing with the SEC (10K, 10Q, 8K) — US public companies + internationals using IFRS. Data from the last **5+ years** with quarterly + annual. Concept-level data navigable. Supports US-GAAP and IFRS with automatic concept mapping. Income/balance/cashflow statements in JSON/CSV from XBRL facts.

**Alpaca Data:** **5,000+** US stocks + crypto + options with historical and real-time data. IEX feed. Snapshots, bars (OHLCV), trades, quotes. Multi-asset with symbol normalization. Generous free tier for historical data, real-time with limit.

**Finnhub:** **32** free REST endpoints with US/EU/UK coverage + forex + crypto. Quotes, company profile, financials, earnings calendar, recommendations trends, price targets, insider transactions, company peers, ESG scores, news, economic data, WebSocket. Freemium **60 calls/min**.

**Finviz:** **8K+** US stocks (NYSE, NASDAQ, AMEX) + Canada. Fundamental data (P/E, EPS, PEG, margins), technical (RSI, MACD, SMA, ATR), insider trading, institutional ownership, news, online screener with filters (market cap, P/E, sector, performance). Scraper of the Finviz site.

**Macrotrends:** **~6,500** tickers from US markets (NYSE, NASDAQ, AMEX), including international ADRs from **+30 countries**. Financial statements, ratios, employee count with **15+ years** of historical data. Income/balance/cashflow with **5-30 years** of history, profitability ratios, debt, margins, per-share data, segment data.

**MarketScreener:** **20K+** global stocks including ADRs. Quote, profile, financials (income/balance/cashflow), valuation, analyst consensus, news, earnings transcripts list, insider trading, shareholders, corporate governance, earnings calendar, recommendations, ownership structure. Global multi-country coverage.

**MarketWatch:** US stocks and global ADRs. Quotes, financials, SEC filings, analyst estimates, options chain, futures, historical OHLCV. Point-in-time data per ticker, comparable companies panel, screeners by category. Futures data on indices, commodities, rates and currencies.

**CompaniesMarketCap:** global financial rankings (market cap, earnings, revenue, employees, P/E, margins, assets, debt, cash), historical marketcap of stocks and ETF holdings. Global coverage — top companies by any metric, historical capitalization, ETF holdings. Uses native CSV download of the site.

**SimplyWallSt:** **120,000+** global stocks in **106** exchanges. Snowflake scores (1-5 stars: value, income, health, past, future, management), valuation vs sector, dividend history (**19+ years**) and projected, financial health score, insider transactions, price targets, P/E/P/B/ROE analysis. Internal REST API of the web frontend.

**EarningsWhispers:** **33,500+** global stocks tracked (US, Europe, Asia, LatAm). COMPLETE earnings transcripts (prepared remarks + Q&A) via public API without auth. No anti-bot, no aggressive rate limiting. Tested on **60+** tickers (AAPL, MSFT, GGAL, SHEL, TM, VALE, etc). Metadata: date, fiscal period, participants.

**Barchart:** **30K+** US stocks and global ADRs, plus futures. Delayed quotes, fundamentals, insider summary, analyst estimates, opinion pages with ticker search. Futures data on indices, commodities, currencies, rates. Scraper of the Barchart site.

**Nasdaq Data:** US stocks (nasdaq + nyse + other US exchanges). Internal REST API of Nasdaq.com with access to quotes, short interest (semi-monthly), financials, **13F** filings (institutional holdings), insider transactions, options chains, dividends, earnings, news, ETFs where the stock is a Top 10 Holding.

**CBOE Data:** CBOE indices (VIX, SPX, DJ, RUT), options, VX futures (VIX futures chain) + bond futures (IBHY, IBIG) and variance (VA), options with greeks, intraday **1-min** bars, market summary per exchange (BZX, BYX, EDGX, EDGA), most-active equities and options, symbol lookup, historical HV/IV.

**Investing.com:** **81K+** equities, **10K+** indices, **2.4K** currencies, **344** commodities, futures on indices/commodities/rates, **30K+** ETFs, **4K+** crypto. Global coverage. Quotes, historical OHLCV, fundamentals (income/balance/cashflow/ratios), dividends, earnings, profile. Data delayed **15-20min**. Requires `curl_cffi` for Cloudflare bypass.

**Morningstar:** **53** universes, **102K+** listings, **39** countries. Argentine CEDEARs (XBUE, 469), NYSE (XNYS, 2,343), Nasdaq (XNAS, 3,741), Frankfurt (XFRA, 14K+), Tokyo (XTKS, 3,989), Shanghai (XSHG, 2,365), Shenzhen (XSHE, 2,934), Hong Kong (XHKG, 2,757), India (XBOM, XNSE, 5K+), Korea (XKRX, 2,877), Brazil (BVMF, 2,070), BMV (XMEX, 2,233), London (XLON, 1,333), Paris (XPAR, 728), Zurich (XSWX, 507), Tel Aviv (XTAE, 546), Johannesburg (XJSE, 332), and **30+** more. **33** fields per listing: price, market cap, ratios, returns 1d/1w/1m/3m/6m/12m/36m/60m/120m, debt, dividend yield, sector, industry. Multi-currency, multi-country, multi-language.

**TradingView:** GLOBAL coverage — **100K+** stocks, **50K+** cryptos, indices, forex, bonds. Scanner API with **~300** columns (quote, pre-calculated technical indicators RSI/MACD/EMAs/SMAs/pivots, aggregated BUY/SELL ratings, valuation, financials, earnings + forecasts, analyst targets, dividends, ownership, short interest, returns). Symbol Search v3 with ISIN/CUSIP/CIK (joinable with SEC EDGAR). News Headlines (**~200** per stock, Dow Jones/Reuters/MarketBeat). HTML scraping of **16+** subpages (technicals, financials-income-statement, balance-sheet, cash-flow, options-chain, forecast, ideas). Mass SQL-like screener with filters + sort + pagination. **24** CLI modes with **4** unique HTTP endpoints.

#### Data — Regional (Argentina)

**BCRA Macro:** **1,220** total series → **638** national series (official catalog v4.0) from the Central Bank. Daily/periodic series: exchange rate (official, wholesale, MEP, CCL, blue*), reserves, monetary policy rate, BADLAR, CER, UVA, LELIQ, monetary base, M2, deposits, loans. Data since **1996**.

**Data912:** Argentine market live — local stocks, CEDEARs, bonds, bills, options, MEP, CCL. US live — stocks and volatilities. Refreshes every **20** seconds, rate limit **120 req/min**. Historical OHLCV, filter screener, fundamental data of AR companies.

**MAE:** **17** endpoints. Complete wholesale trading: fixed income (LECAPs, BONCAPs, BOPREALes, hard dollar bonds, corporate bonds), repos (CAARS pesos, CAUSD dollars by term), REPO, swaps, FORWORD, wholesale FOREX, deferred dollar (DDF), ARS-MAE index, primary auctions, institutional communications, fund flows for TIR/MD curves.

**BYMA:** **9** endpoints. Complete Argentine stock exchange: leading stock panels, CEDEARs, sovereign bonds + LECAPs/BONCAPs, corporate bonds, repos, options and SENEBI. Historical OHLCV of instruments and indices (MERVAL, BURCAP). Equity (local stocks + CEDEARs), fixed income (sovereign, LECAPs, corporate bonds), derivatives (options). Bond technical sheet with amortization schedule.

**CAFCI:** **1,152** funds and **4,615** classes active as of 2026-06. Categories: Money Market, Fixed Income, Equity, Mixed Income, PyMes, Total Return, Infrastructure, Closed Funds, ASG, RG900. JSON catalog (fees, IDs, metadata), daily XLSX snapshot (VCP, equity, market share, variations), individual markdown sheet (TNA returns per period), portfolio composition (top assets). **4** endpoints + local daily cache.

#### Brokers

**Alpaca Trading:** paper trading (free) and live trading of US stocks, crypto and options. REST API over Alpaca Broker. Market data via IEX feed. Market/limit/stop/trailing-stop orders, short selling, multi-leg options. Positions, account, watchlists, calendar. Official SDK: `alpaca-py`.

#### Tools

*(empty — backtesting tools, custom screeners, greeks calculation, etc will be added)*

---

## Compatibility

Tested with:

- Claude Code, Antigravity, Cursor, Windsurf, Gemini CLI
- Codex, OpenCode, CommandCode CLI, Kimi CLI, Trae

## License

[MIT](./LICENSE)
