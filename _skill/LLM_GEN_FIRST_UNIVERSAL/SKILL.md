---
name: llm_gen_first_universal_skill
description: Used when discriminating whether a target LLM corresponds to the general-purpose 'first LLM' supplied externally by big tech (layer 4 of the architecture diagram), and when diagnosing the limits of hallucination and security leakage that come along with the ability to generate natural sentences.
---

# The First LLM — Skill

## Purpose
Discriminate whether the target LLM corresponds to the 'first LLM', and diagnose its generation ability and limits.

## Input
- Information on the supplying entity and the learning method of the target LLM
- Samples of sentence generation results
- The LLM architecture diagram (the layer 1-4/5 structure)

## Procedure (Steps)
1. Confirm whether the supplying entity is big tech and whether it is a general-purpose model supplied from outside.
2. Check whether it is concentrated on natural sentence generation on the basis of huge corpus learning.
3. When the conditions are met, classify it as the 'first LLM' (layer 4 of the architecture diagram).
4. Diagnose hallucination and the risk of security leakage together and record them.

## Output
The discrimination result of the 'first LLM', and a diagnostic report on the risks of hallucination and security leakage.

## Criteria
It is determined as PASS when the discrimination result conforms to the source criteria (external supply by big tech, concentration on natural sentence generation) and the diagnosis of the limits is recorded along with it.

## Derivation
[method](../../_method/llm_gen_first_universal_method.md) -> [knowledge](../../_knowledge/llm_gen_first_universal_knowledge.md) ->
[task](../../_task/llm_gen_first_universal_task.md) -> [goal](../../_goal/llm_gen_first_universal_goal.md) ->
[identity](../../_identity/LLM_GEN_FIRST_UNIVERSAL.md)
