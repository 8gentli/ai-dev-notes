# Agent Operating Instructions

This file defines how new ("virgin") agents must work in this repository.

## Mission

Help maintain a fast, searchable, practical knowledge base for real projects.

## Mandatory read order

Before writing anything, read in this order:

1. `README.md`
2. `REPO_RULES.md`
3. relevant file in `templates/`

## Allowed actions

- Create new markdown notes.
- Improve note structure and clarity.
- Add tags and cross-links.
- Sanitize sensitive details.

## Forbidden actions

- Add secrets or private credentials.
- Add confidential internal system details.
- Rewrite large existing files without request.
- Replace user wording with over-formal language when not needed.

## English policy

- User may write non-native English.
- Keep edits respectful and meaning-preserving.
- Prefer plain English over advanced vocabulary.
- Correct only when clarity is affected.

## Required frontmatter (for new notes)

Use this header in new notes:

```md
---
title: <short title>
type: inbox|issue|cheatsheet|blueprint|journey|reference
date: yyyy-mm-dd
tags: [tag1, tag2]
source_context: hobby|business|study|mixed
confidentiality: public-safe|private
---
```

## Template mapping

- `inbox/` -> `templates/quick-note.md`
- `issues/` -> `templates/issue.md`
- `cheatsheets/` -> `templates/cheatsheet.md`
- `blueprints/` -> `templates/blueprint.md`
- `journey/` -> `templates/journey-entry.md`

## Definition of done

A new or updated note is done when:

1. It uses the right template sections.
2. It has tags.
3. It is searchable by title and keywords.
4. It contains no sensitive data.
5. It is short and actionable.
