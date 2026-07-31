---
name: governance_context_element_validation_skill
description: Use this when it must be checked whether AI results are being confirmed by the criteria of factuality, logic, quality, and policy conformance, that is, whether the validation component of the governance context is in place.
---

# Validation — Skill

## Purpose
Check the checklist and quality criteria for confirming results, and determine whether factuality, logic, quality, and policy conformance are being confirmed in correspondence with international standards (ISO/IEC 42001, NIST, EU AI Act).

## Input
- List of AI result types
- Validation checklist per type

## Procedure (Steps)
1. Identify the types of results AI produces.
2. Organize, per type, by which criteria (factuality, logic, quality, policy conformance) confirmation must be made.
3. Confirm whether the validation criteria correspond to the requirements of ISO/IEC 42001, NIST, and the EU AI Act.
4. Determine whether actual results are being used after going through validation.

## Output
Determination result for confirmation of factuality, logic, quality, and policy conformance (corresponding to ISO/IEC 42001 performance evaluation and monitoring, NIST Measure, and EU AI Act accuracy and robustness Article 15).

## Criteria
PASS is determined when which results must be confirmed by which criteria is clearly judged; FAIL is determined when results are used without validation.

## Derivation
[method](../../_method/governance_context_element_validation_method.md) -> [knowledge](../../_knowledge/governance_context_element_validation_knowledge.md) ->
[task](../../_task/governance_context_element_validation_task.md) -> [goal](../../_goal/governance_context_element_validation_goal.md) ->
[identity](../../_identity/GOVERNANCE_CONTEXT_ELEMENT_VALIDATION.md)
