---
name: knowledge_chain_stage_result_record_skill
description: Use this when the grounds, process, and premises of a generated result must be recorded within the organization in a traceable form.
---

# Result Recording — Skill

## Purpose
Judge whether the result recording stage of the knowledge chain turns the generated result into a traceable asset in which grounds, process, and version remain, converting a response from a "scattered response" into a record the organization can reuse.

## Input
- The result (response candidate) produced in the response generation stage
- The grounds and process that led to that result
- The premises used

## Procedure (Steps)
1. Confirm the result and its grounds, process, and premises.
2. Record the grounds, process, and premises, and assign a version.
3. Check whether the record makes it possible to later trace why it is correct, where it went wrong, and what premises were used.
4. Pass the completed record on to the next stage (re-reflection into organizational knowledge).

## Output
A traceable record (grounds, process, version).

## Criteria
It is judged PASS when the grounds of the result are recorded and traceable, and FAIL when verification/accountability tracing is difficult.

## Derivation
[method](../../_method/knowledge_chain_stage_result_record_method.md) -> [knowledge](../../_knowledge/knowledge_chain_stage_result_record_knowledge.md) ->
[task](../../_task/knowledge_chain_stage_result_record_task.md) -> [goal](../../_goal/knowledge_chain_stage_result_record_goal.md) ->
[identity](../../_identity/KNOWLEDGE_CHAIN_STAGE_RESULT_RECORD.md)
