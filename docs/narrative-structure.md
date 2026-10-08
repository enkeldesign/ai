# Narrative structure

> Status: AUTHOR-APPROVED STRUCTURAL RULE. Implementation details remain open unless explicitly decided below.

## Core format

The novel uses a **recurring first-person ensemble**.

Each chapter is narrated in first person by one POV character and is titled with that character's name.

Core POV characters recur across the book. The sequence is not a fixed rotation. A working pattern may look like:

`A → B → C → A → D → B → …`

A character returns when their consciousness can advance or reinterpret the story.

## Two timelines

Maintain two separate structures:

1. **Story chronology** — what objectively happens and when. This lives in `docs/timeline.md`.
2. **Reading order** — the sequence in which POV chapters reveal those events.

Reading order may move backward over a limited stretch of time when the new POV materially changes what the reader understands.

Example function:
- journalist broadcasts an event;
- a later chapter rewinds into the same hour with a tech insider who knows the hidden mechanism;
- another chapter continues forward with a government official hearing the broadcast in a car and responding institutionally.

The overlap is justified because each chapter changes meaning, not because the same event is exciting twice.

## Overlap gate

A chapter may revisit previously covered time only if it adds at least one of:
- new causal information;
- a consequence unavailable to the previous POV;
- a materially different interpretation;
- dramatic irony created by information asymmetry;
- a relationship or moral choice that changes the event's meaning.

If none applies, advance time instead.

## Primary witness rule

Major events normally get one primary witnessing chapter. Other POVs encounter:
- broadcasts or reporting;
- alerts and official briefings;
- social/media reaction;
- private logs or leaked material;
- aftermath and physical consequences;
- hidden causal mechanisms.

This keeps the braided structure connective rather than repetitive.

## POV tiers

### Core POV
- recurs through multiple movements;
- sustains a distinctive first-person voice and cognition;
- has an irreversible internal arc;
- offers access that cannot be replaced without loss;
- creates conflict rather than merely covering a domain.

### Secondary recurring POV
- returns more selectively;
- becomes essential at particular phases or events;
- still requires a real internal arc.

### Non-POV major character
Can be central to the novel without narrating. This may be especially useful for characters whose mystery or charisma is stronger when seen externally.

### One-off POV
Not a default tool. Use only if the architecture earns the exception; do not create disposable witnesses merely for spectacle.

## Voice rule

POVs must differ in **cognition**, not only diction.

Examples:
- a journalist notices sourcing, contradictions, audience framing, and what can be verified;
- a tech insider notices system boundaries, failure modes, interfaces, and hidden dependencies;
- a government operator notices authority, jurisdiction, legitimacy, and downstream consequences;
- a theologian notices language, interpretation, historical echoes, and category mistakes.

Repeated characters should remain recognizably themselves while their attention, assumptions, and moral vocabulary change under pressure.

## Chapter naming

Manuscript-facing chapter title: **POV character name**.

Exact typography and whether first name or full name is used remain open until final names are chosen.

Draft metadata may include story date/time, parent epic, overlap relationship, and status, but that metadata is not necessarily printed in the novel.

## Relationship to Revelation structure

Revelation provides macrostructure and symbolic pressure; POV perception provides the reader's lived experience.

Parts/movements may correspond to Seals, Trumpets, Beast, Bowls, Babylon/New Creation, but chapter titles should not mechanically announce the biblical mapping unless a later author decision changes this.

## Open implementation choices

- exact number of core vs secondary POVs;
- whether the charismatic tech leader ever receives first-person POV;
- whether the blood-rain prologue uses a core POV or remains a prototype/outlier;
- how much explicit date/time information appears on the page;
- whether part titles directly reference Revelation or remain subtler.
