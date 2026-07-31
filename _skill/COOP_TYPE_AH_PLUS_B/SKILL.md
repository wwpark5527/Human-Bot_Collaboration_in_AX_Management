---
name: coop_type_ah_plus_b_skill
description: Used when determining whether the cooperation type of a human-bot coexistence organization corresponds to AH+B (intelligent division of labor, one augmented human orchestrating multiple bots).
---

# AH + B (intelligent division of labor) — Skill

## Purpose
Identify whether the organization's cooperation structure is the AH + B type in which one augmented human (AH) directs multiple bots (B) in a strategy-execution configuration, and distinguish it from H+B/H+AH/AH+AB.

## Input
- The organization's member composition (including whether the humans/bots are augmented)
- Whether the subject formulating strategy and the subject carrying out execution are separated
- The number of bots directed by one human

## Procedure (Steps)
1. Confirm whether the member composition is one augmented human (AH) and multiple bots (B).
2. Confirm whether the human is augmented and the bots are not augmented.
3. Confirm whether it is a division-of-labor configuration in which the human is responsible for strategy and the bots for execution.
4. If all conditions are satisfied, judge it as AH + B, and together check the application status of the multi-agent environment, human-in-the-loop, and role-based agent design.

## Output
The cooperation type judgment result (H+B | H+AH | AH+B | AH+AB), the list of organizations of the AH + B type, and the results of checking the strategy-execution division-of-labor structure.

## Criteria
When, with the human augmented and the bots non-augmented, one AH orchestrates many Bs, a PASS judgment is made as AH + B.

## Derivation
[method](../../_method/coop_type_ah_plus_b_method.md) -> [knowledge](../../_knowledge/coop_type_ah_plus_b_knowledge.md) ->
[task](../../_task/coop_type_ah_plus_b_task.md) -> [goal](../../_goal/coop_type_ah_plus_b_goal.md) ->
[identity](../../_identity/COOP_TYPE_AH_PLUS_B.md)
