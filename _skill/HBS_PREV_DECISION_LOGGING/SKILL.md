---
name: hbs_prev_decision_logging_skill
description: Use this when determining whether the grounds of judgment, the data used, the approver, and the risks reviewed are recorded without omission for a judgment in which AI was involved.
---

# AI's judgment process must be recorded — Skill

## Purpose
Confirm whether the judgment process in which AI was involved (grounds, data, approver, risks reviewed) is left as a record, thereby preventing the extinction of responsibility caused by the absence of a record.

## Input
- Cases of judgment in which AI was involved
- Whether the grounds, data used, approver, and risks reviewed for that judgment are recorded

## Procedure (Steps)
1. Check whether AI was involved in the target judgment.
2. Check whether the grounds of judgment are recorded.
3. Check whether the data used, the approver, and the risks reviewed are each recorded.
4. Determine whether any of the four items is missing.

## Output
The result of examining the completeness of the record of AI's judgment process (the four items of grounds, data, approver, risks).

## Criteria
It is judged PASS when the four items (grounds of judgment, data used, approver, risks reviewed) are all recorded, and FAIL when even one is missing.

## Derivation
[method](../../_method/hbs_prev_decision_logging_method.md) -> [knowledge](../../_knowledge/hbs_prev_decision_logging_knowledge.md) ->
[task](../../_task/hbs_prev_decision_logging_task.md) -> [goal](../../_goal/hbs_prev_decision_logging_goal.md) ->
[identity](../../_identity/HBS_PREV_DECISION_LOGGING.md)
