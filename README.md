# 🧠 OpenClaw Master Skills

<div align="center">

<a href="https://myclaw.ai">
  <img src="https://img.shields.io/badge/Powered%20by-MyClaw.ai-blue?style=for-the-badge" alt="Powered by MyClaw.ai" />
</a>
<img src="https://img.shields.io/badge/Updated-Weekly-green?style=for-the-badge" alt="Weekly Updates" />

**Languages:**
[English](README.md) · [中文](README.zh-CN.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Русский](README.ru.md) · [日本語](README.ja.md) · [Italiano](README.it.md) · [Español](README.es.md)

</div>

---

## 🤖 Powered by [MyClaw.ai](https://myclaw.ai)

**[MyClaw.ai](https://myclaw.ai)** is an AI personal assistant platform that gives every user a fully-featured AI agent running on a dedicated server. OpenClaw Master Skills is our curated, weekly-updated collection of the best skills from across the ecosystem — hand-picked to help your AI agent do more.

> 🌐 **Try MyClaw.ai**: [https://myclaw.ai](https://myclaw.ai)

---

## 📦 Skill Index

| Skill | Description | Category | Source | Added |
|---|---|---|---|---|
| [`openclaw-guardian`](skills/openclaw-guardian/) | 🛡️ Gateway watchdog with auto-repair & git rollback | DevOps | [GitHub](https://github.com/LeoYeAI/openclaw-guardian) | 2026-03-02 |
| [`pdf`](skills/pdf/) | Use this skill whenever the user wants to do anything with PDF files. This includes reading or extracting text/tables fr | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`docx`](skills/docx/) | Use this skill whenever the user wants to create, read, edit, or manipulate Word documents (.docx files). Triggers inclu | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`xlsx`](skills/xlsx/) | Use this skill any time a spreadsheet file is the primary input or output. This means any task where the user wants to:  | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`pptx`](skills/pptx/) | Use this skill any time a .pptx file is involved in any way — as input, output, or both. This includes: creating slide d | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`skill-creator`](skills/skill-creator/) | Create new skills, modify and improve existing skills, and measure skill performance. Use when users want to create a sk | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`brand-guidelines`](skills/brand-guidelines/) | Applies Anthropic's official brand colors and typography to any sort of artifact that may benefit from having Anthropic' | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`webapp-testing`](skills/webapp-testing/) | Toolkit for interacting with and testing local web applications using Playwright. Supports verifying frontend functional | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`canvas-design`](skills/canvas-design/) | Create beautiful visual art in .png and .pdf documents using design philosophy. You should use this skill when the user  | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`mcp-builder`](skills/mcp-builder/) | Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services | AI Tools | [GitHub](https://github.com/anthropics/skills) | 2026-03-02 |
| [`brainstorming`](skills/brainstorming/) | You MUST use this before any creative work - creating features, building components, adding functionality, or modifying  | Productivity | [GitHub](https://github.com/obra/superpowers) | 2026-03-02 |
| [`systematic-debugging`](skills/systematic-debugging/) | Use when encountering any bug, test failure, or unexpected behavior, before proposing fixes | Productivity | [GitHub](https://github.com/obra/superpowers) | 2026-03-02 |
| [`test-driven-development`](skills/test-driven-development/) | Use when implementing any feature or bugfix, before writing implementation code | Productivity | [GitHub](https://github.com/obra/superpowers) | 2026-03-02 |
| [`writing-plans`](skills/writing-plans/) | Use when you have a spec or requirements for a multi-step task, before touching code | Productivity | [GitHub](https://github.com/obra/superpowers) | 2026-03-02 |
| [`executing-plans`](skills/executing-plans/) | Use when you have a written implementation plan to execute in a separate session with review checkpoints | Productivity | [GitHub](https://github.com/obra/superpowers) | 2026-03-02 |
| [`seo-audit`](skills/seo-audit/) | When the user wants to audit, review, or diagnose SEO issues on their site. Also use when the user mentions "SEO audit," | Marketing | [GitHub](https://github.com/coreyhaines31/marketingskills) | 2026-03-02 |
| [`copywriting`](skills/copywriting/) | When the user wants to write, rewrite, or improve marketing copy for any page — including homepage, landing pages, prici | Marketing | [GitHub](https://github.com/coreyhaines31/marketingskills) | 2026-03-02 |
| [`content-strategy`](skills/content-strategy/) | When the user wants to plan a content strategy, decide what content to create, or figure out what topics to cover. Also  | Marketing | [GitHub](https://github.com/coreyhaines31/marketingskills) | 2026-03-02 |
| [`vercel-react-best-practices`](skills/vercel-react-best-practices/) | React and Next.js performance optimization guidelines from Vercel Engineering. This skill should be used when writing, r | Frontend | [GitHub](https://github.com/vercel-labs/agent-skills) | 2026-03-02 |
| [`web-design-guidelines`](skills/web-design-guidelines/) | Review UI code for Web Interface Guidelines compliance. Use when asked to "review my UI", "check accessibility", "audit  | Frontend | [GitHub](https://github.com/vercel-labs/agent-skills) | 2026-03-02 |
| [`supabase-postgres-best-practices`](skills/supabase-postgres-best-practices/) | Postgres performance optimization and best practices from Supabase. Use this skill when writing, reviewing, or optimizin | Database | [GitHub](https://github.com/supabase/agent-skills) | 2026-03-02 |

> More skills added every Monday. [Submit yours →](../../issues/new?template=submit-skill.md)

---

## 🚀 How to Install

```bash
# Install a single skill via ClaWHub
clawhub install <skill-name>

# Or clone and copy manually
git clone https://github.com/LeoYeAI/openclaw-master-skills.git
cp -r openclaw-master-skills/skills/<skill-name> ~/.openclaw/workspace/skills/
```

## 📬 Submit a Skill

[Open a Submit Skill issue](../../issues/new?template=submit-skill.md) or open a Pull Request with your skill folder under `skills/`.

**Review criteria:** valid `SKILL.md` · clear purpose · no hardcoded credentials · works on standard OpenClaw

## 📅 Weekly Updates

See [CHANGELOG.md](CHANGELOG.md) — updated every Monday.

## 🔍 How We Collect

Every week our script scans:
- **[skills.sh](https://skills.sh)** — top leaderboard skills
- **GitHub** — repos tagged `openclaw-skill`
- **[ClaWHub](https://clawhub.ai)** — latest published skills

Validated, tested, merged, and pushed automatically.

## License

MIT © [MyClaw.ai](https://myclaw.ai)
