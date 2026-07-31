---
name: step_audit_record_skill
description: Use when an audit record system must be built that preserves the prompts, materials, results, corrections, and approval history of AI work. It performs the seventh step of the AI Inclusive-Transformation ESG execution model (9 steps).
---

# 7. Audit Record — Skill

## Purpose
Preserve the history of prompts, materials, results, corrections, and approvals so that the whole course of AI work can be reconstructed and verified after the fact. It performs the seventh step of the AI Inclusive-Transformation ESG execution model (9 steps). The ESG linkage is G (Governance).

## Input
- The output of step 5, human approval criteria (the points at which approval history remains), the output of step 6, appeal procedure (the points at which intake and processing history is recorded), the AI workflow and the list of tools used, and internal standards related to record retention, personal data, and security

## Procedure (Steps)
1. Define the five kinds of preservation objects (prompts, materials, results, corrections, approval history) at the item level.
2. Designate the record generation point and the automatic collection method for each kind.
3. Set the output-artifact identifiers and linking rules so that the five kinds are bound into a single history.
4. Determine the retention period, storage location, access rights, and method of tamper prevention.
5. Incorporate the approval history and the appeal processing history into this record system.
6. Determine the method of calculating the record preservation rate and calculate it periodically to find the gaps where records are missing.

## Output
The preserved audit record — the definitions of the five kinds of records, the collection points and methods, the rules linking history at the output-artifact level, the retention period, access rights, and method of tamper prevention, and the method of calculating the record preservation rate.

## Criteria
It is judged PASS if all five kinds are preserved, history can be reconstructed at the output-artifact level, and the retention period, access rights, and tamper prevention are determined; it is judged FAIL if even one kind has no collection point or history cannot be linked. (ESG linkage: G)

## Derivation
[method](../../_method/step_audit_record_method.md) -> [knowledge](../../_knowledge/step_audit_record_knowledge.md) ->
[task](../../_task/step_audit_record_task.md) -> [goal](../../_goal/step_audit_record_goal.md) ->
[identity](../../_identity/STEP_AUDIT_RECORD.md)
