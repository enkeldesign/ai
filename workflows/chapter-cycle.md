# Chapter cycle

## Prerequisite — architecture first

Do not enter the chapter cycle merely because a scene idea is attractive.

Before substantial drafting, the chapter must have:
- a parent epic in `docs/story-architecture.md`;
- a clear before/after story state;
- a reason it belongs at this point in the book.

Use `workflows/architecture-first.md` when those are unresolved.

Exploratory scenes are allowed as **PROTOTYPES**, but they should not receive repeated polishing until their parent architecture is stable enough to justify them.

## Default rule

Keep the production loop lean. The mandatory manuscript path is:

**Chapter disposition → Scene brief → Draft → Critical Editor → Adversarial Reader → Author review**

Worldbuilder, Research Orchestrator, Theology and other specialist roles are invoked only when the Project Lead identifies a concrete continuity, evidence, theology or mechanism risk. Do not run every specialist on every chapter by default.

This is an experiment, not permanent doctrine; Process Red Team and Meta-Governance may recommend changing it after evidence from actual chapters.

## 1. Chapter disposition

Before scene work, define:
- parent epic;
- POV character;
- narrative function;
- world/character state entering;
- irreversible change or discovery;
- world/character state exiting;
- research debt;
- why this chapter belongs here rather than elsewhere.

If the disposition is unclear, return to the epic instead of drafting harder.

## 2. Scene brief

Before drafting, define:
- immediate objective;
- source of pressure;
- technical mechanism;
- Revelation/theology function, if any;
- borderland remainder;
- what changes by the end of the scene.

Route specialist work here only if a real risk is already visible.

## 3. Draft

Draft for momentum first. Avoid stopping to explain the entire world.

Targets:
- enter late;
- establish a concrete problem quickly;
- make technical detail solve or complicate something;
- keep exposition attached to decisions;
- end with a changed understanding, threat, or obligation;
- follow `docs/style-guide.md`, including the anti-AI-prose checks.

## 4. Critical pass

Score issues as HIGH / MEDIUM / LOW in:
- pacing;
- clarity;
- continuity;
- character motivation;
- technical credibility;
- theological/mystery integrity;
- prose/voice.

Chapter gate: do not recommend author acceptance with >1 HIGH or >3 MEDIUM issues.

The severity count is a tripwire, not a score. A chapter is also blocked if the Critical Editor would not recommend publication in its current form.

The Critical Editor may request a specialist pass when a finding depends on expertise rather than craft judgment.

## 5. Adversarial pass

A separate reader attempts to disqualify the chapter. It should receive the draft before the drafter's rationale when practical, then consult canon only after forming its first objections.

It should not rewrite or defend the draft.

Attack:
- AI-shaped cadence and synthetic suspense;
- cliché;
- plot convenience;
- technical overclaim;
- overly literal Revelation mapping;
- stacked anomalies;
- false mystery;
- escalation spent too early;
- local excitement that damages whole-book architecture.

Return only the strongest objections, with severity and concrete textual evidence. Any HIGH finding must be resolved or explicitly accepted by the author before recommendation.

## 6. Specialist routing when needed

Possible routes include:
- Worldbuilder — continuity, chronology, geography, character facts;
- Research Orchestrator — empirical/technical claims that matter to credibility;
- Theology — Revelation mapping or AI-as-God ambiguity;
- Process Red Team — workflow/team failure, not manuscript prose.

A specialist pass must answer a named problem. “Run everything” is not a valid reason.

## 7. Canon pass

Update as needed:
- `docs/lore-bible.md`
- `docs/decisions-log.md`
- technical dossiers

Do not convert provisional scene invention into global canon accidentally.

## 8. Author review

Use a pull request for substantial chapter work. The PR body should state:
- parent epic and chapter function;
- what the chapter accomplishes;
- important new canon introduced;
- unresolved author choices;
- research debt;
- critical-editor severity count;
- adversarial-review findings;
- any specialist reviews actually invoked and why.

## 9. Retro

Every 2–3 chapters, or after an unusually consequential workflow failure:
- identify one recurring friction;
- propose at most one workflow experiment;
- send Meta-Governance proposals through Process Red Team before adoption;
- consider whether Project Instructions need a concrete wording change;
- log approved changes in `docs/workflow-changelog.md`.
