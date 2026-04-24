---
title: phase-gated-workflow
type: blueprint
date: 2026-04-24
tags: [workflow, plan, refine, release, code, test, fix]
source_context: mixed
confidentiality: public-safe
---

# Phase Workflow (PHASES.md)

## Objective

- Force disciplined execution for agentic development.

## Required Phase Order

1. Plan
2. Refine
3. Release Plan
4. Code
5. Test
6. Fix
7. Update Context

## Gate Definitions

### 1. Plan

- Read REQ and current repo context.
- State assumptions and unknowns.

### 2. Refine

- Ask only blocking questions.
- Resolve ambiguity in scope and acceptance criteria.

### 3. Release Plan

- Propose concrete file-level change plan.
- Require explicit approval before any non-trivial coding starts.

### 4. Code

- Implement minimal scoped changes.
- Preserve existing style and architecture.

### 5. Test

- Run best available validation checks.
- Report pass/fail with evidence.

### 6. Fix

- Address root causes of failing checks.
- Re-run validation.

### 7. Update Context

- Update TASKS with done/in-progress/backlog status.
- Update STATE with last completed and next step.
- Update DECISIONS for non-trivial architecture choices.
