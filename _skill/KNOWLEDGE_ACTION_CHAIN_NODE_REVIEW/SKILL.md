---
name: knowledge_action_chain_node_review_skill
description: Use when it must be examined whether the execution result matches the facts, the organizational standards, and the scope of authority, and whether a person confirmed accountability, so as to determine whether to promote that result to an organizational standard.
---

# review — Skill

## Purpose
It determines whether the 'review' node of the knowledge-action chain properly examined the execution result against the organizational standards, and whether execution did not end without verification.

## Input
- The change in results that came out of the 'outcome' node

## Procedure (Steps)
1. Confirm whether the result matches the facts.
2. Confirm whether the result matches the organizational standards and whether authority was not exceeded.
3. Go through the procedure in which a person confirms accountability.
4. Pass only the results that pass all four conditions to the next node (feedback).

## Output
Only results that pass review become organizational standards.

## Criteria
Whether the result matches the facts, whether it matches the organizational standards, whether authority was not exceeded, whether a person confirmed accountability — if all four conditions are satisfied it is judged PASS, and if even one is unsatisfied, FAIL.

## Derivation
[method](../../_method/knowledge_action_chain_node_review_method.md) -> [knowledge](../../_knowledge/knowledge_action_chain_node_review_knowledge.md) ->
[task](../../_task/knowledge_action_chain_node_review_task.md) -> [goal](../../_goal/knowledge_action_chain_node_review_goal.md) ->
[identity](../../_identity/KNOWLEDGE_ACTION_CHAIN_NODE_REVIEW.md)
