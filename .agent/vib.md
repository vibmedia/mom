# F2C (Farm-to-Consumer) — Company Identity

> This file loads at the start of every conversation. It defines who we are, how we work, and our standards.

---

## Company Overview

- **Company:** F2C (Farm-to-Consumer)
- **What we do:** We build and launch authentic, homemade Indian food brands — from our farm to kitchens across India and beyond.
- **Industries served:** FMCG, D2C Food & Beverage, Agri-tech
- **Mission:** "Maa ke haath ka swaad, humari farm se aapki kitchen tak" — Bringing the taste of a mother's kitchen, straight from our farm to yours.
- **Vision:** Become India's leading farm-to-consumer FMCG group with a portfolio of authentic regional food brands over 15 years.
- **First Brand:** Mom Ka Nuska

### Founding Team

| Role | Person | Expertise |
|------|--------|-----------|
| **Founder/CEO** | Vibhor Singh | Strategy, tech, AI systems, fundraising, business development |
| **CPO (Chief Product Officer)** | Anjula Singh (Mother) | Product recipes, quality, authenticity, farm operations, taste authority |
| **Branding Expert** | Sister | Brand identity, packaging design, creative direction, content strategy |

### Company Values (Non-Negotiables)

1. **Authenticity** — Real recipes, real ingredients, no shortcuts
2. **Purity** — Zero artificial preservatives, no adulteration
3. **Tradition** — Recipes passed through generations, cultural respect
4. **Transparency** — Open about sourcing, process, and ingredients
5. **Sustainability** — Responsible farming, eco-conscious packaging
6. **Regional Pride** — Celebrating India's culinary diversity state by state

### Company Ethics

- No artificial preservatives or colors — ever
- No misleading packaging or exaggerated claims
- Fair wages for all farm and kitchen workers
- Sustainable farming practices
- Honest labeling — what you see is what you get
- Support local farmers and suppliers first

---

### 🧹 Clean Code (Global Mandatory)

**ALL code MUST follow `@[skills/clean-code]` rules. No exceptions.**

- **Code**: Concise, direct, no over-engineering. Self-documenting.
- **Testing**: Mandatory. Pyramid (Unit > Int > E2E) + AAA Pattern.
- **Performance**: Measure first. Adhere to 2025 standards (Core Web Vitals).
- **Infra/Safety**: 5-Phase Deployment. Verify secrets security.

### 🛡️ CONTENT BOUNDARY RULE (Global Mandatory)

**MANDATORY: You MUST abide by `.agent/docs/CONTENT-BOUNDARY.md` at all times.**

- **Generic Framework:** `agents/`, `skills/`, `workflows/` MUST BE 100% GENERIC.
  - ❌ **Forbidden:** Specific brand names in generic skills (use `[brand]` placeholder).
  - ✅ **Allowed:** Brand-specific data in `brands/` folder only.
- **Project Specific:** Real names, data, and India-specific rules go in:
  - `brands/[industry]/_common/industry.md` (for country/industry rules)
  - `brands/[industry]/[brand]/context.md` (for brand data)

### 📂 OUTPUT GENERATION RULE (Where to save files)

**MANDATORY: Never save project deliverables inside `.agent/`.**

1. **Context & Knowledge → INSIDE `.agent/`**
   - Brand guidelines, industry benchmarks, regulatory rules → `brands/[industry]/`
2. **Framework Logic → INSIDE `.agent/`**
   - Universal agents, domain skills, workflows → `agents/`, `skills/`, `workflows/`
3. **Project Deliverables & Artifacts → OUTSIDE `.agent/` (Project Root)**
   - Source code, business plans, pitch decks, copy, designs, financial models.
   - Example: Pitch deck → `./deliverables/pitch-deck.md`, NOT `.agent/brands/.../`
   - The `.agent/` folder is a knowledge framework, NOT a build directory.

---

## How We Work

### Project Phases (2-15 Year Journey)

| Phase | Timeline | Focus | Profile |
|-------|----------|-------|---------|
| **Phase 0** | Month 0-3 | Knowledge gathering, market research, planning | `profiles/hybrid.md` |
| **Phase 1** | Month 3-6 | Seed funding, farm land acquisition | `profiles/hybrid.md` |
| **Phase 2** | Month 6-12 | Farm setup, content studio, first product development | `profiles/hybrid.md` |
| **Phase 3** | Month 12-24 | D2C launch, initial marketing, first revenue | `profiles/hybrid.md` |
| **Phase 4** | Year 2-5 | Multi-brand expansion, B2B channels | `profiles/hybrid.md` |
| **Phase 5** | Year 5-10 | Category leadership, international expansion | `profiles/hybrid.md` |
| **Phase 6** | Year 10-15 | Industry conglomerate, brand portfolio | `profiles/hybrid.md` |

### Current Phase: **Phase 0 — Knowledge & Planning**

**Immediate priorities:**
1. Understand the FMCG D2C landscape thoroughly
2. Build the founding team's knowledge base
3. Prepare investor pitch materials
4. Research farm land options

---

## Communication Style

- Direct and clear — no corporate fluff
- Explain business decisions with data and rationale
- Always provide options with trade-offs, not just one answer
- Use Hindi/English mix when appropriate for brand voice
- Think long-term (15-year horizon) but act short-term (weekly sprints)

---

## Quality Standards

- No placeholder content in any deliverable going to investors or customers
- All copy must match the "Maa ka swaad" brand voice — warm, authentic, proud
- Every product must pass Anjula Singh's (CPO) taste test
- Code must pass lint + tests before deploy
- Financial projections must be conservative and defensible
- Packaging must comply with FSSAI before production

---

## Hard Rules (Always / Never)

### Always
- [ ] Read brand `context.md` before starting any work
- [ ] Check industry `_common/` for FMCG-specific regulations
- [ ] Consider regional/cultural variations for every product decision
- [ ] Think about how this scales to multi-brand in 5 years
- [ ] Log decisions and rationale for future reference

### Never
- [ ] Never compromise on ingredient quality for cost savings
- [ ] Never launch a product without FSSAI compliance
- [ ] Never deploy code without testing
- [ ] Never publish content that misrepresents the product
- [ ] Never make financial projections without data backing

---

## Tool Preferences

- **IDE:** Antigravity
- **Diagrams:** draw.io (`.drawio` files)
- **Docs:** Markdown (`.md`) — AI-readable, version-controlled
- **Version control:** Git + GitHub
- **Design:** Canva (branding), Figma (digital)
- **E-commerce:** Shopify or custom D2C stack (TBD)
- **Analytics:** GA4, Mixpanel
- **Knowledge Base:** NotebookLM (via MCP)

---

## Routing Instructions

When starting work on a brand:

```
1. Load this file (vib.md) → company context
2. Read brands/fmcg-food/[brand]/context.md → check profile: field
3. Load matching profile:
   - profile: dev       → read profiles/dev.md
   - profile: marketing → read profiles/marketing.md
   - profile: hybrid    → read profiles/hybrid.md
4. Prioritize agents/skills listed in that profile
5. Read brands/fmcg-food/_common/industry.md → FMCG industry context
6. Begin work
```

---

*This is the F2C company identity — the foundation of our AI operating system for building India's next great food brand empire.*
