---
type: pattern
source:
  - "[[ai-memory-validator-onepager|AI Memory Validator]]"
status: seed
---
# Proactive Memory Review
*◆ pattern*

Memory items are surfaced to the user on a schedule (daily or weekly), not buried in settings. New or changed items are prioritized. The interaction is designed for mobile: swipe to confirm, tap to edit, dismiss to delete. Budget: under two minutes a day.

## How it works

The app surfaces a queue of memory items needing review. New items from recent conversations appear first. Changed or potentially stale items come next. The user works through them with swipe gestures.

Daily review is the strongest governance signal — but history shows most people don't sustain daily reviews of anything. The design must make review so frictionless it doesn't feel like a task. In corporate contexts, review can be mandated. In personal contexts, the system must still work without it — [[implicit-validation-signals|Implicit Validation Signals]] provide governance through normal usage when explicit review doesn't happen.

## Connections

Addresses [[ai-memory-is-unreviewed|AI memory is unreviewed]]. Uses [[cascading-validation|Cascading Validation]] for change propagation. Implements [[anti-automation-pro-sovereignty|Anti-automation, pro-sovereignty]]. Produces [[trusted-knowledge-layer|Trusted Knowledge Layer]]. Complemented by [[implicit-validation-signals|Implicit Validation Signals]] when users skip review.
