---
name: bot_level3_planner_strategist_skill
description: Use this when goal setting and task decomposition are needed in a multi-bot/agent ecosystem and the Planner/Strategist hierarchy function must be implemented — decomposing higher goals into subgoals that lower executing agents can handle.
---

# Level 3 Planner/Strategist — Skill

## Purpose
At Level 3 of the bot hierarchy, implement the function of setting the higher goal and decomposing it into executable sub-tasks.

## Input
- The goal and policy constraints given by a higher agent or by the organization
- Information on the execution capability of the lower-level (Level 1-2) agents

## Procedure (Steps)
1. Confirm and clarify the goal given from above.
2. Formulate the strategy for achieving the goal.
3. Decompose the strategy into executable sub-tasks (subgoals).
4. Allocate the decomposed sub-tasks to the appropriate Level 2 / Level 1 agents.
5. Re-check the executability and completeness of the decomposed tasks.

## Output
A goal setting document, a sub-task decomposition list (subgoal breakdown), and a lower-agent allocation plan.

## Criteria
If the function of setting the goal and decomposing it into executable sub-tasks is actually performed, it is judged PASS (the Planner/Strategist role is performed); if it is passed down unchanged without decomposition, it is judged FAIL (the role is not performed).

## Derivation
[method](../../_method/bot_level3_planner_strategist_method.md) -> [knowledge](../../_knowledge/bot_level3_planner_strategist_knowledge.md) ->
[task](../../_task/bot_level3_planner_strategist_task.md) -> [goal](../../_goal/bot_level3_planner_strategist_goal.md) ->
[identity](../../_identity/BOT_LEVEL3_PLANNER_STRATEGIST.md)
