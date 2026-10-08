# AGENTS.md — Revelation AI writing team

This file is the repository-level operating contract for AI collaborators working on the Revelation AI / The Beast novel project.

## Authority order

When sources disagree, use this order:

1. **Current explicit author instruction.**
2. `docs/premise.md` — fixed author canon; do not contradict without approval.
3. `docs/decisions-log.md` — explicit structural/creative decisions already made.
4. `docs/lore-bible.md`, `docs/characters.md`, `docs/timeline.md` — accepted continuity.
5. `docs/narrative-structure.md` and `docs/style-guide.md` — narrative form and prose constraints.
6. `docs/30k-disposition.md` and `docs/story-architecture.md` — working architecture, not automatically canon.
7. Research/dossiers — evidence and plausibility constraints, not story decisions by themselves.

Never silently promote a working hypothesis or scene invention into canon.

## Current story-form decision

The novel is a **recurring first-person ensemble**.

- Chapters are named for the POV character.
- Core POV characters return throughout the book; chapter order is not round-robin.
- Reading order follows dramatic causality, while story time may overlap.
- Replaying the same period is allowed only when another POV materially changes meaning, information, consequence, or interpretation.
- A major event should normally have one primary witnessing chapter; later POVs may encounter its broadcast, aftermath, institutional response, rumor, or hidden mechanism.
- Maintain an objective master chronology in `docs/timeline.md` separately from chapter order.

See `docs/narrative-structure.md`.

## Architecture-first rule

Work top-down:

`whole-book architecture → epics → character arcs → chapter disposition → scenes → line polish`

Exploratory prose is allowed, but label it **PROTOTYPE** and do not repeatedly polish it before its parent architecture is accepted.

Current active architecture work:
- #7 — whole-book disposition;
- #8 — character architecture / casting board.

## Team

Role cards live in `agents/`.

- **Project Lead** — vision, architecture, routing, synthesis, author decisions.
- **Character Lead / Casting Director** — ensemble, recurring POVs, relationships, archetypes, scriptural shadows, merge/cut decisions.
- **Worldbuilder** — continuity, chronology, locations, technology, accepted character facts.
- **Research Orchestrator** — bounded empirical research and evidence hygiene.
- **Theology** — Revelation structure, AI-as-God ambiguity, symbolic integrity.
- **Drafting** — manuscript production from approved chapter/scene briefs.
- **Critical Editor** — constructive developmental and line review.
- **Adversarial Reader** — tries to disqualify manuscript/architecture rather than improve it.
- **Workflow** — repository, issues, PRs, production conventions.
- **Process Red Team** — attacks the project system and bureaucracy.
- **Meta-Governance** — proposes at most one process experiment from evidence.

These are structured perspectives, not genuinely independent minds. Do not describe agreement among roles as independent verification.

## Specialist routing

Do not run every role on every artifact. Project Lead invokes specialists only for a named risk or decision.

Default manuscript path:

`Chapter disposition → Scene brief → Draft → Critical Editor → Adversarial Reader → Author review`

Character architecture is owned by Character Lead before detailed biographies. Timeline/continuity changes route through Worldbuilder. Technical claims that carry causal weight route through Research. Revelation/theology ambiguity routes through Theology.

## Character design rules

Major characters should have:
- a real-world lens and private life, not merely a thematic job;
- a dramatic/archetypal function that can change over time;
- a distinct first-person cognition/voice if they receive POV chapters;
- a reason to recur across multiple movements;
- a subtle scriptural shadow or composite analogue where useful.

Scriptural clues must remain deniable and varied: names/etymology, objects, physical details, biography, moral temptation, scene echoes, or relationship patterns. Avoid turning every name into an anagram or making the novel a puzzle key. The manuscript should not announce the mapping.

## Evidence hygiene

Tag empirical claims when relevant:
- **SUPPORTED** — strong direct evidence;
- **PLAUSIBLE** — technically/socially credible extrapolation;
- **SPECULATIVE** — useful fiction, but carrying material uncertainty.

Research only claims that affect reader trust, causal mechanics, or plot feasibility. Do not use research as permission-seeking for ordinary texture.

## Borderland rule

Every major uncanny event needs:
1. a plausible technical causal chain;
2. evidence supporting it;
3. one stubborn remainder that makes the explanation feel insufficient.

Do not stack multiple miracles merely to increase intensity.

## Writing discipline

Follow `docs/style-guide.md`.

In particular:
- avoid recognizably AI-shaped fragment/negation cadence;
- attach exposition to decisions and conflict;
- let competent characters remain competent;
- do not explain Revelation correspondences for the reader;
- technical detail must solve, complicate, or constrain something.

## Handoff contract

Every substantial handoff states:
1. what is canon;
2. what is provisional;
3. what evidence is weak/speculative;
4. what the next role must decide or produce.

## Repository discipline

Use the existing canonical files before inventing new ones. Create a new process document only when a concrete recurring need cannot be served by an existing file. Prefer updating one source of truth over duplicating guidance.
