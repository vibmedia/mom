# F2C Framework — Architecture

> AI Operating System for Farm-to-Consumer FMCG Food Brands

---

## 📋 Overview

The F2C Framework is a specialized AI agent toolkit for building and scaling FMCG food brands in India. It consists of:

- **20 Specialist Agents** — Role-based AI personas (5 custom FMCG + 15 core)
- **64 Skills** — Domain knowledge modules (12 custom FMCG + 52 core)
- **21 Slash Commands** — Executable workflows (6 custom FMCG + 15 core)

---

## 🏗️ Directory Structure

```plaintext
.agent/
├── vib.md                   # Company identity (loads first)
├── telos.md                 # Framework tracker
├── ARCHITECTURE.md          # This file
├── profiles/                # Project-type routing (3 profiles)
├── agents/                  # 20 Specialist Agents
├── skills/                  # 64 Skills (tagged: dev|marketing|shared)
├── workflows/               # 21 Slash Commands
├── brands/                  # Industry → Brand context
│   └── fmcg-food/
│       ├── _common/industry.md    # FMCG India market data
│       └── mom-ka-nuska/          # First brand
│           ├── context.md         # Brand identity
│           └── todo.md            # Phased roadmap
├── docs/                    # Authoring guides
├── rules/                   # Global rules
└── scripts/                 # Validation scripts
```

---

## 🤖 Agents (20)

### FMCG Custom Agents (5)

| Agent | Focus | Team Member | Skills Used |
|-------|-------|-------------|-------------|
| `fmcg-brand-strategist` | Brand positioning, USP, investor pitch | Vibhor | d2c-brand-building, fmcg-market-intelligence, fmcg-funding-pitch |
| `d2c-growth-hacker` | Digital marketing, influencer, growth | All | d2c-influencer-marketing, d2c-content-strategy, paid-ads |
| `fmcg-operations-manager` | Recipe SOPs, compliance, packaging | Anjula (Mom) | fmcg-product-development, d2c-packaging-design, fmcg-legal-compliance |
| `fmcg-finance-advisor` | Funding, accounting, legal structure | Vibhor | fmcg-funding-pitch, fmcg-legal-compliance, pricing-strategy |
| `fmcg-content-creator` | Farm storytelling, social, UGC | Sister | d2c-content-strategy, social-content, copywriting |

### Core Agents (15)

| Agent | Focus | Skills Used |
|-------|-------|-------------|
| `orchestrator` | Multi-agent coordination | behavioral-modes |
| `project-planner` | Discovery, task planning | brainstorming, plan-writing, architecture |
| `frontend-specialist` | Web UI/UX (D2C website) | frontend-design, nextjs-react-expert, tailwind-patterns |
| `backend-specialist` | API, business logic | api-patterns, nodejs-best-practices, database-design |
| `database-architect` | Schema, SQL | database-design |
| `devops-engineer` | CI/CD, Docker | deployment-procedures |
| `security-auditor` | Security compliance | — |
| `test-engineer` | Testing strategies | testing-patterns |
| `debugger` | Root cause analysis | systematic-debugging |
| `seo-specialist` | Ranking, visibility | seo-fundamentals, geo-fundamentals |
| `documentation-writer` | Docs, manuals | documentation-templates |
| `product-manager` | Requirements, user stories | plan-writing, brainstorming |
| `product-owner` | Strategy, backlog, MVP | plan-writing |
| `code-reviewer` | Code quality review | clean-code |
| `explorer-agent` | Codebase analysis | — |

---

## 🧩 Skills (64)

### FMCG Custom Skills (12)

| Skill | Category | Description |
|-------|----------|-------------|
| `fmcg-market-intelligence` | Strategy | TAM/SAM/SOM, SWOT, competitor analysis |
| `d2c-brand-building` | Strategy | Brand identity, USP, moat, 4P marketing |
| `fmcg-funding-pitch` | Finance | Seed pitch, unit economics, investor landscape |
| `fmcg-legal-compliance` | Operations | FSSAI, GST, trademark, incorporation, CA |
| `fmcg-farm-setup` | Operations | Land selection, kitchen unit, content studio |
| `fmcg-product-development` | Operations | Recipe SOPs, regional palate, shelf-life |
| `d2c-packaging-design` | Operations | Format, FSSAI labels, print specs |
| `d2c-influencer-marketing` | Marketing | Barter deals, affiliate, campaign playbook |
| `fmcg-pricing-offers` | Marketing | Pricing psychology, offers, upselling |
| `d2c-content-strategy` | Marketing | Content pillars, YouTube, UGC |
| `d2c-website-strategy` | Marketing | Location-first UX, geo-product routing |
| `fmcg-b2b-integration` | Strategy | White-label, HoReCa, marketplace, distributor |

### Marketing & CRO Skills (18)

| Skill | Description |
|-------|-------------|
| `page-cro` | Landing page conversion |
| `signup-flow-cro` | Registration optimization |
| `form-cro` | Lead/order form optimization |
| `popup-cro` | Email capture popups |
| `copywriting` | Marketing copy |
| `copy-editing` | Edit existing copy |
| `email-sequence` | Automated email flows |
| `social-content` | Social media content |
| `content-strategy` | Content planning |
| `paid-ads` | Google, Meta ad campaigns |
| `ad-creative` | Bulk ad creative generation |
| `analytics-tracking` | GA4, GTM setup |
| `ab-test-setup` | Experiment design |
| `referral-program` | Referral/affiliate programs |
| `marketing-ideas` | Growth ideas |
| `marketing-psychology` | Consumer behavior |
| `launch-strategy` | Product launches |
| `pricing-strategy` | Pricing, packaging |

### SEO Skills (6)

| Skill | Description |
|-------|-------------|
| `seo-fundamentals` | E-E-A-T, Core Web Vitals |
| `seo-audit` | Technical SEO audit |
| `ai-seo` | AI search optimization |
| `geo-fundamentals` | Generative Engine Optimization |
| `programmatic-seo` | Scaled page generation |
| `schema-markup` | Structured data / JSON-LD |
| `site-architecture` | URL structure, navigation |

### Dev & Infrastructure Skills (17)

| Skill | Description |
|-------|-------------|
| `nextjs-react-expert` | React & Next.js |
| `tailwind-patterns` | Tailwind CSS v4 |
| `frontend-design` | UI/UX patterns |
| `api-patterns` | REST, GraphQL |
| `nodejs-best-practices` | Node.js |
| `python-patterns` | Python |
| `database-design` | Schema design |
| `deployment-procedures` | CI/CD |
| `server-management` | Infrastructure |
| `testing-patterns` | Jest, Vitest |
| `systematic-debugging` | Troubleshooting |
| `verification-before-completion` | Evidence before claims |
| `clean-code` | Coding standards |
| `data-analysis` | SQL, pandas, charts |
| `bash-linux` | Linux commands |
| `powershell-windows` | Windows PowerShell |
| `documentation-templates` | Doc formats |

### Framework Skills (10)

| Skill | Description |
|-------|-------------|
| `app-builder` | Full-stack scaffolding |
| `architecture` | System design |
| `plan-writing` | Task planning |
| `brainstorming` | Socratic questioning |
| `executing-plans` | Batch execution |
| `behavioral-modes` | Agent modes |
| `intelligent-routing` | Auto agent selection |
| `prompt-engineering` | System prompts, LLM optimization |
| `github-mcp` | GitHub automation |
| `notebooklm-rag` | NotebookLM RAG |

---

## 🔄 Workflows (21)

### FMCG Custom Workflows (6)

| Command | Description |
|---------|-------------|
| `/launch-brand` | End-to-end brand launch (9 steps) |
| `/new-product-intake` | Recipe → listing (9 steps) |
| `/influencer-campaign` | Budget → ROI report (7 steps) |
| `/funding-prep` | Financial model → investor outreach (7 steps) |
| `/market-research` | TAM → positioning (7 steps) |
| `/farm-setup` | Land → operational farm (7 steps) |

### Core Workflows (15)

| Command | Description |
|---------|-------------|
| `/brainstorm` | Socratic discovery |
| `/create` | Create new features |
| `/create-prd` | Product Requirements Doc |
| `/debug` | Debug issues |
| `/deploy` | Deploy application |
| `/enhance` | Improve existing code |
| `/orchestrate` | Multi-agent coordination |
| `/plan` | Task breakdown |
| `/preview` | Preview changes |
| `/status` | Check project status |
| `/test` | Run tests |
| `/ui-ux-pro-max` | Design with 50 styles |
| `/update` | Sync system after changes |
| `/audit-goals` | Goal gap analysis |
| `/system-check` | System health check |

---

## 🎯 Quick Reference

| Need | Agent | Skills |
|------|-------|--------|
| **Brand strategy** | `fmcg-brand-strategist` | d2c-brand-building, fmcg-market-intelligence |
| **Marketing/growth** | `d2c-growth-hacker` | d2c-influencer-marketing, paid-ads |
| **Product/recipes** | `fmcg-operations-manager` | fmcg-product-development, d2c-packaging-design |
| **Finance/legal** | `fmcg-finance-advisor` | fmcg-funding-pitch, fmcg-legal-compliance |
| **Content/social** | `fmcg-content-creator` | d2c-content-strategy, social-content |
| **D2C website** | `frontend-specialist` | nextjs-react-expert, frontend-design |
| **API/backend** | `backend-specialist` | api-patterns, nodejs-best-practices |
| **SEO** | `seo-specialist` | seo-audit, ai-seo, schema-markup |
| **Planning** | `project-planner` | brainstorming, plan-writing |
| **Debug** | `debugger` | systematic-debugging |

---

## 📊 Statistics

| Metric | Value |
|--------|-------|
| **Total Agents** | 20 (5 FMCG + 15 core) |
| **Total Skills** | 64 (12 FMCG + 52 core) |
| **Total Workflows** | 21 (6 FMCG + 15 core) |
| **Profiles** | 3 (dev, marketing, hybrid) |
| **Brands** | 1 (Mom Ka Nuska) |
| **Industry** | 1 (FMCG Food India) |

---

## 📖 Docs

| Document | Purpose |
|----------|---------|
| `docs/BUILDING-AGENTS.md` | How to create agents |
| `docs/BUILDING-SKILLS.md` | How to create skills |
| `docs/BUILDING-WORKFLOWS.md` | How to create workflows |
| `docs/COMBINING-COMPONENTS.md` | How components work together |
| `docs/CONTENT-BOUNDARY.md` | Rules for content separation |
| `docs/FOOD-SYSTEM-RULES.md` | FMCG-specific system rules |
| `docs/workflow-coverage-map.md` | Workflow→agent→skill mapping |

---

*Last updated: April 2026 | F2C Framework v1.0*
