---
name: knowledge_chain_function_structural_distance_skill
description: Use when the distance between the current concept structure and the target structure must be measured so as to identify missing concepts and misconceptions.
---

# Structural-Distance Measurement — Skill

## Purpose
It determines whether the structural-distance measurement function of the knowledge chain calculates the difference between the current concept structure and the target structure and thereby identifies not only what one does not know but also what one knows incorrectly.

## Input
- The current concept structure
- The target concept structure

## Procedure (Steps)
1. Confirm the current concept structure and the target structure respectively.
2. Count the numbers of missing concepts, incorrect connections, and unnecessary connections.
3. Calculate the structural-distance value reflecting the three elements.
4. Identify missing concepts and misconceptions from the structural distance.

## Output
The structural-distance value between the current concept structure and the target structure (identification of missing concepts and misconceptions).

## Criteria
If missing concepts and misconceptions are identified, it is judged PASS; if they are not identified, FAIL.

## Derivation
[method](../../_method/knowledge_chain_function_structural_distance_method.md) -> [knowledge](../../_knowledge/knowledge_chain_function_structural_distance_knowledge.md) ->
[task](../../_task/knowledge_chain_function_structural_distance_task.md) -> [goal](../../_goal/knowledge_chain_function_structural_distance_goal.md) ->
[identity](../../_identity/KNOWLEDGE_CHAIN_FUNCTION_STRUCTURAL_DISTANCE.md)
