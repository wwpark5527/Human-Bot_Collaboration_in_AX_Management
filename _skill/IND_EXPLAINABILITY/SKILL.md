---
name: ind_explainability_skill
description: Used when the AI-decision explanation-provision rate and user comprehension must be measured. It produces the sixth of the 12 Inclusive Transition ESG indicators.
---

# Explainability — Skill

## Purpose
By calculating the AI-decision explanation-provision rate and user comprehension, make it possible to confirm whether explanations for AI decisions are actually provided and whether those explanations are understood by the people who receive them. It measures the sixth of the 12 Inclusive Transition ESG indicators.

## Input
- The definition of the AI decision types to which the duty of explanation attaches and the list of decision cases in the period, the records of dispatch and delivery of explanation notifications and the form of explanation, the comprehension confirmation questions and the response data, the roster of persons concerned and their job and grade composition, and the measurement results of the previous cycle (for time-series comparison)

## Procedure (Steps)
1. Fix the scope of the AI decisions subject to explanation (the denominator of the provision rate).
2. Fix the minimum requirements of an explanation (grounds of the decision, data used, criteria applied, route of appeal).
3. Calculate the explanation-provision rate as the proportion of cases in which an explanation meeting the minimum requirements was delivered.
4. Fix the method of measuring comprehension as restatement or confirmation questions (the use of satisfaction questions is prohibited).
5. Measure user comprehension and record alongside the response rate and sample composition.
6. Decompose comprehension by job, grade, and experience of using AI.
7. Bind the provision rate and comprehension into one reporting unit and mark the ranges in which comprehension is low relative to the provision rate.
8. Fix a measurement cycle and accumulate a time series on the same standard.

## Output
The measured values of the explanation-provision rate and user comprehension — the scope subject to explanation, the minimum requirements of an explanation, the explanation-provision rate, the method and questions for measuring comprehension, user comprehension with the response rate and sample composition, the decomposition by group, the ranges of divergence between provision rate and comprehension, the time-series record.

## Criteria
With the scope subject to explanation and the minimum requirements stated explicitly, it is judged PASS when both the provision rate and comprehension are calculated, comprehension is measured by a method of confirming understanding, and they are reported together; it is judged FAIL if the provision rate was filled without minimum requirements, if comprehension was measured as satisfaction, or if only the provision rate was produced and comprehension was not.

## Derivation
[method](../../_method/ind_explainability_method.md) -> [knowledge](../../_knowledge/ind_explainability_knowledge.md) ->
[task](../../_task/ind_explainability_task.md) -> [goal](../../_goal/ind_explainability_goal.md) ->
[identity](../../_identity/IND_EXPLAINABILITY.md)
