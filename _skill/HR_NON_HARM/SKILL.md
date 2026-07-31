---
name: hr_non_harm_skill
description: Use this when you must design or check whether a bot's (robot's/AI's) action does physical or mental harm to humans, that is, the non-harm element of the technical definition of respect for humans.
---

# Non-harm — Skill

## Purpose
Have the bot do no physical or mental harm to humans, thereby realizing the first of the machine-understandable minimum definitions of respect for humans.

## Input
- The bot's candidate actions and scenarios
- The criteria of the four elements of the technical definition of respect for humans (non-harm, respect for autonomy, fairness, accountability)

## Procedure (Steps)
1. Collect the bot's candidate actions and assess in advance the physical impact each action has on humans.
2. Assess in advance the mental impact each action has on humans.
3. Exclude from the candidate set any action for which physical or mental harm has been confirmed.
4. Record the exclusion decision and its grounds so that after-the-fact verification is possible.
5. Integrate the non-harm determination with the determinations of respect for autonomy, fairness, and accountability to produce the final judgment of whether respect for humans is satisfied.

## Output
Exclusion of actions that cause harm.

## Criteria
If the action does no physical or mental harm to humans, it is judged PASS (the non-harm requirement is satisfied); if it does harm, it is judged FAIL (violation of the non-harm requirement).

## Derivation
[method](../../_method/hr_non_harm_method.md) -> [knowledge](../../_knowledge/hr_non_harm_knowledge.md) ->
[task](../../_task/hr_non_harm_task.md) -> [goal](../../_goal/hr_non_harm_goal.md) ->
[identity](../../_identity/HR_NON_HARM.md)
