---
identity: IND_HUMAN_JUDGMENT_RIGHT
displayName: "Human Judgment Right"
runID: 20260719_164605
derivedFromIdentity: ../_identity/IND_HUMAN_JUDGMENT_RIGHT.md
---

# Human Judgment Right — Knowledge

## Core Knowledge
- "Human judgment right" (`IND_HUMAN_JUDGMENT_RIGHT`, S2C-0517) is the **fifth indicator** constituting the "12 Inclusive Transition ESG indicators" (`INCLUSIVE_TRANSITION_ESG_12_INDICATORS`, S2C-0158, class INDEX). Definition: "an indicator that checks whether tasks requiring human approval are defined and actually observed." The criteria are "the existence of a list of tasks requiring human approval and the number of approval omissions," and the output is "a list of tasks requiring approval and the number of approval omissions."
- The higher context of the 12 indicators as a whole is source line 531 — "Furthermore, AI inclusive-transition ESG must be measurable. The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly." This indicator is placed at line 537 as the fifth item of that list.
- **This indicator looks at structure and execution as a pair.** The first value, "list of tasks requiring human approval," is the structural condition of whether a document exists, and the second value, "number of approval omissions," is the execution condition of whether that document was observed. If there is no list, the very standard by which to judge what counts as an omission does not exist, and if there is only a list without counting the omissions, one cannot know whether the document remained a declaration.
- **The second value is a 'count' and its direction is reversed.** The values of the preceding four indicators were generally ratios, hours, and distributions where higher is better, whereas the number of approval omissions is a **defect count where lower is better**. Therefore the direction in which the time series is read is also reversed, and the goal is not increase but convergence to 0.
- **The greatest measurement trap of this indicator is the scope of the list.** If the list of tasks requiring approval is written narrowly, the number of omissions automatically falls. In the extreme, if only one item is written in the list, omissions hardly occur, and looking only at the figures the organization appears well controlled. Therefore the number of omissions must always be read together with the scope the list covers, and a number of omissions without a record of the scope is not an interpretable value.
- **The second trap is detectability.** If there are no materials (approval history, processing logs, audit records) for finding cases processed without approval, omissions are invisible in the first place. The "0 omissions" that comes out in that case means not "there are no omissions" but "they cannot be detected," so the two states must be recorded as distinct. In this respect this indicator depends on nodes in the audit-record series — the approval history preserved by "7. Audit record" of the 9 steps (line 526, `STEP_AUDIT_RECORD`, WalkOrder 356) becomes the detection basis of this indicator, and the audit record indicator of the same set of 12 indicators (`IND_AUDIT_RECORD`, WalkOrder 366) measures that preservation rate separately.
- **It must be distinguished from the execution-step layer.** The fifth step of the 9-step ESG execution structure is "5. Human approval criteria" (line 524, `STEP_HUMAN_APPROVAL_CRITERIA`, WalkOrder 354), and its execution content is "defining the outputs and decisions requiring human intervention". That is, **creating** the very list whose existence this indicator confirms is step 5, and **counting** whether that list exists and is observed is this indicator. The two nodes differ in layer, and this identity does not take "defines" as its own procedure and performs only "confirms whether it is defined".
- **It must also be distinguished from the rights layer.** The fourth item of the 8 rights is "right of AI judgment: the right for humans to provide purpose, meaning, and criteria in important judgments" (line 490, `RIGHT_AI_JUDGMENT`, WalkOrder 345). The indicator's name is "human judgment right" and the right's name is "right of AI judgment," differing in prefix, but the subject the two nodes treat is the same judgment authority, and the layers differ — the right prescribes the entitlement of humans to be involved in judgment, and this indicator counts whether that involvement was prescribed in a list and actually observed. **This node must not be read as a right merely because the indicator's name contains "right"**; what is measured is the operational facts of the list's existence and the number of omissions.
- The problem this indicator seeks to expose is itself already conceptualized in the preceding section. The judgment-authority item in the discussion of AI-based stratification is `GAP_AI_JUDGMENT_RIGHT` (AI judgment right gap, WalkOrder 312), and if approval omissions appear concentrated in particular departments or grades, that is read as a signal that judgment authority is not operating evenly within the organization.
- **The ordering logic with respect to the preceding indicator.** If labor transition (line 536) looked at whether people were pushed aside in the phase where jobs change, this indicator looks at whether the human's seat of judgment is maintained within the remaining work. Even if the seat is maintained, if actual approval is not carried out in that seat, judgment becomes a formality, so the very order of the list, the judgment right coming after transition, carries meaning.
- In the Stage-1 structure, S1C-183 was classified as class **INDEX** (a value transferred as is from the Stage-1 C0 row), and in Stage-2 it was SPLIT and divided into individual indicator fragments. This candidate is the **fifth fragment** of that.
- **Note the placement of the source list.** The list of 12 indicators is not continuous. The indicators continue at lines 533-539, then at line 541 a paragraph concerning the EU AI Act, UNESCO, and the OECD is inserted, and the remaining indicators resume at lines 543-548. This identity (line 537) lies before that interruption point and is unaffected, but when quoting the latter part of the list the line numbers must be confirmed individually.

## Source Evidence Quotation
> "Furthermore, AI inclusive-transition ESG must be measurable. The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly."

> "Human judgment right: list of tasks requiring human approval, number of approval omissions"

> "Right of AI judgment: the right for humans to provide purpose, meaning, and criteria in important judgments"

> "5. Human approval criteria / Defining the outputs and decisions requiring human intervention / G"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 531-548 (the item in question 537), 490, 524

## Derivation
[identity](../_identity/IND_HUMAN_JUDGMENT_RIGHT.md)
