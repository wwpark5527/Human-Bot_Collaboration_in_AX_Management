---
name: hbcmp_root_cause_skill
description: Used when determining, from an observed human or bot stress case, whether the root cause belongs to the anxiety, relationships, and identity family or to the overload, conflict, and misalignment family.
---

# Root Cause — Skill

## Purpose
It classifies the fundamental cause of a stress case according to the 'root cause' axis of the human stress vs bot stress comparison structure, thereby providing the grounds for selecting a response system that matches the cause.

## Input
- Information on the agent showing signs of stress (human/bot)
- The context in which the stress arose (descriptions related to anxiety, relationships, and identity, or descriptions related to overload, conflict, and misalignment)

## Procedure (Steps)
1. Confirm whether the agent is a human or a bot.
2. If a human, review the grounds for whether the cause is anxiety, relationships, or identity.
3. If a bot, review the grounds for whether the cause is Overload, Conflict, or Misalignment.
4. Produce the confirmed family of cause as the root cause value.

## Output
The classification result of the root cause of the target stress case (anxiety/relationships/identity or overload/conflict/misalignment).

## Criteria
If the cause is confirmed as one of anxiety, relationships, or identity it is judged PASS (human stress cause), if it is confirmed as one of overload, conflict, or misalignment it is judged PASS (bot stress cause), and if the cause is unclear or intermixed it is judged FAIL (reinvestigation of the cause required).

## Derivation
[method](../../_method/hbcmp_root_cause_method.md) -> [knowledge](../../_knowledge/hbcmp_root_cause_knowledge.md) ->
[task](../../_task/hbcmp_root_cause_task.md) -> [goal](../../_goal/hbcmp_root_cause_goal.md) ->
[identity](../../_identity/HBCMP_ROOT_CAUSE.md)
