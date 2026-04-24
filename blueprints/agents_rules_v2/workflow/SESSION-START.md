---
title: session-start-protocol
type: blueprint
date: 2026-04-24
tags: [session, protocol, handoff]
source_context: mixed
confidentiality: public-safe
---

# Session Start Protocol (SESSION-START.md)

At the beginning of each session:

1. Read STATE.md and TASKS.md.
2. Summarize:
- completed in prior session
- next planned step
- open blockers
3. Confirm intended scope for this session.
4. If OpenClaw is used, consult openclaw_notes/ only at session start.
5. If openclaw_notes/ exists and the session is an OpenClaw review, triage pending notes before new implementation work.

## End-of-Session Protocol

1. Update TASKS.md.
2. Update STATE.md.
3. Add one DECISIONS row if architecture changed.
4. Note remaining risks and next action.
5. Update note statuses for any handled openclaw_notes entries.

