# Wardley Map — AI Business Model Evolution

**User Anchor:** SMB seeking business outcomes from AI (leads, sales, cost reduction)  
**Date:** February 2026  
**Context:** Mapping the AI monetization landscape to identify strategic positioning for a bootstrapped founder with e-commerce, marketing, and automation expertise.

---

## Axes

- **Y-axis (vertical):** Value chain visibility — top is user-facing, bottom is invisible infrastructure
- **X-axis (horizontal):** Evolution — Genesis → Custom → Product → Commodity

---

## Components (top to bottom)

### User-Visible Layer

| Component | Evolution Stage | Position | Notes |
|---|---|---|---|
| **Business Outcomes** | Custom | Top | The actual user need — leads, sales, cost reduction. Not "AI." |
| **AI Education** | Genesis | High | Workshops, audits, implementation programs. Low competition, immediate revenue. |
| **AI Consulting** | Genesis–Custom | High | Solution design and strategy. Entry point for client relationships. |
| **Analytics Dashboards** | Product | High | Attribution, conversion tracking. High demand, under-served. |
| **Productized Services** | Custom–Product | High | Packaged offers (€299–499/mo). Recurring revenue with low marginal cost. |

### Services Layer

| Component | Evolution Stage | Position | Notes |
|---|---|---|---|
| **AI Automation Agency** | Custom | Mid-upper | Custom implementations for SMBs. Transitional phase — will commoditize. |
| **Vertical AI SaaS** | Product | Mid-upper | **Strategic sweet spot.** Repeatable, scalable, differentiated, not yet commoditized. |
| **Data & Attribution** | Product | Mid | Tracking pipelines, analytics layer. Feeds both dashboards and SaaS products. |

### Frameworks Layer

| Component | Evolution Stage | Position | Notes |
|---|---|---|---|
| **Workflow Automation** | Custom–Product | Mid | n8n, Make, Zapier. Evolving rapidly toward commodity. |
| **Agent Frameworks** | Genesis–Custom | Mid-lower | LangChain, CrewAI. Still unstable, fast-moving. |
| **Orchestration** | Custom | Mid-lower | Prompt chains, RAG patterns. Standardizing quickly. |
| **Agent Deploy Tools** | Custom | Mid-lower | The "Level 5" / platform idea. Between Custom → Product. Valid but premature without upper-layer experience. |

### Infrastructure Layer

| Component | Evolution Stage | Position | Notes |
|---|---|---|---|
| **Vector DBs** | Product | Low | Pinecone, Weaviate. Commoditizing. |
| **LLM APIs** | Product–Commodity | Low | OpenAI, Anthropic, Google. Sliding right fast. |
| **Cloud Infra** | Commodity | Bottom | AWS, Azure, GCP. Already utility. |
| **GPUs** | Commodity | Bottom | NVIDIA dominance. Capital-intensive commodity game. |

---

## Strategic Zones

### 🟢 Sweet Spot — Vertical AI SaaS (Product stage)
- Repeatable, scalable, still differentiated
- Where investors and bootstrappers both win
- Natural evolution target from services

### 🟡 Fast Money — AI Services & Agency (Custom stage)
- Immediate revenue, low barrier
- "Paid learning" — builds market knowledge
- Transitional: will compress as patterns standardize

### 🔴 Big Tech Battlefield — Infrastructure (Commodity stage)
- Capital-heavy, brutal competition
- OpenAI, Google, Microsoft, NVIDIA territory
- Not a bootstrapped founder game

---

## Key Dependencies

```
Business Outcomes
├── AI Consulting
│   └── AI Automation Agency
│       ├── Workflow Automation → Orchestration
│       ├── Agent Frameworks → LLM APIs
│       └── evolves into → Vertical AI SaaS
├── Analytics Dashboards
│   └── Data & Attribution
├── Productized Services
│   └── evolves from Agency patterns
└── AI Education
    └── feeds into Consulting relationships

Vertical AI SaaS
├── Orchestration → LLM APIs
├── Agent Frameworks → LLM APIs
└── Data & Attribution

LLM APIs
├── Cloud Infra
└── GPUs
```

---

## Evolution Dynamics

### Commoditization Pressure (→ rightward)
- LLMs, vector DBs, hosting — sliding right fast
- Agent frameworks will follow within 12–18 months
- Agencies will compress as patterns become repeatable

### Value Migration (↑ upward)
- Tech gets cheaper, outcomes become valuable
- Winning moves are UP the value chain, not down
- Advantage shifts to: data, distribution, brand, vertical expertise

### Transitional Risk
- AI agencies are a **transitional phase** — Wardley doctrine predicts custom solutions evolve into products
- Building long-term infrastructure only for agencies is risky unless tightly scoped
- The Custom → Product transition that took SaaS 3–5 years in the 2010s may compress to 12–18 months in AI

---

## Recommended Strategic Path

| Phase | Action | Timeline | Map Movement |
|---|---|---|---|
| **① AI Services** | Sell outcomes powered by AI to SMBs | Now | Enter at Custom stage, high on value chain |
| **② Productize** | Package repeating patterns into €299–499/mo offers | 6–12 months | Move rightward (Custom → Product) |
| **③ Vertical SaaS** | Build software from observed patterns across 10–30 clients | 12–24 months | Solidify in Product stage |
| **④ Platform** | Optional infrastructure play if vertical position is strong | 24+ months | Move downward only with proven distribution |

---

## Core Insight

> "Start near the user, not near the GPUs."

The instinct to go "meta/platform" is moving **down** the value chain too early. Bootstrappers win in **Custom → Product**, not in Commodity. The real battle is shifting upward — toward whoever owns the relationship with the end user and delivers measurable business outcomes.

> "Bootstrappers win in Custom → Product, not Commodity."

---

## Wardley Doctrine Applied

- **Exploit Genesis → Custom chaos:** AI is chaotic now. Services, consulting, and experimentation thrive in chaos.
- **Productize emerging patterns:** As patterns repeat across clients, turn them into products. This is the SaaS window — we are entering it now.
- **Expect commoditization:** Agents, orchestration, and deployment will become trivial. Future advantage = data + distribution + brand + vertical expertise.
- **The real shovel business:** Historically, gold rush shovel sellers were Levi's, hotels, transport — infrastructure *around* the rush, not the pickaxe. True AI shovels today = automation agencies, vertical consultants, workflow integrators.
