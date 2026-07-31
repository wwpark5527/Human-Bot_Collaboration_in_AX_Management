---
name: knowledge_chain_stage_question_skill
description: Use this when it must be checked whether a request that a human or an AI poses to the organization is consumed one-off and ends, or is connected onward to the following stages of the knowledge chain (organizational context reference and so on).
---

# Question — Skill

## Purpose
Judge whether the question, as the entry stage of the knowledge chain, does not end in one-off consumption but continues as a request unit passed on to subsequent stages.

## Input
- The request (question) posed to the organization by a human or an AI
- Path information on how that request connects to subsequent processing stages

## Procedure (Steps)
1. Identify the received question.
2. Confirm whether that question is consumed within the one-off structure of "question → answer → end."
3. Confirm whether the question is structured as a request unit that continues on to the next stage, such as organizational context reference.
4. Judge whether the question has been incorporated into the circulation/accumulation structure of the knowledge chain.

## Output
The judgment result on the request unit passed on to subsequent stages.

## Criteria
It is judged PASS when the question is connected onward to context reference, validation, and recording, and FAIL when it is consumed one-off and ends.

## Derivation
[method](../../_method/knowledge_chain_stage_question_method.md) -> [knowledge](../../_knowledge/knowledge_chain_stage_question_knowledge.md) ->
[task](../../_task/knowledge_chain_stage_question_task.md) -> [goal](../../_goal/knowledge_chain_stage_question_goal.md) ->
[identity](../../_identity/KNOWLEDGE_CHAIN_STAGE_QUESTION.md)
