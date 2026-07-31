---
name: digital_worker_ai_agent_skill
description: Used when evaluating the autonomy level of a digital worker (bot) on six axes to determine whether it corresponds to an AI agent (the highest autonomy).
---

# AI agent — Skill

## Purpose
Identify, among digital workers, the autonomous AI actor that understands a goal, plans on its own, and executes, that is, the AI agent, and distinguish it from the Subagent and the Bot.

## Input
- The autonomy level of the target digital worker
- Whether goal setting is possible, the role scope, whether decision-making is possible, the mode of collaboration, and the degree of memory/context retention

## Procedure (Steps)
1. Confirm whether the target's autonomy is high.
2. Confirm whether it can set goals on its own (even partially).
3. Confirm whether the role scope is comprehensive and complex, decision-making is possible, it collaborates with humans and other agents, and memory/context retention is strong.
4. If all six axes are at the top value, determine it to be an AI agent; otherwise reclassify it as a Subagent (intermediate) or a Bot (lowest).

## Output
Digital worker autonomy determination result (AI agent | Subagent | Bot), list of AI agents.

## Criteria
It is determined PASS as an AI agent when all six axes — autonomy, goal setting, role scope, decision-making, collaboration, and memory — are at the top value.

## Derivation
[method](../../_method/digital_worker_ai_agent_method.md) -> [knowledge](../../_knowledge/digital_worker_ai_agent_knowledge.md) ->
[task](../../_task/digital_worker_ai_agent_task.md) -> [goal](../../_goal/digital_worker_ai_agent_goal.md) ->
[identity](../../_identity/DIGITAL_WORKER_AI_AGENT.md)
