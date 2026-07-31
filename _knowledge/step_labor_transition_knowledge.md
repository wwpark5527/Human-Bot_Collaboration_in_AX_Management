---
identity: STEP_LABOR_TRANSITION
displayName: "4. Labor Transition"
runID: 20260719_164605
derivedFromIdentity: ../_identity/STEP_LABOR_TRANSITION.md
---

# 4. Labor Transition — Knowledge

## Core Knowledge
- "4. Labor Transition" (`STEP_LABOR_TRANSITION`, S2C-0507) is the **fourth execution step** constituting "ESG execution structure (AI Inclusive-Transformation ESG execution model, 9 steps)" (`ESG_EXECUTION_STRUCTURE`, S2C-0157, class METHOD). Definition: "the step of designing job impact assessment, reskilling, and role reconfiguration." The criterion is "whether a job impact assessment was conducted before AI introduction and reskilling and role reconfiguration were designed," and the output is "the job impact assessment result, the reskilling plan, and the reconfigured roles (measured by the transition-placement rate)." The ESG linkage is S alone.
- The source presents the 9 steps in the form of a three-column table `Step / Execution Content / ESG Linkage` inside a code block (lines 518-529), and the fourth row is "4. Labor Transition          Design job impact assessment, reskilling, role reconfiguration                S" (line 523). The word "Design" placed at the head of the `Execution Content` column is exactly as the source table was typeset, and in sense it indicates that this step is the step of **designing** job impact assessment, reskilling, and role reconfiguration. The higher-level context of all 9 steps is the sentence "AI Inclusive-Transformation ESG must not remain a declaration of philosophy. It must come down into an operating model that can be executed inside the organization" (line 516).
- **The objects of design are three** — job impact assessment, reskilling, and role reconfiguration. That the criterion specifies "**before** AI introduction" is the core constraint of this step. It must be advance design before introduction, not after-the-fact remediation following introduction.
- **[Important] This identifier is an execution step, not a measurement indicator.** Two nodes with overlapping names exist within the same document:
  - **`STEP_LABOR_TRANSITION` (this identifier, WalkOrder 353, S2C-0507)** — **step 4 of the 9-step execution model** of Inclusive-Transformation ESG. Line 523. It is the execution step the organization *carries out*.
  - **`IND_LABOR_TRANSITION` (WalkOrder 362, S2C-0516)** — the "labor transition" indicator, an item of the **12 indicators** of Inclusive-Transformation ESG. Line 536, "Labor transition: whether a job impact assessment was conducted before AI introduction, transition placement rate." It is the measurement item that *confirms* whether the organization operates responsibly.
  The two nodes have different parents (the 9-step model vs. the 12 indicators), different positions in the source (line 523 vs. line 536), and different natures (execution vs. measurement). This file has been written solely as an **execution step** and does not mix in the language of indicators. That "measured by the transition-placement rate" is included in this step's output definition is because the Stage-2 SplitSet child row prescribed it so, and it was not brought in from the indicator layer.
- Line 531 of the source introduces the 12 indicators, stating "furthermore, AI Inclusive-Transformation ESG must be measurable. The following indicators (provisionally, the Inclusive-Transformation ESG 12 indicators) are the basic items for confirming whether the organization operates AI transformation responsibly" — this is the document's own declaration that the 9 steps (execution) and the 12 indicators (measurement) are introduced as separate layers.
- A corresponding node also exists in the rights layer. `RIGHT_AI_TRANSITION` (the AI right of transition, WalkOrder 348) is "the right to receive role redesign and transition education when a job changes due to the introduction of AI," the seventh of the 8 rights. That is, the same matter unfolds across three layers: **the right (the right of transition) → the execution step (4. Labor Transition) → the measurement indicator (the labor transition indicator)**. This identifier is located in the execution-step layer among them.
- In the order of steps, this step is placed after step 3, authority design, and before step 5, human approval criteria. The flow is that after access authority is determined, people's jobs are redesigned, and then it is determined which judgments require human approval.
- In the Stage-1 structure, S1C-182 was classified as class METHOD, and in Stage-2 it was SPLIT into 9 independent fragments. This candidate is the **fourth fragment** of those.

## Source Evidence Quotation
> "AI Inclusive-Transformation ESG must not remain a declaration of philosophy. It must come down into an operating model that can be executed inside the organization."

> "4. Labor Transition          Design job impact assessment, reskilling, role reconfiguration                S"

> "Furthermore, AI Inclusive-Transformation ESG must be measurable. The following indicators (provisionally, the Inclusive-Transformation ESG 12 indicators) are the basic items for confirming whether the organization operates AI transformation responsibly."

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 514-529 (the relevant item at 523), 516, 531, 536

## Derivation
[identity](../_identity/STEP_LABOR_TRANSITION.md)
