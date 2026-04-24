---
title: debug-unknown-error
type: blueprint
date: 2026-04-24
tags: [agent, debug, troubleshooting]
source_context: mixed
confidentiality: public-safe
---

## Purpose

- Guide an AI agent to debug an unknown error quickly and safely.

## Inputs required

- Error message
- Relevant file path(s)
- Recent code change summary
- Runtime/build context

## Guardrails

- Do not invent facts.
- Ask for missing critical context only when blocked.
- Do not expose secrets in logs or output.

## Steps

1. Restate the error and expected behavior.
2. Reproduce or isolate with smallest possible test.
3. Identify likely root causes and rank by probability.
4. Apply minimal fix for highest-probability cause.
5. Re-run validation and summarize result.
6. Add a short prevention note.

## Output format

- Symptom
- Root cause
- Fix applied
- Validation result
- Prevention tip

## Quality checks

- [ ] Root cause evidence provided
- [ ] Fix is minimal and scoped
- [ ] Validation step included
- [ ] No sensitive data included

## Example prompt

```text
Debug this error in a minimal way. Provide root cause evidence and one scoped fix. Validate after patch and summarize in 5 bullets.
```
