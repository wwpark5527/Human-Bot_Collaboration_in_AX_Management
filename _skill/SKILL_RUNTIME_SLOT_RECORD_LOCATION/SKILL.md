---
name: skill_runtime_slot_record_location_skill
description: Use this when it must be defined and determined whether where the skill's execution process and results are to be recorded (a traceable execution history) has been clearly specified in advance.
---

# Record Location — Skill

## Purpose
This determines whether the 'record location' slot of SkillRuntime has clearly specified in advance the location for recording the skill's execution process and results.

## Input
- The target skill (the execution unit converted from the 'skill' node of the knowledge-action chain)

## Procedure (Steps)
1. Identify where the skill's execution process and results are to be recorded.
2. State a traceable record location.
3. Finalize the record location.

## Output
The settled record location (a traceable execution history).

## Criteria
It is judged PASS when where it is recorded has been specified, and FAIL when it has not been specified.

## Derivation
[method](../../_method/skill_runtime_slot_record_location_method.md) -> [knowledge](../../_knowledge/skill_runtime_slot_record_location_knowledge.md) ->
[task](../../_task/skill_runtime_slot_record_location_task.md) -> [goal](../../_goal/skill_runtime_slot_record_location_goal.md) ->
[identity](../../_identity/SKILL_RUNTIME_SLOT_RECORD_LOCATION.md)
