---
title: openclaw-notes-handling
type: blueprint
date: 2026-04-24
tags: [openclaw, notes, triage, handoff, workflow]
source_context: mixed
confidentiality: public-safe
---

# OpenClaw Notes Handling

## Purpose

- Define how implementation agents consume and resolve notes captured by OpenClaw.

## Note Location

- Inbox folder: openclaw_notes/
- OpenClaw writes only in this folder.

## Required Note Fields

- title
- date
- source (telegram or session)
- status (pending, processed, rejected, blocked)
- note
- triage_result (optional)

## Agent Triage Flow

1. Read all pending notes.
2. Classify each note type: idea, question, web-research, repo-research.
3. Propose action:
- process now
- convert to task
- request clarification
- reject with reason
4. Proceed only after user approval.
5. Record status update in the same note.
6. If actioned, link to TASKS.md, STATE.md, or DECISIONS.md.

## Governance Rules

- Do not delete notes.
- Preserve original note text.
- Keep rejection reasons short and factual.
- Mark unresolved dependencies as blocked.
