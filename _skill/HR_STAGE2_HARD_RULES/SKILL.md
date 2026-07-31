---
name: hr_stage2_hard_rules_skill
description: Use as Stage 2 (hard rules) of the five-stage architecture for implementing human respect, when a bot's action candidates must be checked and blocked against the absolutely forbidden zone (harmful actions, deception/manipulation, illegal acts) regardless of reward.
---

# Stage 2 (Hard Rules) — Skill

## Purpose
Define an absolutely forbidden zone that operates independently of reward, thereby fundamentally blocking the human-violating actions that reward design alone cannot prevent.

## Input
- The bot's action candidates
- The definition of the absolutely forbidden zone (harmful actions, deception/manipulation, illegal acts)

## Procedure (Steps)
1. List the types of harmful actions, deception/manipulation, and illegal acts to define the absolutely forbidden zone.
2. Implement the absolutely forbidden zone as a hard-rule layer independent of reward-function calculation.
3. Pass every action candidate of the bot through this hard-rule layer to check in advance whether it falls into the absolutely forbidden zone.
4. Immediately block any action that falls into the absolutely forbidden zone, regardless of its reward value.
5. Record the blocking history to confirm afterwards whether the hard rules actually operated without being bypassed.

## Output
An absolute prohibition line that operates independently of reward calculation.

## Criteria
If an action does not fall into the absolutely forbidden zone, it is judged PASS (the hard-rule requirement is satisfied); if it does, it is judged FAIL (hard-rule violation, immediate blocking) regardless of reward.

## Derivation
[method](../../_method/hr_stage2_hard_rules_method.md) -> [knowledge](../../_knowledge/hr_stage2_hard_rules_knowledge.md) ->
[task](../../_task/hr_stage2_hard_rules_task.md) -> [goal](../../_goal/hr_stage2_hard_rules_goal.md) ->
[identity](../../_identity/HR_STAGE2_HARD_RULES.md)
