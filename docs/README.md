# Project sources

This directory contains the story's sources of truth. Status matters: not every planning document is canon.

## Author canon / decisions

- `premise.md` — fixed core premise; highest repository-level story authority.
- `decisions-log.md` — explicit author-approved creative and structural decisions.
- `narrative-structure.md` — approved narrative form: recurring first-person ensemble, named POV chapters, braided/overlapping chronology.

## Continuity ledgers

- `lore-bible.md` — accepted world, technology, symbol, and continuity facts.
- `characters.md` — accepted character facts and status; provisional casting stays clearly marked.
- `timeline.md` — objective story chronology, separate from chapter reading order.

These files should record accepted continuity, not every possibility under discussion.

## Working architecture

- `30k-disposition.md` — concise whole-book macro-arc.
- `story-architecture.md` — expanded Seals / Trumpets / Beast / Bowls / ending architecture.

These are working design artifacts. They may change until author-approved decisions are copied into the relevant canon/continuity files.

## Thematic / technical frameworks

- `theology.md` — AI-as-God framework and theological ambiguity.
- `climate-ai-mechanics.md` — compute/climate mechanisms and plausibility boundaries.
- `persuasion-dossier.md` — persuasion, AI-psychosis, swarm/leader dynamics.
- `style-guide.md` — prose and voice rules.

## Research

- `research/` — bounded research notes with sources and evidence strength.

Research constrains plausibility; it does not choose the story.

## Process history

- `workflow-changelog.md` — approved workflow changes and experiments.
- `process-reviews/` — adversarial reviews of the production system.

Repository-level agent instructions are in `/AGENTS.md`; detailed role cards are in `/agents/`; production workflows are in `/workflows/`.

## Canon update rule

When a working architecture choice becomes accepted:

1. record the decision in `decisions-log.md` if it materially changes structure or premise;
2. update `characters.md`, `timeline.md`, and/or `lore-bible.md` for continuity;
3. leave discarded alternatives in planning/issues rather than preserving them as pseudo-canon.
