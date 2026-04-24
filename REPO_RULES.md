# Repository Rules

These rules apply to all contributors, including AI agents.

## 1) Purpose

This repo is a practical knowledge base for on-the-job work.
Do not turn this into a school-style curriculum.

## 2) Confidentiality and data safety

- Never commit secrets, tokens, passwords, keys, private certificates.
- Never copy customer data or internal confidential data.
- Sanitize business context before writing notes.
- If a detail could identify internal systems, generalize it.

## 3) Writing style

- Use short, simple English.
- Non-native English is fully accepted.
- Keep original meaning; do not over-polish language.
- Prefer clear bullets and short sections.

## 4) Capture workflow

1. Quick capture in `inbox/`.
2. Promote reusable content to:
   - `issues/` for recurring errors and fixes
   - `cheatsheets/` for reusable commands/processes
   - `blueprints/` for reusable AI workflows
3. Add tags to improve search.

## 5) File naming

- Use lowercase kebab-case.
- Include date when useful: `yyyy-mm` or `yyyy-mm-dd`.
- Keep names specific and short.

## 6) Required sections by content type

- Issue note: Context, Symptom, Cause, Fix, Reuse Rule, Tags
- Cheatsheet: Goal, Fast Steps, Gotchas, Snippets, Tags
- Blueprint: Purpose, Inputs, Guardrails, Steps, Output, Quality Checks, Tags

## 7) Agent behavior

- Agents must read `AGENTS.md` before creating or editing files.
- Agents must keep edits minimal and scoped.
- Agents must not restructure unrelated files.
- Agents must preserve user intent even if grammar is imperfect.

## 8) Quality bar

- Notes must be actionable.
- Avoid long theory blocks.
- If a command is added, include context and expected result.
- If uncertainty exists, mark it as "Assumption".
