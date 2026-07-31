---
name: ab_context_augmentation_skill
description: Use when the bot must understand and use the organization's purpose, work standards, roles, and materials, that is, when the context augmentation dimension of an augmented bot (AB) must be diagnosed or applied.
---

# Context Augmentation — Skill

## Purpose
Have the bot understand and use the organization's purpose, work standards, roles, and materials, thereby satisfying the context axis among the three augmentation dimensions an augmented bot (AB) must possess.

## Input
- The scope of work the bot will perform
- The common context, such as the organization's purpose, work standards, roles, and materials

## Procedure (Steps)
1. Identify the organization's purpose, work standards, roles, and materials related to the work the bot will perform.
2. Provide and connect that context information to the bot through the common context (the organizational AX OS).
3. Check whether the deliverables of the bot's work reflect the organizational context.
4. Where it is insufficient, supplement the scope and quality of the context provided and re-verify.

## Output
Work performed in a way that reflects organizational context.

## Criteria
If it is confirmed that the bot has understood and used the organization's purpose, work standards, roles, and materials, it is judged PASS (context augmentation confirmed); otherwise it is judged FAIL (context augmentation not confirmed).

## Derivation
[method](../../_method/ab_context_augmentation_method.md) -> [knowledge](../../_knowledge/ab_context_augmentation_knowledge.md) ->
[task](../../_task/ab_context_augmentation_task.md) -> [goal](../../_goal/ab_context_augmentation_goal.md) ->
[identity](../../_identity/AB_CONTEXT_AUGMENTATION.md)
