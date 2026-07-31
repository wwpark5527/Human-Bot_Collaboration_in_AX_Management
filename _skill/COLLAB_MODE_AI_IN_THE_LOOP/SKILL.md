---
name: collab_mode_ai_in_the_loop_skill
description: Used to determine whether a mode of human-AI collaboration falls under AI-in-the-loop (human-led + AI assist, real-time AI augmentation under human leadership).
---

# AI-in-the-loop (human-led + AI assist) — Skill

## Purpose
Identify whether a mode of human-AI collaboration is the AI-in-the-loop type, a structure of human leadership + real-time AI assistance, and distinguish it from Human-in-the-loop/HOTL/Autonomous AI.

## Input
- Where the initiative for the work lies (human vs. AI)
- The point of AI intervention (prior approval vs. real time vs. post hoc oversight)
- Whether the AI's assistance is in real time

## Procedure (Steps)
1. Confirm whether the initiative for the work lies with the human.
2. Confirm whether the AI comes 'inside' the loop and assists in real time.
3. Confirm whether that intervention is real-time augmentation during the course of the work rather than prior approval.
4. If all the conditions are satisfied, judge it AI-in-the-loop.

## Output
The result of the collaboration-mode judgment (HITL | AI-in-the-loop | HOTL | Autonomous AI), and the history of real-time augmentation interventions.

## Criteria
It is judged PASS as AI-in-the-loop when, under human leadership, the AI assists in real time during the course of the work.

## Derivation
[method](../../_method/collab_mode_ai_in_the_loop_method.md) -> [knowledge](../../_knowledge/collab_mode_ai_in_the_loop_knowledge.md) ->
[task](../../_task/collab_mode_ai_in_the_loop_task.md) -> [goal](../../_goal/collab_mode_ai_in_the_loop_goal.md) ->
[identity](../../_identity/COLLAB_MODE_AI_IN_THE_LOOP.md)
