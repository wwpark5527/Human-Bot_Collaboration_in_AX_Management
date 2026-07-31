---
name: human_member_skill
description: Use when determining which of H (a non-augmented traditional human)/AH (augmented human)/AB (augmented bot)/B (bot) an AX-organization member corresponds to, and in particular whether it is the H type.
---

# H: Human — Skill

## Purpose
Identify, among the members of an AX organization, the traditional human members (H) whose physical and mental capabilities have not been augmented by AI, and distinguish them from the AH/AB/B types.

## Input
- The entity of the target member (human | bot)
- Whether the target member is AI-augmented (the current status of the enhancement of physical and mental capabilities)

## Procedure (Steps)
1. Confirm whether the entity of the target member is a human or a bot.
2. If the entity is a human, confirm whether its physical and mental capabilities have been augmented by AI.
3. If it is a non-augmented human, judge it to be the H (human) type.
4. If it is an augmented human, reclassify it as AH, and if the entity is a bot, reclassify it as B or AB, excluding it from the H type.

## Output
The member-type judgment result (H | AH | AB | B) and the list of H-type members.

## Criteria
It is judged PASS as the H type when it is confirmed that the entity is a human and has not been augmented by AI.

## Derivation
[method](../../_method/human_member_method.md) -> [knowledge](../../_knowledge/human_member_knowledge.md) ->
[task](../../_task/human_member_task.md) -> [goal](../../_goal/human_member_goal.md) ->
[identity](../../_identity/HUMAN_MEMBER.md)
