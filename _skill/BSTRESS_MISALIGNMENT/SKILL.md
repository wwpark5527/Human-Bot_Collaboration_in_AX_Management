---
name: bstress_misalignment_skill
description: Used to determine whether a case falls under the misalignment bot stress that arises when the AI fails to align with human values.
---

# Misalignment — Skill

## Purpose
Determine whether a bot's unstable behavior falls under misalignment among the bot stress types (5 types), and provide the grounds for realignment measures per cause.

## Input
- The bot's training data, rule system, command history, and governance policy documents
- Observed logs of the bot's behavior (whether unpredictability, emergent behavior, or policy violation occurred)

## Procedure (Steps)
1. Confirm whether there is bias, incompleteness, conflict, or ambiguity in the bot's data, rules, commands, and governance system.
2. Confirm whether increased unpredictability, emergent behavior, or the risk of policy violation is observed in the bot's behavior.
3. If both conditions are confirmed, judge it misalignment.
4. Produce the priority of realignment measures per causal area (data/rules/commands/governance).

## Output
The judgment result of whether the target bot's state falls under misalignment, and the priority of realignment measures per cause.

## Criteria
It is judged PASS (misalignment) when one or more of data bias, incomplete rules, conflicting commands, or governance ambiguity is confirmed together with one or more of increased unpredictability, emergent behavior, or policy violation, and FAIL (another bot stress type) otherwise.

## Derivation
[method](../../_method/bstress_misalignment_method.md) -> [knowledge](../../_knowledge/bstress_misalignment_knowledge.md) ->
[task](../../_task/bstress_misalignment_task.md) -> [goal](../../_goal/bstress_misalignment_goal.md) ->
[identity](../../_identity/BSTRESS_MISALIGNMENT.md)
