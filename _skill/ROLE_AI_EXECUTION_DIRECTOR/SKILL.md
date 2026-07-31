---
name: role_ai_execution_director_skill
description: Use when an AI work direction that is clear in role, input materials, output format, constraints, verification standards, and scope of responsibility must be designed, rather than using AI vaguely like a simple search tool.
---

# AI Execution Director — Skill

## Purpose
This supports AX talent in giving AI clearly designed work directions instead of vague requests.

## Input
- The work request to be entrusted to AI
- The related input materials and an outline of the desired deliverable

## Procedure (Steps)
1. Define the role to be entrusted to AI.
2. Specify the input materials concretely.
3. State explicitly the desired output format.
4. Present the constraints.
5. State the verification standards and the scope of responsibility explicitly in the direction.

## Output
A clear work direction rather than a vague request.

## Criteria
If all six — role, input materials, output format, constraints, verification standards, and scope of responsibility — are clear, it is judged PASS (clear work direction); if even one is vague, it is judged FAIL (direction needs supplementation).

## Derivation
[method](../../_method/role_ai_execution_director_method.md) -> [knowledge](../../_knowledge/role_ai_execution_director_knowledge.md) ->
[task](../../_task/role_ai_execution_director_task.md) -> [goal](../../_goal/role_ai_execution_director_goal.md) ->
[identity](../../_identity/ROLE_AI_EXECUTION_DIRECTOR.md)
