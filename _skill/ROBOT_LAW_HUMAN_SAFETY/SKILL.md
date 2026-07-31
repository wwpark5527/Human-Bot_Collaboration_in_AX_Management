---
name: robot_law_human_safety_skill
description: Use this when the first of the three laws of robotics (respect for human safety and life) must be designed or checked — whether a bot (robot/AI) does not harm humans and does not leave a human in danger unattended.
---

# ① Respect for (protection of) human safety and life — Skill

## Purpose
By making a bot not harm humans and not leave a human in danger unattended, the most classic and fundamental principle of internalizing respect for humans is realized.

## Input
- Candidate actions and scenarios of the bot
- The criteria of the three laws of robotics (first law: respect for human safety and life, second law: obedience, third law: self-preservation)

## Procedure (Steps)
1. Classify in advance all candidate actions of a bot by the criterion of their potential to harm a human.
2. Design the cognitive logic that detects a human in danger and the duty logic that intervenes upon detection.
3. Redesign the action, reward, and verification structures around humans so that only actions that do not violate humans are selected.
4. Verify that the designed logic satisfies both the prohibition of harmful actions and the duty to intervene in danger in real situations.
5. Specify a priority system so that the second law (obedience) and the third law (self-preservation) do not conflict with the first law.

## Output
Prohibition of harmful actions and a duty to intervene for a human in danger.

## Criteria
It is judged PASS (respect for human safety and life satisfied) when a bot's actions are confirmed not to harm humans and to intervene for a human in danger, and FAIL (violation of the first law) when a harmful action occurs or a human in danger is left unattended.

## Derivation
[method](../../_method/robot_law_human_safety_method.md) -> [knowledge](../../_knowledge/robot_law_human_safety_knowledge.md) ->
[task](../../_task/robot_law_human_safety_task.md) -> [goal](../../_goal/robot_law_human_safety_goal.md) ->
[identity](../../_identity/ROBOT_LAW_HUMAN_SAFETY.md)
