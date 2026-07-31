---
name: skill_runtime_slot_tool_skill
description: Use when it is necessary to define and judge whether the scope of execution means of the tools allowed for a skill's execution has been clearly specified in advance.
---

# Tool — Skill

## Purpose
Judge whether the 'tool' slot of SkillRuntime has clearly specified in advance the tools to be used in a skill's execution.

## Input
- The target skill (the execution unit converted from the 'skill' node of the knowledge-action chain)

## Procedure (Steps)
1. Identify which tools are needed for a skill's execution.
2. State the scope of execution means of the allowed tools explicitly.
3. Settle the list of tools.

## Output
A list of allowed tools (the scope of execution means).

## Criteria
It is judged PASS if which tools will be used has been specified, and FAIL if it has not been specified.

## Derivation
[method](../../_method/skill_runtime_slot_tool_method.md) -> [knowledge](../../_knowledge/skill_runtime_slot_tool_knowledge.md) ->
[task](../../_task/skill_runtime_slot_tool_task.md) -> [goal](../../_goal/skill_runtime_slot_tool_goal.md) ->
[identity](../../_identity/SKILL_RUNTIME_SLOT_TOOL.md)
