# skills

Colección de skills compatibles con el estándar [SKILL.md](https://skills.sh) abiertos. Desarrollados para los cursos de IA de UCEMA.

[![skills.sh](https://skills.sh/b/gauss314/skills)](https://skills.sh/gauss314/skills)


## Skills disponibles

| Skill | Descripción | Instalar |
|-------|-------------|----------|
| [BCRA Macro](./skills/bcra-macro/) | API de Estadísticas Monetarias v4.0 del BCRA: 638 series macroeconómicas. | `npx skills add gauss314/skills --skill bcra-macro` |
| [Data912](./skills/data912/) | API del mercado argentino: acciones, CEDEARs, bonos, MEP, CCL (live + OHLC). | `npx skills add gauss314/skills --skill data912` |
| [Alpha Vantage](./skills/alpha-vantage/) | API de EE.UU.: acciones, forex, crypto, 50+ indicadores técnicos, fundamental data. | `npx skills add gauss314/skills --skill alpha-vantage` |
| [Alpaca Data](./skills/alpaca-data/) | Market Data API: acciones US, crypto, opciones con historical y real-time data. Feed IEX gratis. | `npx skills add gauss314/skills --skill alpaca-data` |
| [Alpaca Trading](./skills/alpaca-trading/) | Trading API: órdenes, posiciones, cuenta para acciones, crypto y opciones. Paper trading gratis. | `npx skills add gauss314/skills --skill alpaca-trading` |
| [Yahoo Finance](./skills/yahoo-finance/) | API no oficial de Yahoo Finance: precios, históricos, fundamentales, opciones, noticias en JSON puro. | `npx skills add gauss314/skills --skill yahoo-finance` |
| [SEC Data](./skills/sec-data/) | SEC EDGAR: financial statements estructurados (income, balance, cash flow) desde XBRL JSON API. | `npx skills add gauss314/skills --skill sec-data` |
| [Finviz](./skills/finviz/) | Scraper de Finviz: datos fundamentales, técnicos, insider trading, news y screener para acciones US. Sin API oficial. | `npx skills add gauss314/skills --skill finviz` |

## Estructura

Cada skill es un directorio que sigue la estructura del estándar Agent Skills:

```
.
├── skills/
│   └── <skill-name>/
│       ├── SKILL.md           # requerido: frontmatter + instrucciones
│       ├── references/        # opcional: documentación complementaria
│       ├── scripts/           # opcional: scripts ejecutables
│       └── assets/           # opcional: plantillas, configs
├── README.md
├── LICENSE                   # MIT
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
