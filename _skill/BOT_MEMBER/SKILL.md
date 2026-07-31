---
name: bot_member_skill
description: Used when determining which of H/AH/AB/B a member of an AX organization corresponds to, and in particular whether it is a non-augmented bot (B).
---

# B: Bot — Skill

## Purpose
Identify, among the members of an AX organization, the non-augmented bot (B) whose entity is a bot and in which common & governance context is not embedded, and distinguish it from the AB/AH/H types.

## Input
- The entity of the target member (human | bot)
- Whether common & governance context and AI governance are embedded in the target bot

## Procedure (Steps)
1. Confirm whether the entity of the target member is a human or a bot.
2. If the entity is a bot, confirm whether common & governance context and AI governance are embedded and operating.
3. If they are not embedded, determine it to be the B (bot) type.
4. If they are embedded, reclassify it as AB, and if the entity is a human, reclassify it as H or AH, excluding it from the B type.

## Output
Member type determination result (H | AH | AB | B), list of B-type bots.

## Criteria
It is determined PASS as the B type when it is confirmed that the entity is a bot and common & governance context is not embedded.

## Derivation
[method](../../_method/bot_member_method.md) -> [knowledge](../../_knowledge/bot_member_knowledge.md) ->
[task](../../_task/bot_member_task.md) -> [goal](../../_goal/bot_member_goal.md) ->
[identity](../../_identity/BOT_MEMBER.md)
