---
name: ind_audit_record_skill
description: Used when the preservation rate and traceability of the five kinds of record — prompt, data, result, correction, approval — must be measured. It produces the eighth of the 12 Inclusive Transition ESG indicators.
---

# Audit Record — Skill

## Purpose
By calculating separately the preservation rate of the five kinds of record — prompt, data, result, correction, approval — and verifying the traceability between records, make it possible to confirm whether the history of AI operation actually remains in a form that can be traced back later. It measures the eighth of the 12 Inclusive Transition ESG indicators.

## Input
- The list of AI operation cases subject to preservation and the scope of the systems used, prompt logs, referenced data and provenance records, the output repository, correction history and information on who made the corrections, approval records and times of approval, the record-retention policy and the retention-period rules, and the measurement results of the previous cycle (for time-series comparison)

## Procedure (Steps)
1. Fix the scope of the AI operation cases subject to preservation (the denominator of every preservation rate).
2. Fix the preservation requirements for each of the five kinds — prompt, data, result, correction, approval.
3. Calculate the per-kind preservation rate five times separately (summed averages are prohibited).
4. State the lowest per-kind preservation rate as a separate item.
5. Verify traceability by connecting a sample of outputs through to prompt, data, correction, and approval, and record the points where the connection breaks.
6. Confirm the retention period and integrity (whether later alteration is possible).
7. Present the per-kind preservation rates, the minimum, and the traceability verification result bound together as one reporting unit.
8. Fix a measurement cycle and accumulate a time series on the same standard.

## Output
The record preservation-rate figure — the scope subject to preservation, the preservation requirements and preservation rates for each of the five kinds, the per-kind minimum, the traceability sample verification result and the points of breakage, the result of confirming the retention period and integrity, the time-series record.

## Criteria
With the scope subject to preservation and the preservation requirements of the five kinds stated explicitly, it is judged PASS when the per-kind preservation rates are each calculated and the per-kind minimum and the traceability verification result are reported together; it is judged FAIL if the five kinds were summed and only a single average was reported, if the connections between records were not confirmed, or if the scope subject to preservation was not stated explicitly.

## Derivation
[method](../../_method/ind_audit_record_method.md) -> [knowledge](../../_knowledge/ind_audit_record_knowledge.md) ->
[task](../../_task/ind_audit_record_task.md) -> [goal](../../_goal/ind_audit_record_goal.md) ->
[identity](../../_identity/IND_AUDIT_RECORD.md)
