---
name: collab_mode_human_in_the_loop_skill
description: Used to determine whether a mode of human-AI collaboration falls under Human-in-the-loop (human-approval-centered, the human giving final approval after the AI's proposal).
---

# Human-in-the-loop (human-approval-centered) — Skill

## Purpose
Identify whether a mode of human-AI collaboration is the Human-in-the-loop type, in which the human gives final approval after the AI's proposal, and distinguish it from AI-in-the-loop/HOTL/Autonomous AI.

## Input
- Whether a stage of AI proposal exists
- Where the final approval authority lies (human vs. AI)
- The point of human intervention (approval point vs. real time vs. post hoc oversight)

## Procedure (Steps)
1. Confirm whether there is a stage at which the AI proposes a result.
2. Confirm whether that proposal must pass the human's review and approval to be finalized.
3. Confirm whether the final approval authority lies with the human.
4. If all the conditions are satisfied, judge it Human-in-the-loop.

## Output
The result of the collaboration-mode judgment (HITL | AI-in-the-loop | HOTL | Autonomous AI), and the history of passage through the approval gate.

## Criteria
It is judged PASS as Human-in-the-loop when a result is finalized only if there is the human's final approval after the AI's proposal.

## Derivation
[method](../../_method/collab_mode_human_in_the_loop_method.md) -> [knowledge](../../_knowledge/collab_mode_human_in_the_loop_knowledge.md) ->
[task](../../_task/collab_mode_human_in_the_loop_task.md) -> [goal](../../_goal/collab_mode_human_in_the_loop_goal.md) ->
[identity](../../_identity/COLLAB_MODE_HUMAN_IN_THE_LOOP.md)
