---
identity: IND_BENEFIT_SHARING
displayName: "Benefit Sharing"
runID: 20260719_164605
derivedFromIdentity: "[IND_BENEFIT_SHARING](../_identity/IND_BENEFIT_SHARING.md)"
---

# Benefit Sharing — Knowledge

To measure this indicator correctly, one line of the source text must be read exactly. That line specifies **three** channels of reinvestment, which differs from the number of channels enumerated by the execution step of the same document. This difference is not a typographical error but a result that follows from the definition of this indicator.

## Core Knowledge

- **The value the source text demands is one ratio.** "Reinvestment rate of AI productivity gains into compensation, education, and welfare" — the denominator is the AI productivity gains, the numerator is the share reinvested through the three channels. The source text does not prescribe the appropriate level of reinvestment or the manner of distribution. This indicator does not judge how much is appropriate; it counts how much went.
- **The indicator has three channels, the execution step four — the difference comes from the definition.** The execution-step list of the same document (line 527) gives **four** places, saying "reinvest AI productivity gains in education, compensation, welfare, and **organizational capability**". This indicator (line 545) gives only **three** places, "compensation, education, welfare". What is missing is organizational capability. This is not an omission but a consequence of the definition — because the definition of this indicator asks whether the gains "flow back **to members**", and strengthening organizational capability is a share that stays in the organization, not a share attributed to members. Therefore reinvestment that went into organizational capability is not put in the numerator. However, being removed from the numerator does not mean it is left out of sight; it is kept as a separate item so that the whole whereabouts of the gains is exposed.
- **The vulnerability of this indicator is not the numerator but the denominator.** Since the reinvestment rate is a fraction, setting the denominator small raises it without increasing the numerator. AI productivity gains are not a value fixed automatically in the accounts but a value that emerges only once the computation method, reference point in time, and scope of covered work are decided, and the party deciding these three is the very organization being measured. That is why a reinvestment rate whose basis of computation is not disclosed cannot be interpreted, whether high or low, and unless the time series of the gains themselves is seen alongside, a rise due to a shrinking denominator cannot be distinguished from an improvement.
- **The total conceals channel skew.** If only the sum of the three channels is reported, an organization that put the entire amount into education with 0 in compensation and an organization that distributed evenly across the three channels appear as the same figure. Since the source enumerated the three items side by side, decomposition by channel is a requirement of the measurement, and if one channel is 0 that fact must be exposed in the figures.
- **The total amount conceals concentration of benefit.** Even if the reinvestment rate is high, if that share was concentrated in a few senior grades then the benefit has not been shared. `GAP_AI_OUTCOME_DISTRIBUTION` (AI outcome distribution gap, WalkOrder 315, line 129), which the same document diagnoses, points precisely at this state — "concentration at the top, exclusion at the bottom". This indicator demands the proportion of beneficiaries and the distribution by grade and employment type alongside precisely in order to prevent that gap from hiding behind the total amount. In particular, if non-regular, contract, and dispatched personnel are left out of the distribution computation, sharing ends up being claimed without counting the excluded stratum.
- **This indicator is neither a right nor a step.** The same document treats benefit sharing at three layers. The rights layer (line 494, `RIGHT_AI_BENEFIT_SHARING`, WalkOrder 349) prescribes what members can demand, and the execution-step layer (line 527, `STEP_BENEFIT_DISTRIBUTION`, WalkOrder 357) prescribes what the organization performs. This indicator only **confirms in a single ratio** whether that right was guaranteed and whether that step was executed; it neither grants a right nor performs a procedure.

## Source Evidence Quotation

> "Benefit sharing: reinvestment rate of AI productivity gains into compensation, education, and welfare"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` line 545 (excluding the list marker `- `).

The four channels given by the execution-step list of the same document are as follows (as a row inside a code-block table, with the leading whitespace excluded and the column spacing transcribed as in the source).

> "8. Benefit distribution / Reinvest AI productivity gains in education, compensation, welfare, and organizational capability / S"

Source: the same document line 527.

The character of the indicator group to which this item belongs is prescribed by line 531.

> "The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly."

## Derivation
[identity](../_identity/IND_BENEFIT_SHARING.md)
