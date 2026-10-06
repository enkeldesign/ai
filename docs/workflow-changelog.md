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

**Pending, not yet adopted**
The initial Process Red Team recommends making only Critical Editor + Adversarial Reader mandatory manuscript passes and routing all specialists on demand. This remains a proposed workflow experiment until author approval.
