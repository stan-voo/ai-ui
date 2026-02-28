# Playbook Map

This vault explores a single question: **What should the interface for human knowledge look like in the AI era?**

> **New here?** [[Start Here]] — a jargon-free introduction for anyone who uses AI chat.

---

## You already know this problem
*The problems*

You use AI every day. You know it could help more if it just *knew* what you know. Instead:

- [[knowledge-created-in-conversations-is-fragile|Knowledge created in conversations is fragile]] — decisions and insights are buried in AI chats and voice notes
- [[manual-context-curation-is-hidden-labor|Manual context curation is hidden labor]] — you copy-paste, re-explain, and search for old conversations constantly
- [[context-assembly-is-the-new-bottleneck|Context assembly is the new bottleneck]] — the hard part isn't storing knowledge, it's getting the right context to AI
- [[context-rot|Context rot]] — unchecked errors multiply over time; Anthropic's term for degrading recall as context grows
- [[ai-memory-is-unreviewed|AI memory is unreviewed]] — AI builds models of you that nobody audits

---

## Why current solutions don't work
*The failures*

Neither extreme works — not chat, not files, not auto-retrieval:

- [[chat-ui-is-also-not-the-answer|Chat UI is also not the answer]] — chat is linear, ephemeral, and hard to reuse
- [[files-are-storage-primitives-not-cognitive-primitives|Files are storage primitives, not cognitive primitives]] — humans think in situations, not file paths
- [[structure-as-users-responsibility-fails|Structure as user's responsibility fails]] — asking users to organize their own knowledge doesn't work under cognitive load
- [[retrieval-is-context-blind|Retrieval is context-blind]] — search finds text, not meaning
- [[no-built-in-memory-governance|No built-in memory governance]] — archives grow while understanding decays
- [[lost-in-the-middle-effect|Lost in the middle effect]] — models ignore mid-context information, making ordering a design variable
- [[context-security-surface|Context security surface]] — every piece of context is a potential attack vector

---

## The real question isn't where to store — it's what the AI should know right now
*The principles*

The fundamental question shifts from "where does this note live?" to "when should this knowledge be used?":

- [[context-is-curation-not-search|Context is curation, not search]] — assembling context is an act of curation, not keyword retrieval
- [[memory-is-governance-not-storage|Memory is governance, not storage]] — the bottleneck is deciding what matters, not storing more
- [[when-should-this-knowledge-be-used|When should this knowledge be used?]] — replaces "where should this note live?"

> You don't need to organize if you can assemble context on demand.

- [[humans-think-in-threads-not-files|Humans think in threads, not files]] — cognitive units are goals, decisions, and open loops
- [[plain-text-right-substrate-wrong-interface|Plain text is the right substrate, wrong interface]] — Markdown is the right foundation, but not the right interaction layer
- [[effective-vs-nominal-context-length|Effective context length << nominal context length]] — bigger windows don't eliminate the need to curate

---

## What if you could compose context in 5 seconds?
*The solution — Context Assembly UI*

The concrete solution: a pre-flight interface where you see, adjust, and send context before every AI interaction.

- [[context-composer|Context Composer]] — the pre-flight interface for adjusting what the AI knows
- [[propose-adjust-send|Propose → Adjust → Send]] — system proposes context, user adjusts, prompt sends
- [[context-chips|Context Chips]] — removable/addable chips showing what the AI will consider
- [[context-strength-slider|Context Strength Slider]] — minimal/balanced/deep control over context depth
- [[context-must-be-adjustable-in-under-5-seconds|Context must be adjustable in under 5 seconds]] — if it's slow, users won't do it
- [[swipe-to-add-context|Swipe to add context]] — rapid yes/no/later gestures for context curation
- [[why-is-this-included|Why is this included?]] — transparency for every context item
- [[visual-context-map|Visual Context Map]] — semantic tree view replacing folder browsing

---

## But context needs something to draw from
*The trust layer — Governed Memory*

Reliable context requires governed memory — AI proposes, humans decide:

- [[trusted-knowledge-layer|Trusted Knowledge Layer]] — what emerges when information passes through human governance
- [[ai-proposes-memory-candidates|AI proposes memory candidates]] — AI extracts, humans govern
- [[human-in-the-loop-promotion|Human-in-the-loop promotion]] — swipe to confirm, reject, or edit memories
- [[proactive-memory-review|Proactive Memory Review]] — daily surfacing of memory items, not buried settings
- [[cascading-validation|Cascading Validation]] — change one fact, flag everything downstream
- [[anti-automation-pro-sovereignty|Anti-automation, pro-sovereignty]] — AI proposes, humans decide, plain text ensures independence
- [[implicit-validation-signals|Implicit Validation Signals]] — trust accumulates through usage patterns, not just explicit review
- [[voice-to-markdown-gateway|Voice-to-Markdown Gateway]] — frictionless capture from voice to plain text

---

## The bigger picture
*The architecture*

For those who want to go deeper — the full architecture and vision:

- [[four-layer-architecture|Four-Layer Architecture]] — plain text substrate → thread workspaces → governed memory → context-aware retrieval
- [[thread-workspaces|Thread Workspaces]] — persistent, evolving spaces organized around situations, not files
- [[thread-workspace-vs-project|Thread Workspace vs Project]] — threads are thinking-centric; projects are task-centric
- [[immutable-raw-layer|Immutable Raw Layer]] — capture everything as plain Markdown first, govern later
- [[context-pack|Context Pack]] — a curated set of context assembled for a specific AI interaction
- [[the-new-knowledge-loop|The New Knowledge Loop]] — raw → substrate → context pack → AI reasoning → new knowledge → trusted memory
- [[pkm-as-context-operating-system|PKM as Context Operating System]] — PKM reframed for AI-era context orchestration
- [[cross-system-identity-layer|Cross-System Identity Layer]] — a unified, validated identity across AI platforms
- [[overlapping-contexts-replace-hierarchy|Overlapping contexts replace hierarchy]] — notes belong to multiple contexts, not one folder
- [[file-folder-metaphor-is-transitional|File-folder metaphor is transitional]] — CLI + repo is the Unix moment, not the final form
- [[wardley-positioning-of-context-composer|Wardley Positioning of Context Composer]] — strategic positioning on the Wardley Map: Custom → Product sweet spot

---

## What we're building first
*The roadmap — pages in `project/`*

**Priority 1: Context Assembly UI** — the highest-leverage starting point.

- [[Founder Roadmap]] — 30/60/90 day plan: MVP scope, 5-phase build sequence, finding collaborators, go-to-market
- [[context-assembly-ui-pitch-v0.1|Context Assembly UI pitch v0.1]] — full v0.1 pitch document
- [[Demand Validation Research]] — evidence that people need this, competitor analysis, and Twigg.ai case study
- [[vertical-beachhead-analysis|Vertical Beachhead Analysis]] — which non-developer professions have the highest context assembly pain and willingness to pay
- [[Risks and Open Questions]] — where we could be wrong, by concept area
- [Context Composer Pitch Deck](assets/context-composer-pitch.html) — 18-slide visual pitch for non-technical audiences

---

## Vault maintenance
*Operational pages in `project/`*

- [[Table of Contents]] — all atomic notes grouped by type
- [[Illustration Needs]] — task list of images and diagrams to create
- [[Revisions]] — log of major changes to this vault

---

## Source Documents

Original vision documents in `sources/`:
- [[governed_memory_pitch|Governed Memory for the AI Era]] — the governed memory thesis
- [[ai-memory-validator-onepager|AI Memory Validator]] — AI memory validation app
- [[context construction UX|Context Construction UX]] — context composer design
- [[pkm_context_operating_system_onepager|PKM as Context Operating System]] — PKM as context OS
- [[unix_philosophy_human_knowledge_onepager|Unix Philosophy Applied to Human Knowledge]] — Unix philosophy applied to knowledge
- [[file-folder metaphor|File-Folder Metaphor]] — why files are transitional
- [[context-composer-wardley-positioning|Context Composer Wardley Positioning]] — strategic analysis mapping playbook concepts to Wardley coordinates
- [[vertical-market-research-feb2026|Vertical Market Research Feb 2026]] — detailed vertical-by-vertical analysis of non-developer context assembly pain
- [[context-engineering-2026-chatgpt-deep research-report|Context Engineering 2026 Deep Research Report]] — comprehensive academic + industry landscape of context engineering
