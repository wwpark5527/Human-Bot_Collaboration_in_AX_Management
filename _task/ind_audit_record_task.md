---
identity: IND_AUDIT_RECORD
displayName: "Audit Record"
runID: 20260719_164605
derivedFromIdentity: ../_identity/IND_AUDIT_RECORD.md
---

# Audit Record — Task

## Tasks
1. Define the scope of the AI operation cases subject to preservation — state explicitly which work and which systems' AI use will be regarded as subject to preservation. This becomes the denominator of every preservation rate.
2. Define the preservation requirements for each of the five kinds of record — **prompt** (the instruction actually entered), **data** (the sources referenced and their provenance), **result** (the output generated), **correction** (the details of what a person changed), **approval** (who approved and when). For each kind, prescribe what must remain for it to be recognized as preserved.
3. Calculate the **per-kind preservation rate** separately — do not sum the five values into one. A summed average conceals a state in which a particular kind does not remain at all.
4. State the lowest per-kind preservation rate separately — this value is closest to the organization's actual level of traceability.
5. **Confirm the connections between records (traceability)** — draw a sample and actually trace back from a single output to the prompt that produced it, the referenced data, the correction details, and the approval record. Even if each record exists separately, if they are not connected to one another tracing does not hold.
6. Confirm the retention period and integrity — confirm whether the records are maintained for the prescribed period and whether they are in a form that permits later alteration.
7. Report the per-kind preservation rates, the minimum, and the traceability sample verification result together, and fix a measurement cycle to accumulate a time series on the same standard.

## Deliverables
The record preservation-rate figure — the scope subject to preservation, the preservation requirements for each of the five kinds, the per-kind preservation rates and the per-kind minimum, the traceability sample verification result, the result of confirming the retention period and integrity, the measurement cycle and the time-series record.

## Derivation
[identity](../_identity/IND_AUDIT_RECORD.md)
