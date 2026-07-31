---
name: skill_runtime_slot_result_format_skill
description: Use when it is necessary to define and judge whether a standardized format for the output of a skill's execution has been clearly specified in advance.
---

# Result Format — Skill

## Purpose
Judge whether the 'result format' slot of SkillRuntime has clearly specified in advance the format of the output of a skill's execution.

## Input
- The target skill (the execution unit converted from the 'skill' node of the knowledge-action chain)

## Procedure (Steps)
1. Identify what format the output of a skill's execution must take.
2. State the standardized output format explicitly.
3. Settle the result format.

## Output
A standardized output format.

## Criteria
It is judged PASS if what the result format is has been specified, and FAIL if it has not been specified.

## Derivation
[method](../../_method/skill_runtime_slot_result_format_method.md) -> [knowledge](../../_knowledge/skill_runtime_slot_result_format_knowledge.md) ->
[task](../../_task/skill_runtime_slot_result_format_task.md) -> [goal](../../_goal/skill_runtime_slot_result_format_goal.md) ->
[identity](../../_identity/SKILL_RUNTIME_SLOT_RESULT_FORMAT.md)
