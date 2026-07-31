---
identity: IND_ENVIRONMENTAL_RESPONSIBILITY
displayName: "Environmental Responsibility"
runID: 20260719_164605
derivedFromIdentity: "[IND_ENVIRONMENTAL_RESPONSIBILITY](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)"
---

# Environmental Responsibility — Knowledge

To measure this indicator correctly, one must know that the source text demanded three values and that those three values are of **different kinds**. Two are absolute quantities and one is a ratio, and this difference in nature determines the whole of the judgment.

## Core Knowledge

- **The values the source text demands are three.** "AI-infrastructure power usage, carbon emissions, data-center efficiency." The first two are absolute quantities (kWh, tCO2e) and the third is a ratio. It is the only item among the 12 indicators that demands absolute quantities, and it is distinguished from the rest, which all deal with relative values such as ratios, case counts, and completion rates.
- **Efficiency and absolute quantities can move in opposite directions.** This is the most important knowledge in this indicator. A state in which total power usage increases while data-center efficiency improves is not an exception but a common case — because when the unit cost of computation falls, the volume of computation rises. If only the efficiency indicator is reported, this state is read as an improvement, and at that moment this indicator loses its function of measuring the environmental burden. This is why the source text gave two absolute quantities and one efficiency figure **together**, and submitting only one of the three does not satisfy the demand of the source text.
- **If the measurement boundary is limited to the company itself, the indicator works paradoxically.** If AI computation is moved to an external cloud, the power captured on the company's own meters decreases. The burden has not disappeared but has moved onto the provider's books, and yet if the boundary is drawn at the company itself that movement is tallied as an improvement. That is, the result is that the more AI is used, the better the figures become. Therefore stating explicitly a boundary that includes outsourced computation is not a matter of accuracy but a condition for this indicator to hold at all.
- **If unobtained values are filled in as 0, the organization that did not measure is advantaged.** There are in fact many cases in which external providers do not supply item-by-item data. If those values are treated as 0, an organization that made the effort to obtain the data receives worse figures than one that failed to obtain it. Marking them as 'unmeasured' and disclosing their share alongside is the only coherent treatment.
- **This indicator measures only part of the items given by the E-axis theory — it must be used in knowledge of that fact.** The E-axis extension discussion of the same document (lines 430-456) enumerates **six** environmental items: power use, water use, carbon emissions, semiconductors and minerals, electronic waste, and local environmental impact. What this indicator (line 548) gives is only the three of **power usage, carbon emissions, and data-center efficiency**, and water use, semiconductors and minerals, electronic waste, and local environmental impact are not included. Moreover, the third value, data-center efficiency, is an **efficiency ratio** that appears nowhere among the six E-axis items. Therefore satisfying this indicator does not mean that the whole E axis has been managed. What is measured is two of the six burdens plus one efficiency figure, and the remaining four lie outside the scope of this indicator. To report satisfaction of this indicator as fulfilment of environmental responsibility without recording this limitation is over-reporting.
- **This indicator is not an axis but a set of figures.** `ESG_EXT_E_AXIS` (the extension of E, WalkOrder 328) **argues** how far the E axis must be extended to include in the AI era, and that argument closes with "the environmental impact of AI must be managed on the E axis of ESG". This indicator **confirms** in three values at what level that management is actually being carried out. It neither asserts the extension nor prescribes the level of management.

## Source Evidence Quotation

> "Environmental responsibility: AI-infrastructure power usage, carbon emissions, data-center efficiency"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` line 548 (excluding the list marker `- `).

The sentence with which the E-axis extension discussion of the same document closes is as follows.

> "AI operates in this way on top of large-scale physical infrastructure such as large-scale power, water, semiconductors, and data centers. Therefore E is no longer merely a matter of factories, facilities, and carbon emissions alone, but must be extended in the direction of also including the impact that the entirety of corporate infrastructure in the AI era has on the environment, and the environmental impact of AI must be managed on the E axis of ESG."

Source: the same document line 456.

The character of the indicator group to which this item belongs is prescribed by line 531.

> "The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly."

## Derivation
[identity](../_identity/IND_ENVIRONMENTAL_RESPONSIBILITY.md)
