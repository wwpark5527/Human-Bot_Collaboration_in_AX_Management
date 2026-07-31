---
name: llm_layer_3_knowledge_chain_skill
description: Use this when determining whether a knowledge chain based on common & governance context (layer 3 of the LLM architecture) has been formed in the target organization, and when diagnosing whether synergy arises upon connection with layer 4 (an external LLM).
---

# Layer 3 (knowledge chain based on common & governance context) — Skill

## Purpose
By the standard of the LLM architecture, determine whether the target organization has secured layer 3 (the knowledge chain).

## Input
- The status of the target organization's information-to-knowledge conversion system
- The implementation status of the common context and the governance context
- The LLM architecture (the layer 1–4/5 structure)

## Procedure (Steps)
1. Confirm whether there is a knowledge chain that converts information inside the organization into knowledge.
2. Inspect whether the common context and the governance context are implemented inside the organizational AX OS.
3. If both conditions are confirmed, judge layer 3 to be secured.
4. If it is insufficient, record in the diagnostic report the risk that connection to layer 4 (an external LLM) will remain at the level of personal AX.
5. Evaluate whether synergy arises upon connection with layer 4 according to the level at which layer 3 is secured.

## Output
The judgment result on securing layer 3 (the knowledge chain), and a diagnostic report on the synergy of connecting to layer 4.

## Criteria
It is judged PASS when the determination result accurately conforms to the standard of the source (whether a knowledge chain based on common and governance context has been formed).

## Derivation
[method](../../_method/llm_layer_3_knowledge_chain_method.md) -> [knowledge](../../_knowledge/llm_layer_3_knowledge_chain_knowledge.md) ->
[task](../../_task/llm_layer_3_knowledge_chain_task.md) -> [goal](../../_goal/llm_layer_3_knowledge_chain_goal.md) ->
[identity](../../_identity/LLM_LAYER_3_KNOWLEDGE_CHAIN.md)
