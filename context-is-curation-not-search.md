---
type: principle
source:
  - "[[context construction UX|Context Construction UX]]"
status: seed
---
# Context is curation, not search
*○ principle*

When a user continues a thread, they're implicitly answering: What is the goal right now? Which past decisions matter? Which conversations matter? What should the AI ignore? This is curation, not search. The UI must support rapid curation of context — selecting, confirming, removing — not keyword-based retrieval.

## Why it matters

Search finds text; curation assembles meaning. Existing tools conflate the two. As [[when-should-this-knowledge-be-used|When should this knowledge be used?]] puts it: you don't need to organize if you can assemble context on demand. Treating context as curation changes the entire UX paradigm from "find the right file" to "confirm the right focus."

## Connections

This is the philosophical foundation of [[context-composer|Context Composer]], which treats context assembly as an intentional act of curation rather than a passive retrieval step. It contrasts sharply with [[retrieval-is-context-blind|Retrieval is context-blind]], where RAG systems retrieve text without understanding relevance to the user's current goal. The curation model is implemented concretely through [[context-chips|Context Chips]] and [[swipe-to-add-context|Swipe to add context]], which give users fast, tactile control over what enters the conversation.
