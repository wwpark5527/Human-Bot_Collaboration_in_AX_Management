---
name: collab_mode_human_on_the_loop_skill
description: Use this when determining whether a human-AI mode of collaboration corresponds to Human-on-the-loop (HOTL, autonomous AI execution + after-the-fact, continuous human oversight).
---

# Human-on-the-loop (AI-autonomous + human oversight) — Skill

## Purpose
Identify whether a human-AI mode of collaboration is the Human-on-the-loop type, in which the AI performs most of the work autonomously and the human acts as overseer, and distinguish it from Human-in-the-loop / AI-in-the-loop / Autonomous AI.

## Input
- The executor of the work (human vs AI)
- The mode of human intervention (prior approval vs real-time assistance vs after-the-fact, continuous monitoring vs non-intervention)
- Whether human intervention is possible when an anomaly occurs

## Procedure (Steps)
1. Confirm whether execution of the work has passed to the AI.
2. Confirm whether the human is in the position of an after-the-fact, continuous monitor 'on' the loop.
3. Confirm whether human intervention takes the form of after-the-fact, continuous oversight rather than prior approval.
4. When all conditions are met, judge it to be Human-on-the-loop.

## Output
The mode-of-collaboration judgment result (HITL | AI-in-the-loop | HOTL | Autonomous AI), the results of autonomous AI execution, and the record of human oversight and intervention judgments.

## Criteria
When the AI is the executor and the human functions as an after-the-fact, continuous overseer, a PASS judgment of Human-on-the-loop is made.

## Derivation
[method](../../_method/collab_mode_human_on_the_loop_method.md) -> [knowledge](../../_knowledge/collab_mode_human_on_the_loop_knowledge.md) ->
[task](../../_task/collab_mode_human_on_the_loop_task.md) -> [goal](../../_goal/collab_mode_human_on_the_loop_goal.md) ->
[identity](../../_identity/COLLAB_MODE_HUMAN_ON_THE_LOOP.md)
