---
name: knowledge_chain_stage_context_reference_skill
description: Use this when it must be checked whether a question is interpreted against the organization's common context (purpose, standards, roles, sources, format), so that the answer is produced by referencing the organization's standards without being swayed by per-user differences in interpretation.
---

# Organizational Context Reference — Skill

## Purpose
Judge whether the question was interpreted by referencing the organization's history, intent, norms, and memory, and whether an interpretation context reflecting organizational standards was formed as a result.

## Input
- The request unit passed on from the question stage
- The definition of the organization's common context (purpose, standards, roles, sources, format)

## Procedure (Steps)
1. Map the request unit onto the items of the organization's common context.
2. Confirm the related parts of the organization's history, intent, norms, and memory.
3. Confirm whether the interpretation result is grounded in the organization's standards rather than being swayed from user to user.
4. Judge whether an interpretation context reflecting organizational standards was formed.

## Output
The judgment result on the interpretation context in which organizational standards are reflected.

## Criteria
It is judged PASS when the answer is produced by referencing the organization's standards without being swayed by per-user differences in interpretation, and FAIL otherwise.

## Derivation
[method](../../_method/knowledge_chain_stage_context_reference_method.md) -> [knowledge](../../_knowledge/knowledge_chain_stage_context_reference_knowledge.md) ->
[task](../../_task/knowledge_chain_stage_context_reference_task.md) -> [goal](../../_goal/knowledge_chain_stage_context_reference_goal.md) ->
[identity](../../_identity/KNOWLEDGE_CHAIN_STAGE_CONTEXT_REFERENCE.md)
