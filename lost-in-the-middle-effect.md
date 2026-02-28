---
type: problem
source:
  - "[[context-engineering-2026-chatgpt-deep research-report|Context Engineering 2026 Deep Research Report]]"
status: seed
---
# Lost in the Middle Effect
*△ problem*

LLMs underuse information placed in the middle of their context window. Evidence at the beginning and end of context gets disproportionate attention, while mid-context material is effectively invisible — even when it contains the correct answer.

This is an empirically documented position bias, not a theoretical concern. The "Lost in the Middle" paper showed that models can fail to use relevant information simply because of where it appears in the token sequence.

## Why it matters for context curation

This makes context ordering a design variable, not a cosmetic choice. Two identical sets of context chips, arranged differently, can produce meaningfully different AI outputs. A [[context-composer|Context Composer]] that understands this can place high-priority context where the model will actually attend to it — a feature invisible to users but valuable in practice.

It also means "just stuff everything in" fails even when the window is large enough. More context can mean worse results if the arrangement is wrong. This directly supports the case for [[context-is-curation-not-search|curation over search]].

## Connections

Compounds [[context-rot|Context rot]] — position bias means even non-stale context can be functionally invisible. Validates [[effective-vs-nominal-context-length|effective context length << nominal context length]]. Relevant to [[context-strength-slider|Context Strength Slider]] design — "minimal" mode isn't just fewer tokens, it's better-placed tokens. Motivates why [[propose-adjust-send|Propose → Adjust → Send]] is more than a trust mechanism — it's a quality mechanism.
