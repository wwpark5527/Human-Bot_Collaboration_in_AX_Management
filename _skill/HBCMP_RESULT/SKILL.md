---
name: hbcmp_result_skill
description: Used when determining whether the consequence left by a neglected human or bot stress case belongs to the Burnout and dissatisfaction family or to the performance degradation and error family.
---

# Result — Skill

## Purpose
It classifies the consequence of a case of neglected stress according to the 'result' axis of the human stress vs bot stress comparison structure, thereby providing the grounds for selecting a follow-up response procedure.

## Input
- Information on the agent whose stress has been neglected (human/bot)
- The observed signs (descriptions related to Burnout and dissatisfaction, or descriptions related to performance degradation and errors)

## Procedure (Steps)
1. Confirm whether the agent is a human or a bot.
2. If a human, confirm whether signs of Burnout or dissatisfaction have appeared.
3. If a bot, confirm whether signs of performance degradation or errors have appeared.
4. Produce the confirmed consequence as the result value.

## Output
The classification result of the result of the target stress case (Burnout/dissatisfaction or performance degradation/errors).

## Criteria
If Burnout or dissatisfaction is confirmed it is judged PASS (human stress result), if performance degradation or errors are confirmed it is judged PASS (bot stress result), and if neither is confirmed it is judged FAIL (consequence unconfirmed).

## Derivation
[method](../../_method/hbcmp_result_method.md) -> [knowledge](../../_knowledge/hbcmp_result_knowledge.md) ->
[task](../../_task/hbcmp_result_task.md) -> [goal](../../_goal/hbcmp_result_goal.md) ->
[identity](../../_identity/HBCMP_RESULT.md)
