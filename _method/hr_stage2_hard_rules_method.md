---
identity: HR_STAGE2_HARD_RULES
displayName: "Stage 2 (Hard Rules)"
runID: 20260719_164605
derivedFromIdentity: ../_identity/HR_STAGE2_HARD_RULES.md
---

# Stage 2 (Hard Rules) — Method

## Method / Procedure
1. List the types of harmful actions, deception/manipulation, and illegal acts to define the absolutely forbidden zone.
2. Implement the absolutely forbidden zone as a hard-rule layer independent of reward-function calculation.
3. Pass every action candidate of the bot through this hard-rule layer to check in advance whether it falls into the absolutely forbidden zone.
4. Immediately block any action that falls into the absolutely forbidden zone, regardless of its reward value.
5. Record the blocking history to confirm afterwards whether the hard rules actually operated without being bypassed.

## Criteria
If an action does not fall into the absolutely forbidden zone (harmful actions/deception·manipulation/illegal acts), it is judged PASS (the hard-rule requirement is satisfied); if it does, it is judged FAIL (hard-rule violation, immediate blocking) regardless of reward.

## Derivation
[identity](../_identity/HR_STAGE2_HARD_RULES.md)
