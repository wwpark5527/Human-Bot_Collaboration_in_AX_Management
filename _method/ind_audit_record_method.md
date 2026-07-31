---
identity: IND_AUDIT_RECORD
displayName: "Audit Record"
runID: 20260719_164605
derivedFromIdentity: ../_identity/IND_AUDIT_RECORD.md
---

# Audit Record — Method

## Method / Procedure
1. Fix the scope of the AI operation cases subject to preservation — state explicitly whose work and which systems' AI use will be regarded as within scope. This scope is the denominator of every per-kind preservation rate, and it is fixed throughout the measurement cycle.
2. Fix the preservation requirements for each of the five kinds — **prompt** (the full text of the instruction actually entered), **data** (the sources referenced and their provenance), **result** (the generated output), **correction** (the details of what a person changed and who made the change), **approval** (the approver and the time of approval). For each kind, prescribe what must remain for it to be recognized as preserved.
3. **Calculate the per-kind preservation rate separately** — compute five times separately the proportion of cases in which the record of that kind remains and meets the requirements, relative to the cases in scope. Do not combine the five values into a single average.
4. **State the lowest per-kind preservation rate explicitly** — present the lowest of the five values as a separate item. This value is closest to the organization's actual level of traceability.
5. **Verify traceability by sampling** — draw a sample of outputs and actually connect each through to the prompt that produced it, the referenced data, the correction details, and the approval record. Record the points where the connection breaks, and leave the sample size and the method of selection alongside.
6. Confirm the retention period and integrity — confirm whether the records are maintained for the prescribed period and whether they are in a form that permits later alteration or deletion. Since records that can be altered after the fact are weak in character as audit grounds, state that fact explicitly.
7. Present the per-kind preservation rates, the per-kind minimum, and the traceability verification result bound together as one reporting unit.
8. Fix a measurement cycle and accumulate a time series on the same standard.

## Criteria
With the scope subject to preservation and the preservation requirements of the five kinds stated explicitly, it is PASS when **the preservation rate of each of prompt, data, result, correction, and approval is calculated separately**, the **per-kind minimum** is presented alongside, the result of **traceability verification** through sampling is attached, and a time series on the same standard is accumulated. It is judged FAIL if any one of the following applies — (a) the case in which the five kinds were summed and only a single average preservation rate was reported, (b) the case in which per-kind preservation rates were produced but the connections between records were not confirmed, so that the definitional requirement "in a traceable way" was not verified, (c) the case in which the scope subject to preservation was not stated explicitly, so that the denominator is unclear. (a) hides behind a good average value a state in which correction and approval records are missing entirely, (b) leads to scattered records being wrongly reported as a traceable history, and (c) makes the preservation rate itself irreproducible.

## Derivation
[identity](../_identity/IND_AUDIT_RECORD.md)
