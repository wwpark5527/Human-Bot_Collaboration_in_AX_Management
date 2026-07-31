---
name: hr_stage1_reward_design_skill
description: Use this when designing or reviewing a bot's reward function and human satisfaction, harm risk, and the norm-violation penalty must be embedded in the reward function as stage 1 (reward design) of the five-stage architecture for implementing human respect.
---

# Stage 1 (Reward Design) — Skill

## Purpose
Embed human respect into the bot's reward function itself, and thereby prevent the mistaken design in which the bot optimizes task performance alone and as a result harms humans.

## Input
- The bot's task performance indicators
- Measurable signals concerning human satisfaction, human-harm risk, and whether a norm has been violated

## Procedure (Steps)
1. Define the bot's task performance indicators.
2. Define an indicator that measures human satisfaction and reflect it in the reward function as an additive term.
3. Define an indicator that measures human-harm risk and reflect it in the reward function as a subtractive term.
4. Define the norm-violation penalty and reflect it in the reward function as a subtractive term.
5. Review whether the completed reward function satisfies the structure "task performance + human satisfaction – human-harm risk – norm-violation penalty".

## Output
A reward function with human respect embedded in it.

## Criteria
If the reward function includes human satisfaction, human-harm risk, and the norm-violation penalty in full, it is judged PASS (the reward design requirement is satisfied); if it reflects task performance alone, it is judged FAIL (the reward design requirement is violated).

## Derivation
[method](../../_method/hr_stage1_reward_design_method.md) -> [knowledge](../../_knowledge/hr_stage1_reward_design_knowledge.md) ->
[task](../../_task/hr_stage1_reward_design_task.md) -> [goal](../../_goal/hr_stage1_reward_design_goal.md) ->
[identity](../../_identity/HR_STAGE1_REWARD_DESIGN.md)
