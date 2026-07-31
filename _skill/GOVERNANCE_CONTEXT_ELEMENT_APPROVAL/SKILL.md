---
name: governance_context_element_approval_skill
description: Use when it must be checked whether it is clearly defined which output artifacts are to be used only after human approval, that is, whether the approval component of the governance context is in place.
---

# Approval — Skill

## Purpose
Check the necessary conditions for human review and approval, and determine whether human intervention and the final judgment criteria are being observed in correspondence with the international standards (ISO/IEC 42001, NIST, EU AI Act).

## Input
- A list of the types of output artifacts AI produces
- The definition of the necessary conditions for human approval by type

## Procedure (Steps)
1. Identify the types of output artifacts AI produces.
2. Confirm for each type whether human approval is required and, if so, by what criteria approval is given.
3. Confirm whether the approval procedure corresponds to the requirements of ISO/IEC 42001, NIST, and the EU AI Act.
4. Determine whether there are output artifacts used without human approval (missing approval).

## Output
The determination result on human intervention and the final judgment criteria (corresponding to ISO/IEC 42001 operational control procedures, NIST Manage, and EU AI Act human oversight, Article 14).

## Criteria
It is judged PASS when which output artifacts must be used only after human approval is clearly determined, and FAIL when there is missing approval.

## Derivation
[method](../../_method/governance_context_element_approval_method.md) -> [knowledge](../../_knowledge/governance_context_element_approval_knowledge.md) ->
[task](../../_task/governance_context_element_approval_task.md) -> [goal](../../_goal/governance_context_element_approval_goal.md) ->
[identity](../../_identity/GOVERNANCE_CONTEXT_ELEMENT_APPROVAL.md)
