---
name: ind_benefit_sharing_skill
description: Used when calculating the reinvestment rate of AI productivity gains into compensation, education, and welfare each accounting cycle in order to fix as a single figure whether the gains flowed back to members. The basis of computation for the denominator is made a mandatory submission, the three channels are decomposed, and PASS is judged only after the proportion of beneficiaries and the distribution by grade and employment type have been confirmed.
---

# ind_benefit_sharing_skill — Measuring the Benefit Sharing Reinvestment Rate

## Purpose

Measure **benefit sharing**, the tenth item of the 12 Inclusive Transition ESG indicators. The value produced is one — the reinvestment rate of AI productivity gains into compensation, education, and welfare. This skill does not distribute benefit. It counts whether distribution occurred, and inspects whether that figure is hiding manipulation of the denominator or concentration of benefit.

## Input

- The measurement period (half-yearly or annual, aligned with the accounting cycle).
- Materials for computing the AI productivity gains — a document containing the computation method, reference point in time, and scope of covered work.
- Execution materials for each of compensation paid, education invested, and welfare executed (with the basis of execution unified).
- Materials on out-of-channel reinvestment amounts (organizational capability, facilities, retention, and so on).
- A specification of beneficiaries — number of people, grade, employment type (stating explicitly whether non-regular, contract, and dispatched personnel are included).
- The baseline values announced in advance (reinvestment rate, proportion of beneficiaries).
- The reinvestment rate and gains of the immediately preceding cycle and the same period of the previous year.

## Procedure

1. Compute the denominator and fix the computation method, reference point in time, and covered work in a document. If there is no basis document, stop here and treat it as invalid.
2. Fix compensation, education, and welfare each separately, then sum them to form the numerator. Unify and state explicitly the basis of execution.
3. Exclude from the numerator reinvestment not attributed to members (organizational capability and the like) and leave it as a separate amount. Show the remainder of the gains as well.
4. Calculate the reinvestment rate = (compensation + education + welfare) ÷ gains × 100 and produce the composition ratio by channel.
5. Calculate the number and proportion of beneficiaries and the distribution of amounts by grade and by employment type. State explicitly whether non-regular, contract, and dispatched personnel are included.
6. Attach the values of the gains themselves for the immediately preceding cycle and the same period of the previous year.
7. Compare with the immediately preceding cycle and the same period of the previous year.
8. Decide PASS/FAIL according to the criteria and record it together with the grounds.

## Output

- **The reinvestment-rate figure**.
- The amounts and composition ratios by the channels of compensation, education, and welfare.
- The amount of the gains, the document of the computation basis, and the time series of the gains.
- The out-of-channel reinvestment amount (the portion excluded from the numerator) and the remainder.
- The proportion of beneficiaries and the distribution table by grade and by employment type.
- The trend against the immediately preceding cycle and the same period of the previous year.
- The PASS/FAIL judgment and the list of unsatisfied conditions.

## Criteria

It is PASS only when **all** four conditions are satisfied.

- (a) The reinvestment rate is at or above the baseline announced in advance.
- (b) **All three channels of compensation, education, and welfare exceed 0** — if even one is 0, it is FAIL regardless of the total.
- (c) The document of the denominator's computation basis is presented and the time series of the gains is reported alongside.
- (d) The proportion of beneficiaries is at or above the standard and there is no concentration by grade or employment type.

Explicit FAIL conditions: a reinvestment rate without a basis for the denominator (the most common form of failure), a case in which a rise in the reinvestment rate is accompanied by a fall in the gains (FAIL unless an increase in the absolute amount of the numerator can be shown), submission of the total alone without decomposition by channel, submission of the total amount alone without the distribution of benefit, and a calculation including out-of-channel reinvestment such as organizational capability in the numerator (the figure is invalid).

## Derivation
[method](../../_method/ind_benefit_sharing_method.md) -> [knowledge](../../_knowledge/ind_benefit_sharing_knowledge.md) ->
[task](../../_task/ind_benefit_sharing_task.md) -> [goal](../../_goal/ind_benefit_sharing_goal.md) ->
[identity](../../_identity/IND_BENEFIT_SHARING.md)
