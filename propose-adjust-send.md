---
type: pattern
source:
  - "[[context construction UX|Context Construction UX]]"
status: seed
---
# Propose-Adjust-Send
*◆ pattern*

The core interaction loop for context construction: the system proposes relevant context, the user quickly adjusts (add, remove, confirm), then sends the prompt. Not manual assembly, not full automation — human-guided curation in seconds.

## How it works

When the user starts a message, the system shows suggested context. The user adjusts via [[context-chips|Context Chips]], [[swipe-to-add-context|Swipe to add context]], or [[context-strength-slider|Context Strength Slider]]. Then the prompt is sent with the curated context.

## Connections

Implemented by [[context-composer|Context Composer]]. Respects [[context-must-be-adjustable-in-under-5-seconds|Context must be adjustable in under 5 seconds]]. Embodies [[context-is-curation-not-search|Context is curation, not search]]. Same philosophy as [[ai-proposes-memory-candidates|AI proposes memory candidates]] applied to context.
