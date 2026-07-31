---
name: ind_human_judgment_right_skill
description: Used when the existence of a list of tasks requiring human approval and the number of approval omissions must be measured. It produces the fifth of the 12 Inclusive Transition ESG indicators.
---

# Human Judgment Right — Skill

## Purpose
By calculating the existence of the list of tasks requiring human approval and the number of approval omissions, make it possible to confirm whether the tasks a human must judge are actually prescribed and whether that prescription is observed in operation. It measures the fifth of the Inclusive-Transition ESG 12 indicators.

## Input
- The document of the list of tasks requiring human approval and its revision history, approval history and processing logs, audit records, records of the release and completion of AI outputs, the table of approval authority assignments, and the measurement results of the previous cycle (for time-series comparison)

## Procedure (Steps)
1. Confirm the existence of the list of tasks requiring approval, whether it is finally approved, and its most recent revision date.
2. Record the scope of tasks and decisions the list covers and the excluded items.
3. State explicitly the source materials for detecting omissions, and mark as undetectable the ranges with no such source.
4. Detect the cases among the tasks falling under the list that were processed without approval.
5. Tally the number of approval omissions by type (no approval, approval without authority, formal after-the-fact approval).
6. Present the scope of the list and the number of omissions bound together as one reporting unit, and if there has been a narrowing of the scope, state it explicitly.
7. Fix a measurement cycle and accumulate a time series on the same standard.

## Output
The list of tasks requiring approval and the number of approval omissions — the location, most recent revision date, and covered scope of the list, the detection source materials and the undetectable ranges, the number of approval omissions by type, the record of changes in scope, the time-series record.

## Criteria
With the list existing as a finally approved version and its scope recorded, it is judged PASS when the number of approval omissions is tallied by type with the detection basis stated explicitly and reported together; it is judged FAIL if the scope was not recorded, if 0 omissions was reported without a detection basis, or if only the existence of the list was confirmed and the number of omissions was not produced.

## Derivation
[method](../../_method/ind_human_judgment_right_method.md) -> [knowledge](../../_knowledge/ind_human_judgment_right_knowledge.md) ->
[task](../../_task/ind_human_judgment_right_task.md) -> [goal](../../_goal/ind_human_judgment_right_goal.md) ->
[identity](../../_identity/IND_HUMAN_JUDGMENT_RIGHT.md)
