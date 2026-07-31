---
name: llm_gen_third_full_stack_skill
description: Used when discriminating whether a target system stops at the sum of layers 1 through 4 (the 'second LLM') or has reached the status of the 'third LLM' (layers 1 through 5 fully in place) with layer 5 added.
---

# The Third LLM — Skill

## Purpose
Discriminate whether the completion status of the target system is the 'second LLM' (layers 1 through 4) or the 'third LLM' (layers 1 through 5 fully in place).

## Input
- The current status of layers 1 through 4 being fully in place in the target system
- The constituent requirements of layer 5 on the basis of Chapter 8
- The LLM architecture diagram (the layer 1-4/5 architecture)

## Procedure (Steps)
1. Confirm whether layers 1 through 4 (the level of the 'second LLM') are fully in place.
2. Check whether the layer 5 requirements on the basis of Chapter 8 are met.
3. When layer 5 is also met, classify it as the 'third LLM' (layers 1 through 5 fully in place); otherwise classify it as the 'second LLM' (layers 1 through 4).

## Output
The status discrimination result of the 'second LLM' | the 'third LLM'.

## Criteria
It is determined as PASS when the discrimination result exactly conforms to the source criterion (distinguishing the second LLM and the third LLM by the presence or absence of layer 5).

## Derivation
[method](../../_method/llm_gen_third_full_stack_method.md) -> [knowledge](../../_knowledge/llm_gen_third_full_stack_knowledge.md) ->
[task](../../_task/llm_gen_third_full_stack_task.md) -> [goal](../../_goal/llm_gen_third_full_stack_goal.md) ->
[identity](../../_identity/LLM_GEN_THIRD_FULL_STACK.md)
