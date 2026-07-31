---
name: common_context_element_role_skill
description: Use this when it is necessary to inspect who confirms, interprets, verifies, approves, records, and improves what in AI work, that is, whether the role component of the common context is clearly arranged down to the responsible subject.
---

# Role — Skill

## Purpose
Inspect the arrangement of the roles of problem definer, context composer, AI execution director, result interpreter, verifier, responsibility judge, evidence manager, and improvement reflector, and judge whether the accountability structure for AI results is clear.

## Input
- A list of the stages of the AI workflow (from problem definition to improvement reflection)
- Materials on the personnel and role assignments by stage

## Procedure (Steps)
1. Decompose the AI workflow stage by stage.
2. Assign the applicable role (of the eight kinds) to each stage.
3. Mark the stages to which no role has been assigned.
4. Judge whether the subject who will interpret, verify, approve, record, and improve the result is designated.

## Output
The arrangement of responsibility by role and the judgment result on the clarification of the accountability structure.

## Criteria
A PASS judgment is made when 'who must confirm what' is not unclear and the subject who will interpret, verify, approve, record, and improve the result is designated; otherwise, a FAIL judgment is made.

## Derivation
[method](../../_method/common_context_element_role_method.md) -> [knowledge](../../_knowledge/common_context_element_role_knowledge.md) ->
[task](../../_task/common_context_element_role_task.md) -> [goal](../../_goal/common_context_element_role_goal.md) ->
[identity](../../_identity/COMMON_CONTEXT_ELEMENT_ROLE.md)
