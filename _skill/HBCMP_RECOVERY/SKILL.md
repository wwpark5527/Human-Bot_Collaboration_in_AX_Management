---
name: hbcmp_recovery_skill
description: Used when determining whether to apply a prescription of the rest, empathy, and motivation family or one of the readjustment and relearning family to a human or bot state of stress.
---

# Recovery Mode — Skill

## Purpose
It selects the recovery prescription for a state of stress according to the 'recovery mode' axis of the human stress vs bot stress comparison structure, thereby providing the grounds for applying an effective response prescription.

## Input
- Information on the agent in a state of stress requiring recovery (human/bot)
- The nature of the current state (psychological and emotional exhaustion or technical misalignment)

## Procedure (Steps)
1. Confirm whether the agent is a human or a bot.
2. If a human, judge which prescription among rest, empathy, and motivation suits the situation.
3. If a bot, judge which prescription between readjustment (realignment) and relearning suits the situation.
4. Produce the selected prescription as the recovery mode value.

## Output
The classification result of the recovery prescription to apply to the target state of stress (rest/empathy/motivation or readjustment/relearning).

## Criteria
If one of rest, empathy, or motivation is selected for a human case it is judged PASS (human recovery mode), if one of readjustment or relearning is selected for a bot case it is judged PASS (bot recovery mode), and if the agent or the prescription family is unclear it is judged FAIL (re-determination required).

## Derivation
[method](../../_method/hbcmp_recovery_method.md) -> [knowledge](../../_knowledge/hbcmp_recovery_knowledge.md) ->
[task](../../_task/hbcmp_recovery_task.md) -> [goal](../../_goal/hbcmp_recovery_goal.md) ->
[identity](../../_identity/HBCMP_RECOVERY.md)
