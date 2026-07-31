---
name: dynamic_role_balance_skill
description: Used when a dynamic role balance that switches and reallocates human-AI role combinations in real time according to situational changes such as crisis, innovation, and operations must be designed and operated in an AX organization.
---

# Dynamic role balance — Skill

## Purpose
Break away from static role assignment and reallocate the optimal human-AI role combination for each situation in real time, thereby transforming the organization into a living role ecosystem.

## Input
- Information for judging the current situation the organization faces (crisis/innovation/operations, and so on)
- A correspondence table of human roles and AI support elements by situation

## Procedure (Steps)
1. Monitor the organization's situation and detect types such as crisis, innovation, and operations.
2. Confirm the role combination for each situation type (for example, crisis -> shaper + AI risk agent, innovation -> creator + Creative AI, operations -> implementer + Workflow bot).
3. Activate and reallocate the role combination suited to the detected situation in real time.
4. Readjust the role assignment when the situation changes.

## Output
Situationally reallocated dynamic role compositions.

## Criteria
If the role combination is reallocated in real time in response to changes in the situation it is judged PASS, and if roles remain fixed it is judged FAIL.

## Derivation
[method](../../_method/dynamic_role_balance_method.md) -> [knowledge](../../_knowledge/dynamic_role_balance_knowledge.md) ->
[task](../../_task/dynamic_role_balance_task.md) -> [goal](../../_goal/dynamic_role_balance_goal.md) ->
[identity](../../_identity/DYNAMIC_ROLE_BALANCE.md)
