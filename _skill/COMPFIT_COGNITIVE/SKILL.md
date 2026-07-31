---
name: compfit_cognitive_skill
description: Use this when, in cognitive tasks such as strategy meetings, human intuition, creativity, and imagination and the bot's computation, search, and memory are to be divided in accordance with the cognitive complementation type.
---

# Cognitive complementation — Skill

## Purpose
By dividing a cognitive task into a human-assigned part (intuition, creativity, and imagination) and a bot-assigned part (computation, search, and memory), realize the augmentation of human capability rather than the replacement of humans.

## Input
- The content of the cognitive task (for example, the agenda of a strategy meeting)
- A list of sub-tasks requiring computation, search, and memory
- A list of sub-tasks requiring intuition, creativity, and imagination

## Procedure (Steps)
1. Decompose the task into computation, search, and memory elements and into intuition, creativity, and imagination elements.
2. Assign the computation, search, and memory elements (for example, data simulation) to the bot.
3. Deliver the bot's output to the human and request an interpretation of the strategic meaning.
4. Confirm whether the final judgment was made on the basis of human intuition and creativity.

## Output
A cognitive complementation result in which the bot's output based on computation, search, and memory is combined with the human's strategic interpretation.

## Criteria
PASS if a division is confirmed in which the bot takes charge of computation, search, and memory and the human takes charge of interpretation and judgment; FAIL if either side exclusively handles the entire cognitive function.

## Derivation
[method](../../_method/compfit_cognitive_method.md) -> [knowledge](../../_knowledge/compfit_cognitive_knowledge.md) ->
[task](../../_task/compfit_cognitive_task.md) -> [goal](../../_goal/compfit_cognitive_goal.md) ->
[identity](../../_identity/COMPFIT_COGNITIVE.md)
