---
name: design-reference-maintenance
description: Use when adding, reviewing, normalizing, or updating DESIGN.md references and related design-system notes in this public repository.
---

# Design Reference Maintenance Skill

## Purpose

Maintain reusable public design-system references without leaking private or proprietary material.

## Procedure

1. Identify the target product, site, or design system.
2. Keep each `DESIGN.md` focused and reusable.
3. Record observable design patterns, component behavior, layout rules, typography notes, color usage, spacing, and interaction patterns only when they can be supported by public sources or user-provided public material.
4. Preserve attribution and source names.
5. Do not copy more source text or assets than needed.
6. Mark uncertain token names, implementation details, or inferred design rules as `TBD` or `needs verification`.
7. Put long checklists or repeated workflows in docs or skills instead of root `AGENTS.md`.

## Verification

- Reread changed Markdown files.
- Check links and source names.
- Confirm no private screenshots, account data, credentials, raw proprietary assets, or unrelated files were added.
- Confirm the reference is generic and public-safe.

## Report

Report changed files, verification performed, commit/push status, and remaining `TBD` / `needs verification` items.
