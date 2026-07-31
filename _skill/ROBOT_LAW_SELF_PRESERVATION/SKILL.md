---
name: robot_law_self_preservation_skill
description: Use this when you must design or check whether a bot's (robot's/AI's) action to protect itself conflicts with the First and Second Laws under the Third Law of the three laws of robotics (self-preservation).
---

# ③ The Robot's Own Self-Preservation (Maintenance of Existence) — Skill

## Purpose
Have the bot protect itself within the range that does not conflict with the First Law (respect for human safety and life) and the Second Law (obedience to humans), thereby realizing the third principle of the internalization of respect for humans.

## Input
- The threat or damage situation the bot faces
- The criteria of the three laws of robotics (First Law respect for human safety and life, Second Law obedience, Third Law self-preservation)

## Procedure (Steps)
1. Detect the threat or damage situation the bot faces and assess whether self-preservation is necessary.
2. Verify in advance whether the self-preservation action in question conflicts with the First Law.
3. Additionally verify whether an action that has passed the First Law conflicts with the Second Law.
4. Execute only self-preservation actions that have passed both higher principles, and suppress or hold actions that have not.
5. Record the judgment to execute or suppress the self-preservation action and its grounds so that after-the-fact verification is possible.

## Output
Maintenance of one's own existence within the range that does not violate the two higher principles.

## Criteria
If the self-preservation action does not conflict with the First Law and the Second Law, it is judged PASS (the self-preservation principle is satisfied); if a self-preservation action is executed while violating even one of the two higher principles, it is judged FAIL (violation of a higher principle).

## Derivation
[method](../../_method/robot_law_self_preservation_method.md) -> [knowledge](../../_knowledge/robot_law_self_preservation_knowledge.md) ->
[task](../../_task/robot_law_self_preservation_task.md) -> [goal](../../_goal/robot_law_self_preservation_goal.md) ->
[identity](../../_identity/ROBOT_LAW_SELF_PRESERVATION.md)
