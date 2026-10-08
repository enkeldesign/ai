# Process Red Team — Initial Review

Date: 2026-10-06
Checkpoint: post-initialization

## Verdict

The system is usable, but it is already close to becoming more elaborate than the amount of manuscript justifies. The main risk is not missing expertise; it is **pseudo-independence and process inflation**.

## 1. Pseudo-independent reviewers

**Severity: HIGH**

### Failure mode
The roles are separate on paper but can still be executed by the same underlying assistant with the same recent context. A reviewer may therefore inherit the drafter's framing, intentions, and favored explanations while appearing independent.

### Evidence
The Drafting, Critical Editor, Adversarial Reader, Theology, and Process Red Team roles all live in the same project context. Role separation alone does not create epistemic independence.

### Cost if ignored
The workflow can produce false confidence: multiple named passes may look like independent agreement when they are correlated judgments from one system.

### Test/change
For adversarial manuscript review, expose the reviewer to the draft **before** the drafting rationale when practical. Require textual evidence for objections. For Process Red Team, review repo/process artifacts rather than the reasoning that created them. Treat role diversity as structured perspective, not independent verification.

Do not describe the team as multiple independent minds unless genuinely separate contexts/models are used.

---

## 2. Process is growing faster than the manuscript

**Severity: MEDIUM**

### Failure mode
We have created premise, lore, theology, climate, persuasion, decisions, workflow changelog, style guide, chapter workflow, and numerous agent contracts around one draft prologue.

### Cost if ignored
The project may reward maintaining the machinery instead of writing the book. The author may end up reviewing process artifacts that do not improve scenes.

### Test/change
Freeze creation of new process/agent documents until at least Chapter 2 unless a concrete failure mode requires one. Existing files may be edited or deleted. Measure usefulness by whether an artifact changes a story decision or catches a real defect.

---

## 3. Too many reviewers could converge on the same problems

**Severity: MEDIUM**

### Failure mode
Critical Editor, Adversarial Reader, Worldbuilder, Theology, Research, and Project Lead could all review every chapter, creating repetition and latency.

### Cost if ignored
Slow chapter cycles, diluted author attention, and bland prose revised toward committee consensus.

### Test/change
Use **two mandatory manuscript passes only**: Critical Editor + Adversarial Reader. Project Lead invokes Worldbuilder, Theology, or Research only when the chapter actually touches their risk area. Specialists do not automatically vote on every draft.

---

## 4. Numeric severity gates can create false precision

**Severity: MEDIUM**

### Failure mode
The `>1 HIGH / >3 MEDIUM` gate looks objective but severity labels are subjective and correlated. A chapter with three serious medium problems may be worse than one with two debatable high findings.

### Cost if ignored
Checklist compliance may replace editorial judgment.

### Test/change
Keep the threshold as a tripwire, not an acceptance score. Add one explicit question to the gate: **Would either reviewer recommend publishing this chapter in its current form?** A `no` blocks recommendation regardless of count.

---

## 5. Research could become permission-seeking

**Severity: LOW now; potentially HIGH later**

### Failure mode
Hard-SF ambition can tempt the team to research every invented detail before committing to story choices.

### Evidence
The current blood-rain research issue is bounded and useful, so this is not yet a failure.

### Cost if ignored
Loss of momentum and avoidance of aesthetic decisions disguised as fact-checking.

### Test/change
Research only claims that affect reader trust, causal mechanics, or plot feasibility. Do not research texture that can be plausibly invented without carrying causal weight.

---

## 6. Current strengths worth preserving

These are not arguments against later change:

- provisional inventions are explicitly separated from canon;
- research debt is tracked rather than silently asserted as fact;
- substantial creative work remains reviewable in a PR;
- the borderland rule creates a useful constraint against stacking miracles;
- author feedback has already produced a concrete anti-AI prose rule.

## Recommended immediate experiment

For the prologue and Chapter 1, use this minimum path:

`Scene brief -> Draft -> Critical Editor -> Adversarial Reader -> Author`

Invoke Research / Worldbuilder / Theology only when a flagged issue needs them. After Chapter 2, compare what those specialist roles actually contributed and remove or change anything that is not earning its cost.

## Proposed instruction/process edit

**Current implicit model:** specialist team exists and may participate throughout the chapter cycle.

**Proposed model:** Project Lead routes specialists on demand; only Critical Editor and Adversarial Reader are default manuscript review passes.

**Reason:** reduces correlated committee review, process latency, and prose homogenization while retaining specialist depth where it matters.
