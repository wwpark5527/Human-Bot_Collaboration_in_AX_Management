---
name: coupled_dynamic_role_allocation_skill
description: Used to perform the role of dynamic role allocation (Dynamic Role Allocation) when, in the Human-Bot Coupled TRB structure, the team's workload, cognitive load, stress, and expertise availability must be analyzed in real time to dynamically reallocate roles.
---

# Dynamic role allocation (Dynamic Role Allocation) — Skill

## Purpose
Optimize the team's role distribution by analyzing the team's state in real time and redistributing and reassigning roles.

## Input
- Workload data per team member
- Cognitive load and stress signals per team member
- Expertise availability data per team member

## Procedure (Steps)
1. Analyze workload in real time.
2. Analyze cognitive load and stress in real time.
3. Analyze expertise availability.
4. Synthesize the analysis results and produce a role-reallocation plan.
5. Apply the reallocation plan to the team.

## Output
Role-reallocation results grounded in real-time analysis of workload, cognitive load, stress, and expertise availability.

## Criteria
If all four elements are analyzed in real time and role-reallocation results grounded in them are produced it is judged PASS, and otherwise FAIL.

## Derivation
[method](../../_method/coupled_dynamic_role_allocation_method.md) -> [knowledge](../../_knowledge/coupled_dynamic_role_allocation_knowledge.md) ->
[task](../../_task/coupled_dynamic_role_allocation_task.md) -> [goal](../../_goal/coupled_dynamic_role_allocation_goal.md) ->
[identity](../../_identity/COUPLED_DYNAMIC_ROLE_ALLOCATION.md)
