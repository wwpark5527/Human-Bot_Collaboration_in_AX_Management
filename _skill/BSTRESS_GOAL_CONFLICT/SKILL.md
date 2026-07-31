---
name: bstress_goal_conflict_skill
description: Used to determine whether a case falls under the goal conflict bot stress that arises when different goals are demanded simultaneously in an agentic AI.
---

# Goal Conflict — Skill

## Purpose
Determine whether a bot's anomalous behavior falls under goal conflict among the bot stress types (5 types), and provide the grounds for adjusting goal priorities.

## Input
- The list of goals assigned to the bot and the relative weight of each goal
- Observed logs of the bot's behavior (whether oscillation, repetitive loops, or inconsistent behavior occurred)

## Procedure (Steps)
1. Confirm whether conflicting relationships such as speed vs. accuracy, profitability vs. ethics, or user satisfaction vs. governance compliance exist among the goals assigned to the bot.
2. Confirm whether oscillation, repetitive loops, or inconsistent behavior is observed in the bot's behavior.
3. If both conditions are confirmed, judge it goal conflict.
4. Produce a priority-adjustment proposal for each conflicting goal pair.

## Output
The judgment result of whether the target bot's state falls under goal conflict, and a proposal for adjusting goal priorities.

## Criteria
It is judged PASS (goal conflict) when conflicting goal pairs exist and one or more of oscillation, repetitive loops, or inconsistent behavior is confirmed, and FAIL (another bot stress type) otherwise.

## Derivation
[method](../../_method/bstress_goal_conflict_method.md) -> [knowledge](../../_knowledge/bstress_goal_conflict_knowledge.md) ->
[task](../../_task/bstress_goal_conflict_task.md) -> [goal](../../_goal/bstress_goal_conflict_goal.md) ->
[identity](../../_identity/BSTRESS_GOAL_CONFLICT.md)
