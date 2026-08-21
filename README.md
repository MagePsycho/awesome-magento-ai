<div align="center">

# Awesome Magento AI

**A curated list of AI tooling for Magento 2, Adobe Commerce and Mage-OS** — agent skills, MCP servers, store modules, CLIs, starter kits and services.

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg?style=flat-square)](LICENSE)

</div>

---

Entries are grouped by **what kind of thing a tool is**, not by who made it — so you can jump straight to the layer you need: skills for your coding agent, an MCP server for your store, a module your merchant will actually click on.

Every description here comes from the project's own repository or site. Star counts are live badges, never stale.

## Legend

| | Meaning |
|---|---|
| 🎓 | Agent skills / subagents (Claude Code, Codex, OpenCode, Copilot…) |
| 🔌 | MCP server |
| 🧩 | Magento module (installs into the store) |
| 🖥 | CLI or standalone tool |
| 📦 | Starter kit / template |
| ☁️ | Hosted or commercial product |
| 🧭 | Not Magento-specific, but useful in a Magento workflow |

## Contents

- [🎓 Agent Skills & Subagents](#-agent-skills--subagents)
- [🔌 MCP Servers](#-mcp-servers)
- [🧩 Magento Modules — AI in the Store](#-magento-modules--ai-in-the-store)
- [🔍 SEO, AEO & LLM Discoverability](#-seo-aeo--llm-discoverability)
- [🖥 CLI & Developer Tooling](#-cli--developer-tooling)
- [📦 Starter Kits & Templates](#-starter-kits--templates)
- [☁️ Hosted & Commercial](#-hosted--commercial)
- [📚 Reading & Resources](#-reading--resources)
- [Contributing](#contributing)
- [License](#license)

---

## 🎓 Agent Skills & Subagents

Prompt packs, skills and subagent definitions that teach a coding agent how Magento works. Drop-in — nothing installs into the store.

- **[claude-code-magento-agents](https://github.com/rubenzantingh/claude-code-magento-agents)** ![stars](https://img.shields.io/github/stars/rubenzantingh/claude-code-magento-agents?style=flat-square&label=&color=555) — Collection of Claude Code subagents designed to be used for Magento 2 development.
- **[claude-code-magento-agents (NobreTakeshi)](https://github.com/NobreTakeshi/claude-code-magento-agents)** ![stars](https://img.shields.io/github/stars/NobreTakeshi/claude-code-magento-agents?style=flat-square&label=&color=555) — 30+ specialized agents for Magento 2 development, built around expert collaboration and task delegation.
- **[claude-skills (df2k2)](https://github.com/df2k2/claude-skills)** ![stars](https://img.shields.io/github/stars/df2k2/claude-skills?style=flat-square&label=&color=555) — Heavyweight, load-on-demand reference packs for ecommerce and web development: Magento 2 (~2,700 official doc files), Hyvä, Akeneo PIM + connector, OrderGroove, Printful.
- **[claude-skills (ProxiBlue)](https://github.com/ProxiBlue/claude-skills)** ![stars](https://img.shields.io/github/stars/ProxiBlue/claude-skills?style=flat-square&label=&color=555) — Skill library for Magento 2 / Mage-OS / Hyvä plus general audit and diagnostic skills, delivered as a Claude Code plugin; authored during a live M1→M2 migration across DDEV environments.
- **[dev-skills-hub](https://github.com/ddtcorex/dev-skills-hub)** ![stars](https://img.shields.io/github/stars/ddtcorex/dev-skills-hub?style=flat-square&label=&color=555) — Extensible, flat AI skills registry for Claude Code, OpenCode, Codex and Copilot, pre-configured for Magento 2 workflows.
- **[hiberus-magento/ai-tools](https://github.com/hiberus-magento/ai-tools)** ![stars](https://img.shields.io/github/stars/hiberus-magento/ai-tools?style=flat-square&label=&color=555) — Skills spanning Magento backend modules and core architecture through to Hyvä and Adobe Commerce Storefront frontends.
- **[hyva-ai-tools](https://github.com/hyva-themes/hyva-ai-tools)** ![stars](https://img.shields.io/github/stars/hyva-themes/hyva-ai-tools?style=flat-square&label=&color=555) — Official Hyvä skills for creating Hyvä themes, modules and CMS components with an AI coding assistant.
- **[magento-ai-toolkit](https://github.com/furan917/magento-ai-toolkit)** ![stars](https://img.shields.io/github/stars/furan917/magento-ai-toolkit?style=flat-square&label=&color=555) — Collection of agents and skills for Magento.
- **[magento-claude-skills (magendooro)](https://github.com/magendooro/magento-claude-skills)** ![stars](https://img.shields.io/github/stars/magendooro/magento-claude-skills?style=flat-square&label=&color=555) — Interact with your store over REST and GraphQL directly from Claude — no MCP server needed.
- **[magento-claude-skills (staksoft)](https://github.com/staksoft/magento-claude-skills)** ![stars](https://img.shields.io/github/stars/staksoft/magento-claude-skills?style=flat-square&label=&color=555) — Module scaffolding, DI conventions, debugging and storefront performance audits for Magento 2 / Mage-OS / Adobe Commerce.
- **[magento-skills](https://github.com/tuanhaviet22/magento-skills)** ![stars](https://img.shields.io/github/stars/tuanhaviet22/magento-skills?style=flat-square&label=&color=555) — Backend-focused skills: module scaffold, `system.xml`, widgets, plugins/observers, transactional email, Hyvä template + ViewModel generators.
- **[magento2-agent-skills](https://github.com/maxnorm/magento2-agent-skills)** ![stars](https://img.shields.io/github/stars/maxnorm/magento2-agent-skills?style=flat-square&label=&color=555) — Specialized agent skills giving domain expertise across the whole Magento / Adobe Commerce development workflow.
- **[magento2-tools](https://github.com/muon-m2/magento2-tools)** ![stars](https://img.shields.io/github/stars/muon-m2/magento2-tools?style=flat-square&label=&color=555) — Claude Code plugin of skills for end-to-end Magento 2 engineering — scaffolding, review, testing, bug-fixing, deployment, auditing — built around a shared context-resolver that adapts to any project and environment.
- **[agentic-commerce-skills-plugins](https://github.com/OrcaQubits/agentic-commerce-skills-plugins)** ![stars](https://img.shields.io/github/stars/OrcaQubits/agentic-commerce-skills-plugins?style=flat-square&label=&color=555) — Agentic-commerce skills and plugins for UCP, ACP, AP2, A2A and WebMCP; see the [`magento2-commerce`](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/magento2-commerce) plugin.

### 🧭 Adjacent & general-purpose

- **[php-modernization-skill](https://github.com/netresearch/php-modernization-skill)** ![stars](https://img.shields.io/github/stars/netresearch/php-modernization-skill?style=flat-square&label=&color=555) — PHP 8.x modernization patterns — typing, attributes, PHPStan.
- **[wardenenv/ai-skills](https://github.com/wardenenv/ai-skills)** ![stars](https://img.shields.io/github/stars/wardenenv/ai-skills?style=flat-square&label=&color=555) — Agent skills for Warden, the Docker-based local development environment many Magento shops run on.
- **[claude-code-templates](https://github.com/davila7/claude-code-templates)** ![stars](https://img.shields.io/github/stars/davila7/claude-code-templates?style=flat-square&label=&color=555) — CLI for configuring and monitoring Claude Code.
- **[agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills)** ![stars](https://img.shields.io/github/stars/sickn33/agentic-awesome-skills?style=flat-square&label=&color=555) — Agent-first control plane over a 2,005+ skill catalog, with CLI, local MCP, plugins and workbench.

## 🔌 MCP Servers

### Dev-side — codebase, standards and docs

- **[magento2-dev-mcp](https://github.com/elgentos/magento2-dev-mcp)** ![stars](https://img.shields.io/github/stars/elgentos/magento2-dev-mcp?style=flat-square&label=&color=555) — MCP server to help with Magento 2 development.
- **[magento-bricklayer](https://github.com/Inchoo/magento-bricklayer)** ![stars](https://img.shields.io/github/stars/Inchoo/magento-bricklayer?style=flat-square&label=&color=555) — AI-assisted development toolkit: introspection tools, code generation and Magento knowledge exposed to coding agents over MCP.
- **[magector](https://github.com/krejcif/magector)** ![stars](https://img.shields.io/github/stars/krejcif/magector?style=flat-square&label=&color=555) — Technology-aware MCP server that builds a semantic vector index of the whole codebase (18,000+ files) and exposes 47 tools with Magento pattern detection — plugins, observers, DI preferences, layout XML.
- **[magento-coding-standard-mcp](https://github.com/Midhun-edv/magento-coding-standard-mcp)** ![stars](https://img.shields.io/github/stars/Midhun-edv/magento-coding-standard-mcp?style=flat-square&label=&color=555) — Teaches assistants Magento 2 coding standards: validate code, look up patterns, check security, apply theme rules (Hyvä, Luma, Breeze, Porto).
- **[magento-graphql-docs-mcp](https://github.com/florinel-chis/magento-graphql-docs-mcp)** ![stars](https://img.shields.io/github/stars/florinel-chis/magento-graphql-docs-mcp?style=flat-square&label=&color=555) — Local stdio MCP server for searching and retrieving Magento 2 GraphQL API documentation offline.
- **[magento.watch](https://magento.watch)** ☁️ — Free JSON API and MCP server for Magento Open Source, Adobe Commerce and Mage-OS version release dates, end-of-life schedules and PHP/MySQL/OpenSearch/Redis system requirements.
- **[n98-magerun2 `mcp:server:start`](https://netz98.github.io/n98-magerun2/command-docs/mcp/mcp-server-start/)** ![stars](https://img.shields.io/github/stars/netz98/n98-magerun2?style=flat-square&label=&color=555) 🖥 — Exposes n98-magerun2 commands as executable tools to MCP clients over stdio transport, with include/exclude patterns and command groups (`@cache`, `@database`, `@development`) controlling what a client can run.

### Store-side — catalog, orders and customers

> **Magebit** ships a core MCP module plus tool extensions.

- **[magento2-mcp-module](https://github.com/magebitcom/magento2-mcp-module)** ![stars](https://img.shields.io/github/stars/magebitcom/magento2-mcp-module?style=flat-square&label=&color=555) 🧩 — Extensible MCP module — interact with your store through any MCP-compatible AI agent.
  - **[magento2-mcp-catalog-tools](https://github.com/magebitcom/magento2-mcp-catalog-tools)** ![stars](https://img.shields.io/github/stars/magebitcom/magento2-mcp-catalog-tools?style=flat-square&label=&color=555) — Catalog tool extension for the module above.
- **[magemcp](https://github.com/magendooro/magemcp)** ![stars](https://img.shields.io/github/stars/magendooro/magemcp?style=flat-square&label=&color=555) — Exposes catalog, orders, customers and inventory as MCP tools over REST and GraphQL, with built-in PII redaction.
- **[magento2-mcp-server](https://github.com/yuriyakishin/magento2-mcp-server)** ![stars](https://img.shields.io/github/stars/yuriyakishin/magento2-mcp-server?style=flat-square&label=&color=555) 🧩 — Free MCP server for catalog, orders, customers, CMS and sales, secured with OAuth 2.1 and Magento ACL.
- **[AgentoAI](https://github.com/Genaker/AgentoAI)** ![stars](https://img.shields.io/github/stars/Genaker/AgentoAI?style=flat-square&label=&color=555) 🧩 — Magento MCP AI agent plus AI features: product content, report generation, grid filters, promotion images, product video, AI analytics.
- **[magento2-mcp](https://github.com/adwise/magento2-mcp)** ![stars](https://img.shields.io/github/stars/adwise/magento2-mcp?style=flat-square&label=&color=555) 🧩 — Lightweight Magento MCP server with store information, module status, configuration, cache and indexer tools.
  - **[magento2-mcp-catalog](https://github.com/adwise/magento2-mcp-catalog)** ![stars](https://img.shields.io/github/stars/adwise/magento2-mcp-catalog?style=flat-square&label=&color=555) — Catalog management tools and resources for the core MCP module.
  - **[magento2-mcp-hyva-cms](https://github.com/adwise/magento2-mcp-hyva-cms)** ![stars](https://img.shields.io/github/stars/adwise/magento2-mcp-hyva-cms?style=flat-square&label=&color=555) — Hyvä CMS guidance, prompts and page-editing tools for the core MCP module.

## 🧩 Magento Modules — AI in the Store

> **Mage-OS Lab** and **MinsarAI** both ship suites; their modules appear below under the job they do.

### Content & catalog generation

- **[magento2-mage-ai](https://github.com/mageprince/magento2-mage-ai)** ![stars](https://img.shields.io/github/stars/mageprince/magento2-mage-ai?style=flat-square&label=&color=555) — Generate product short/long descriptions and product images with OpenAI, Anthropic or Gemini; customizable prompts, multiple models, clean HTML output.
- **[module-catalog-data-ai](https://github.com/mage-os-lab/module-catalog-data-ai)** ![stars](https://img.shields.io/github/stars/mage-os-lab/module-catalog-data-ai?style=flat-square&label=&color=555) — Generate product descriptions and similar content with AI.
- **[magento2-cms-ai-builder](https://github.com/graycoreio/magento2-cms-ai-builder)** ![stars](https://img.shields.io/github/stars/graycoreio/magento2-cms-ai-builder?style=flat-square&label=&color=555) — Extends the CMS page editor with AI content generation and visual preview.
- **[magento2-ai-category-hero-images](https://github.com/elgentos/magento2-ai-category-hero-images)** ![stars](https://img.shields.io/github/stars/elgentos/magento2-ai-category-hero-images?style=flat-square&label=&color=555) — Generate AI hero images for categories using OpenAI.
- **[module-automatic-translation](https://github.com/mage-os/module-automatic-translation)** ![stars](https://img.shields.io/github/stars/mage-os/module-automatic-translation?style=flat-square&label=&color=555) — Automatic AI content translation for Mage-OS.
- **[mage-seo](https://github.com/florinel-chis/mage-seo)** ![stars](https://img.shields.io/github/stars/florinel-chis/mage-seo?style=flat-square&label=&color=555) — AI SEO content generation platform with hallucination detection and approval workflows.

### Admin experience

- **[module-admin-assistant](https://github.com/mage-os-lab/module-admin-assistant)** ![stars](https://img.shields.io/github/stars/mage-os-lab/module-admin-assistant?style=flat-square&label=&color=555) — AI-empowered admin experience for Magento 2.
- **[magento2-ai-admin-assistant](https://github.com/minsarai/magento2-ai-admin-assistant)** ![stars](https://img.shields.io/github/stars/minsarai/magento2-ai-admin-assistant?style=flat-square&label=&color=555) — Instant explanations for admin configuration fields via Gemini or OpenAI.
- **[magento-module-admin-grid-ai](https://github.com/tons-of-limes/magento-module-admin-grid-ai)** ![stars](https://img.shields.io/github/stars/tons-of-limes/magento-module-admin-grid-ai?style=flat-square&label=&color=555) — AI-powered filtering, sorting and column management for admin grids.
- **[Minsar Admin Toolkit](https://github.com/minsarai/chrome-extensions)** ![stars](https://img.shields.io/github/stars/minsarai/chrome-extensions?style=flat-square&label=&color=555) 🖥 — Chrome extension for the Magento 2 admin: `Ctrl+K` omni-search, one-click cache flush, dark and compact modes, environment bar. No server module needed.

### Storefront & customer

- **[magento2-cart-agent](https://github.com/minsarai/magento2-cart-agent)** ![stars](https://img.shields.io/github/stars/minsarai/magento2-cart-agent?style=flat-square&label=&color=555) — AI shopping concierge — a chat bubble that places orders for your customers.

### Forecasting, ops & security

- **[magento2-mage-ai-predict](https://github.com/mageprince/magento2-mage-ai-predict)** ![stars](https://img.shields.io/github/stars/mageprince/magento2-mage-ai-predict?style=flat-square&label=&color=555) — Demand forecasting: per-product stock forecasts from sales history, with an optional AI layer over a free built-in statistics engine.
- **[magento2-stock-sense](https://github.com/minsarai/magento2-stock-sense)** ![stars](https://img.shields.io/github/stars/minsarai/magento2-stock-sense?style=flat-square&label=&color=555) — Inventory demand forecasting — predicts stockouts, severity alerts and reorder recommendations via Gemini, OpenAI or Claude.
- **[magento2-fraud-sentinel](https://github.com/minsarai/magento2-fraud-sentinel)** ![stars](https://img.shields.io/github/stars/minsarai/magento2-fraud-sentinel?style=flat-square&label=&color=555) — Fraud detection with identity clustering, velocity tracking and automated order protection.
- **[magento2-ai-release-guardian](https://github.com/minsarai/magento2-ai-release-guardian)** ![stars](https://img.shields.io/github/stars/minsarai/magento2-ai-release-guardian?style=flat-square&label=&color=555) — Automated testing with AI failure analysis: smoke tests, full checkout flow, live progress, recommendations.
- **[magewatch-module-agent](https://github.com/krivtsuna/magewatch-module-agent)** ![stars](https://img.shields.io/github/stars/krivtsuna/magewatch-module-agent?style=flat-square&label=&color=555) — Runs inside Magento and reports what uptime pings miss: stopped cron, invalid indexers, order-rate anomalies, stuck queue consumers, unexpected PHP under `pub/`. Pairs with [MageWatch](#-hosted--commercial).

### Foundations

- **[module-ai-base](https://github.com/mage-os-lab/module-ai-base)** ![stars](https://img.shields.io/github/stars/mage-os-lab/module-ai-base?style=flat-square&label=&color=555) — Configure multiple AI backends once and select them from other modules via `AiServiceSelectorInterface`.
- **[magento2-module-ai-anthropic](https://github.com/hyva-themes/magento2-module-ai-anthropic)** ![stars](https://img.shields.io/github/stars/hyva-themes/magento2-module-ai-anthropic?style=flat-square&label=&color=555) — Anthropic Claude API implementation for the Hyvä AI framework.

## 🔍 SEO, AEO & LLM Discoverability

Making the store legible to answer engines and shopping agents, not just to Googlebot.

- **[module-seo](https://github.com/mage-os-lab/module-seo)** ![stars](https://img.shields.io/github/stars/mage-os-lab/module-seo?style=flat-square&label=&color=555) 🧩 — SEO + AEO + GEO in one: JSON-LD, Open Graph/Twitter meta, canonicals, hreflang, FAQ rich results, Speakable/LocalBusiness/Article, plus `/llms.txt`, `/llms.jsonl`, AI-crawler robots directives and `/.well-known/` manifests (UCP, `ai-plugin.json`). Every concern is an extensible provider pool.
- **[llms.txt](https://github.com/mage-os-lab/llms.txt)** ![stars](https://img.shields.io/github/stars/mage-os-lab/llms.txt?style=flat-square&label=&color=555) 🧩 — Serve an `llms.txt`, with an assistant that generates it for you.
- **[module-robots-txt-aeo](https://github.com/angeo-dev/module-robots-txt-aeo)** ![stars](https://img.shields.io/github/stars/angeo-dev/module-robots-txt-aeo?style=flat-square&label=&color=555) 🧩 — Inject AI crawler rules into `robots.txt` (OAI-SearchBot, GPTBot, Google-Extended).
- See also **[mage-seo](https://github.com/florinel-chis/mage-seo)** for AI-generated SEO content with an approval workflow.

## 🖥 CLI & Developer Tooling

- **[magecli](https://github.com/atlanticbt/magecli)** ![stars](https://img.shields.io/github/stars/atlanticbt/magecli?style=flat-square&label=&color=555) — A Magento CLI built for AI agents.
- **[MageContext](https://github.com/infinri/MageContext)** ![stars](https://img.shields.io/github/stars/infinri/MageContext?style=flat-square&label=&color=555) — Static-analysis CLI that compiles Magento 2 architecture into deterministic, AI-ready context bundles.
- **[magento2-ai-guidelines](https://github.com/fruitcake/magento2-ai-guidelines)** ![stars](https://img.shields.io/github/stars/fruitcake/magento2-ai-guidelines?style=flat-square&label=&color=555) 🧩 — Generates a `CLAUDE.md` with project context via `bin/magento ai:generate-context`; installs as a module or an n98-magerun2 module.
- **[magento2-module-generator](https://github.com/florinel-chis/magento2-module-generator)** ![stars](https://img.shields.io/github/stars/florinel-chis/magento2-module-generator?style=flat-square&label=&color=555) — Generate complete modules from natural language: LLM for intent, deterministic code generation for output — 40+ files per module.
- **[magequery](https://github.com/cresset-tools/magequery)** ![stars](https://img.shields.io/github/stars/cresset-tools/magequery?style=flat-square&label=&color=555) — Fast Rust CLI that answers "how is this codebase wired?" without booting the framework: module load order, DI resolution, events, cron, routes, config scopes and the admin permission tree, every result citing file and line. Runs in milliseconds on a checkout that was never set up — no database, no `setup:di:compile`.
- **[openclaw-magento2](https://github.com/caravanglory/openclaw-magento2)** ![stars](https://img.shields.io/github/stars/caravanglory/openclaw-magento2?style=flat-square&label=&color=555) — AI copilot in OpenClaw — inspect, diagnose and operate your store in natural language.
- **[mage-local-ai](https://github.com/MaheshLalwaani/mage-local-ai)** ![stars](https://img.shields.io/github/stars/MaheshLalwaani/mage-local-ai?style=flat-square&label=&color=555) — Offline Magento customization advisor.
- **[mageops-squad](https://github.com/omdeshpande/mageops-squad)** ![stars](https://img.shields.io/github/stars/omdeshpande/mageops-squad?style=flat-square&label=&color=555) — A team of AI agents to help manage your Magento store.
- **[mnemix](https://github.com/minsarai/mnemix)** ![stars](https://img.shields.io/github/stars/minsarai/mnemix?style=flat-square&label=&color=555) — Organisational AI memory layer for engineering teams using Claude Code.
- See also **[n98-magerun2](https://github.com/netz98/n98-magerun2)** — its [`mcp:server:start`](https://netz98.github.io/n98-magerun2/command-docs/mcp/mcp-server-start/) command turns the CLI into an MCP server; see [🔌 MCP Servers](#-mcp-servers).

## 📦 Starter Kits & Templates

> **Graycore** ships AI-ready store starters, regenerated weekly.

- **[magento2-ai-starter-hyva](https://github.com/graycoreio/magento2-ai-starter-hyva)** ![stars](https://img.shields.io/github/stars/graycoreio/magento2-ai-starter-hyva?style=flat-square&label=&color=555) — Magento Open Source + Hyvä starter, pre-wired for GitHub Codespaces, Actions and Claude Code. A prototyping baseline, explicitly not a production store.
- **[magento2-ai-starter-daffodil](https://github.com/graycoreio/magento2-ai-starter-daffodil)** ![stars](https://img.shields.io/github/stars/graycoreio/magento2-ai-starter-daffodil?style=flat-square&label=&color=555) — Magento Open Source + Daffodil Angular storefront starter with CI (`check-store`), release-please and Dependabot.

## ☁️ Hosted & Commercial

- **[Agent for Magento](https://agentformagento.com/)** — A chat where you describe what to build, change or fix in your store; a specialized agent clarifies, completes and validates the task in minutes.
- **[MageWatch](https://magewatch.io/)** — Health monitoring for Magento 2 stores built for agencies: stuck indexers, dead crons, silent order drops. Open-source in-store agent: [magewatch-module-agent](https://github.com/krivtsuna/magewatch-module-agent).
- **[Byte8 Pulsar](https://byte8.io/products/pulsar)** — Magento-aware monitoring: external synthetic uptime, real-Chromium checkout-flow testing (Luma and Hyvä presets), and an optional extension with 20 health collectors — indexer drift, cron heartbeat, queue backlog, OpenSearch state, stuck `pending_payment` orders. Catches the silent failures that still return HTTP 200. Part of the [Byte8 platform](https://byte8.io/products) alongside Orbit, Horizon and Cargoman.

## 📚 Reading & Resources

- **[Magento AI Agent: Automating Issue Resolution](https://elgentos.com/blog/magento-ai-agent-digitale-werknemer)** — elgentos on the AI agent they built to automate issue resolution and streamline workflows.
- **[ai-blueprint](https://github.com/bradtraversy/ai-blueprint)** ![stars](https://img.shields.io/github/stars/bradtraversy/ai-blueprint?style=flat-square&label=&color=555) 🧭 — A repeatable process for coding with AI while staying the architect of your project.
- **[awesome-magento-aeo](https://github.com/angeo-dev/awesome-magento-aeo)** ![stars](https://img.shields.io/github/stars/angeo-dev/awesome-magento-aeo?style=flat-square&label=&color=555) — Modules, specifications and tools that make a Magento 2 or Adobe Commerce store discoverable, readable and transactable by AI systems.

## Contributing

Found something missing? PRs and issues welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format and inclusion criteria.

## License

[CC0-1.0](LICENSE) — to the extent possible under law, contributions to this list are released into the public domain. Linked projects keep their own licenses.
