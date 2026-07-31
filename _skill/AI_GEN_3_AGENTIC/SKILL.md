---
name: ai_gen_3_agentic_skill
description: Use when discriminating whether a target AI system/function falls at the AI 3.0 (Agentic AI, agent type) stage of the AI generational-classification table, and when diagnosing whether its autonomy remains at the individual-agent unit or must be expanded to the organizational unit.
---

# AI 3.0 (Agentic AI) — Skill

## Purpose
Discriminate, on the basis of the AI generational-classification table, whether the target AI is at the agent-type (Agentic AI) stage and whether its operating unit is the individual agent.

## Input
- List of the actual operations of the target AI system/function (including autonomous planning and execution)
- AI generational-classification table (function definitions for AI 1.0–4.0)

## Procedure (Steps)
1. Confirm whether the target AI understands goals and sets up plans and executes them on its own.
2. Distinguish whether it stops at generation (Generative) or has autonomous execution beyond that.
3. Check whether the operating unit of the autonomous execution is the individual agent or the whole organization.
4. If it is at the individual-agent unit, classify it as AI 3.0 (Agentic AI).
5. If it has expanded to the operation of the whole organization, reclassify it as AI 4.0 (Organizational AI).

## Output
AI generation discrimination result, diagnostic report on the operating unit (individual/organization).

## Criteria
If the discrimination result accurately conforms to the table's standard (whether autonomous execution is present, operating unit individual vs. organization), it is determined PASS.

## Derivation
[method](../../_method/ai_gen_3_agentic_method.md) -> [knowledge](../../_knowledge/ai_gen_3_agentic_knowledge.md) ->
[task](../../_task/ai_gen_3_agentic_task.md) -> [goal](../../_goal/ai_gen_3_agentic_goal.md) ->
[identity](../../_identity/AI_GEN_3_AGENTIC.md)
