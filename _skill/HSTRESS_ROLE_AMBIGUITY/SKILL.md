---
name: hstress_role_ambiguity_skill
description: Used when determining whether a case corresponds to Role Ambiguity stress, which arises because "who is responsible for what?" is unclear when humans and bots work together.
---

# Role Ambiguity — Skill

## Purpose
Determine whether a stress of an AX organization member corresponds to role ambiguity among the human stress types (5 types), and provide the grounds for a response that clarifies the division of roles.

## Input
- Records of stress expressions and utterances observed in human-bot collaboration situations
- Observed context related to the division of roles (the agent of strategy formulation, the scope of decision-making authority, the locus of responsibility in case of failure, etc.)

## Procedure (Steps)
1. Confirm whether the division-of-roles question "who is responsible for what?" is raised in the expression of stress.
2. Distinguish whether it is unclearness in the locus of strategy, decision-making, or the ultimate responsible party.
3. Confirm whether there are signs of judgment-recommendation conflict, damage to self-esteem when the AI is superior, or the problem of attributing responsibility in case of failure.
4. Synthesize the confirmed characteristics and judge whether it is role ambiguity stress.

## Output
The judgment result of whether the target situation corresponds to role ambiguity stress, and the priority for clarifying the division of roles.

## Criteria
If unclearness in the division of roles (strategy / decision-making / ultimate responsible party) is confirmed, judge PASS (role ambiguity); otherwise judge FAIL (another human stress type).

## Derivation
[method](../../_method/hstress_role_ambiguity_method.md) -> [knowledge](../../_knowledge/hstress_role_ambiguity_knowledge.md) ->
[task](../../_task/hstress_role_ambiguity_task.md) -> [goal](../../_goal/hstress_role_ambiguity_goal.md) ->
[identity](../../_identity/HSTRESS_ROLE_AMBIGUITY.md)
