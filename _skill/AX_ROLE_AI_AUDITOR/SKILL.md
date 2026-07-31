---
name: ax_role_ai_auditor_skill
description: Used when the AI Auditor role, which verifies the accuracy and reliability of outputs produced by AI in an AX organization (analysis results, generated content, decision proposals, etc.), must be designed and operated.
---

# AI Auditor — Skill

## Purpose
Systematically verify the accuracy and reliability of AI outputs so that errors, hallucination and bias are found early and acted upon.

## Input
- A list of the outputs produced by AI (analysis results, generated content, decision proposals, etc.)
- The organization's criteria for verifying quality and reliability

## Procedure (Steps)
1. Grasp the types of AI outputs.
2. Establish verification criteria by type.
3. Check AI outputs against the verification criteria and record the results.
4. When errors, hallucination or bias are found, connect to a rework or reporting procedure.

## Output
A document of AI result verification criteria and procedures, and records of AI result verification results.

## Criteria
If a verification procedure for AI results is established and is actually performed and recorded, it is judged PASS; otherwise it is judged FAIL.

## Derivation
[method](../../_method/ax_role_ai_auditor_method.md) -> [knowledge](../../_knowledge/ax_role_ai_auditor_knowledge.md) ->
[task](../../_task/ax_role_ai_auditor_task.md) -> [goal](../../_goal/ax_role_ai_auditor_goal.md) ->
[identity](../../_identity/AX_ROLE_AI_AUDITOR.md)
