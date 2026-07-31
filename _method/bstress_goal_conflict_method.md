---
identity: BSTRESS_GOAL_CONFLICT
displayName: "Goal Conflict"
runID: 20260719_164605
derivedFromIdentity: ../_identity/BSTRESS_GOAL_CONFLICT.md
---

# Goal Conflict — Method

## Method / Procedure
1. List the goals assigned to the bot and confirm whether different goals collide, as in speed vs. accuracy, profitability vs. ethics, or user satisfaction vs. governance compliance.
2. Confirm whether oscillation, repetitive loops, or inconsistent behavior is observed in the bot's outputs and behavior.
3. If the above conditions are confirmed, judge it goal conflict and establish rules of priority among the goals.
4. After applying the priority rules, re-confirm whether the oscillation, repetitive loops, and inconsistent behavior are resolved.

## Criteria
It is judged PASS as goal conflict when different goals (speed/accuracy, profitability/ethics, user satisfaction/governance compliance, and so on) collide and one or more of oscillation, repetitive loops, or inconsistent behavior accompanies it. If the cause falls under another bot stress type such as limits of computational resources or value misalignment, it is judged FAIL (reclassified into another type).

## Derivation
[identity](../_identity/BSTRESS_GOAL_CONFLICT.md)
