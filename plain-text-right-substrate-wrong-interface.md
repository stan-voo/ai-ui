---
type: principle
source:
  - "[[unix_philosophy_human_knowledge_onepager|Unix Philosophy Applied to Human Knowledge]]"
status: seed
---
# Plain text is the right substrate, wrong interface
*○ principle*

Plain text (Markdown) is the right substrate for knowledge: portable, versionable, vendor-independent, searchable. But files and CLI are the wrong interface for human cognition. The missing layer is not more tooling — it is memory governance and thread-centric context built on top of plain text.

## Why it matters

This resolves the tension between sovereignty (plain text) and usability (human-native interfaces). You don't have to choose — you layer the interface on top of the substrate.

## Connections

This principle reconciles the Unix philosophy with [[humans-think-in-threads-not-files|Humans think in threads, not files]], honoring the durability of plain text while acknowledging that humans need richer interaction models. It serves as the foundation for [[four-layer-architecture|Four-Layer Architecture]], where plain text sits at the base and governance, context, and interface layers are built above it. In this framing, files become infrastructure per [[file-folder-metaphor-is-transitional|File-folder metaphor is transitional]] — essential plumbing, but invisible to the user.
