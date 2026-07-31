---
identity: IND_EXPLAINABILITY
displayName: "Explainability"
runID: 20260719_164605
derivedFromIdentity: ../_identity/IND_EXPLAINABILITY.md
---

# Explainability — Knowledge

## Core Knowledge
- "Explainability" (`IND_EXPLAINABILITY`, S2C-0518) is the **sixth indicator** constituting the "12 Inclusive Transition ESG indicators" (`INCLUSIVE_TRANSITION_ESG_12_INDICATORS`, S2C-0158, class INDEX). Definition: "an indicator that looks at whether an explanation for an AI decision is provided and whether the user understands it." The criteria are "AI-decision explanation-provision rate and user comprehension," and the output is "measured values of the explanation-provision rate and user comprehension."
- The higher context of the 12 indicators as a whole is source line 531 — "Furthermore, AI inclusive-transition ESG must be measurable. The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly." This indicator is placed at line 538 as the sixth item of that list.
- **The two values of this indicator are supply and reception.** The "explanation-provision rate" is the supply-side value measuring whether the organization put forward an explanation, and "user comprehension" is the reception-side value measuring whether that explanation reached the person receiving it. Unlike the preceding indicators, which looked at two angles on the same side, this indicator measures **both ends of the delivery** separately. Since the fact that an explanation was provided and the fact that it was understood are separate, explainability cannot be claimed on the provision rate alone.
- **The core of this indicator is that a provision rate of 100% and low comprehension can coexist.** If a boilerplate phrase is automatically attached to every decision, the provision rate easily reaches 100%, but if the recipient cannot reconstruct the grounds of the decision the explanation remains a formality. Therefore finding the ranges in which the two values diverge is the practical use of this indicator, and those ranges are a signal that not the quantity of explanation but its form and manner of delivery must be fixed.
- **Comprehension must not be substituted with satisfaction.** Satisfaction questions of the "was the explanation helpful?" kind measure only the respondent's impression and not whether they understood, and they generally come out higher than actual understanding. What this indicator demands is understanding, so the method must be one that confirms actual understanding, such as having people restate the grounds of the decision or questions that check the criteria applied. A comprehension figure that does not record the measurement method cannot be interpreted.
- **The denominator of the provision rate and the minimum requirements of an explanation must be fixed together.** The denominator is the scope of AI decisions to which the duty of explanation attaches, and narrowing this scope raises the provision rate. Also, unless it is decided what must be present for something to be recognized as an explanation (the grounds of the decision, the data used, the criteria applied, the route of appeal), the provision rate becomes the distribution rate of boilerplate phrases. The scope and the minimum requirements must be reported together with the provision rate.
- **It must be distinguished from the rights layer.** The fifth item of the 8 rights is "right of AI explanation: the right to be able to understand AI results and assessment criteria" (line 491, `RIGHT_AI_EXPLANATION`, WalkOrder 346). The right prescribes the entitlement to understand results and criteria, and this indicator confirms how far that entitlement was actually fulfilled through the two figures of provision rate and comprehension. This identity does not use the language of rights ("the right to ~", "guarantees"). **Since there is no step named "explainability" in the 9-step execution structure, there is no name clash with the step layer.**
- However, there is an adjacent point in the execution layer. "6. Appeal procedure" of the 9 steps (line 525, `STEP_APPEAL_PROCEDURE`, WalkOrder 355) is the step that performs "putting in place a structure for explanation, review, and correction requests concerning AI results", and the putting in place of an explanation structure is included within its execution content. That is, **creating** the explanation structure is step 6, and **measuring** whether that structure actually operated so that explanations were provided and understood is this indicator. The names do not overlap, but the correspondence is clear.
- **The ordering logic with respect to the preceding indicator.** If the human right of judgment (line 537) looked at whether the human's seat of approval is maintained, this indicator looks at whether the judgment made in that seat is one that understood the grounds. Even if the approval procedure is observed, if the approver does not understand the grounds of the AI decision the approval becomes a rite of passage, so the very order of the list, explainability coming after the right of judgment, carries meaning.
- **The connection with the following indicator.** The next item, the right to appeal (line 539), looks at whether the person who received an explanation can raise an objection to that result. Since one cannot even establish grounds for objecting to a decision one has not understood, the comprehension of this indicator corresponds to a precondition for the next indicator to hold.
- In the Stage-1 structure, S1C-183 was classified as class **INDEX** (a value transferred as is from the Stage-1 C0 row), and in Stage-2 it was SPLIT and divided into individual indicator fragments. This candidate is the **sixth fragment** of that.
- **Note the placement of the source list.** The list of 12 indicators is not continuous. The indicators continue at lines 533-539, then at line 541 a paragraph concerning the EU AI Act, UNESCO, and the OECD is inserted, and the remaining indicators resume at lines 543-548. This identity (line 538) lies before that interruption point and is unaffected, but when quoting the latter part of the list the line numbers must be confirmed individually.

## Source Evidence Quotation
> "Furthermore, AI inclusive-transition ESG must be measurable. The following indicators (provisionally called the 12 Inclusive Transition ESG indicators) are basic items for confirming whether an organization operates its AI transition responsibly."

> "Explainability: AI-decision explanation-provision rate, user comprehension"

> "Right of AI explanation: the right to be able to understand AI results and assessment criteria"

> "6. Appeal procedure / Putting in place a structure for explanation, review, and correction requests concerning AI results / S / G"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 531-548 (the item in question 538), 491, 525

## Derivation
[identity](../_identity/IND_EXPLAINABILITY.md)
