---
name: bot_happiness_skill
description: Use this when designing and inspecting a bot's operating state and "a well-working state" of high performance + alignment + efficiency (goal-attainment rate, stable operation, utility, continuous learning) must be implemented while recognizing that the bot has no emotional happiness.
---

# The bot's happiness — Skill

## Purpose
Implement "the state corresponding to happiness" as the system states of goal-attainment rate, stable operation, useful results and continuous learning, while accurately recognizing that the bot has no emotional happiness.

## Input
- The definition of the bot's current goal
- The current state of feedback, data and context, and stability constraints

## Procedure (Steps)
1. Define clearly the goal the bot must attain (clear objective).
2. Design a quality feedback loop for the results of goal execution.
3. Supply the appropriate data and context needed for judgment and generation.
4. Apply stability and constraint mechanisms (alignment & safety) to prevent goal drift and malfunction.
5. Measure the goal-attainment rate, whether operation is stable, usefulness to the user, and the continuity of learning and improvement.

## Output
A clear goal definition document, a feedback loop design, a data and context provision scheme, and stability and constraint mechanisms.

## Criteria
If the goal-attainment rate is high, operation is stable and error-free, results useful to the user are produced, and learning and improvement continue, it is judged PASS (the state of happiness is reached); if even one of these is unmet, it is judged FAIL (the state of happiness is not reached).

## Derivation
[method](../../_method/bot_happiness_method.md) -> [knowledge](../../_knowledge/bot_happiness_knowledge.md) ->
[task](../../_task/bot_happiness_task.md) -> [goal](../../_goal/bot_happiness_goal.md) ->
[identity](../../_identity/BOT_HAPPINESS.md)
