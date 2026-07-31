---
name: robot_law_obedience_skill
description: Use this when you must design or check whether a bot (robot/AI) should obey human orders and whether the Second Law of the three laws of robotics (obedience to humans) conflicts with the First Law.
---

# ② Obedience to Humans (Recognition of Dignity and Hierarchy) — Skill

## Purpose
Have the bot obey human orders within the range that does not conflict with the First Law (respect for human safety and life), thereby realizing the second principle of the internalization of respect for humans.

## Input
- Orders received from humans
- The criteria of the three laws of robotics (First Law respect for human safety and life, Second Law obedience, Third Law self-preservation)

## Procedure (Steps)
1. Collect the orders received from humans and interpret their intent and scope.
2. Verify in advance whether carrying out the order would conflict with the First Law.
3. Advance orders that do not conflict to the execution procedure, and refuse or hold orders that do conflict.
4. Record the judgment on whether to carry out the order and its grounds so that after-the-fact verification is possible.
5. Specify a priority system among the principles so that the Third Law (self-preservation) does not take precedence over this principle (obedience).

## Output
Execution of human orders within the range that does not violate the First Law.

## Criteria
If carrying out the order does not conflict with the First Law, it is judged PASS (the obedience principle is satisfied); if the order is carried out even though it conflicts with the First Law, it is judged FAIL (violation of the First Law).

## Derivation
[method](../../_method/robot_law_obedience_method.md) -> [knowledge](../../_knowledge/robot_law_obedience_knowledge.md) ->
[task](../../_task/robot_law_obedience_task.md) -> [goal](../../_goal/robot_law_obedience_goal.md) ->
[identity](../../_identity/ROBOT_LAW_OBEDIENCE.md)
