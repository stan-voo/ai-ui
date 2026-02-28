---
type: problem
source:
  - "[[context-engineering-2026-chatgpt-deep research-report|Context Engineering 2026 Deep Research Report]]"
status: seed
---
# Context Security Surface
*△ problem*

Every piece of context fed to an LLM is a potential attack vector. Models do not naturally separate "instruction" from "data," and long contexts amplify the risk surface. As context assembly becomes more sophisticated — pulling from memory stores, retrieved documents, tool outputs, and user history — the number of entry points for malicious or corrupted content grows.

## The threat landscape

- **Direct prompt injection** — adversarial instructions embedded in user input that override system instructions
- **Indirect prompt injection** — hidden instructions planted in documents, web pages, or data sources that get retrieved and ingested by the model
- **RAG poisoning** — corrupting a knowledge base so the model confidently produces targeted wrong answers when it retrieves poisoned content
- **Memory poisoning** — injecting false information into persistent memory stores, which then contaminates all future sessions
- **Tool abuse** — manipulating tool calls to take unintended actions, especially in agentic workflows with multiple tool chains

The operational stance in 2026 is shifting from "prevent entirely" to "assume residual risk; contain blast radius."

## Why this matters for Context Composer

A [[context-composer|Context Composer]] that lets users see and curate context before it reaches the AI is not just a UX feature — it's a **security layer**. The [[propose-adjust-send|Propose → Adjust → Send]] interaction creates a human checkpoint where suspicious or unexpected context items can be caught and removed before they influence the model.

Conversely, a poorly designed context assembly system that pulls from untrusted sources without visibility becomes a *new* injection surface. Transparency ([[why-is-this-included|Why is this included?]]) and user control ([[context-chips|Context Chips]]) are security primitives, not just convenience features.

## Connections

Related to [[context-rot|Context rot]] — poisoned context compounds in the same way stale context does. Motivates [[anti-automation-pro-sovereignty|Anti-automation, pro-sovereignty]] — full automation of context assembly removes the human checkpoint that catches bad inputs. Relevant to [[trusted-knowledge-layer|Trusted Knowledge Layer]] — governed memory is inherently more resistant to poisoning than ungoverned memory. Connected to [[cascading-validation|Cascading Validation]] — if a poisoned item is caught, its downstream effects can be traced and cleaned.
