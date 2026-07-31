---
identity: IND_ENVIRONMENTAL_RESPONSIBILITY
displayName: "Environmental Responsibility"
runID: 20260719_164605
derivedFromIdentity: "[IND_ENVIRONMENTAL_RESPONSIBILITY](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)"
---

# Environmental Responsibility — Goal

The reason this indicator exists in an AX organization is to make the organization able to answer in figures for the **physical resource consumption** that AI transformation produces. The effects of introducing AI are generally spoken of as changes in people and work, but those changes occur on top of the physical consumption of power, computation, and cooling. This indicator fixes that consumption in three values.

## Objectives

- **Fix the environmental burden of AI infrastructure as measured values.** Calculate the two absolute quantities of power usage and carbon emissions, and the one ratio of data-center efficiency. This indicator does not judge whether the burden is within an allowable range; it counts how large the burden is.
- **Prevent efficiency improvement from concealing an increase in absolute quantities.** This is the most important objective of this indicator. A state in which efficiency improves while total usage increases is in fact common, and if only the efficiency figure is reported, that state looks like an improvement. By requiring the absolute quantities and the efficiency always to be submitted together, the very fact that the two values move in opposite directions is exposed.
- **State the measurement boundary explicitly to prevent the illusion produced by externalization.** If only in-house infrastructure is taken as the boundary, the more AI computation is moved to an external cloud, the better the figures become. Not because the burden decreased, but because it moved onto someone else's books. Stating explicitly a boundary that includes outsourced portions is the condition under which this indicator has meaning.
- **Do not treat unobtained items as 0.** Items for which data could not be received from an external provider are marked as 'unmeasured'. If they are filled in as 0, an organization that failed to measure ends up with better figures than an organization with no burden.

## Success Criteria

This indicator is judged a success when all five of the following are satisfied in each measurement cycle.

1. All three values were produced from metered measurement or provider-supplied data. Items using estimates are marked as estimates and the basis of computation is presented alongside.
2. The measurement boundary is stated explicitly in a document, and whether externally outsourced computation is included is recorded.
3. The absolute quantities (power, carbon) and the efficiency indicator were reported **together**.
4. No claim was made that an increase in absolute quantities is offset on the grounds of efficiency improvement.
5. Items that could not be obtained were stated explicitly as 'unmeasured' and were not substituted with 0.

If even one of the five conditions is unsatisfied, the indicator is recorded as a failure, and the unsatisfied item and its reason are recorded alongside.

## Derivation
[identity](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)
