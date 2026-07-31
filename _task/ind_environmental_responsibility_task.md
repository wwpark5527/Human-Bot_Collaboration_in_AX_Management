---
identity: IND_ENVIRONMENTAL_RESPONSIBILITY
displayName: "Environmental Responsibility"
runID: 20260719_164605
derivedFromIdentity: "[IND_ENVIRONMENTAL_RESPONSIBILITY](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)"
---

# Environmental Responsibility — Task

The tasks performed in order to realize the objectives are a matter of **collecting, converting, and fixing three values, and inspecting whether those values have been distorted by boundary setting and the efficiency illusion**. Reducing the environmental burden is not a task of this indicator — this indicator only measures how large the burden is.

## Tasks

1. **Fix the measurement boundary.** Define the scope of AI infrastructure. State explicitly the inclusion or exclusion of each of the company's own data centers, in-house servers, externally outsourced cloud computation (including training and inference APIs), and leased facilities. The boundary is decided before the measurement and is not changed during the period.
2. **Collect the power usage.** Collect in kWh the power consumed by the AI infrastructure within the boundary. Collect it as metered data for the company's own facilities and as provider-supplied data for outsourced portions. For facilities where AI load and non-AI load are mixed, fix an allocation standard and record that standard.
3. **Convert the carbon emissions.** Apply an emission factor to the power usage to convert it into tCO2e. Record the source and year of the emission factor applied, and how procured renewable energy is reflected. Aggregate emissions from the company's own facilities and emissions from outsourced computation separately.
4. **Calculate the data-center efficiency.** Calculate the ratio of IT-equipment power to total facility power (PUE and the like) or the efficiency indicator the organization has adopted. State explicitly the formula and the measurement points. For the efficiency values of outsourced facilities use the provider's published figures and leave the source.
5. **Mark the unobtained items.** State explicitly as 'unmeasured' the values not received from providers. Do not leave them as 0 or blank, and record alongside the share the unmeasured items occupy within the whole.
6. **Place the absolute quantities and the efficiency side by side.** Arrange the absolute quantities of power and carbon and the efficiency indicator in the same table, and mark the increase or decrease against the same period of the previous year for each. If the two values moved in opposite directions, describe that fact explicitly.
7. **Calculate the intensity.** Produce alongside the power and carbon per unit of AI workload (the intensity). The intensity does not replace the absolute quantities, and has meaning only when stated alongside them.
8. **Judge and record.** Decide PASS/FAIL by checking against the five success criteria conditions, and if FAIL, state the unsatisfied conditions and the reasons.

## Deliverables

- **The power usage figure** (kWh), **the carbon emissions figure** (tCO2e), **the data-center efficiency figure** — the three values this indicator must produce.
- The measurement boundary definition document (stating explicitly the inclusion of in-house, outsourced, and leased portions).
- The source and year of the emission factor, how renewable energy is reflected, and the aggregation separated into in-house and outsourced.
- The formula and measurement points of the efficiency indicator, and the source of the efficiency values of outsourced facilities.
- The list of unmeasured items and their share.
- The table stating absolute quantities and efficiency together, the increase or decrease against the same period of the previous year, and a description of whether they moved in opposite directions.
- The intensity per unit of AI workload.
- The PASS/FAIL judgment and the record of unsatisfied conditions.

## Derivation
[identity](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)
