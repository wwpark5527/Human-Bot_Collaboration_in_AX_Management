---
name: coop_type_h_plus_b_skill
description: Used when determining whether the cooperation type of a human-bot coexistence organization corresponds to H+B (tool-type cooperation, human-led + bot-assisted).
---

# H + B (Tool-Type Cooperation) — Skill

## Purpose
Identify whether the organization's human-bot cooperation structure is the early AX stage of human-led + bot-assisted (H + B), and distinguish it from H + AH, AH + B, and AH + AB.

## Input
- The organization's member composition (including whether they are augmented)
- The role position of the bot (tool | object of orchestration | joint judgment subject)
- The locus of accountability

## Procedure (Steps)
1. Confirm whether there are non-augmented humans and bots in the member composition.
2. Confirm whether the bot remains in the position of a productivity-improving tool.
3. Confirm whether responsibility is concentrated on the human.
4. If all three conditions are satisfied, determine it to be the H + B type; if the human is augmented, reclassify it as H + AH, and if the bot is an object of orchestration, reclassify it as AH + B.

## Output
Cooperation type determination result (H+B | H+AH | AH+B | AH+AB), list of H + B type organizations.

## Criteria
It is determined PASS as H + B when it is a non-augmented human + bot composition, the bot remains in the position of a tool, and responsibility is concentrated on the human.

## Derivation
[method](../../_method/coop_type_h_plus_b_method.md) -> [knowledge](../../_knowledge/coop_type_h_plus_b_knowledge.md) ->
[task](../../_task/coop_type_h_plus_b_task.md) -> [goal](../../_goal/coop_type_h_plus_b_goal.md) ->
[identity](../../_identity/COOP_TYPE_H_PLUS_B.md)
