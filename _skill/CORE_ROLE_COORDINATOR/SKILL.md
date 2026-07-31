---
name: core_role_coordinator_skill
description: Used when people, AI, tools, output artifacts, schedules, and approval flows are disconnected from one another and must be connected into one workflow.
---

# Coordinator — Skill

## Purpose
By connecting people, AI, tools, output artifacts, schedules, and approval flows to one another, it makes the outputs produced by the shaper, implementer, validator, and operator continue as one unbroken workflow.

## Input
- The work state of people, AI, tools, and output artifacts that are separated from one another
- Schedules in progress and items awaiting approval

## Procedure (Steps)
1. Check the role and output of each actor — people, AI, and tools.
2. Inspect the path by which output artifacts are passed to the next stage.
3. Find the points where the schedule breaks off or is delayed.
4. Connect the relevant parties needed for the approval flow.
5. Integrate people, AI, tools, output artifacts, and approval flows into one flow and confirm it.

## Output
Connectivity — a connected workflow.

## Criteria
If people, AI, tools, output artifacts, and approval flows are all connected to one another it is judged PASS (connectivity secured), and if even one of them breaks off it is judged FAIL (flow discontinuity).

## Derivation
[method](../../_method/core_role_coordinator_method.md) -> [knowledge](../../_knowledge/core_role_coordinator_knowledge.md) ->
[task](../../_task/core_role_coordinator_task.md) -> [goal](../../_goal/core_role_coordinator_goal.md) ->
[identity](../../_identity/CORE_ROLE_COORDINATOR.md)
