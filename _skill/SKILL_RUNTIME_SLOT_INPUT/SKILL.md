---
name: skill_runtime_slot_input_skill
description: Use this when it must be defined and determined whether the input a skill must receive when it is executed has been clearly specified in advance.
---

# Input — Skill

## Purpose
This determines whether the 'input' slot of SkillRuntime has clearly specified in advance the input required for executing the skill.

## Input
- The target skill (the execution unit converted from the 'skill' node of the knowledge-action chain)

## Procedure (Steps)
1. Identify what the skill must receive in order to be executed.
2. Specify the kind and format of the required input.
3. Finalize the input specification.

## Output
A finalized input specification.

## Criteria
It is judged PASS when what the input is has been specified in advance, and FAIL when it has not been specified.

## Derivation
[method](../../_method/skill_runtime_slot_input_method.md) -> [knowledge](../../_knowledge/skill_runtime_slot_input_knowledge.md) ->
[task](../../_task/skill_runtime_slot_input_task.md) -> [goal](../../_goal/skill_runtime_slot_input_goal.md) ->
[identity](../../_identity/SKILL_RUNTIME_SLOT_INPUT.md)
