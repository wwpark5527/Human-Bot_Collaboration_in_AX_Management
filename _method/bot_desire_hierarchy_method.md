---
identity: BOT_DESIRE_HIERARCHY
displayName: "Formation of the bot's desire hierarchy"
runID: 20260719_164605
derivedFromIdentity: ../_identity/BOT_DESIRE_HIERARCHY.md
---

# Formation of the bot's desire hierarchy — Method

## Method / Procedure
1. Set the higher goal the bot is to pursue (for example, maximizing user satisfaction).
2. Define the lower goals that support the higher goal (for example, accuracy, speed, safety) and design the layered structure between higher and lower goals.
3. Where a reinforcement-learning-based hierarchy is needed, design a meta-reward (higher) and sub-reward (lower) structure (for example, long-term performance as the higher and short-term task success as the lower).
4. Where a structural hierarchy is needed, apply a Hierarchical RL structure in which strategic decision-making is the high-level policy and behavioral execution is the low-level policy.
5. In an Agentic AI environment, design and verify that the agent generates subgoals by itself under the higher goal.

## Criteria
If higher goals and lower goals (or meta-reward/sub-reward, high-level/low-level policy) are designed as a layered structure and behavior that looks like desire is observed, it is judged PASS (formation of a desire hierarchy reflected); if only a single flat goal exists and layered behavior does not appear, it is judged FAIL (formation of a desire hierarchy not reflected).

## Derivation
[identity](../_identity/BOT_DESIRE_HIERARCHY.md)
