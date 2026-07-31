---
name: compfit_behavioral_skill
description: Use this when dividing, in work-execution tasks, the bot's repetitive, routine behavior (the routine workflow) and the human's response to non-routine, exceptional situations (crisis handling) in accordance with the behavioral complementation type.
---

# Behavioral complementation — Skill

## Purpose
Divide work-execution tasks into those handled by the bot (repetitive, routine behavior) and those handled by the human (responses to non-routine, exceptional situations), thereby augmenting humans with the capability of responding to exceptions rather than excluding them from execution.

## Input
- The content of the work-execution task
- A list of sub-tasks that can be classified as repetitive, routine behavior (the routine workflow)
- A list of sub-tasks classified as non-routine, exceptional situations (crisis handling)

## Procedure (Steps)
1. Classify the task into repetitive, routine behavior and non-routine, exceptional situations.
2. Assign repetitive, routine behavior to the bot and have it performed automatically.
3. When an exceptional or crisis situation is detected during the bot's performance, escalate it to the human.
4. The human responds to and handles the exceptional or crisis situation.

## Output
The result of behavioral complementation, combining the bot's performance of routine work with the human's response to exceptions and crises.

## Criteria
A PASS judgment is made when the bot takes charge of routine behavior and the human takes charge of responses to exceptions and crises and escalation is smooth; a FAIL judgment is made when the bot handles exceptional situations at its own discretion or there is no escalation.

## Derivation
[method](../../_method/compfit_behavioral_method.md) -> [knowledge](../../_knowledge/compfit_behavioral_knowledge.md) ->
[task](../../_task/compfit_behavioral_task.md) -> [goal](../../_goal/compfit_behavioral_goal.md) ->
[identity](../../_identity/COMPFIT_BEHAVIORAL.md)
