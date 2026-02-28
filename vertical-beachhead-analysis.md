---
type: action
source:
  - "[[vertical-market-research-feb2026|Vertical Market Research Feb 2026]]"
status: seed
---
# Vertical Beachhead Analysis
*▸ action*

Research into which non-developer professional verticals have the highest context assembly pain and willingness to pay for a [[context-composer|Context Composer]]-style tool.

## Core finding

Every non-developer profession that uses AI heavily exhibits the same pattern: scattered source material across multiple systems, manual re-assembly of context per AI interaction, and dangerous consequences when context is missing or stale. No tool currently helps with the *curation* step -- tools help with storage, retrieval, or generation, but not the "which pieces of context are relevant to THIS specific task" decision.

## Recommended beachhead: solo and small-firm lawyers

The strongest combination of pain, willingness to pay, and reachability points to solo and small-firm lawyers:

- **Extreme documented pain** -- court sanctions ($10K-$31K per incident), AI hallucination cases growing from 2/week to 2-3/day by late 2025, 90% of sanctioned firms are solo/small
- **Highest spending growth** -- legal tech spending surged 9.7% YoY, legal AI market at $7.2B and growing to $10B+
- **Large reachable market** -- ~350K solo practitioners in the US alone, concentrated in bar associations and legal tech communities
- **Regulatory urgency** -- courts now requiring AI disclosure, sanctions increasing, creating a forcing function for better context tools
- **Clear value prop** -- "Never send AI a legal question without the right case context again"

## Secondary targets

| Vertical | Pain level | Pay willingness | Market size | Reachability |
|----------|-----------|-----------------|-------------|-------------|
| Grant/proposal writers | Very high (88% report high stress, 50% of outputs generic) | High ($100-500/mo existing tool spend) | $2.5-4.5B proposal software market | High (concentrated communities) |
| Independent consultants | Very high (context assembly IS their work) | Very high (bill $150-500/hr) | ~750K consultants in US | Medium (fragmented) |
| Financial analysts/advisors | High (compliance risk, client-specific context) | Very high ($24K/yr Bloomberg users) | ~500K analysts+advisors in US | Medium (regulated) |
| Marketing strategists | High (88% use AI daily, brand voice drift) | Medium-high ($100-500/mo) | ~600K marketing managers in US | High (many communities) |
| Compliance officers | High (regulatory penalties) | Very high (mandatory spend) | ~300K in US, $12B RegTech market | Medium (enterprise sale) |

## Why this matters for Context Composer

The [[context-assembly-is-the-new-bottleneck|context assembly bottleneck]] is not just a developer problem. Non-technical professionals face the same fundamental challenge but with even fewer workarounds. Developers have CLI tools, config files, and MCP servers. A lawyer preparing a brief, a grant writer responding to an RFP, or a consultant assembling a client deliverable has nothing but copy-paste.

The [[propose-adjust-send|Propose-Adjust-Send]] interaction pattern maps directly to these workflows: the system proposes relevant case files, funder requirements, or client history as [[context-chips|Context Chips]]; the professional adjusts what's included; the curated [[context-pack|Context Pack]] is sent with the prompt.

## Connections

Extends [[Demand Validation Research]] with vertical-specific evidence. Informs [[Founder Roadmap]] by narrowing the target user. Reinforces [[manual-context-curation-is-hidden-labor|Manual context curation is hidden labor]] with profession-specific examples and dollar costs.
