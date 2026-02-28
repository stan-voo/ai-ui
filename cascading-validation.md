---
type: pattern
source:
  - "[[ai-memory-validator-onepager|AI Memory Validator]]"
status: seed
---
# Cascading Validation
*◆ pattern*

When you change something significant in your AI's model (a goal, a job, a relationship status), the system shows you everything downstream that's affected. Change "I work at Company X" and it flags every memory item that referenced that job. This prevents stale context from compounding silently.

## How it works

The system maintains a dependency graph of memory items. When a core fact is updated, all items referencing it are flagged for re-review. The user confirms, updates, or removes each affected item.

## Connections

Directly addresses [[context-rot|Context rot]]. Part of [[proactive-memory-review|Proactive Memory Review]]. Enables trust in [[trusted-knowledge-layer|Trusted Knowledge Layer]]. Future extension to [[cross-system-identity-layer|Cross-System Identity Layer]].
