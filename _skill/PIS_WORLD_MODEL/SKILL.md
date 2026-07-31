---
name: pis_world_model_skill
description: Used when it must be determined whether AI can internally represent and predict the state of the environment, its changes, and the results of actions, and whether pre-execution scenario simulation and risk prediction are possible.
---

# World model — Skill

## Purpose
Determine whether AI has reached the world model level, at which it predicts future states and the results of actions beyond merely generating responses.

## Input
- The status of the AI system's prediction and simulation functions

## Procedure (Steps)
1. Confirm whether the current world state can be represented.
2. Confirm whether state changes and the results of actions can be predicted.
3. Confirm whether several paths can be compared to find the path closer to the goal.
4. Confirm whether the risks before execution can be simulated.

## Output
Prediction of future states and the results of actions, pre-execution scenario simulation, and grounds for planning and autonomous action.

## Criteria
PASS is judged when the core question "what will happen" is answered, and FAIL when it stops at generating responses.

## Derivation
[method](../../_method/pis_world_model_method.md) -> [knowledge](../../_knowledge/pis_world_model_knowledge.md) ->
[task](../../_task/pis_world_model_task.md) -> [goal](../../_goal/pis_world_model_goal.md) ->
[identity](../../_identity/PIS_WORLD_MODEL.md)
