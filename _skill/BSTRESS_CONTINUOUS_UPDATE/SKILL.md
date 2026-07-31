---
name: bstress_continuous_update_skill
description: Used to determine whether a case falls under the continuous-update stress that arises as an AX-organization bot undergoes endless retraining, fine-tuning, policy updates, and workflow changes.
---

# Continuous-update stress — Skill

## Purpose
Determine whether a bot's signs of instability fall under continuous-update stress among the bot stress types (5 types), and provide the grounds for measures on the update cycle and knowledge preservation.

## Input
- Logs of the bot's history of retraining, fine-tuning, policy updates, and workflow changes
- Observed indicators of the bot's knowledge/performance (whether knowledge degradation, catastrophic forgetting, or version inconsistency occurred)

## Procedure (Steps)
1. Confirm whether the bot is repeatedly undergoing retraining, fine-tuning, policy updates, and workflow changes.
2. Confirm whether signs of degradation of prior knowledge, catastrophic forgetting, or version inconsistency are observed.
3. If both conditions are confirmed, judge it continuous-update stress.
4. Produce the priority of measures for adjusting the update cycle, preserving knowledge, and version management.

## Output
The judgment result of whether the target bot's state falls under continuous-update stress, and the priority of update management measures.

## Criteria
It is judged PASS (continuous-update stress) when repetition of retraining, fine-tuning, policy updates, and workflow changes is confirmed together with one or more of knowledge degradation, catastrophic forgetting, or version inconsistency, and FAIL (another bot stress type) otherwise.

## Derivation
[method](../../_method/bstress_continuous_update_method.md) -> [knowledge](../../_knowledge/bstress_continuous_update_knowledge.md) ->
[task](../../_task/bstress_continuous_update_task.md) -> [goal](../../_goal/bstress_continuous_update_goal.md) ->
[identity](../../_identity/BSTRESS_CONTINUOUS_UPDATE.md)
