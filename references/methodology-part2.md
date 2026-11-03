# Methodology Part 2 — Resume Experience Writing

## Purpose
Transform the **structured experience archive** produced by Part 1 into clear, specific, verifiable resume entries. The goal is **selective communication**, not summarizing every personal memory or rewriting the person's identity.

## Core idea
**Structured Experience Archive → Evidence Extraction → Selection → XYZ-Inspired Writing → Fact Check → User Authorization**

STAR-T reconstructs the experience. XYZ is an output-writing heuristic, not a replacement for the archive.

## Inputs
- Primary: approved STAR-T experience records from Part 1.
- Supporting: original raw narration and trustworthy supporting artifacts, when available.
- Context: the approved resume baseline, target purpose/audience, available space and preferred section order.
- If there is no structured record, run Part 1 or ask the user whether to reconstruct it first. Do not silently invent STAR-T fields.

## Step 1 — Read without rewriting
Understand what happened, the user's actual responsibilities, technical methods, decisions, team boundaries, final outcomes, uncertainties, and reflection. Retain the original source; do not overwrite it.

## Step 2 — Extract resume-worthy evidence
Identify:
- Scope: project, team, context, objective and constraints.
- Ownership: what the user personally led, designed, implemented, debugged, analyzed or wrote.
- Mechanism: architecture, algorithms, hardware, tools, workflows, experiments and decisions.
- Evidence: functioning artifact, tested capability, measured specification, award, publication, internal use, or observable result.
- Verification: whether each assertion is explicit, uncertain, or unsupported.

Do not automatically include feelings, dislikes, personality claims or retrospective lessons in the resume. Preserve them for the archive, PS or interview stories.

## Step 3 — Select rather than copy everything
Prioritize high-signal contributions relevant to the resume's purpose. Balance technical depth, distinct contributions and actual outcomes. Exclude redundant information; do not hide facts in the archive to make the resume look better. Do not include an experience merely because it is in the archive.

## Step 4 — Draft with XYZ
**X:** What was accomplished?
**Y:** What supports or measures the accomplishment?
**Z:** How was it accomplished?

Default to natural technical phrasing, not an inflexible sentence formula. For engineering and research, **Action → Technical Substance → Outcome** may read more naturally.

Example of permitted evidence: a five-layer RTOS architecture, approximately 10,000 lines of C, or a verified 1 kHz control loop. These are scope or implementation evidence, **not proof of higher performance** unless testing shows that.

Never invent time savings, efficiency gains, precision, adoption, user counts, experimental success rates or coauthorship. When quantified results are unavailable, use a genuine deliverable or state the accomplishment without a fabricated Y.

## Step 5 — Organize bullets
For a substantial entry, generally aim for 2–3 nonredundant bullets:
1. Scope and ownership.
2. Technical contribution and method.
3. Outcome, implementation, testing or other verified evidence.

This is a guideline, not a mandatory fixed pattern. A short experience may need one or two bullets.

## Step 6 — Verify
For each bullet ask:
- Does the archive explicitly support this claim?
- Is individual work distinguished from team work?
- Does the verb describe what was actually done?
- Are tool names, figures, dates and statuses correct?
- Is any ongoing or planned work misrepresented as completed?
- Could a professor or engineer ask a technical follow-up that the user can answer?
- Does the language convey something real rather than generic impressiveness?

Show uncertainties separately as **Details to verify**. Ask focused questions only when the answers would materially strengthen or correct the draft.

## Step 7 — Present proposal; await authorization
Display only the newly proposed entry or changed section, with brief rationale and unanswered questions. **Do not update an approved resume or personal statement** unless the user explicitly approves the change. Once approved, keep the same section order and preserve unmodified text; save a versioned new baseline.

## Example conversion (illustrative, source-derived)
**STAR-T evidence:** Led a five-person aerial robotic arm team; designed five-layer FreeRTOS system of ~10,000 lines of C; implemented 1 kHz motor-control and 50 Hz application/sensor threads; integrated PCBs.

**Proposed bullets:**
- Led a five-person team developing a lightweight aerial robotic arm, coordinating component selection, PCB design, embedded software and motor control.
- Built a five-layer embedded architecture (~10,000 lines of C) on STM32 and FreeRTOS, separating hardware drivers, control modules and application logic.
- Implemented 1 kHz motor-control and 50 Hz application/sensor threads and integrated custom PCBs into the embedded control system.

The bullets report implemented work and verified scope. They do not assert unverified improvements in performance.

## Quality criteria
- Specific; concise; intelligible to the intended audience.
- Concrete individual contribution and actual engineering mechanism.
- Credible outcome or evidence without forced numerical metrics.
- Faithful to the user's account and their chosen professional emphasis.
- Proposed until explicitly authorized.

## Output of Part 2
A **proposed resume experience section** and its evidence/verification notes, followed—only with approval—by a versioned update to the canonical resume.

## One-sentence summary
> **Resume Experience Writing = Structured STAR-T archive + evidence selection + XYZ-inspired compression + fact checking + human authorization.**

## Core principle
> **Select evidence first. Write concisely second. Verify before accepting.**
