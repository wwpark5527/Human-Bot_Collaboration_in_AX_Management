---
name: knowledge_action_chain_node_context_skill
description: Use when the results that have passed through review and feedback must be accumulated into the organizational standard so as to close the knowledge-action chain, and it must be determined whether that works in a refined way as the input to the next execution.
---

# context (organizational standard) — Skill

## Purpose
It determines whether the 'context' node of the knowledge-action chain actually accumulated the results that passed through review and feedback into the organizational standard, and whether the chain was closed and became the input for the next execution.

## Input
- The updated prohibition rules and training materials that came out of the 'feedback' node

## Procedure (Steps)
1. Accumulate the updated prohibition rules and training materials into the organizational standard.
2. Confirm whether the accumulation was actually reflected into the next standard.
3. Confirm whether the next execution becomes more refined on the basis of the accumulated execution assets.
4. Close the chain and provide the accumulated organizational standard as the input to the next knowledge-action chain.

## Output
The updated and accumulated organizational standard (the input to the next knowledge-action chain).

## Criteria
Whether it was reflected into the next standard, and whether the next execution becomes more refined on the basis of the accumulated execution assets — if both conditions are confirmed it is judged PASS, and if they are not confirmed, FAIL.

## Derivation
[method](../../_method/knowledge_action_chain_node_context_method.md) -> [knowledge](../../_knowledge/knowledge_action_chain_node_context_knowledge.md) ->
[task](../../_task/knowledge_action_chain_node_context_task.md) -> [goal](../../_goal/knowledge_action_chain_node_context_goal.md) ->
[identity](../../_identity/KNOWLEDGE_ACTION_CHAIN_NODE_CONTEXT.md)
