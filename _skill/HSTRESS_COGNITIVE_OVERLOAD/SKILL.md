---
name: hstress_cognitive_overload_skill
description: Used when determining whether a case corresponds to Cognitive Overload stress, which arises as the human, as a meta-manager, simultaneously supervises, orchestrates, and verifies multiple AI agents, data, and workflows.
---

# Cognitive Overload — Skill

## Purpose
Determine whether a stress of an AX organization member corresponds to cognitive overload among the human stress types (5 types), and provide the grounds for a response that alleviates the meta-manager's cognitive burden.

## Input
- Records of stress expressions observed in members' utterances and behavior
- The observed list of objects of simultaneous management (number of AI agents, real-time data, automated workflows, governance compliance items, etc.)

## Procedure (Steps)
1. Confirm whether, in the expression of stress, the human is performing the role of a meta-manager (supervision, orchestration, verification).
2. Confirm whether the objects of simultaneous management (AI agents, real-time data, automated workflows, verification of AI recommendations, governance compliance) increase.
3. Confirm whether there are signs of decision fatigue, attention fragmentation, or continuous monitoring burden.
4. Synthesize the confirmed characteristics and judge whether it is cognitive overload.

## Output
The judgment result of whether the target situation corresponds to cognitive overload, and the priority for alleviating the meta-manager's cognitive burden.

## Criteria
If an increase in the objects of simultaneous management as a meta-manager is confirmed, judge PASS (cognitive overload); otherwise judge FAIL (another human stress type).

## Derivation
[method](../../_method/hstress_cognitive_overload_method.md) -> [knowledge](../../_knowledge/hstress_cognitive_overload_knowledge.md) ->
[task](../../_task/hstress_cognitive_overload_task.md) -> [goal](../../_goal/hstress_cognitive_overload_goal.md) ->
[identity](../../_identity/HSTRESS_COGNITIVE_OVERLOAD.md)
