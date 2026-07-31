---
name: aiu_stage_collaborative_user_skill
description: Use when it must be identified whether, on the AI Utilization (AIU) ladder, a member falls into the Collaborative User stage, at which one repeatedly converses with AI to revise results and explore alternatives.
---

# Collaborative User — Skill

## Purpose
Judge whether a member is at the Collaborative User stage on the AI-utilization ladder, at which one repeatedly converses with AI to revise results and explore alternatives, thereby securing the reference point for designing the transition path to the AI Orchestrator stage.

## Input
- The member's number of prompt improvements
- The degree to which the member incorporates AI feedback and the number of repeated interactions with AI

## Procedure (Steps)
1. Tally the number of prompt improvements.
2. Record the degree to which AI feedback is incorporated.
3. Tally the number of repeated interactions with AI.
4. Evaluate "Does AI expand my thinking?" and judge whether the member falls into the stage.

## Output
A record table of the number of prompt improvements, an indicator of the degree to which AI feedback is incorporated, and the Collaborative User stage judgment result.

## Criteria
If it is confirmed that AI expands thinking, it is judged PASS (falls into the Collaborative User stage); otherwise it is judged FAIL (does not fall into the Collaborative User stage).

## Derivation
[method](../../_method/aiu_stage_collaborative_user_method.md) -> [knowledge](../../_knowledge/aiu_stage_collaborative_user_knowledge.md) ->
[task](../../_task/aiu_stage_collaborative_user_task.md) -> [goal](../../_goal/aiu_stage_collaborative_user_goal.md) ->
[identity](../../_identity/AIU_STAGE_COLLABORATIVE_USER.md)
