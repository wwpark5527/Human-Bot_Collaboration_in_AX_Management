---
name: compfit_emotional_skill
description: Use this when, in the task of emotional support for members, the human provision of empathy, trust, and psychological stability and the bot's immediate response and continuous feedback are to be divided in accordance with the emotional complementation type.
---

# Emotional complementation — Skill

## Purpose
By dividing an emotional support task into a human-assigned part (empathy, trust, and psychological stability) and a bot-assigned part (immediate response, freedom from fatigue, and continuous feedback), realize the augmentation rather than the replacement of the human emotional role.

## Input
- The content of the emotional support task (for example, managing members' stress and psychological state)
- A list of sub-tasks requiring immediate response and continuous feedback
- A list of sub-tasks requiring the provision of empathy, trust, and psychological stability

## Procedure (Steps)
1. Decompose the task into immediacy, fatigue-free, and continuity elements and into empathy, trust, and psychological stability elements.
2. Assign the immediate-response and continuous-feedback elements (for example, 24-hour always-on support) to the bot (AI coach).
3. Assign the empathy, trust, and psychological stability elements (for example, the formation of psychological safety) to the human leader.
4. Confirm whether the combination of the two forms of support substantially contributes to the emotional support of members.

## Output
An emotional complementation result in which the bot's immediate and continuous support is combined with the human's provision of empathy and psychological safety.

## Criteria
PASS if a division is confirmed in which the bot takes charge of immediacy, freedom from fatigue, and continuity and the human takes charge of empathy, trust, and psychological stability; FAIL if either side exclusively handles the entire emotional function.

## Derivation
[method](../../_method/compfit_emotional_method.md) -> [knowledge](../../_knowledge/compfit_emotional_knowledge.md) ->
[task](../../_task/compfit_emotional_task.md) -> [goal](../../_goal/compfit_emotional_goal.md) ->
[identity](../../_identity/COMPFIT_EMOTIONAL.md)
