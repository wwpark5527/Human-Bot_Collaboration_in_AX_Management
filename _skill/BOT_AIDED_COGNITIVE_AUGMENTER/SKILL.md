---
name: bot_aided_cognitive_augmenter_skill
description: Use this to perform the Cognitive Augmenter role when, in the Bot-Aided TRB structure, the human's cognitive work (data organization, alternative generation, risk simulation, schedule optimization) must be handled on their behalf so as to augment and ease the human's cognitive burden.
---

# Cognitive Augmenter — Skill

## Purpose
Augment human decision-making by handling the human's cognitive burden on their behalf through information provision and coordination support.

## Input
- The raw data needed for decision-making
- The team's schedule and resource constraints

## Procedure (Steps)
1. Collect and organize the raw data.
2. Generate decision alternatives.
3. Simulate the risks of each alternative.
4. Optimize the schedule by reflecting the simulation results.
5. Provide the results to the human decision-maker.

## Output
The results of data organization, alternative generation, risk simulation, and schedule optimization.

## Criteria
If the results of data organization, alternative generation, risk simulation, and schedule optimization are all produced, it is judged PASS; otherwise FAIL.

## Derivation
[method](../../_method/bot_aided_cognitive_augmenter_method.md) -> [knowledge](../../_knowledge/bot_aided_cognitive_augmenter_knowledge.md) ->
[task](../../_task/bot_aided_cognitive_augmenter_task.md) -> [goal](../../_goal/bot_aided_cognitive_augmenter_goal.md) ->
[identity](../../_identity/BOT_AIDED_COGNITIVE_AUGMENTER.md)
