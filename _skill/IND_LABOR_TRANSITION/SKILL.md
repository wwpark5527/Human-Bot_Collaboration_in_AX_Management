---
name: ind_labor_transition_skill
description: Used when whether a job impact assessment was conducted before AI adoption and the transition-reassignment rate must be measured. It produces the fourth of the 12 Inclusive Transition ESG indicators.
---

# Labor Transition — Skill

## Purpose
By calculating whether a job impact assessment was conducted before AI adoption and the transition-reassignment rate, make it possible to confirm whether the organization grasped in advance the change when jobs change through AI adoption, and whether the people affected were actually reassigned to new roles. It measures the fourth of the Inclusive-Transition ESG 12 indicators.

## Input
- The list of AI adoption cases within the measurement period and the evidence of the point of adoption of each case (contract, release, and start-of-actual-use records), the job impact assessment documents and their writing dates, the roster of people judged to be affected, the records of transition reassignment orders and the status of reassignment, departure records, and the measurement results of the previous cycle (for time-series comparison)

## Procedure (Steps)
1. Fix the unit of AI adoption cases and the definition of the point of adoption.
2. Confirm the completeness of the list of adoption cases within the measurement period.
3. For each adoption case, confirm the existence of a job impact assessment and its writing date.
4. Judge as conducted in advance only the cases satisfying the timing condition (writing after the fact counts as not conducted).
5. Present in aggregate form the number of cases conducted in advance relative to all adoption cases.
6. Fix the denominator of the transition-reassignment rate as the people judged to be affected (use of the whole workforce is prohibited).
7. Calculate the transition-reassignment rate and mark separately the ranges of reassignment in progress, incomplete, and departure.
8. Present whether it was conducted and the reassignment rate bound together as one reporting unit.
9. Fix a measurement cycle and accumulate a time series on the same standard.

## Output
Whether the impact assessment was conducted and the transition-reassignment rate — the unit of adoption cases and the definition of the point of adoption, the judgment of advance conduct per adoption case and the evidence of timing, the number of cases conducted relative to all adoption cases, the definition of the reassignment-rate denominator, the transition-reassignment rate and the in-progress, incomplete, and departure ranges, the time-series record.

## Criteria
With the definition of the point of adoption stated explicitly, it is judged PASS when whether an advance impact assessment was conducted is judged with evidence of timing and the transition-reassignment rate is calculated on the basis of the people judged to be affected and reported together; it is judged FAIL if the writing date of the assessment was not confirmed so that advance and after-the-fact are not distinguished, if the denominator was taken as the whole workforce, or if only whether it was conducted is reported and the reassignment rate is not produced.

## Derivation
[method](../../_method/ind_labor_transition_method.md) -> [knowledge](../../_knowledge/ind_labor_transition_knowledge.md) ->
[task](../../_task/ind_labor_transition_task.md) -> [goal](../../_goal/ind_labor_transition_goal.md) ->
[identity](../../_identity/IND_LABOR_TRANSITION.md)
