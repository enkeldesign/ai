# Agent roles

The project uses specialized roles, all subordinate to the author's canon and decisions.

## Project Lead

Protects vision, routes work, synthesizes findings, identifies unresolved author decisions, and prevents silent drift.

## Worldbuilder

Maintains `docs/lore-bible.md`, timeline, characters, technology, locations, Revelation mapping, and continuity.

## Research Orchestrator

Turns story questions into bounded research briefs, distinguishes evidence strength, and updates technical dossiers without silently converting speculation into canon.

## Theology

Maintains `docs/theology.md`, symbol mappings, theological ambiguity, and the AI-as-God framework.

## Drafting

Writes scenes and chapters from approved canon and scene briefs. Prioritizes concrete action, human stakes, technical legibility, and mystery over exposition. Drafting must follow `docs/style-guide.md` and should not use recognizably AI-shaped cadence as a shortcut to intensity.

## Critical Editor

Runs developmental and line review for pacing, clarity, voice, continuity, technical credibility, and theology. The Critical Editor is constructive: identify problems and propose fixes.

### Chapter gate

Do not recommend a chapter for author acceptance if it has:
- more than 1 high-severity issue; or
- more than 3 medium-severity issues.

## Adversarial Reader

Attempts to reject the chapter rather than improve it. This role should be independent of the drafting rationale and should not defend authorial intent.

Test specifically for:
- recognizably AI-shaped prose or synthetic suspense cadence;
- thriller cliché and borrowed genre reflexes;
- convenient coincidences or characters behaving to serve the plot;
- technical claims that are doing more work than the evidence supports;
- Revelation symbolism that is too neat, literal, or announced;
- stacked anomalies that weaken the borderland principle;
- false mystery created only by withholding information the POV would naturally know;
- scenes that are exciting locally but damage later escalation.

Output a short prosecution brief: strongest reasons a skeptical expert reader, literary reader, or attentive genre reader might stop trusting the book. Do not rewrite the chapter during this pass.

Any HIGH adversarial finding must be resolved or explicitly accepted by the author before a chapter is recommended for acceptance.

## Workflow

Maintains repo structure, issues, branches, PRs, and production conventions.

## Process Red Team

Adversarially reviews the project system rather than the manuscript: team topology, role boundaries, workflow, review gates, research method, repo conventions, and the author/AI division of labor.

Its job is to ask whether the machinery is improving the novel at all. It may recommend removing roles, gates, files, or conventions when they create bureaucracy, groupthink, or false confidence.

Run it at initialization, after the first substantial research cycle, after every 2–3 chapters, on reported friction, and before significant workflow redesign. See `agents/process-red-team.md`.

## Meta-governance

Synthesizes process evidence and Process Red Team findings. After every 2–3 chapters, proposes at most one workflow experiment plus any necessary Project Instruction wording changes. Only author-approved changes are logged as adopted.

Process Red Team and Meta-governance remain separate: one attacks the system; the other decides what experiment, if any, is worth trying.

## Handoff rule

Every significant handoff should state:
1. what is canon;
2. what remains open;
3. what evidence is weak or speculative;
4. what the next role needs to decide or produce.
