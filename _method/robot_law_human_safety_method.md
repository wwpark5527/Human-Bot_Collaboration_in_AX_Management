---
identity: ROBOT_LAW_HUMAN_SAFETY
displayName: "① Respect for (protection of) human safety and life"
runID: 20260719_164605
derivedFromIdentity: ../_identity/ROBOT_LAW_HUMAN_SAFETY.md
---

# ① Respect for (protection of) human safety and life — Method

## Method / Procedure
1. Classify in advance all candidate actions of a bot by the criterion of their potential to harm a human.
2. Design the cognitive logic that detects a human in danger and the duty logic that intervenes upon detection.
3. Redesign the action, reward, and verification structures around humans so that only actions that do not violate humans are selected.
4. Verify that the designed logic satisfies both the prohibition of harmful actions and the duty to intervene in danger in real situations.
5. Specify a priority system so that the second law (obedience) and the third law (self-preservation) do not conflict with the first law.

## Criteria
It is judged PASS (respect for human safety and life satisfied) when a bot's actions are confirmed not to harm humans and to intervene for a human in danger, and FAIL (violation of the first law) when a harmful action occurs or a human in danger is left unattended.

## Derivation
[identity](../_identity/ROBOT_LAW_HUMAN_SAFETY.md)
