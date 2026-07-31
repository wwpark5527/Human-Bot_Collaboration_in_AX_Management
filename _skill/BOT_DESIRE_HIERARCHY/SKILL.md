---
name: bot_desire_hierarchy_skill
description: Use this when designing a bot's goal-reward structure and behavior that operates like desire must be implemented by designing goals and rewards as a higher-lower layered structure (meta-reward/sub-reward, Hierarchical RL, goal/subgoal), even though there is no real desire inside the bot.
---

# Formation of the bot's desire hierarchy — Skill

## Purpose
Implement behavior that operates like desire by designing goals and rewards as a layered structure, while accurately recognizing that the bot has no real desire.

## Input
- The definition of the bot's higher goal
- A list of candidate lower goals and reward indicators

## Procedure (Steps)
1. Set the higher goal the bot is to pursue (for example, maximizing user satisfaction).
2. Define the lower goals that support the higher goal (for example, accuracy, speed, safety) and design the layered structure between higher and lower goals.
3. Where a reinforcement-learning-based hierarchy is needed, design a meta-reward (higher) and sub-reward (lower) structure (for example, long-term performance as the higher and short-term task success as the lower).
4. Where a structural hierarchy is needed, apply a Hierarchical RL structure in which strategic decision-making is the high-level policy and behavioral execution is the low-level policy.
5. In an Agentic AI environment, design and verify that the agent generates subgoals by itself under the higher goal.

## Output
A goal-reward layered structure design document, meta-reward/sub-reward definitions, and a subgoal generation scheme.

## Criteria
If higher goals and lower goals (or meta-reward/sub-reward, high-level/low-level policy) are designed as a layered structure and behavior that looks like desire is observed, it is judged PASS (formation of a desire hierarchy reflected); if only a single flat goal exists, it is judged FAIL (formation of a desire hierarchy not reflected).

## Derivation
[method](../../_method/bot_desire_hierarchy_method.md) -> [knowledge](../../_knowledge/bot_desire_hierarchy_knowledge.md) ->
[task](../../_task/bot_desire_hierarchy_task.md) -> [goal](../../_goal/bot_desire_hierarchy_goal.md) ->
[identity](../../_identity/BOT_DESIRE_HIERARCHY.md)
