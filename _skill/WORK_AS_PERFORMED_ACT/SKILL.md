---
name: work_as_performed_act_skill
description: Used when the fact itself of whether some act was actually performed must be identified and recorded, and when it must be treated separately from whether the result of that act led to a valid change (contribution).
---

# Work — Skill

## Purpose
By identifying the performed act itself in separation from its result (whether there was a change), it provides the basic material for the subsequent judgment of contribution and role.

## Input
- A list of acts reported as having been performed (e.g. the AI's writing of a sentence, summarizing material, reviewing)

## Procedure (Steps)
1. Specify the performed act.
2. Confirm only whether that act actually took place.
3. Do not judge whether the result of the act produced a change, and pass it on to a separate stage.
4. Leave the fact of the act's performance as a record.

## Output
The fact of performance — a record of the act, independent of whether it led to a change.

## Criteria
If the act was actually performed it is judged PASS (fact of performance confirmed), and if the act itself did not take place it is judged FAIL (not performed).

## Derivation
[method](../../_method/work_as_performed_act_method.md) -> [knowledge](../../_knowledge/work_as_performed_act_knowledge.md) ->
[task](../../_task/work_as_performed_act_task.md) -> [goal](../../_goal/work_as_performed_act_goal.md) ->
[identity](../../_identity/WORK_AS_PERFORMED_ACT.md)
