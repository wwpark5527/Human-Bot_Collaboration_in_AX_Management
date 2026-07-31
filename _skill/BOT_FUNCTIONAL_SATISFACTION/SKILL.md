---
name: bot_functional_satisfaction_skill
description: Used when designing a bot's goal-attainment-score-based behavior (strategy maintenance/reinforcement or revision/avoidance) or explaining the bot's state to organizational members requires reflecting that this is not emotion but functional satisfaction/dissatisfaction, a computed result.
---

# Functional Satisfaction/Dissatisfaction — Skill

## Purpose
Organizational members understand accurately that the bot's 'state that looks like satisfaction/dissatisfaction' is not emotion but a computed result based on the goal-attainment score, and make use of it in design.

## Input
- The definition of the bot's goal
- Goal-attainment evaluation indicators

## Procedure (Steps)
1. Define clearly the bot's goal and its failure/success criteria.
2. Design an internal evaluation function (utility/reward function) that computes the goal-attainment score, so that maintenance/reinforcement behavior is computed when the score rises and revision/avoidance behavior when it falls.
3. Place a self-state monitoring layer to judge the success/failure of the strategy, and have the strategy changed on failure.
4. Explain to organizational members that these states of the bot are computation-based, so that they are not confused with human emotion and consciousness.

## Output
Goal-driven system design document, evaluation function design, self-state monitoring scheme, misunderstanding-prevention education material.

## Criteria
It is judged PASS (concept of functional satisfaction/dissatisfaction reflected) when the bot's maintenance/reinforcement and revision/avoidance behavior is designed and explained on the basis of the goal-attainment score computation, and FAIL (concept of functional satisfaction/dissatisfaction not reflected) when it is mistaken for real emotion and consciousness.

## Derivation
[method](../../_method/bot_functional_satisfaction_method.md) -> [knowledge](../../_knowledge/bot_functional_satisfaction_knowledge.md) ->
[task](../../_task/bot_functional_satisfaction_task.md) -> [goal](../../_goal/bot_functional_satisfaction_goal.md) ->
[identity](../../_identity/BOT_FUNCTIONAL_SATISFACTION.md)
