---
name: aiu_stage_orchestrator_skill
description: Use when it must be identified whether, on the AI Utilization (AIU) ladder, a member falls into the AI Orchestrator stage, at which one uses multiple AIs and agents and designs work processes.
---

# AI Orchestrator — Skill

## Purpose
Judge whether a member is at the AI Orchestrator stage on the AI-utilization ladder, at which one uses multiple AIs and agents to design work processes, thereby securing the reference point for designing the transition path to the Augmentation User stage.

## Input
- The number of AIs and agents the member uses
- Records of the proportion of work handled by AI and the level of automation

## Procedure (Steps)
1. Tally the number of AIs and agents in use.
2. Measure the proportion of work handled by AI.
3. Judge the level of automation.
4. Judge whether the member falls into the stage by "Do I do the work directly, or do I design so that AIs do the work?"

## Output
A record table of the number of AIs and agents used and the proportion of work, an indicator of the level of automation, and the AI Orchestrator stage judgment result.

## Criteria
If the level of designing processes so that AIs do the work is confirmed, it is judged PASS (falls into the AI Orchestrator stage); if the share of work the member still performs directly is high, it is judged FAIL (does not fall into the AI Orchestrator stage).

## Derivation
[method](../../_method/aiu_stage_orchestrator_method.md) -> [knowledge](../../_knowledge/aiu_stage_orchestrator_knowledge.md) ->
[task](../../_task/aiu_stage_orchestrator_task.md) -> [goal](../../_goal/aiu_stage_orchestrator_goal.md) ->
[identity](../../_identity/AIU_STAGE_ORCHESTRATOR.md)
