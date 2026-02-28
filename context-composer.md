---
type: concept
source:
  - "[[context construction UX|Context Construction UX]]"
status: seed
---
# Context Composer
*◇ concept*

The Context Composer is a pre-flight interface that opens before a user sends a prompt to an AI. It shows suggested context and lets the user rapidly adjust what the AI will consider. Think: camera focus before taking a photo. Core interaction: propose, adjust, send.

## Why it matters

Replaces the two bad options of manual copy-paste (accurate but painful) and fully automatic retrieval (easy but often wrong). Makes context construction a 5-second interaction.

## Connections

The Context Composer uses [[context-chips|Context Chips]] and [[swipe-to-add-context|Swipe to add context]] as its primary interaction patterns, giving users tactile control over what gets included. It implements the [[propose-adjust-send|Propose → Adjust → Send]] workflow and respects the constraint that [[context-must-be-adjustable-in-under-5-seconds|Context must be adjustable in under 5 seconds]]. The output of every Context Composer session is a [[context-pack|Context Pack]] — the curated bundle that actually reaches the AI.
