---
name: knowledge_action_chain_node_skill_skill
description: Use when, in the knowledge-action chain, knowledge must be converted not into a document meant to be read but into a skill meant to be executed.
---

# skill — Skill

## Purpose
It determines whether the 'skill' node of the knowledge-action chain actually converted knowledge into an executable unit, and whether it does not still remain a document meant to be read.

## Input
- The basis-for-judgment structure secured at the 'knowledge' node
- The related documents (policies, legal standards, how to write minutes, and the like)

## Procedure (Steps)
1. Identify from the documents the work that must be executed repeatedly.
2. Convert the documents into executable skills (for example: customer response policy → policy-based answer verification, legal standards → contract risk analysis, how to write minutes → meeting summary and action derivation).
3. Confirm whether the converted skill works as an execution unit.

## Output
Skills as units of execution (policy-based answer verification, contract risk analysis, meeting summary and action derivation, and the like).

## Criteria
It is judged by what skill that knowledge was turned into. If it has been converted into an executable skill it is judged PASS; if it remains in the state of a document meant to be read, FAIL.

## Derivation
[method](../../_method/knowledge_action_chain_node_skill_method.md) -> [knowledge](../../_knowledge/knowledge_action_chain_node_skill_knowledge.md) ->
[task](../../_task/knowledge_action_chain_node_skill_task.md) -> [goal](../../_goal/knowledge_action_chain_node_skill_goal.md) ->
[identity](../../_identity/KNOWLEDGE_ACTION_CHAIN_NODE_SKILL.md)
