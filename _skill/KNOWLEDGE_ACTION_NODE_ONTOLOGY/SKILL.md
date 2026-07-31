---
name: knowledge_action_node_ontology_skill
description: Use when it must be visually confirmed and determined whether the seven nodes identity·goal·knowledge·method·skill·task·artifact are connected as a knowledge-action chain within one graph.
---

# Knowledge-Action Chain Node Ontology (identity·goal·knowledge·method·skill·task·artifact) — Skill

## Purpose
It determines whether the seven node types identity·goal·knowledge·method·skill·task·artifact that compose the knowledge-action chain are actually connected within one graph structure.

## Input
- The target knowledge system (the set of candidate identity·goal·knowledge·method·skill·task·artifact nodes)

## Procedure (Steps)
1. Identify each of the seven node types.
2. Place the nodes in one graph with a graph visualization tool (Obsidian Graph View or the like).
3. Confirm whether the connections between nodes reflect the actual knowledge-action chain.
4. Organize the step-by-step expansion in the order of the formation flow that starts at the top left and continues clockwise.

## Output
A knowledge-action-chain visualization structure in which the seven nodes (identity·goal·knowledge·method·skill·task·artifact) are connected into one graph.

## Criteria
If all seven nodes are identified and their connection within one graph is confirmed, it is judged PASS; if a node is missing or the connection is not confirmed, FAIL.

## Derivation
[method](../../_method/knowledge_action_node_ontology_method.md) -> [knowledge](../../_knowledge/knowledge_action_node_ontology_knowledge.md) ->
[task](../../_task/knowledge_action_node_ontology_task.md) -> [goal](../../_goal/knowledge_action_node_ontology_goal.md) ->
[identity](../../_identity/KNOWLEDGE_ACTION_NODE_ONTOLOGY.md)
