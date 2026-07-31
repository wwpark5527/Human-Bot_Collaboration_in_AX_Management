---
identity: IND_LABOR_TRANSITION
displayName: "Labor Transition"
runID: 20260719_164605
derivedFromIdentity: ../_identity/IND_LABOR_TRANSITION.md
---

# Labor Transition — Knowledge

## Core Knowledge
- "Labor transition" (`IND_LABOR_TRANSITION`, S2C-0516) is the **fourth indicator** constituting the "12 Inclusive Transition ESG indicators" (`INCLUSIVE_TRANSITION_ESG_12_INDICATORS`, S2C-0158, class INDEX). Definition: "an indicator that checks whether the job changes caused by AI adoption were assessed in advance and connected to reassignment through transition." The criteria are "whether a job impact assessment was conducted before AI adoption, and the transition-reassignment rate," and the output is "whether the impact assessment was conducted and the transition-reassignment rate."
- The higher context of the 12 indicators as a whole is source line 531 — "Furthermore, AI inclusive-transition ESG must be measurable. The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly." This indicator is placed at line 536 as the fourth item of that list.
- **The two values of this indicator differ in character.** Whereas the preceding three indicators placed continuous values such as ratios, hours, and distributions as pairs, this indicator pairs a **yes/no** with a **ratio**. "Whether a job impact assessment was conducted before AI adoption" is a gate dividing whether a condition was satisfied or not, and the "transition-reassignment rate" is the value measuring how far it then proceeded. For an adoption case that did not pass the gate, however high the reassignment rate is, the order this indicator demands is not satisfied.
- **The timing condition "before adoption" is the core of this indicator.** The source text wrote not simply "whether a job impact assessment was conducted" but "whether a job impact assessment was conducted **before** AI adoption". An impact assessment written after the fact is merely a document recording job changes that have already occurred and leaves no room to design a transition, so in this indicator it is not tallied as conducted. Therefore the measurement must always include a procedure confirming the date of writing of the assessment document and the point of adoption separately from source materials.
- **The denominator of the transition-reassignment rate is the second issue.** If the denominator is taken as the whole workforce, then when the people affected are few the reassignment rate appears higher than it actually is. What this indicator seeks to see is "whether the people affected were transitioned," so the denominator must be the people judged in the impact assessment to have their jobs substantively changed. It must also be managed alongside that unless the ranges of incomplete reassignment and departure are marked separately, attrition may quietly drop out of the denominator and inflate the reassignment rate.
- **It must be strictly distinguished from the execution step whose name coincides completely.** The fourth step of the 9-step ESG execution structure is "4. Labor transition" (line 523, `STEP_LABOR_TRANSITION`, WalkOrder 353), and its execution content is "design job impact assessment, reskilling, role reconstruction". The Korean concept name of that step is **exactly the same "labor transition"** as this indicator (on the step side, the step number "4." is prefixed in the notation). But the layers differ — the step is an execution procedure that **performs** job impact assessment and role reconstruction, and this indicator is a measurement item that **counts** whether that performance took place before adoption and how many were reassigned as a result. That is, step 4 is the object of measurement of this indicator. This identity does not take execution verbs such as "designs" and "reconstructs" as its own procedure.
- **It must also be distinguished from the rights layer.** The seventh item of the 8 rights is "right of AI transition: the right to receive role redesign and transition education when a job changes through AI adoption" (line 493, `RIGHT_AI_TRANSITION`, WalkOrder 348). The right prescribes what one is entitled to receive when a job changes, and this indicator confirms in figures how far that entitlement was actually fulfilled. This identity does not use the language of rights ("the right to receive ~", "guarantees").
- The job impact assessment corresponds to the labor aspect of a broader impact assessment procedure. The first of the 9 steps, "1. AI impact assessment" (line 520, `STEP_AI_IMPACT_ASSESSMENT`, WalkOrder 350), is the step that assesses "the impact of AI on labor, judgment, authority, customers, and human rights", and the job impact assessment whose conduct this indicator confirms is the labor aspect thereof, made concrete at step 4.
- **The ordering logic with respect to the preceding indicator.** If AI utilization capability (line 535) asked whether AI utilization was converted into work performance, this indicator asks what happened to the people whose jobs change as that utilization expands. Since productivity gains and job change are two sides of the same change, if the transition-reassignment rate appears low in the range where utilization performance grows, that is read as a signal that only efficiency was taken and the responsibility for transition was not borne.
- In the Stage-1 structure, S1C-183 was classified as class **INDEX** (a value transferred as is from the Stage-1 C0 row), and in Stage-2 it was SPLIT and divided into individual indicator fragments. This candidate is the **fourth fragment** of that.
- **Note the placement of the source list.** The list of 12 indicators is not continuous. The indicators continue at lines 533-539, then at line 541 a paragraph concerning the EU AI Act, UNESCO, and the OECD is inserted, and the remaining indicators resume at lines 543-548. This identity (line 536) lies before that interruption point and is unaffected, but when quoting the latter part of the list the line numbers must be confirmed individually.

## Source Evidence Quotation
> "Furthermore, AI inclusive-transition ESG must be measurable. The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly."

> "Labor transition: whether a job impact assessment was conducted before AI adoption, transition-reassignment rate"

> "Right of AI transition: the right to receive role redesign and transition education when a job changes through AI adoption"

> "4. Labor transition / Design job impact assessment, reskilling, role reconstruction / S"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 531-548 (the item in question 536), 493, 523

## Derivation
[identity](../_identity/IND_LABOR_TRANSITION.md)
