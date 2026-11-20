# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is not a software project — it's a personal English/IELTS learning repo (grammar lessons, paragraph-writing practice, and presentation-speaking practice), published publicly so other learners can use it. There is no build, lint, or test tooling; all work here is Markdown content plus a few PDFs/DOCX reference files. See [`init.md`](./init.md) for the human-facing getting-started guide and [`README.md`](./README.md) for the project's background and goals.

## Repository structure and conventions

### `Grammers/` — grammar lessons
- [`grammer.md`](./Grammers/grammer.md) is the **standard template** for every grammar lesson: Table of Contents → Introduction → What is [Topic]? → Rules & Formation → Examples → Common Uses → Study Exercises → References → Key Takeaways → Practice Tips.
- [`present simple.md`](./Grammers/present%20simple.md) is the first fully worked-out lesson and the reference example for how `grammer.md` should be filled in.
- When adding a new tense/topic, copy `grammer.md` into a new file named after the topic (e.g. `past simple.md`) and fill in every section — don't invent a different structure.

### `PARAGRAPHS/` — paragraph writing practice
Each topic has its own folder (e.g. [`climate change/`](./PARAGRAPHS/climate%20change/)) containing exactly two files, per [`PARAGRAPHS/README.md`](./PARAGRAPHS/README.md):
- `my-version.md` — the user's own handwritten first draft, ~255 words, written without AI help and kept unedited (errors included).
- `ai-corrected.md` — the same ideas rewritten to IELTS Writing Task 2 standard (255 words), ending with a "What changed from my-version.md" section explaining the specific fixes (grammar, cohesion, lexical resource).

When asked to correct a paragraph, preserve the author's original ideas/structure — don't rewrite the argument, only the language — and always include the "What changed" explanation so the correction is a teaching tool, not just a replacement.

### `presention training/` — spoken presentation practice
Mirrors the `PARAGRAPHS/` convention but for 60-second spoken scripts instead of written paragraphs: each topic folder (e.g. [`cloud computing/`](./presention%20training/cloud%20computing/)) has `my-version.md` (user's own script, ~120-150 words for 60 seconds spoken) and `ai-corrected.md` (a polished reference script). [`60 sec tech.md`](./presention%20training/60%20sec%20tech.md) is the index of topics, not a lesson itself.

### `for arab learners/` — localized Arabic-language guide
[`arab_learners.md`](./for%20arab%20learners/arab_learners.md) is a standalone Arabic guide (motivation, recommended channels, study plan). It is independent of the English lesson conventions above — don't restructure it to match `PARAGRAPHS/`/`Grammers/` patterns. `DIC/` holds archived vocabulary resources (AWL book, split as `.rar`/`.z01`/`.zip` parts) and is reference material, not something to edit.

## Working in this repo

- Never fabricate or edit the content of a `my-version.md` file — that must be the user's own writing, by hand.
- Keep `ai-corrected.md` word counts close to the stated target (255 for paragraphs) and always explain the corrections made.
- New topics should follow the existing two-file folder pattern rather than introducing a new format.
