---
name: skill_runtime_slot_material_skill
description: Use this when it must be defined and determined whether the reference scope of the materials to be used in executing a skill has been clearly specified in advance.
---

# Material — Skill

## Purpose
This determines whether the 'material' slot of SkillRuntime has clearly specified in advance the materials to be used in executing the skill.

## Input
- The target skill (the execution unit converted from the 'skill' node of the knowledge-action chain)

## Procedure (Steps)
1. Identify which materials are needed for executing the skill.
2. Specify the reference scope of the usable materials.
3. Finalize the list of materials.

## Output
A list of usable materials (the reference scope).

## Criteria
It is judged PASS when which materials will be used has been specified, and FAIL when it has not been specified.

## Derivation
[method](../../_method/skill_runtime_slot_material_method.md) -> [knowledge](../../_knowledge/skill_runtime_slot_material_knowledge.md) ->
[task](../../_task/skill_runtime_slot_material_task.md) -> [goal](../../_goal/skill_runtime_slot_material_goal.md) ->
[identity](../../_identity/SKILL_RUNTIME_SLOT_MATERIAL.md)
