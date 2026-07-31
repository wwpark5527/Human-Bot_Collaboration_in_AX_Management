---
name: skill_runtime_slot_prohibition_skill
description: Use this when it must be defined and determined whether what must not be done during skill execution (the execution restriction boundary) has been clearly stated in advance.
---

# Prohibition — Skill

## Purpose
This determines whether the 'prohibition' slot of SkillRuntime has clearly stated in advance what must not be done during skill execution.

## Input
- The target skill (the execution unit converted from the 'skill' node of the knowledge-action chain)

## Procedure (Steps)
1. Identify what must not be done during skill execution.
2. State the execution restriction boundary.
3. Finalize the prohibition rules.

## Output
Prohibition rules (the execution restriction boundary).

## Criteria
It is judged PASS when what must not be done has been stated, and FAIL when it has not been stated.

## Derivation
[method](../../_method/skill_runtime_slot_prohibition_method.md) -> [knowledge](../../_knowledge/skill_runtime_slot_prohibition_knowledge.md) ->
[task](../../_task/skill_runtime_slot_prohibition_task.md) -> [goal](../../_goal/skill_runtime_slot_prohibition_goal.md) ->
[identity](../../_identity/SKILL_RUNTIME_SLOT_PROHIBITION.md)
