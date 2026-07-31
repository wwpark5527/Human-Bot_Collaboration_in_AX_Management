---
name: hr_accountability_skill
description: Use this when an action or result of a bot (robot/AI) must be checked for whether it is explainable and verifiable, or when the accountability element of the technical definition of human respect must be designed or reviewed.
---

# Accountability — Skill

## Purpose
Make a bot's actions and results explainable and verifiable, and thereby realize the fourth and final element of the machine-readable minimum definition of human respect.

## Input
- The bot's candidate actions and outputs and the records of their judgment process
- The criteria of the four elements of the technical definition of human respect (non-harm, respect for autonomy, fairness, accountability)

## Procedure (Steps)
1. For each candidate action and output of the bot, record the explainable grounds (input, judgment process, output).
2. Check whether the recorded grounds are in a form that a third party can independently verify.
3. Identify actions and outputs that are unexplainable or unverifiable, and exclude or correct them.
4. Record the exclusion and correction decisions and their grounds, and preserve them so that a future audit is possible.
5. Integrate the accountability judgment result with the non-harm, respect-for-autonomy, and fairness judgments to produce the final determination of whether human respect is satisfied.

## Output
A record of actions that can be explained and verified.

## Criteria
If the actions and results are explainable and verifiable, it is judged PASS (the accountability requirement is satisfied); if they are unexplainable or unverifiable, it is judged FAIL (the accountability requirement is violated).

## Derivation
[method](../../_method/hr_accountability_method.md) -> [knowledge](../../_knowledge/hr_accountability_knowledge.md) ->
[task](../../_task/hr_accountability_task.md) -> [goal](../../_goal/hr_accountability_goal.md) ->
[identity](../../_identity/HR_ACCOUNTABILITY.md)
