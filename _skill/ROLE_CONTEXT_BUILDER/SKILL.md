---
name: role_context_builder_skill
description: Use when the eight work-context elements — work purpose, target user, organizational standards, data scope, prohibited conditions, deliverable format, verification standards, and performance standards — must be built so that AI produces results fitting the organization's actual work.
---

# Context Builder — Skill

## Purpose
Because insufficient context makes AI results generic and superficial and unfit for the organization's actual work, this supports AX talent in building the AI work environment and context sufficiently.

## Input
- The work to be performed and related background information
- The organization's internal standards and usable data

## Procedure (Steps)
1. Define the work purpose and the target user.
2. Check the organizational standards to be followed.
3. Determine the usable data scope and the prohibited conditions.
4. Determine the deliverable format concretely.
5. Set the verification standards and the performance standards.

## Output
Context that prevents generic and superficial results and makes them fit the organization's actual work.

## Criteria
If all eight — work purpose, target user, organizational standards, data scope, prohibited conditions, deliverable format, verification standards, and performance standards — have been built, it is judged PASS (context building complete); if even one is missing, it is judged FAIL (context building needs supplementation).

## Derivation
[method](../../_method/role_context_builder_method.md) -> [knowledge](../../_knowledge/role_context_builder_knowledge.md) ->
[task](../../_task/role_context_builder_task.md) -> [goal](../../_goal/role_context_builder_goal.md) ->
[identity](../../_identity/ROLE_CONTEXT_BUILDER.md)
