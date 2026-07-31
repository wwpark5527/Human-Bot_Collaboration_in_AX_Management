---
name: hbcmp_measurement_skill
description: Used when determining whether to measure a human or bot state of stress with emotional and behavioral indicators or with response speed, accuracy, and stability indicators.
---

# Measurement — Skill

## Purpose
It selects the mode of observing a state of stress according to the 'measurement' axis of the human stress vs bot stress comparison structure, thereby providing indicator-based grounds for judgment.

## Input
- Information on the agent under observation (human/bot)
- The types of data that can be collected (affective and behavioral data or system performance data)

## Procedure (Steps)
1. Confirm whether the agent is a human or a bot.
2. If a human, select emotional and behavioral indicators as the objects of collection.
3. If a bot, select the indicators of Latency, Accuracy, and Stability as the objects of collection.
4. Produce the collected indicators as the measurement result.

## Output
The measurement indicator system applied to the target agent (emotional and behavioral indicators or response speed, accuracy, and stability indicators) and its measured values.

## Criteria
If emotional and behavioral indicators are collected for a human agent it is judged PASS (human stress measurement), if response speed, accuracy, and stability indicators are collected for a bot agent it is judged PASS (bot stress measurement), and if no indicators at all can be collected it is judged FAIL (measurement impossible).

## Derivation
[method](../../_method/hbcmp_measurement_method.md) -> [knowledge](../../_knowledge/hbcmp_measurement_knowledge.md) ->
[task](../../_task/hbcmp_measurement_task.md) -> [goal](../../_goal/hbcmp_measurement_goal.md) ->
[identity](../../_identity/HBCMP_MEASUREMENT.md)
