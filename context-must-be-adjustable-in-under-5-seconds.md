---
type: principle
source:
  - "[[context construction UX|Context Construction UX]]"
status: seed
---
# Context must be adjustable in under 5 seconds
*○ principle*

If context adjustment takes longer than 5 seconds, users will skip it, trust automatic retrieval, or revert to copy-paste. Speed is everything. The interaction must be so fast that curating context feels effortless, not like an additional task.

## Why it matters

This is the key design constraint for the [[context-composer|Context Composer]]. Any solution that slows users down will be abandoned, regardless of how powerful it is. Speed is the non-negotiable.

## Connections

This principle constrains the design of [[context-composer|Context Composer]], [[context-chips|Context Chips]], [[swipe-to-add-context|Swipe to add context]], and [[context-strength-slider|Context Strength Slider]] — each of which must meet the five-second bar or be redesigned. It explains why [[propose-adjust-send|Propose → Adjust → Send]] must be the core loop: proposing a default context and letting users adjust it is the only way to hit that speed target consistently.
