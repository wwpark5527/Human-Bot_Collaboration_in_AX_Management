---
name: arbi_axis_role_balance_skill
description: Use this when evaluating whether the needed roles have been assigned to fit the situation in a collaboration the AI intervened in, that is, ARBI's Role Balance axis.
---

# Role Balance — Skill

## Purpose
It compares the roles needed in the collaboration against the roles actually assigned, determines the adequacy of role assignment, and reveals the risks of role imbalance (vacancy, excess, concentration).

## Input
- Records of the collaboration scene under evaluation
- A list of the roles needed in that collaboration
- Information on the roles actually assigned to the human and the AI

## Procedure (Steps)
1. Specify the collaboration scene under evaluation.
2. Enumerate the roles needed in the collaboration.
3. Confirm the roles actually assigned.
4. Compare the needed roles against the actual assignment to identify vacancy, excess, and concentration.
5. Determine the adequacy of role assignment and record the imbalance risks.

## Output
A judgment on the adequacy of role assignment and a list of role imbalance risks.

## Criteria
If the needed roles are assigned to fit the situation, it is judged PASS; if there is even one instance of vacancy, excess, or concentration, it is judged FAIL.

## Derivation
[method](../../_method/arbi_axis_role_balance_method.md) -> [knowledge](../../_knowledge/arbi_axis_role_balance_knowledge.md) ->
[task](../../_task/arbi_axis_role_balance_task.md) -> [goal](../../_goal/arbi_axis_role_balance_goal.md) ->
[identity](../../_identity/ARBI_AXIS_ROLE_BALANCE.md)
