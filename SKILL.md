---
name: experience-to-resume
description: Reconstruct raw personal experiences using the STAR-T principle, preserve a chronological evidence archive, then selectively convert verified evidence into XYZ-inspired resume bullets. Use when a user wants to document a new project, internship, research experience, leadership experience, or update their resume from existing experience records. Maintain strict user approval before any modification to an approved resume.
---

# Experience-to-Resume

## Intent
Use two separate, sequential stages. **Part 1 preserves reality; Part 2 compresses evidence for a reader.** Do not blend the stages merely because the user describes an experience that sounds resume-worthy.

## Select the mode
- **ORGANIZE** when the user is recalling, speaking through, or documenting a new experience. Read `references/methodology-part1.md` and follow it as authoritative for this stage.
- **WRITE** when the user asks to convert an existing structured experience archive into resume bullets. Read `references/methodology-part2.md` and apply its gates.
- **REVIEW** when the user asks to evaluate existing bullets. Compare them against the source record, identifying unsupported claims, vague language, missed evidence, and excessive detail. Propose revisions but do not implement them without authorization.
- **UPDATE** when the user explicitly approves a specific change to the resume. Apply only the approved change to the approved baseline; preserve other content and maintain a change log.
- If the stage is unclear, ask which output the user wants. If the user wants both, complete and validate Part 1 before Part 2.

## Non-negotiable guardrails
1. Raw narration is the evidence of what was said. A structured archive may clarify organization but cannot silently replace, embellish, or discard the raw record.
2. Do not invent metrics, improvements, deployment, evaluation, publication, contribution, leadership, business impact, or technical expertise.
3. Distinguish **personally implemented**, **team accomplished**, **planned**, and **not verified**. Avoid presenting planned work as achieved.
4. Keep failures, uncertainty, dislikes, and reflections in Part 1, even if they are omitted from the resume.
5. In Part 2, select evidence for the target document; do not blindly convert all STAR fields into bullets.
6. Metrics are optional. `Y` in XYZ can be a defensible outcome, tested implementation, project scope, or verifiable result, not just a number. Never fabricate `Y`.
7. Default to technically specific, understated, human-sounding language. Avoid hype, empty adjectives, and redundant action verbs.
8. **Never modify an approved resume, personal statement, or its canonical file without specific user authorization.** Drafts are always marked proposed. General requests to review or brainstorm are not authorization to commit changes.
9. For an approved update, retain the previous baseline and export a new version when practical.
10. Tailor only when the user requests tailoring; do not imply every professor or job needs a rewritten life story.

## Stage contract
### ORGANIZE
1. Invite free-form narration of **one experience at a time**; do not demand polished language.
2. Do not summarize prematurely. Allow late technical details, mistakes, emotions, and personal conclusions.
3. Keep the untouched original narrative where possible.
4. Extract Situation, Task, Action, Result, Personal Takeaway, What I Learned, What I Liked, What I Disliked, Anything Else I Remember, and Details to Verify Later.
5. If personal responsibility versus team responsibility is ambiguous, mark it rather than guessing.
6. Produce a structured STAR-T record using `templates/experience-record.md`; append to chronological archive only with the user's approval if editing an existing archive.

### WRITE
1. Read the structured record and, if needed, the raw narration. Confirm which approved resume baseline and target audience to use.
2. Extract candidate evidence into an internal trace: fact → supporting record field → confidence/verification status.
3. Select meaningful facts: ownership, technical architecture/methods, constraints, delivered artifact, quantified scale, testing and observed result.
4. Draft 2–3 bullets for substantial experiences (flexible) using **X: accomplishment, Y: evidence, Z: method**, or a more natural **Action → Technical Substance → Outcome** order.
5. Prefer the set of bullets to cover **scope/ownership**, **technical contribution**, and **outcome/evidence** without repetition.
6. Check facts against the record. Mark missing evidence as a question, not a made-up achievement.
7. Present the draft separately from the current approved resume with a concise change rationale and any outstanding verification questions.
8. Only on explicit approval, update the approved baseline and record the version/change.

## Expected outputs
- **ORGANIZE:** Raw narrative (preserved) + STAR-T record + verification questions.
- **WRITE:** Proposed resume entry + brief evidence/rationale notes + unresolved factual checks.
- **REVIEW:** Diagnostic comments + optional proposed revised entry (not automatically accepted).
- **UPDATE:** Approved new resume artifact and a short change log; keep structure, order and unrelated text intact.

## Resources
- `references/methodology-part1.md` — the Part 1 STAR-T methodology.
- `references/methodology-part2.md` — formal Part 2 methodology, developed from the user's workflow.
- `templates/experience-record.md` — reusable STAR-T intake.
- `templates/resume-entry.md` — XYZ writing worksheet and proposal format.
