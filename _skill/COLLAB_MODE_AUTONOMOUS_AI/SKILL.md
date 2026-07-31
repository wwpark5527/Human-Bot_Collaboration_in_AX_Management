---
name: collab_mode_autonomous_ai_skill
description: Use this when determining whether a human-AI collaboration mode corresponds to Autonomous AI (AI autonomous execution, minimal human intervention, HOOTL).
---

# Autonomous AI (AI-autonomous execution) — Skill

## Purpose
Identify whether a human-AI collaboration mode is the Autonomous AI type, in which AI performs fully autonomously and human intervention is effectively absent, and distinguish it from Human-in-the-loop / AI-in-the-loop / Human-on-the-loop.

## Input
- The agent performing the work (human vs AI)
- The mode of human intervention (prior approval vs real-time assistance vs subsequent and continuous monitoring vs non-intervention)
- Whether a human as supervisor remains

## Procedure (Steps)
1. Confirm whether the agent performing the work is AI.
2. Confirm that prior human approval, real-time assistance, and subsequent and continuous monitoring are all absent.
3. Confirm whether even the human as supervisor is effectively absent (HOOTL).
4. When all conditions are satisfied, determine it to be Autonomous AI.

## Output
Collaboration mode determination result (HITL | AI-in-the-loop | HOTL | Autonomous AI), records of AI autonomous execution results.

## Criteria
When AI is the performing agent and human intervention (prior, real-time, and subsequent supervision alike) is absent, a PASS determination of Autonomous AI is made.

## Derivation
[method](../../_method/collab_mode_autonomous_ai_method.md) -> [knowledge](../../_knowledge/collab_mode_autonomous_ai_knowledge.md) ->
[task](../../_task/collab_mode_autonomous_ai_task.md) -> [goal](../../_goal/collab_mode_autonomous_ai_goal.md) ->
[identity](../../_identity/COLLAB_MODE_AUTONOMOUS_AI.md)
