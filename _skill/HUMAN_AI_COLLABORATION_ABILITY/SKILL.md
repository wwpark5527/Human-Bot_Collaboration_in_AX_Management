---
name: human_ai_collaboration_ability_skill
description: Use when dividing work into the parts to entrust to AI and the parts humans will perform, judging how to connect them, and converting from a human who works alone into a collaborative human who divides roles with bots.
---

# Human-AI Collaboration Ability — Skill

## Purpose
Judge how to divide and connect the target work between AI and humans, and support the shift away from the way humans work alone into a state of collaborating with bots.

## Input
- A list of the target work that needs to be decomposed
- Whether AI is currently used and the mode of performing work (alone/collaborative)

## Procedure (Steps)
1. Decompose the target work and distinguish the parts that can be delegated to AI from the parts humans will handle.
2. Design how to connect the results processed by AI with the work of humans.
3. Execute actual collaboration according to the designed role division.
4. Periodically check whether one has reverted to the way of working alone and redesign if necessary.

## Output
The judgment result on the AI/human role division and the mode of connection, and whether collaboration has been executed.

## Criteria
If one judges what to entrust to AI, what humans should do, and how to connect them, and actually divides roles and collaborates, it is judged PASS (a collaborative human); if one still performs all work alone, it is judged FAIL (redesign of role division is needed).

## Derivation
[method](../../_method/human_ai_collaboration_ability_method.md) -> [knowledge](../../_knowledge/human_ai_collaboration_ability_knowledge.md) ->
[task](../../_task/human_ai_collaboration_ability_task.md) -> [goal](../../_goal/human_ai_collaboration_ability_goal.md) ->
[identity](../../_identity/HUMAN_AI_COLLABORATION_ABILITY.md)
