---
name: bot_level2_specialist_executor_skill
description: Use this when the actual execution of sub-tasks is needed in a multi-bot/agent ecosystem and the Specialist/Executor hierarchy function must be implemented — handling the subgoals decomposed by the higher Planner/Strategist through computation, analysis and generation.
---

# Level 2 Specialist/Executor — Skill

## Purpose
At Level 2 of the bot hierarchy, execute, compute and generate the sub-tasks allocated from above and thereby produce actual deliverables.

## Input
- The sub-tasks (subgoals) allocated by the higher Level 3 Planner/Strategist
- The data needed for specialist-domain computation and generation

## Procedure (Steps)
1. Confirm the allocated sub-task.
2. Apply the specialist computation, analysis and generation logic needed to carry out the task.
3. Where necessary, call a Level 1 Tool/Reactive Agent to be supported with detailed execution.
4. Self-check the accuracy and completeness of the deliverable.
5. Report the completed deliverable to the higher level of the hierarchy.

## Output
Executed, computed and generated deliverables, a work performance log, and a report document to the higher level of the hierarchy.

## Criteria
If the given task is actually executed, computed and generated so that a deliverable is produced, it is judged PASS (the Specialist/Executor role is performed); if the task is left incomplete, it is judged FAIL (the role is not performed).

## Derivation
[method](../../_method/bot_level2_specialist_executor_method.md) -> [knowledge](../../_knowledge/bot_level2_specialist_executor_knowledge.md) ->
[task](../../_task/bot_level2_specialist_executor_task.md) -> [goal](../../_goal/bot_level2_specialist_executor_goal.md) ->
[identity](../../_identity/BOT_LEVEL2_SPECIALIST_EXECUTOR.md)
