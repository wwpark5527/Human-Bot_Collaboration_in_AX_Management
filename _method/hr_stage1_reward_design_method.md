---
identity: HR_STAGE1_REWARD_DESIGN
displayName: "Stage 1 (Reward Design)"
runID: 20260719_164605
derivedFromIdentity: ../_identity/HR_STAGE1_REWARD_DESIGN.md
---

# Stage 1 (Reward Design) — Method

## Method / Procedure
1. Define the bot's task performance indicators.
2. Define an indicator that measures human satisfaction and reflect it in the reward function as an additive term.
3. Define an indicator that measures human-harm risk and reflect it in the reward function as a subtractive term.
4. Define the norm-violation penalty and reflect it in the reward function as a subtractive term.
5. Review whether the completed reward function satisfies the structure "task performance + human satisfaction – human-harm risk – norm-violation penalty".

## Criteria
If the reward function includes human satisfaction, human-harm risk, and the norm-violation penalty in full, it is judged PASS (the reward design requirement is satisfied); if it reflects task performance alone, it is judged FAIL (the reward design requirement is violated).

## Derivation
[identity](../_identity/HR_STAGE1_REWARD_DESIGN.md)
