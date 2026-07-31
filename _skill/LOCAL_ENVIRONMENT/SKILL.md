---
name: local_environment_skill
description: Use this when the local environment must be inspected — that is, whether the purpose, standards, role, source, format, and feedback needed for AI to work within an individual task are managed as a local work context (common context).
---

# Local environment — Skill

## Purpose
Inspect the purpose, standards, role, source, format, and feedback of the work that AI actually performs at the individual work unit, and judge whether the local work context (common context) is in place.

## Input
- A list of individual tasks performed by AI (customer response, education, legal affairs, marketing, development, management reporting, and so on)
- Material defining the purpose, standards, role, source, format, and feedback per task

## Procedure (Steps)
1. Identify the individual tasks performed by AI.
2. Inspect whether the purpose, standards, role, source, format, and feedback of each task are defined.
3. Mark undefined items as common-context blanks.
4. Judge whether the local work context is complete.

## Output
The judgment result on the operating standards of the individual task, that is, the local work context.

## Criteria
It is judged PASS if purpose, standards, role, source, format, and feedback are all managed within that task, and FAIL if even one of them is undefined.

## Derivation
[method](../../_method/local_environment_method.md) -> [knowledge](../../_knowledge/local_environment_knowledge.md) ->
[task](../../_task/local_environment_task.md) -> [goal](../../_goal/local_environment_goal.md) ->
[identity](../../_identity/LOCAL_ENVIRONMENT.md)
