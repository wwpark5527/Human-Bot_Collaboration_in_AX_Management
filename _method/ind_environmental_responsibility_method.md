---
identity: IND_ENVIRONMENTAL_RESPONSIBILITY
displayName: "Environmental Responsibility"
runID: 20260719_164605
derivedFromIdentity: "[IND_ENVIRONMENTAL_RESPONSIBILITY](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)"
---

# Environmental Responsibility — Method

The collection cycle is **monthly** and the reporting and judgment cycle is **quarterly**. Since power can be obtained on a monthly basis as metered data, it is gathered monthly, while provider data for outsourced portions is reconciled at the quarterly point in line with the supply cycle. There are two comparison targets: the same period of the previous year (because of the seasonality of absolute quantities, comparison with the immediately preceding quarter alone is insufficient) and the immediately preceding quarter.

## Steps

**Step 1 — Fix the measurement boundary and fix it in a document.**
Define the scope of AI infrastructure and state explicitly the inclusion or exclusion of each of the following.
- The company's own data centers and in-house servers
- Externally outsourced computation on the cloud (including the use of training and inference APIs)
- Leased facilities and colocation
The boundary is decided before the measurement and is not changed during the period. If a change is unavoidable, record the fact and time of the change and mark that period as incomparable.

**Step 2 — Collect the power usage.**
Collect in kWh the power consumed by the AI infrastructure within the boundary. Use metered data for the company's own facilities and provider-supplied data for outsourced portions. For facilities where AI load and non-AI load are mixed, fix an allocation standard (operating hours, allocated resource volume, and so on) and record the standard.

**Step 3 — Convert the carbon emissions.**
Apply an emission factor to the power usage to convert it into tCO2e. Record the source and year of the emission factor, and state explicitly how procured renewable energy is reflected. Aggregate emissions from the company's own facilities and emissions from outsourced computation separately.

**Step 4 — Calculate the data-center efficiency.**
Calculate the ratio of IT-equipment power to total facility power (PUE and the like) or the efficiency indicator the organization has adopted. State explicitly the formula and the measurement points. For outsourced facilities use the provider's published figures and leave the source and the time of publication.

**Step 5 — Mark the unobtained items.**
State explicitly as 'unmeasured' the values that could not be obtained, and record alongside the share the unmeasured items occupy within the whole boundary (on the basis of estimated computation volume). **Do not substitute 0.**

**Step 6 — Place the absolute quantities and the efficiency side by side.**
Put the absolute quantities of power and carbon and the efficiency indicator in the same table and mark the increase or decrease against the same period of the previous year for each. If the two values moved in opposite directions, state that fact explicitly in a sentence.

**Step 7 — Calculate the intensity.**
Calculate power and carbon per unit of AI workload. The intensity is reported only when stated alongside the absolute quantities, and is not submitted on its own.

**Step 8 — Compare and judge.**
Check against the same period of the previous year and the immediately preceding quarter, and decide PASS/FAIL by the criteria below.

**Step 9 — Record.**
Leave the three values, the boundary definition document, the source of the emission factor, the efficiency formula, the list of unmeasured items and their share, the table stating absolute quantities and efficiency together, the intensity, and the judgment result and its grounds.

## Criteria

Only when **all** five of the following conditions are satisfied is it judged PASS.

- **(a) The three values were produced from metered measurement or provider-supplied data.** Items using estimates are marked as estimates and the basis of computation is presented alongside.
- **(b) The measurement boundary is stated explicitly in a document, and whether externally outsourced computation is included is recorded.**
- **(c) The absolute quantities (power, carbon) and the efficiency indicator were reported together.**
- **(d) No claim was made that an increase in absolute quantities is offset on the grounds of efficiency improvement.**
- **(e) Unobtained items were stated explicitly as 'unmeasured' and were not substituted with 0.**

The following are explicit FAIL conditions.

- **A result submitting only the efficiency indicator and omitting the absolute quantities** — since two of the three values demanded by the source text are missing, it is FAIL.
- **A result judged as an improvement on the grounds of efficiency improvement when the absolute quantities increased** — this is the core judgment line of this indicator. Efficiency cannot offset absolute quantities. If the absolute quantities increased, then however much efficiency improved, the environmental burden has increased.
- **Figures calculated with the boundary drawn only around in-house infrastructure and outsourced computation excluded** — since a decrease due to externalization is tallied as an improvement, the figure itself is invalidated.
- **A result treating unobtained values as 0** — since a state of not having measured is shown as a state of having no burden, it is FAIL.
- **A result submitting only the intensity and omitting the absolute quantities** — since an improvement in intensity is compatible with an increase in the total, submission on its own does not satisfy (c).

When the absolute quantities have increased, the judgment record leaves the increase and its cause (increase in computation volume, expansion of the boundary, introduction of new facilities, and so on) distinguished from one another. An increase due to expansion of the boundary is different from an actual increase in burden, and an increase or decrease submitted without this distinction cannot be interpreted.

## Derivation
[identity](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)
