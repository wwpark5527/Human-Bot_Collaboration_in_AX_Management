---
name: ax_role_trust_manager_skill
description: Used to perform the Trust Manager role when members' trust in AI in an AX organization must be measured and adjusted so that it does not tilt toward either overconfidence or distrust.
---

# Trust Manager — Skill

## Purpose
Manage the level of organizational members' trust in AI within an appropriate range so as to lower the risks on both sides of blind faith and distrust.

## Input
- Records of members' acceptance rate, appeals and requests for re-verification regarding AI outputs
- The history of past AI errors and successes

## Procedure (Steps)
1. Collect members' expressions of trust in AI outputs.
2. Analyze the level of trust and identify the ranges of deviation toward overconfidence or distrust.
3. Grasp the causes of the deviation.
4. Adjust the level of trust by providing explanations, guiding verification procedures, and so on.

## Output
The result of AI trust management.

## Criteria
If the result of AI trust management is produced and measures to adjust the deviation are implemented, it is judged PASS; otherwise it is judged FAIL.

## Derivation
[method](../../_method/ax_role_trust_manager_method.md) -> [knowledge](../../_knowledge/ax_role_trust_manager_knowledge.md) ->
[task](../../_task/ax_role_trust_manager_task.md) -> [goal](../../_goal/ax_role_trust_manager_goal.md) ->
[identity](../../_identity/AX_ROLE_TRUST_MANAGER.md)
