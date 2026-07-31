---
name: ah_indicator_decision_skill
description: Use when, in augmented human (AH) measurement, it must be confirmed whether decision quality actually improved after using AI, by means of decision accuracy, error-reduction rate, and prediction success rate.
---

# Decision Augmentation (Decision A.) — Skill

## Purpose
Measure whether the use of AI improves a member's actual decision quality, and thereby confirm the second indicator of whether the augmented human (AH) has been realized.

## Input
- Records of decisions made without the use of AI (the baseline)
- Records of decisions made with the use of AI

## Procedure (Steps)
1. Record decision accuracy, error rate, and prediction success rate in the state without AI use.
2. Record decision accuracy, error rate, and prediction success rate in the state with AI use.
3. Compare the two states and calculate decision accuracy, error-reduction rate, and prediction success rate.
4. Combine the three measures and judge whether decision augmentation has occurred.

## Output
A comparison table of decision accuracy, measurement results for the error-reduction rate, and measurement results for the prediction success rate.

## Criteria
If decision accuracy, the error-reduction rate, and the prediction success rate have improved after the use of AI, it is judged PASS (decision augmentation confirmed); if they have not improved, it is judged FAIL (decision augmentation not confirmed).

## Derivation
[method](../../_method/ah_indicator_decision_method.md) -> [knowledge](../../_knowledge/ah_indicator_decision_knowledge.md) ->
[task](../../_task/ah_indicator_decision_task.md) -> [goal](../../_goal/ah_indicator_decision_goal.md) ->
[identity](../../_identity/AH_INDICATOR_DECISION.md)
