---
type: principle
source:
  - "[[context-engineering-2026-chatgpt-deep research-report|Context Engineering 2026 Deep Research Report]]"
status: seed
---
# Effective Context Length << Nominal Context Length
*○ principle*

A model advertising a 1M-token context window does not mean it can usefully process 1M tokens. Benchmarks (RULER, L-Eval, ∞Bench) consistently show that recall, precision, and reasoning quality degrade well before the nominal limit is reached. Anthropic explicitly describes this as [[context-rot|context rot]] — the transformer's all-to-all attention pattern means token interaction costs grow quadratically, and adding tokens can actually *reduce* output quality.

## The implication

"Just make the window bigger" does not solve the context problem. Even with multi-million token windows (Llama 4, Gemini), the need for curation, compression, and intelligent selection remains. This is the strongest technical argument for why [[context-composer|Context Composer]] matters: the value isn't in fitting more in — it's in choosing what belongs.

## Supporting evidence

- **RULER** — expands evaluation beyond needle-in-a-haystack to aggregation and multi-hop tracing; models that "pass NIAH" still fail deeper reasoning tasks
- **L-Eval** — human-labelled evaluations showing naive string-overlap metrics fail at long lengths
- **∞Bench** — targets 100K+ token tasks and finds simple passage retrieval insufficient for global understanding
- **LongLoRA** — quantifies the training cost growth of extending context, showing it's expensive even for providers
- **Context compression research** (LLMLingua-2, Selective Context) — demonstrates that smart compression can preserve task performance while dramatically reducing tokens

## Connections

Underpins [[context-rot|Context rot]] at the model level. Validates [[context-is-curation-not-search|Context is curation, not search]] — bigger windows don't eliminate the need to choose. Relevant to [[context-strength-slider|Context Strength Slider]] — the "deep" setting needs to be smart about what it includes, not just include everything. Related to [[lost-in-the-middle-effect|Lost in the middle effect]] — even within the "effective" range, position matters.
