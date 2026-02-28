# AI-UI Playbook — Instructions for AI Assistants

## What this vault is

A living playbook exploring the future of human-AI knowledge interfaces. The core vision: governed memory with human validation, wrapped in thread-centric interfaces that match human cognition rather than file systems. Extracted from product vision documents and organized as atomic, interconnected notes.

## Note types

- **concept** — A named idea with a clear definition (Context Pack, Thread Workspace, etc.)
- **problem** — A specific friction, failure mode, or pain point in current tools
- **principle** — A design belief or constraint that guides decisions
- **pattern** — A concrete UX or architecture approach
- **question** — An open question worth exploring
- **action** — A next step, build priority, or MVP definition

## Frontmatter

Every note has:

```yaml
---
type: concept | problem | principle | pattern | question | action
source:
  - "[[source-file-name]]"
status: seed | growing | mature
---
```

- `type` — one of the six types above
- `source` — links to original onepager(s) in `sources/` that the note was extracted from
- `status` — `seed` (just extracted), `growing` (being developed), `mature` (well-formed and stable)

## File naming

- Lowercase with dashes: `context-pack.md`, `memory-is-governance-not-storage.md`
- Descriptive but concise
- No date prefixes, no numbering

## Linking rules

- Use `[[wiki links]]` inline whenever referencing another concept
- Every note should link to at least 2 other notes
- Don't create orphan notes — if a note has no connections, it probably belongs as a section in another note

## Folder structure

- **Root (`/`)** — Atomic notes (the results/output of the vault) — **public**
- **`assets/`** — Images and SVGs (public-facing) — **public**
- **`sources/`** — Imported knowledge: original vision documents, external analyses. Treat as read-only reference — **private** (gitignored)
- **`project/`** — Work-related files: roadmaps, revisions, task lists, operational pages — **private** (gitignored)

Atomic notes link back to sources but don't duplicate their full content.

## Repository structure and visibility

This repo is public on GitHub. Not everything in the maintainer's local vault is tracked in git:

- **Public (tracked in git):** Root-level `.md` files (atomic notes, navigation pages) and `assets/`. This is what contributors see when they fork the repo.
- **Private (gitignored):** `project/` and `sources/`. These exist only in the maintainer's local Obsidian vault. Forks and clones will not contain these folders.

Because of this split:

- References to `[[source-file-name]]` in note frontmatter may point to files that don't exist in a fork — this is expected and normal. Leave these references intact.
- `Playbook Map.md` and `Start Here.md` are the navigation entry points for anyone exploring the repo.
- Contributors should only add or modify public files (root-level notes and `assets/`).

## How to add new knowledge

1. If the user shares new thinking, extract atomic notes — don't append to existing ones
2. New raw/imported documents go in `sources/`
3. Images and SVGs go in `assets/`
4. Update `Playbook Map.md` when adding major new concepts
5. Prefer creating a new note over making an existing note too long
6. When a concept appears across multiple sources, create ONE note with multiple `source:` entries

## How to evolve notes

- Notes can change type (a question becomes a concept when answered)
- Update status: seed → growing → mature as thinking develops
- Add new `[[links]]` as connections emerge
- Never delete notes — mark as superseded if outdated

## Revision logging

When making a major revision (adding new concepts, restructuring sections, changing priorities, or significant rewrites), add an entry to `[[Revisions]]` with:
- Date
- Brief description of what changed and why
- Which notes were affected

Minor fixes (typos, link corrections, small wording tweaks) do not need revision entries.

## Git workflow

**For contributors:** Fork the repo → create a feature branch → make changes → open a PR. One atomic note per commit where practical. PRs should explain the "why" behind the change.

**Branch naming:**

- `add/note-name` — new notes
- `update/note-name` — edits to existing notes
- `fix/note-name` — corrections or broken links

**Commit messages:** Imperative mood, concise. Examples:

- `Add lost-in-the-middle-effect note`
- `Update context-rot with two-level framing`
- `Fix broken links in memory-governance`

**What belongs in a PR:**

- New atomic notes
- Edits to existing notes
- New links between notes
- Corrections and research additions

**What belongs in an issue:**

- Critiques or questions about the framing
- Suggestions that need conversation before action
- Discussion of missing concepts or alternative perspectives

**Don't commit:**

- Private operational files (`project/`, `sources/`)
- Obsidian configuration (`.obsidian/`)
- Claude Code settings (`.claude/`)

## What NOT to do

- Don't create folder hierarchies beyond `sources/`, `project/`, and `assets/`
- Don't create Obsidian templates
- Don't auto-generate notes without user review
- Don't merge atomic notes into long documents
- Don't add tags redundant with the `type` field
- Don't duplicate content that exists in another note — link to it instead
