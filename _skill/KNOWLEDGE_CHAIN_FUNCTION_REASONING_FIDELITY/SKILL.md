---
name: knowledge_chain_function_reasoning_fidelity_skill
description: Use when the validity of the reasoning process leading to the result, rather than the conclusion, must be evaluated.
---

# Reasoning-Chain Fidelity Measurement — Skill

## Purpose
It determines whether the reasoning-chain fidelity measurement function of the knowledge chain actually evaluates the validity of the reasoning path (intermediate steps, connections, evidence) rather than the correctness of the conclusion.

## Input
- The conclusion to be evaluated
- The intermediate reasoning steps leading to it

## Procedure (Steps)
1. Confirm the conclusion and the intermediate reasoning steps.
2. Check the validity of each intermediate step.
3. Confirm the connection between steps and whether the last step supports the answer.
4. Confirm whether each step is connected to evidence, and produce the result of the process-validity evaluation.

## Output
The result of the process-validity evaluation (a judgment on the reasoning path, not the result).

## Criteria
If the validity of the intermediate steps, the connection between steps, the last step's support of the answer, and the connection to evidence are all confirmed, it is judged PASS; if even one is not confirmed, FAIL.

## Derivation
[method](../../_method/knowledge_chain_function_reasoning_fidelity_method.md) -> [knowledge](../../_knowledge/knowledge_chain_function_reasoning_fidelity_knowledge.md) ->
[task](../../_task/knowledge_chain_function_reasoning_fidelity_task.md) -> [goal](../../_goal/knowledge_chain_function_reasoning_fidelity_goal.md) ->
[identity](../../_identity/KNOWLEDGE_CHAIN_FUNCTION_REASONING_FIDELITY.md)
