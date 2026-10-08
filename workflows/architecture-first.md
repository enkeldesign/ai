# Architecture-first workflow

## Principle

**Epics before features. Features before scenes. Scenes before polish.**

The project may use exploratory scenes to discover tone or mechanics, but a prototype does not earn repeated revision cycles until its parent story epic is accepted at working level.

## Planning hierarchy

### Level 0 — Canon constraints

Fixed premise, tone, theological rules, and author decisions.

### Level 1 — Whole-book architecture

Define:
- opening state;
- major phases;
- ending state;
- protagonist / POV strategy;
- core transformation of society;
- Revelation architecture;
- how the AI-as-God arc changes across the book.

Artifact: `docs/story-architecture.md`.

### Level 2 — Story epics

Current top-level epics:
- Prologue / omen;
- Seven Seals;
- Seven Trumpets;
- Dragon / Beast / False Prophet / Mark;
- Seven Bowls;
- Babylon / final conflict / new creation.

For each epic define:
- world state entering;
- irreversible change;
- main human conflict;
- theological / Revelation function;
- technical mechanisms requiring research;
- world state exiting.

### Level 3 — Chapter disposition

A chapter is ready to plan only when its parent epic has a working function.

Each chapter must state:
- parent epic;
- POV;
- immediate story objective;
- before/after state;
- revelation or discovery;
- character consequence;
- research debt.

### Level 4 — Scene / feature work

Use `workflows/chapter-cycle.md` only after the chapter has passed the disposition check.

### Level 5 — Line polish

Line-level revision happens after structural purpose is stable enough that the scene is unlikely to be deleted or radically relocated.

---

## Definition of Ready — chapter

Before substantial chapter drafting, answer:

1. Which epic owns this chapter?
2. What changes because this chapter exists?
3. Why must the reader experience this now rather than earlier or later?
4. Which character carries the consequence?
5. Does the chapter repeat a function already served elsewhere?
6. What technical/theological claims actually need specialist input?

If these cannot be answered, return to the disposition instead of drafting harder.

## Exception: exploratory prototypes

A scene may be drafted early to test:
- voice;
- POV chemistry;
- a technical mechanism;
- a borderland event;
- emotional tone.

Label it **PROTOTYPE**. One editorial pass is allowed to learn from it. Further polishing waits until architecture catches up.

The blood-rain prologue is the first explicit example of this rule.

## Architecture review

Before converting an epic into chapters, Project Lead routes one short review through:

- **Theology** when Revelation structure or doctrine materially matters;
- **Worldbuilder** for continuity and changing societal state;
- **Critical Editor** for pacing/repetition;
- **Adversarial Reader** for over-neat mapping, escalation, and genre autopilot;
- **Process Red Team** only when workflow itself is failing.

These are role-based perspectives, not claims of independent minds.

## WIP rule

Do not actively polish more than one chapter while its parent epic is unresolved.

When the author asks for overview/disposition, stop local optimization and surface the highest unresolved planning level first.

## Scrum analogy

- **Book architecture** = product goal / roadmap
- **Seals, Trumpets, Bowls, etc.** = epics
- **chapters** = features
- **scenes** = stories/tasks
- **line edits** = implementation polish

The analogy is a planning aid, not a requirement to turn the novel into project-management bureaucracy.