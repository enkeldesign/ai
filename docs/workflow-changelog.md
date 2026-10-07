# Workflow changelog

## 2026-10-06 — v0.1 initialization

**What changed**
- Repurposed `enkeldesign/ai` as the Revelation AI novel repository.
- Added fixed premise, lore bible, theology framework, climate/AI mechanics, persuasion dossier, agent roles, and chapter-cycle workflow.
- Established author-canon protection and chapter quality gate.

**Why**
Create a minimal production system that supports drafting immediately without requiring a heavy project-management layer.

**Who**
Erik + SOL

**Next checkpoint**
After the first substantial research pass or after 2–3 drafted chapters, whichever comes first.

## 2026-10-06 — v0.2 adversarial layers and prose guardrails

**What changed**
- Added `docs/style-guide.md` with an explicit guardrail against recognizably AI-shaped prose cadence, prompted by author feedback on the prologue.
- Split constructive editorial review from an `Adversarial Reader` that attempts to disqualify manuscript passages.
- Added explicit role cards in `agents/` so responsibilities and handoffs are not only implicit in chat context.
- Added a separate `Process Red Team` to challenge team topology, workflow, review gates, research method, repo conventions, and author/AI boundaries.
- Kept Process Red Team separate from Meta-Governance: one attacks the system; the other may propose a small experiment after considering the attack.
- Ran the initial process red-team checkpoint and stored it in `docs/process-reviews/2026-10-06-initial-red-team.md`.

**Why**
Author feedback identified two correlated risks: synthetic/LLM-like prose patterns and a need for adversarial review not only of the manuscript but also of the production system itself.

**Who**
Erik + SOL

## 2026-10-06 — v0.3 lean review experiment approved

**What changed**
- Adopted, provisionally, the Process Red Team recommendation that the default manuscript path is `Scene brief → Draft → Critical Editor → Adversarial Reader → Author review`.
- Worldbuilder, Research Orchestrator, Theology and other specialists are now routed only when a concrete risk requires them.
- Added a rule that specialist work must answer a named problem rather than run as ceremony.
- Added independence guardrail: Adversarial Reader should see the draft before the drafter's rationale when practical.
- Meta-Governance process proposals should be challenged by Process Red Team before adoption.

**Why**
Prevent committee fiction, duplicated review work and process growth from outrunning manuscript production while preserving adversarial pressure where it matters.

**Who**
Erik approved the experiment; SOL implemented it.

**Review condition**
Reassess after 2–3 chapters or sooner if the lean cycle misses a material continuity, technical or theological failure.

## 2026-10-06 — first research checkpoint

**What happened**
- Adversarial Reader reviewed prologue 0.2 and opened #5.
- Research #3 validated the core blood-rain mechanism and was closed as completed.
- Full research note added at `docs/research/blood-rain-opening.md`.
- Follow-up worldbuilding dependencies (radar geometry and cooling architecture) moved to #6 rather than being silently canonized.

**Process observation**
The lean routing rule worked in this case: AR identified the actual failure mode first, then Research was invoked against a bounded technical question. No Theology or Worldbuilder pass was needed yet.

## 2026-10-07 — v0.4 architecture-first correction

**What changed**
- Added `docs/story-architecture.md` as the active whole-book disposition / epic planning artifact.
- Added `workflows/architecture-first.md` with the hierarchy `architecture → epics → chapters → scenes → line polish`.
- Changed the chapter cycle so a chapter needs a parent epic, a before/after state, and a structural reason before substantial drafting.
- Explicitly classified early exploratory scenes as prototypes; they may teach us something without earning repeated polishing.
- Moved adversarial thinking up to the epic/architecture level before chapter decomposition.
- Logged the author's preference for implicit Revelation mappings and the current working hypotheses around the white rider, black rider, blood rain, and possible upload/rapture motif.

**Why**
The project optimized the prologue before producing a whole-book disposition. The author identified the correct planning failure in Scrum terms: we worked at feature level before agreeing on epics.

**Who**
Erik identified and approved the correction; SOL implemented it after role-based input from Project Lead, Theology, Worldbuilder, Drafting, editorial/adversarial review, and Process Red Team.

**Immediate effect**
Freeze further prologue line polish. Current priority is disposition and epic design. The prologue remains a useful prototype and may later be revised, moved, or removed according to the architecture.

**Review condition**
After the first chapter-level disposition exists for the Seals, ask whether the architecture-first layer is clarifying decisions or merely creating new ceremony.