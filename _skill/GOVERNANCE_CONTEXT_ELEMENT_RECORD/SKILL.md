---
name: governance_context_element_record_skill
description: Use this when it must be checked whether where the history of prompts, materials, results, revisions, and approvals is kept is clearly defined, that is, whether the record component of the governance context is in place.
---

# Record — Skill

## Purpose
Check the location and manner in which the history of prompts, materials, results, revisions, and approvals is kept, and determine whether traceability and auditability are being secured in correspondence with international standards (ISO/IEC 42001, NIST, EU AI Act).

## Input
- List of AI operation history items (prompts, materials, results, revisions, approvals)
- Definition of the record location and method per history item

## Procedure (Steps)
1. Identify the history items that arise in the course of AI operation.
2. Confirm, per item, the location and the way in which the record is kept.
3. Confirm whether the record system corresponds to the requirements of ISO/IEC 42001, NIST, and the EU AI Act.
4. Determine whether the history is not scattered and whether tracing and auditing are possible (whether record discontinuity exists).

## Output
Determination result for securing traceability and auditability (corresponding to ISO/IEC 42001 documentation requirements, NIST Govern/Measure, and EU AI Act automatic logging and record-keeping Article 12).

## Criteria
PASS is determined when where the history of instructions, materials, results, revisions, and approvals is kept is clearly judged; FAIL is determined when there is record discontinuity.

## Derivation
[method](../../_method/governance_context_element_record_method.md) -> [knowledge](../../_knowledge/governance_context_element_record_knowledge.md) ->
[task](../../_task/governance_context_element_record_task.md) -> [goal](../../_goal/governance_context_element_record_goal.md) ->
[identity](../../_identity/GOVERNANCE_CONTEXT_ELEMENT_RECORD.md)
