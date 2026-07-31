---
name: arbi_axis_ai_intervention_transparency_skill
description: Use when it is necessary to evaluate whether it was revealed where and how AI intervened in AI-intervened collaboration, that is, ARBI's AI intervention transparency axis.
---

# AI Intervention Transparency — Skill

## Purpose
Identify the points at which AI was involved in a collaboration output and determine whether that intervention is explicitly revealed, thereby exposing the risk of concealed AI intervention.

## Input
- Collaboration outputs and the history of utterances
- Information on the stages of AI involvement (data analysis/drafting/verification/recording and so on)

## Procedure (Steps)
1. Identify the stages in which AI was involved.
2. Confirm whether intervention at each stage is specified.
3. Mark unspecified points of intervention as concealment risks.
4. Determine whether AI intervention transparency holds.

## Output
Determination result on whether the points of AI intervention are exposed and a list of concealment risks.

## Criteria
If all points of AI intervention are revealed, it is determined PASS; if even one is not revealed, it is determined FAIL.

## Derivation
[method](../../_method/arbi_axis_ai_intervention_transparency_method.md) -> [knowledge](../../_knowledge/arbi_axis_ai_intervention_transparency_knowledge.md) ->
[task](../../_task/arbi_axis_ai_intervention_transparency_task.md) -> [goal](../../_goal/arbi_axis_ai_intervention_transparency_goal.md) ->
[identity](../../_identity/ARBI_AXIS_AI_INTERVENTION_TRANSPARENCY.md)
