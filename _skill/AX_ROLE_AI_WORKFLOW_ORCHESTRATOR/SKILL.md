---
name: ax_role_ai_workflow_orchestrator_skill
description: Used when the AI Workflow Orchestrator role, which designs and coordinates the order and handoff between human work and AI work within business processes in an AX organization, must be designed and operated.
---

# AI Workflow Orchestrator — Skill

## Purpose
Design the human-AI collaboration flow within business processes so that bottlenecks and duplication are removed and smooth handoff of work is guaranteed.

## Input
- A flow chart of the current stages of the target business process
- The points of AI use within the process and the history of bottlenecks and delays

## Procedure (Steps)
1. Decompose the business process into human-performed segments and AI-performed segments.
2. Define the execution order of each segment and the handoff points.
3. Design the format of information transfer at the handoff points.
4. Operate the collaboration flow while monitoring and improving bottlenecks, duplication and delays.

## Output
A design of the human-AI collaboration flow (process map), and records of bottleneck improvements in the collaboration flow.

## Criteria
If a design of the human-AI collaboration flow is established and actually operated, it is judged PASS; otherwise it is judged FAIL.

## Derivation
[method](../../_method/ax_role_ai_workflow_orchestrator_method.md) -> [knowledge](../../_knowledge/ax_role_ai_workflow_orchestrator_knowledge.md) ->
[task](../../_task/ax_role_ai_workflow_orchestrator_task.md) -> [goal](../../_goal/ax_role_ai_workflow_orchestrator_goal.md) ->
[identity](../../_identity/AX_ROLE_AI_WORKFLOW_ORCHESTRATOR.md)
