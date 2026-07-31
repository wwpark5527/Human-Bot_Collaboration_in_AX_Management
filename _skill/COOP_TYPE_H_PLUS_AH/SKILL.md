---
name: coop_type_h_plus_ah_skill
description: Used when determining whether the cooperation type of a human-bot coexistence organization corresponds to H+AH (augmented-human-centered cooperation, existing humans + augmented humans).
---

# H + AH (augmented-human-centered cooperation) — Skill

## Purpose
Identify whether the organization's cooperation structure is the H + AH type in which existing humans and augmented humans work together, and distinguish it from H + B/AH + B/AH + AB.

## Input
- The organization's member composition (including whether the humans are augmented)
- Whether there is an augmentation gap among the members
- The existence and status of bots

## Procedure (Steps)
1. Confirm whether the composition axis is human versus human and whether bots are not the key element of distinction.
2. Confirm whether some of the members are augmented (AH).
3. Confirm whether the remaining portion is not augmented (H).
4. If all conditions are satisfied, judge it as H + AH, and together check whether the stratification of AI competence has occurred.

## Output
The cooperation type judgment result (H+B | H+AH | AH+B | AH+AB), the list of organizations of the H + AH type, and warning signals of AI-competence stratification.

## Criteria
When the composition axis is human versus human and only some are augmented, a PASS judgment is made as H + AH.

## Derivation
[method](../../_method/coop_type_h_plus_ah_method.md) -> [knowledge](../../_knowledge/coop_type_h_plus_ah_knowledge.md) ->
[task](../../_task/coop_type_h_plus_ah_task.md) -> [goal](../../_goal/coop_type_h_plus_ah_goal.md) ->
[identity](../../_identity/COOP_TYPE_H_PLUS_AH.md)
