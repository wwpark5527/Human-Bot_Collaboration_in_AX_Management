---
name: knowledge_action_chain_node_action_skill
description: Use when a skill must actually be performed following the SkillRuntime defined in the knowledge-action chain, and it must be determined whether this knowledge was actually used and who executed it.
---

# action (execution) — Skill

## Purpose
It determines whether the 'action' node of the knowledge-action chain actually performed the skill following the defined runtime, and whether the knowledge passed over into actual action.

## Input
- The skill execution structure defined at the 'runtime' node (input, materials, tools, prohibitions, result format, review approver, record location)

## Procedure (Steps)
1. Execute the skill using the defined input, materials, and tools.
2. Confirm that the prohibitions were not crossed.
3. Record whether this knowledge was actually used and who executed it.
4. Settle the actual action and its deliverable and pass them to the next node (outcome).

## Output
The actual action and its deliverable.

## Criteria
If it is confirmed whether this knowledge was actually used and who executed it, it is judged PASS; if it is not confirmed, FAIL.

## Derivation
[method](../../_method/knowledge_action_chain_node_action_method.md) -> [knowledge](../../_knowledge/knowledge_action_chain_node_action_knowledge.md) ->
[task](../../_task/knowledge_action_chain_node_action_task.md) -> [goal](../../_goal/knowledge_action_chain_node_action_goal.md) ->
[identity](../../_identity/KNOWLEDGE_ACTION_CHAIN_NODE_ACTION.md)
