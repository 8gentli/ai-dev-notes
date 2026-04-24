---
title: agents-rules-v2
type: blueprint
date: 2026-04-24
tags: [agent, workflow, project-context, copy-paste, copilot, cursor, claude, openclaw]
source_context: mixed
confidentiality: public-safe
---

## Aim

- Provide a reusable project starter for agentic development with three layers:
- agent rules
- project context files
- workflow orchestration

## Explanation

- Keep v2 practical for direct copy/paste into a new repository.
- Preserve high-value context patterns from vzev (REQ, SPEC, TASKS, STATE, DECISIONS).
- Keep one main behavioral contract in AGENTS and avoid duplicate instruction sets.

## INSTRUCTIONS Policy

- INSTRUCTIONS.md is deprecated when its relevant content is fully covered by AGENTS.md, workflow docs, and project-context files.
- Keep INSTRUCTIONS.md only for legacy compatibility during transition.

## Folder Layout

- `BLUEPRINT.md`: metadata and usage guide
- `copy-paste/`: agent entry files to drop into repo root
- `project-context/`: templates for REQ, SPEC, TASKS, STATE, DECISIONS
- `workflow/`: phase-gated process docs to force plan/refine/release/code/test/fix

## Recommended Bootstrap Order

1. Copy files from `copy-paste/` to target repo root.
2. Start with `project-context/REQ.md` and fill manually.
3. Co-create `project-context/SPEC.md` with the agent.
4. Use `workflow/PHASES.md` to enforce gated execution.
5. Let the workflow generate and maintain `TASKS.md`, `STATE.md`, and `DECISIONS.md`.

## Quality Rules

- Keep reusable files concise and explicit.
- Separate stable rules from evolving project context.
- Avoid duplicated instructions across AGENTS, CLAUDE, and tool-specific files.
- Prioritize official vendor docs for baseline practices.
- Consider community ideas when they are materially better and can be validated in practice.
