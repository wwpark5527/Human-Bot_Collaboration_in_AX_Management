---
name: digital_worker_subagent_skill
description: Used when evaluating the autonomy level of a digital worker (bot) on six axes to determine whether it corresponds to a Subagent (intermediate autonomy, a specialized agent that supports a higher agent).
---

# Subagent — Skill

## Purpose
Identify, among digital workers, the Subagent that performs goals assigned by a higher agent in a limited and specialized manner, and distinguish it from the AI agent and the Bot.

## Input
- The autonomy level of the target digital worker
- The goal-setting subject (itself | a higher agent | almost none), the role scope, and the mode of collaboration

## Procedure (Steps)
1. Confirm whether the target's autonomy is intermediate.
2. Confirm whether it is assigned goals by a higher agent.
3. Confirm whether the role scope is limited and specialized, collaboration is limited to internal agent collaboration, and memory/context retention is partial.
4. If all the above conditions are satisfied, determine it to be a Subagent; otherwise reclassify it as an AI agent (autonomy high) or a Bot (autonomy low).

## Output
Digital worker autonomy determination result (AI agent | Subagent | Bot), list of Subagents.

## Criteria
It is determined PASS as a Subagent when the conditions of autonomy intermediate, goals assigned by a higher agent, and role scope limited and specialized are confirmed.

## Derivation
[method](../../_method/digital_worker_subagent_method.md) -> [knowledge](../../_knowledge/digital_worker_subagent_knowledge.md) ->
[task](../../_task/digital_worker_subagent_task.md) -> [goal](../../_goal/digital_worker_subagent_goal.md) ->
[identity](../../_identity/DIGITAL_WORKER_SUBAGENT.md)
