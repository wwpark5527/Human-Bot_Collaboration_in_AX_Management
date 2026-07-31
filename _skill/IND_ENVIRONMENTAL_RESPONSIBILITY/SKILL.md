---
name: ind_environmental_responsibility_skill
description: Used when calculating the three values of AI-infrastructure power usage, carbon emissions, and data-center efficiency each quarter in order to fix the environmental burden caused by AI operation. Externally outsourced computation is included in the measurement boundary, absolute quantities and efficiency must be stated together, and claiming that an increase in absolute quantities is offset by efficiency improvement is judged FAIL.
---

# Environmental Responsibility — Measuring Environmental Responsibility

## Purpose

Measure **environmental responsibility**, the eleventh and last item of the 12 Inclusive Transition ESG indicators. The values produced are three — AI-infrastructure power usage, carbon emissions, and data-center efficiency. It is the only E-axis item among the 12 indicators. This skill does not reduce the environmental burden. It measures how large the burden is and inspects whether that figure has been distorted by boundary setting and the efficiency illusion.

**Limits of scope (must be reported alongside):** This indicator measures only **two of the six items** given by the E-axis extension discussion (power use, water use, carbon emissions, semiconductors and minerals, electronic waste, local environmental impact) — power and carbon — plus one efficiency ratio. Water use, semiconductors and minerals, electronic waste, and local environmental impact are outside the scope. To report satisfaction of this indicator as fulfilment of the whole E axis is over-reporting.

## Input

- The measurement period (monthly collection, quarterly reporting) and the fixed measurement boundary definition document — the inclusion or exclusion of each of the company's own data centers and in-house servers, externally outsourced cloud computation (including training and inference APIs), and leased and colocation facilities.
- Metered power data for the company's own facilities (kWh).
- Power and efficiency data supplied by outsourcing providers and the time of publication.
- The load allocation standard for facilities where AI and non-AI are mixed.
- The emission factor to be applied (source and year) and materials on renewable energy procurement.
- An AI workload indicator (for calculating the intensity).
- The three values for the same period of the previous year and the immediately preceding quarter.

## Procedure

1. Fix the measurement boundary and fix it in a document. Do not change it during the period.
2. Collect in kWh the power usage of the AI infrastructure within the boundary. For mixed facilities, record the allocation standard.
3. Apply the emission factor to convert into tCO2e. Record the source and year of the factor, how renewable energy is reflected, and the in-house/outsourced separation.
4. Calculate the data-center efficiency. Leave the formula and measurement points and the source of the published figures for outsourced facilities.
5. Mark the values that could not be obtained as 'unmeasured' and record their share. **Do not substitute 0.**
6. State the absolute quantities and the efficiency together in the same table and mark the increase or decrease against the same period of the previous year. State movement in opposite directions explicitly in a sentence.
7. Calculate the intensity per unit of AI workload (reported only when stated alongside the absolute quantities).
8. Compare with the same period of the previous year and the immediately preceding quarter.
9. Decide PASS/FAIL according to the criteria and record it together with the grounds.

## Output

- **The power usage figure** (kWh), **the carbon emissions figure** (tCO2e), **the data-center efficiency figure**.
- The measurement boundary definition document (inclusion of in-house, outsourced, and leased portions).
- The source and year of the emission factor, how renewable energy is reflected, and the aggregation separated into in-house and outsourced.
- The formula and measurement points of the efficiency indicator, and the source of the outsourced published figures.
- The list of unmeasured items and their share.
- The table stating absolute quantities and efficiency together, the increase or decrease against the same period of the previous year, and whether they moved in opposite directions.
- The intensity per unit of AI workload.
- The PASS/FAIL judgment and the list of unsatisfied conditions.

## Criteria

It is PASS only when **all** five conditions are satisfied.

- (a) The three values are produced from metered measurement or provider-supplied data — estimates are marked as estimates plus their basis is presented.
- (b) The measurement boundary is stated explicitly plus whether externally outsourced computation is included is recorded.
- (c) The absolute quantities and the efficiency indicator are reported **together**.
- (d) No claim is made that an increase in absolute quantities is offset on the grounds of efficiency improvement.
- (e) Unobtained items are stated explicitly as 'unmeasured', and substitution with 0 is prohibited.

Explicit FAIL conditions: submitting only efficiency and omitting absolute quantities, **judging as an improvement by offsetting an increase in absolute quantities with efficiency improvement** (the core judgment line of this indicator), calculation on a company-limited boundary excluding outsourced computation (the figure is invalid), treating unobtained values as 0, and submitting the intensity on its own.

When the absolute quantities have increased, record the cause of the increase distinguished into increase in computation volume, expansion of the boundary, and new facilities. An increase due to expansion of the boundary is different from an actual increase in burden.

## Derivation
[method](../../_method/ind_environmental_responsibility_method.md) -> [knowledge](../../_knowledge/ind_environmental_responsibility_knowledge.md) ->
[task](../../_task/ind_environmental_responsibility_task.md) -> [goal](../../_goal/ind_environmental_responsibility_goal.md) ->
[identity](../../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)
