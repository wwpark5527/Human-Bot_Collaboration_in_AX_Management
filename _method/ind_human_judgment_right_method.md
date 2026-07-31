---
identity: IND_HUMAN_JUDGMENT_RIGHT
displayName: "Human Judgment Right"
runID: 20260719_164605
derivedFromIdentity: ../_identity/IND_HUMAN_JUDGMENT_RIGHT.md
---

# Human Judgment Right — Method

## Method / Procedure
1. Confirm the existence of the list of tasks requiring human approval — confirm and record the location of the document, whether it is a finally approved version, and the date of its most recent revision. A document in draft status or not approved is not tallied as existing.
2. Record the scope of the list — write down the number and kinds of task and decision types included, together with the items explicitly excluded. This record cannot be omitted, since it becomes the standard for interpreting the number of omissions later.
3. Confirm the source materials for detecting omissions — state explicitly which of approval history, processing logs, and audit records can be used to find cases processed without approval. Ranges of work with no source materials are marked separately as "undetectable".
4. Detect the cases of approval omission — find the cases among the tasks falling under the list that were completed or released without the required human approval, and leave alongside the task type and the time of occurrence.
5. Tally the **number of approval omissions** by type — count them divided into (a) cases where there was no approval at all, (b) cases approved by someone without authority, and (c) cases approved as a formality after processing, so that the character of the control failure is exposed.
6. Present the scope of the list and the number of omissions bound together as one reporting unit — if the scope of the list has narrowed relative to the previous cycle, state that fact explicitly alongside the number of omissions.
7. Fix a measurement cycle and accumulate a time series on the same standard. Since this value is a defect count where lower is better, confirm as a trend whether it converges to 0.

## Criteria
With the list of tasks requiring human approval existing as a finally approved version and its **scope recorded**, it is PASS when the **number of approval omissions is tallied by type** with the detection source materials stated explicitly, the two values are reported together, and a time series on the same standard is accumulated. It is judged FAIL if any one of the following applies — (a) the case in which the list exists but the covered scope was not recorded, so that the number of omissions cannot be interpreted, (b) the case in which the number of omissions is reported as 0 without the detection source materials being stated explicitly, so that "no omissions" and "undetectable" are not distinguished, (c) the case in which only the existence of the list is confirmed and the number of approval omissions is not tallied. (a) makes the approach of eliminating omissions by narrowing the list look like an achievement, (b) turns a control gap into a control success, and (c) fails to confirm whether the document is actually observed, and each therefore runs counter to the purpose of this indicator.

## Derivation
[identity](../_identity/IND_HUMAN_JUDGMENT_RIGHT.md)
