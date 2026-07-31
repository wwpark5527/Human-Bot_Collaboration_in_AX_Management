---
name: governance_context_element_authority_skill
description: Use this when it must be checked whether which context can access which materials and tools is clearly defined, that is, whether the authority component of the governance context is in place.
---

# Authority — Skill

## Purpose
Check the scope of materials and tools AI can access, and determine whether the access and execution scope is managed in correspondence with international standards (ISO/IEC 42001, NIST AI RMF, EU AI Act).

## Input
- Current state of AI-accessed materials and tools per local context
- Defined access authority scope per context

## Procedure (Steps)
1. Identify the materials and tools AI is accessing per context.
2. Compare the defined access scope with the actual state of access.
3. Confirm whether the access scope corresponds to the requirements of ISO/IEC 42001, NIST AI RMF, and the EU AI Act.
4. Determine whether authority confusion (unclear accessible scope) exists.

## Output
Determination result for management of access and execution scope (corresponding to ISO/IEC 42001 role/access control, NIST AI RMF Govern, and EU AI Act human oversight Article 14).

## Criteria
PASS is determined when which context can access which materials and tools is clearly judged; FAIL is determined when there is authority confusion.

## Derivation
[method](../../_method/governance_context_element_authority_method.md) -> [knowledge](../../_knowledge/governance_context_element_authority_knowledge.md) ->
[task](../../_task/governance_context_element_authority_task.md) -> [goal](../../_goal/governance_context_element_authority_goal.md) ->
[identity](../../_identity/GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY.md)
