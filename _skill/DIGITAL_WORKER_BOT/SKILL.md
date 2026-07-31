---
name: digital_worker_bot_skill
description: Used when evaluating the autonomy level of a digital worker (bot) on six axes to determine whether it corresponds to a Bot (the lowest autonomy, a rule-based automation program).
---

# Bot — Skill

## Purpose
Identify, among digital workers, the Bot that automatically performs simple and repetitive work according to designated rules, and distinguish it from the AI agent and the Subagent.

## Input
- The autonomy level of the target digital worker
- Whether goal setting exists, the role scope, the mode of decision-making (whether rule-based), the scope of collaboration, and the degree of memory/context retention

## Procedure (Steps)
1. Confirm whether the target's autonomy is low.
2. Confirm whether goal setting is almost absent.
3. Confirm whether the role scope is simple and repetitive, decision-making is rule-based centered, collaboration is limited, and memory/context retention is weak.
4. If all six axes are at the lowest value, determine it to be a Bot; otherwise reclassify it as a Subagent (intermediate) or an AI agent (highest).

## Output
Digital worker autonomy determination result (AI agent | Subagent | Bot), list of Bots.

## Criteria
It is determined PASS as a Bot when all six axes — autonomy, goal setting, role scope, decision-making, collaboration, and memory — are at the lowest value.

## Derivation
[method](../../_method/digital_worker_bot_method.md) -> [knowledge](../../_knowledge/digital_worker_bot_knowledge.md) ->
[task](../../_task/digital_worker_bot_task.md) -> [goal](../../_goal/digital_worker_bot_goal.md) ->
[identity](../../_identity/DIGITAL_WORKER_BOT.md)
