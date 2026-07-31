---
name: ind_accountability_structure_skill
description: Used when calculating the rate of designating a final responsible party for AI outputs each quarter in order to fix the size of the organization's accountability gap as a single figure. Department-level designation is treated as non-designation, prior designation and retroactive after-the-fact designation are separated, and PASS is judged only after the per-department minimum and the authority sample verification are complete.
---

# ind_accountability_structure_skill — Measuring the Accountability Structure Designation Rate

## Purpose

Measure **accountability structure**, the ninth item of the 12 Inclusive Transition ESG indicators. The value produced is one — the rate of designating a final responsible party for AI outputs. This skill does not design or improve an accountability structure. It counts whether what was designed was actually designated, and inspects whether that figure is trustworthy.

## Input

- The measurement period (quarter) and the unit definition of one AI output (as fixed in a document).
- The list of AI outputs within the measurement period and their total number.
- The recorded final responsible party and the time of recording for each output — collected from approval records, output metadata, and sign-off history.
- Department classification information.
- The baseline values announced in advance (company-wide designation rate, per-department minimum, prior-designation ratio).
- The values of the immediately preceding quarter and the same quarter of the previous year.

## Procedure

1. Confirm the AI output unit definition and fix the denominator N. If the definition was changed during the period, mark it as incomparable.
2. Collect the recorded final responsible party for each output and record the collection source.
3. Classify into three branches — (A) one person designated by an individual identifier, (B) only a department, team, or job title recorded, or multiple parties recorded, (C) no record.
4. Calculate the designation rate = (A) ÷ N × 100.
5. Divide (A) into prior designation and retroactive after-the-fact designation and calculate the prior-designation ratio. Cases whose time cannot be determined are treated as after-the-fact.
6. Repeat steps 3 to 4 at the department level and state the department with the minimum.
7. Draw a sample from (A) and confirm whether the designated responsible party holds the authority of access, modification, and suspension. Cases without authority are reclassified into (B) and step 4 onward is recalculated.
8. Compare with the immediately preceding quarter and the same quarter of the previous year.
9. Decide PASS/FAIL according to the criteria and record it together with the grounds.

## Output

- **The final-responsible-party designation rate figure** (one company-wide value).
- A table of per-department designation rates, the minimum and the department in question.
- The prior-designation ratio, the number of retroactive after-the-fact designations.
- (B) the number of not-individually-identified cases, (C) the number of unrecorded cases.
- The authority sample verification result and the number of reclassifications.
- The trend against the immediately preceding quarter and the same quarter of the previous year.
- The PASS/FAIL judgment and the list of unsatisfied conditions.

## Criteria

It is PASS only when **all** four conditions are satisfied.

- (a) The company-wide designation rate is at or above the baseline announced in advance.
- (b) The **minimum** of the per-department designation rates is at or above the baseline — if only the average is satisfied, FAIL.
- (c) The prior-designation ratio is at or above the standard — if it is mostly retroactive after-the-fact designation, FAIL.
- (d) It passes the authority sample verification — when reclassification occurs, judge again after recalculation.

Explicit FAIL conditions: a designation rate that put department-level designation into the numerator (the figure is invalid), a designation rate submitted without a prior-designation ratio, submission of one company-wide value alone without decomposition by department.

If the designation rate is low, first distinguish **whether it is an absence of designation or an absence of records**, and if the latter, state explicitly in the judgment record that the cause lies outside this indicator.

## Derivation
[method](../../_method/ind_accountability_structure_method.md) -> [knowledge](../../_knowledge/ind_accountability_structure_knowledge.md) ->
[task](../../_task/ind_accountability_structure_task.md) -> [goal](../../_goal/ind_accountability_structure_goal.md) ->
[identity](../../_identity/IND_ACCOUNTABILITY_STRUCTURE.md)
