---
type: principle
source:
  - "[[unix_philosophy_human_knowledge_onepager|Unix Philosophy Applied to Human Knowledge]]"
  - "[[file-folder metaphor|File-Folder Metaphor]]"
status: seed
---
# Files are storage primitives, not cognitive primitives
*○ principle*

Humans think in situations, threads, decisions, questions, open loops, and relationships — not in folders, paths, filenames, and directory trees. The file system is an implementation detail, not a mental model. Files survived because they were the only workable abstraction for computers, not because they match human cognition.

## Why it matters

This insight drives the shift from file-centric to thread-centric interfaces. Recognizing this gap between storage primitives and cognitive primitives opens the design space for [[thread-workspaces|Thread Workspaces]].

## Connections

This principle motivates [[thread-workspaces|Thread Workspaces]] and [[overlapping-contexts-replace-hierarchy|Overlapping contexts replace hierarchy]], both of which abandon rigid file trees in favor of fluid, human-shaped structures. It is closely related to [[plain-text-right-substrate-wrong-interface|Plain text is the right substrate, wrong interface]], which resolves the tension by keeping files as infrastructure while building cognitive interfaces on top. It also explains why [[structure-as-users-responsibility-fails|Structure as user's responsibility fails]] — asking users to organize files is asking them to think in a foreign language.
