---
name: knowledge_action_chain_node_feedback_skill
description: Use when the errors and confusion revealed in review must be returned into the organizational standards, prohibition rules, and training material, and it must be determined whether the organization actually learned.
---

# feedback — Skill

## Purpose
It determines whether the 'feedback' node of the knowledge-action chain actually returned the problems revealed in review into the next standards and materials, and whether the organization learned.

## Input
- The review results of the 'review' node (including errors and confusion)

## Procedure (Steps)
1. Find the recurring errors and reflect them into the organizational standards.
2. Turn the errors AI caused into prohibition rules.
3. Organize the parts where there was confusion into training material.
4. Pass the updated prohibition rules and training material to the next node (context).

## Output
The updated prohibition rules and training material. Only with this process does the organization learn.

## Criteria
Whether recurring errors are reflected into the standards, whether AI errors are turned into prohibition rules, whether confusion is organized into training material — if all three are accomplished it is judged PASS, and if even one is not accomplished, FAIL.

## Derivation
[method](../../_method/knowledge_action_chain_node_feedback_method.md) -> [knowledge](../../_knowledge/knowledge_action_chain_node_feedback_knowledge.md) ->
[task](../../_task/knowledge_action_chain_node_feedback_task.md) -> [goal](../../_goal/knowledge_action_chain_node_feedback_goal.md) ->
[identity](../../_identity/KNOWLEDGE_ACTION_CHAIN_NODE_FEEDBACK.md)
