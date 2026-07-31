---
name: core_role_operator_skill
description: Used when deliverables must be kept operating continuously, and when it must be confirmed through deployment, monitoring, and maintenance that a deliverable does not stop at a one-time result but keeps operating continuously.
---

# Operator — Skill

## Purpose
Deploy the output artifact whose reliability the validator secured, and manage it so that it keeps operating continuously.

## Input
- The output artifact that has passed verification
- The deployment environment and monitoring criteria

## Procedure (Steps)
1. Deploy the validated deliverable.
2. Monitor the operating status.
3. Perform maintenance when problems occur.
4. Confirm whether the deliverable keeps operating continuously.

## Output
Continuity — the continuous operation of the deliverable.

## Criteria
If the deliverable does not stop at a one-time result but keeps operating continuously it is judged PASS (continuity secured), and if operation halts or maintenance is not performed it is judged FAIL (operational continuity not met).

## Derivation
[method](../../_method/core_role_operator_method.md) -> [knowledge](../../_knowledge/core_role_operator_knowledge.md) ->
[task](../../_task/core_role_operator_task.md) -> [goal](../../_goal/core_role_operator_goal.md) ->
[identity](../../_identity/CORE_ROLE_OPERATOR.md)
