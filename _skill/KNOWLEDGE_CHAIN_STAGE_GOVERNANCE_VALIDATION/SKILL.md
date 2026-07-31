---
name: knowledge_chain_stage_governance_validation_skill
description: Use this when it must be checked whether the referenced context and the response to be generated pass the organization's authority, security, verification, and approval standards, and whether verification and accountability tracing are possible.
---

# Governance Validation — Skill

## Purpose
Judge whether the governance validation stage of the knowledge chain actually applies the organization's authority, security, verification, and approval standards and passes on to the next stage only those response candidates for which verification and accountability tracing are possible.

## Input
- The interpretation context passed on from the organizational context reference stage
- The response candidate scheduled to be generated
- The organization's authority, security, verification, and approval standards (the governance context)

## Procedure (Steps)
1. Check the interpretation context and the response candidate against each of the authority, security, verification, and approval standards.
2. Confirm whether there is any item falling short of the standards, and if there is, block the response candidate.
3. Record the validation result and its grounds so that accountability tracing is possible.
4. Confirm whether only the response candidates that have passed validation are passed on to the next stage.

## Output
The judgment result on the response candidate that has passed (or been blocked by) validation.

## Criteria
It is judged PASS when verification and accountability tracing are possible, and FAIL when verification/accountability tracing is difficult.

## Derivation
[method](../../_method/knowledge_chain_stage_governance_validation_method.md) -> [knowledge](../../_knowledge/knowledge_chain_stage_governance_validation_knowledge.md) ->
[task](../../_task/knowledge_chain_stage_governance_validation_task.md) -> [goal](../../_goal/knowledge_chain_stage_governance_validation_goal.md) ->
[identity](../../_identity/KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION.md)
