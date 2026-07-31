---
identity: IND_ACCOUNTABILITY_STRUCTURE
displayName: "Accountability Structure"
runID: 20260719_164605
derivedFromIdentity: "[IND_ACCOUNTABILITY_STRUCTURE](../_identity/IND_ACCOUNTABILITY_STRUCTURE.md)"
---

# Accountability Structure — Method

The measurement cycle is **quarterly**. Since designation is an event that occurs at the moment an output is produced, it is collected continuously, while aggregation and judgment are performed at the end of the quarter. There are two comparison targets: the value of the immediately preceding quarter and the value of the same quarter of the previous year.

## Steps

**Step 1 — Fix the measurement unit and the denominator.**
Define the unit of one AI output (for example, one document going outside, one deployment, one decision requiring approval). Leave the definition in a document, and fix the total number of cases falling under that definition within the measurement period as the denominator N. The unit definition is not changed in the middle of a quarter.

**Step 2 — Collect the designated cases.**
For each output belonging to the denominator, collect whether a final responsible party is recorded and what is recorded. The collection sources are approval records, output metadata, and sign-off history, and the collection sources are stated explicitly.

**Step 3 — Classify the designated cases into three branches.**
- (A) Cases in which one final responsible party is designated by an individual identifier
- (B) Cases in which only a department, team, or job title is recorded, or in which multiple final responsible parties are recorded
- (C) No record

The numerator consists of (A) alone. The numbers of cases in (B) and (C) are each recorded separately.

**Step 4 — Calculate the designation rate.**
Designation rate = (A) ÷ N × 100. This is the value this indicator must produce.

**Step 5 — Classify the time of designation.**
Compare each case in (A) against the time the output was produced and divide them into prior designation and retroactive after-the-fact designation. Cases that cannot be determined because time information is missing are treated as after-the-fact designation. Prior-designation ratio = number of prior designations ÷ (A) × 100.

**Step 6 — Decompose by department.**
Repeat steps 3 to 4 at the department level to calculate the per-department designation rate, and state the minimum and the department in question.

**Step 7 — Verify the actual existence of authority by sampling.**
Draw a sample from (A) and confirm whether the designated responsible party actually holds the authority to demand access to, modification of, or suspension of the output in question. Cases without authority are reclassified into (B) and step 4 onward is recalculated. The sample size and the number of reclassified cases are recorded.

**Step 8 — Compare and judge.**
Place them side by side with the immediately preceding quarter and the same quarter of the previous year, and decide PASS/FAIL by the criteria below.

**Step 9 — Record.**
Leave the designation rate, the per-department table and the minimum, the prior-designation ratio, the numbers of (B) and (C) cases, the sample verification result, and the judgment result and its grounds.

## Criteria

Only when **all** four of the following conditions are satisfied is it judged PASS.

- **(a) The company-wide designation rate is at or above the baseline.** The baseline must have been announced before the measurement, and cannot be adjusted after the fact to fit the result.
- **(b) The minimum of the per-department designation rates is at or above the baseline.** A case that satisfies only the company-wide average is FAIL. Because the average conceals departmental gaps, a judgment made without looking at the minimum is not recognized as a judgment of this indicator.
- **(c) The prior-designation ratio is at or above the standard.** However high the designation rate is, if most of it is retroactive after-the-fact designation it is FAIL. In this case the organization did not design responsibility but distributed it after an accident.
- **(d) It passes the authority sample verification.** If designations without authority are confirmed in the sample, (a) to (c) are judged again after recalculation.

The following are explicit FAIL conditions.

- A designation rate calculated by including department-level designation in the numerator — since this violates the measurement discipline, the figure itself is invalidated.
- A designation rate submitted without a prior-designation ratio — since it cannot be interpreted, judgment is not deferred but recorded as FAIL.
- A result submitting only one company-wide value without decomposition by department — since (b) cannot be judged, it is FAIL.

When the designation rate comes out low, before pointing at a target for improvement, first distinguish **whether there was no designation or no record**. If the latter, the cause lies on the record-retention side rather than in this indicator, so state that fact explicitly in the judgment record.

## Derivation
[identity](../_identity/IND_ACCOUNTABILITY_STRUCTURE.md)
