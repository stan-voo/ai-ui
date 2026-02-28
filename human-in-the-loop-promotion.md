---
type: pattern
source:
  - "[[governed_memory_pitch|Governed Memory for the AI Era]]"
status: seed
---
# Human-in-the-Loop Promotion
*◆ pattern*

Users review AI-proposed memory candidates via lightweight confirmation: swipe, yes/no, voice confirmation. Only confirmed items become trusted memories. The interaction must be fast enough that users actually do it — not a chore, but a quick daily practice.

## How it works

A queue of proposed memories appears. The user swipes right to confirm, left to reject, or taps to edit. Confirmed items enter [[trusted-knowledge-layer|Trusted Knowledge Layer]]. Rejected items stay in [[immutable-raw-layer|Immutable Raw Layer]] but don't influence future context.

Explicit review is the strongest single governance signal — but it is one mechanism among several. When users don't review, [[implicit-validation-signals|Implicit Validation Signals]] (viewing, reusing, not correcting) still accumulate trust over time.

## Connections

Implements [[memory-is-governance-not-storage|Memory is governance, not storage]]. Processes candidates from [[ai-proposes-memory-candidates|AI proposes memory candidates]]. Builds [[trusted-knowledge-layer|Trusted Knowledge Layer]]. Uses same swipe mechanic as [[swipe-to-add-context|Swipe to add context]]. Complemented by [[implicit-validation-signals|Implicit Validation Signals]] for passive governance.
