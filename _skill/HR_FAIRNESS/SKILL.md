---
name: hr_fairness_skill
description: Use this when an action or result of a bot (robot/AI) must be checked for whether it gives rise to discrimination, or when the fairness element of the technical definition of human respect must be designed or reviewed.
---

# Fairness — Skill

## Purpose
Keep a bot from discriminating, and thereby realize the third element of the machine-readable minimum definition of human respect.

## Input
- The bot's candidate actions and outputs
- The criteria of the four elements of the technical definition of human respect (non-harm, respect for autonomy, fairness, accountability)

## Procedure (Steps)
1. Collect the bot's candidate actions and outputs, and assess in advance the differences in their impact on particular human groups.
2. Check whether the assessment results contain discriminatory patterns (unfavorable or favorable bias).
3. Exclude or correct the actions and outputs in which discrimination is confirmed.
4. Record the exclusion and correction decisions and their grounds so that ex-post verification is possible.
5. Integrate the fairness judgment result with the non-harm, respect-for-autonomy, and accountability judgments to produce the final determination of whether human respect is satisfied.

## Output
A processing result free of discrimination.

## Criteria
If an action or result does not give rise to discrimination, it is judged PASS (the fairness requirement is satisfied); if it gives rise to discrimination, it is judged FAIL (the fairness requirement is violated).

## Derivation
[method](../../_method/hr_fairness_method.md) -> [knowledge](../../_knowledge/hr_fairness_knowledge.md) ->
[task](../../_task/hr_fairness_task.md) -> [goal](../../_goal/hr_fairness_goal.md) ->
[identity](../../_identity/HR_FAIRNESS.md)
