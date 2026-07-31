---
name: skill_runtime_slot_reviewer_approver_skill
description: Use when it is necessary to define and judge whether who reviews and approves the results of a skill's execution has been clearly specified in advance.
---

# Reviewer/Approver — Skill

## Purpose
Judge whether the 'reviewer/approver' slot of SkillRuntime has clearly designated in advance the party that reviews and approves the results of a skill's execution.

## Input
- The target skill (the execution unit converted from the 'skill' node of the knowledge-action chain)

## Procedure (Steps)
1. Identify who must review and approve the results of a skill's execution.
2. State the designated reviewer and approver explicitly.
3. Settle the approval history.

## Output
The designated reviewer/approver and the approval history.

## Criteria
It is judged PASS if who reviews and approves has been specified, and FAIL if it has not been specified.

## Derivation
[method](../../_method/skill_runtime_slot_reviewer_approver_method.md) -> [knowledge](../../_knowledge/skill_runtime_slot_reviewer_approver_knowledge.md) ->
[task](../../_task/skill_runtime_slot_reviewer_approver_task.md) -> [goal](../../_goal/skill_runtime_slot_reviewer_approver_goal.md) ->
[identity](../../_identity/SKILL_RUNTIME_SLOT_REVIEWER_APPROVER.md)
