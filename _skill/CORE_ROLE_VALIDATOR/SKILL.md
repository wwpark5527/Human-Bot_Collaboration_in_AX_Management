---
name: core_role_validator_skill
description: Used when an output artifact must be brought to a trustworthy state, and when errors, security risks, and logical flaws must be found through testing, review, and quality checking and it must be judged whether the artifact is at a usable level.
---

# Validator — Skill

## Purpose
Find the errors, security risks, and logical flaws in the output artifact made by the implementer, and bring it to a trustworthy state.

## Input
- The output artifact made by the implementer
- The testing and review criteria needed for verification

## Procedure (Steps)
1. Test the output artifact.
2. Carry out a review.
3. Find errors.
4. Check security risks.
5. Find logical flaws.
6. Judge whether it is at a usable level.

## Output
Reliability — securing the reliability of the output artifact.

## Criteria
If errors, security risks, and logical flaws have all been checked and it is judged to be at a usable level it is judged PASS (reliability secured), and if even one of them is unchecked or it is at an unusable level it is judged FAIL (verification not completed).

## Derivation
[method](../../_method/core_role_validator_method.md) -> [knowledge](../../_knowledge/core_role_validator_knowledge.md) ->
[task](../../_task/core_role_validator_task.md) -> [goal](../../_goal/core_role_validator_goal.md) ->
[identity](../../_identity/CORE_ROLE_VALIDATOR.md)
