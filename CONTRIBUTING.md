# Contributing

Thanks for helping keep this list useful. Pull requests and issues are both fine — an issue with a link is enough if you'd rather not open a PR.

## Inclusion criteria

An entry belongs here if it is:

1. **Relevant** — built for Magento 2, Adobe Commerce or Mage-OS. General-purpose tools are accepted only when they earn their place in a Magento workflow, and are marked 🧭.
2. **AI-related** — an agent skill, MCP server, LLM-powered module, AI-oriented CLI, starter kit, or service. A plain Magento module with no AI angle does not belong here.
3. **Publicly usable** — a public repository, package or product page. No dead links, no private betas, no "coming soon".

Self-promotion is welcome, as long as the entry meets the criteria and the description is honest.

## Entry format

One line per project, **alphabetical within its group**:

```md
- **[project-name](https://github.com/OWNER/REPO)** ![stars](https://img.shields.io/github/stars/OWNER/REPO?style=flat-square&label=&color=555) — What it does, in one sentence.
```

Rules:

- **Descriptions come from the project itself** — its GitHub description, README or site meta description. Trim and tidy, but do not invent features. This is the whole reason the list is trustworthy.
- One sentence, ending with a period. No marketing copy, no "the best", no "revolutionary".
- Drop the star badge for non-GitHub entries and mark them ☁️.
- Add a type marker (see the legend in the README) only when the entry sits in a section where its type is not obvious — e.g. a 🧩 module listed under MCP Servers.
- Keep the name as the project publishes it, and match the owner's exact casing in URLs.

## Choosing a section

Sections group by **what a tool is**, not by who made it:

| Section | Belongs there if… |
|---|---|
| 🎓 Agent Skills & Subagents | it's prompts/skills/subagents you point a coding agent at |
| 🔌 MCP Servers | it speaks the Model Context Protocol |
| 🧩 Magento Modules | it installs into the store and merchants use it |
| 🔍 SEO, AEO & LLM Discoverability | it makes the store legible to answer engines and shopping agents |
| 🖥 CLI & Developer Tooling | it's a standalone binary/script for developers |
| 📦 Starter Kits & Templates | it's a project you clone to start from |
| ☁️ Hosted & Commercial | it's a paid or hosted service |
| 📚 Reading & Resources | it's an article, guide or methodology |

When a vendor ships several projects, they still get filed by type. A one-line lead-in (`> **Vendor** ships …`) keeps the suite visible.

If an entry genuinely fits two sections, put it in the primary one and add a `See also` cross-reference from the other.

## Before you open the PR

- Check the link resolves (`curl -sIL -o /dev/null -w '%{http_code}\n' <url>` should end in `200`).
- Check the project isn't already listed under a different name.
- One project per commit line keeps the diff readable.
