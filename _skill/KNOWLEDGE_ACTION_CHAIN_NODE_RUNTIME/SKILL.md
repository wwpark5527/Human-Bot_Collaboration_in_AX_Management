---
name: knowledge_action_chain_node_runtime_skill
description: Use when an execution structure (SkillRuntime) defining input, materials, tools, prohibitions, result format, review approver, and record location must be built so that a skill works in real tasks.
---

# runtime (SkillRuntime) — Skill

## Purpose
It determines whether the 'runtime' node of the knowledge-action chain completed the skill into an execution structure that works in real tasks, and whether all seven definition items are in place.

## Input
- The execution unit (skill) converted at the 'skill' node

## Procedure (Steps)
1. Define the skill's input.
2. Define the materials and tools to be used.
3. Define the prohibitions and the result format.
4. Define the reviewer and approver and the record location, and thereby complete an executable skill-execution structure.

## Output
An executable skill-execution structure (for the detailed definition slots, see idx 135).

## Criteria
If all seven items — input, materials, tools, prohibitions, result format, review approver, record location — are defined, it is judged PASS; if even one is undefined, FAIL.

## Derivation
[method](../../_method/knowledge_action_chain_node_runtime_method.md) -> [knowledge](../../_knowledge/knowledge_action_chain_node_runtime_knowledge.md) ->
[task](../../_task/knowledge_action_chain_node_runtime_task.md) -> [goal](../../_goal/knowledge_action_chain_node_runtime_goal.md) ->
[identity](../../_identity/KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME.md)
