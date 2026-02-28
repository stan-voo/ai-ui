---
type: principle
source:
  - "[[governed_memory_pitch|Governed Memory for the AI Era]]"
status: seed
---
# Memory is governance, not storage
*○ principle*

The bottleneck in knowledge work is no longer capturing information. It is deciding what deserves to become memory. Memory is governance — the act of confirming, validating, and promoting knowledge — not the act of storing data. Automatic AI summarization is untrustworthy without this governance layer.

## Why it matters

This is the core thesis of the entire product vision. It reframes the problem from "how to store more" to "how to decide what matters." Governance includes both explicit acts (confirming a memory in review) and implicit behavioral signals (using a piece of knowledge without correction). Both are human decisions — one deliberate, one behavioral. See [[implicit-validation-signals|Implicit Validation Signals]].

## Connections

This principle drives the design of [[human-in-the-loop-promotion|Human-in-the-loop promotion]], [[ai-proposes-memory-candidates|AI proposes memory candidates]], and [[implicit-validation-signals|Implicit Validation Signals]], ensuring that AI surfaces candidates but humans — through explicit or implicit action — make the final call. It directly addresses the problem described in [[ai-memory-is-unreviewed|AI memory is unreviewed]], where ungoverned AI memory degrades trust over time. The output of governance is the [[trusted-knowledge-layer|Trusted Knowledge Layer]] — a body of knowledge users can actually rely on.
