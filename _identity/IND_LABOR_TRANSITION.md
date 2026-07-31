---
identity: IND_LABOR_TRANSITION
displayName: "Labor Transition"
class: INDEX
runID: 20260719_164605
walkOrder: 362
stage3SequenceID: S3S-0459
stage2CandidateID: S2C-0516
stage1CandidateID: S1C-183
derivedFrom:
  - "[S1C-183 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0516 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0459 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0459)"
fragmentedFrom: "[S2C-0158 INCLUSIVE_TRANSITION_ESG_12_INDICATORS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[IND_AI_UTILIZATION_CAPABILITY](./IND_AI_UTILIZATION_CAPABILITY.md)"
sequenceNextIdentity: "[IND_HUMAN_JUDGMENT_RIGHT](./IND_HUMAN_JUDGMENT_RIGHT.md)"
sourceDocument: "_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md"
sourceLines: "536"
---

# IND_LABOR_TRANSITION — Labor Transition

## Concept Definition
An indicator that checks whether the job changes caused by AI adoption were assessed in advance and connected to reassignment through transition. As the fourth item of the Inclusive-Transition ESG 12 indicators, it is a basic measurement item for confirming whether an organization runs its AI transition responsibly. This indicator looks at two values of different character together — **whether** a job impact assessment was conducted **before** AI adoption (yes/no), and the **transition-reassignment rate**, the proportion of people judged to be affected who were actually reassigned to new roles. Where the previous indicator (AI utilization capability) asked whether AI use was converted into work performance, this indicator asks whether, when the expansion of that use changes jobs, people were not pushed out but carried through into transition. That the original text nails down "before adoption" is the core of this indicator — an impact assessment written after the fact, following adoption, does not count as conducted for this indicator.

## Decision Criteria
Whether a job impact assessment was conducted before AI adoption, and the transition-reassignment rate.

## Output
Whether the impact assessment was conducted and the transition-reassignment rate.

## Evidence (original quotation)
> "Labor transition: whether a job impact assessment was conducted before AI adoption, transition-reassignment rate"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 536 (the original is presented as a `- ` list item; the quotation above reproduces the item body verbatim, excluding the list marker.)

## Provenance
- Stage-1: [S1C-183](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named measurement set of 12 indicators (AI accessibility, education, utilization capability, labor transition, human judgment right, explainability, right to object, audit records, accountability structure, performance sharing, context capital, responsible operating system, environmental responsibility) making Inclusive-Transition ESG measurable.
- Stage-2: [S2C-0516](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0459](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0459) — SequenceOrder 459
- fragmentedFrom: [S2C-0158 INCLUSIVE_TRANSITION_ESG_12_INDICATORS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [IND_AI_UTILIZATION_CAPABILITY](./IND_AI_UTILIZATION_CAPABILITY.md)
- next: [IND_HUMAN_JUDGMENT_RIGHT](./IND_HUMAN_JUDGMENT_RIGHT.md)

## Derivation
[goal](../_goal/ind_labor_transition_goal.md) · [task](../_task/ind_labor_transition_task.md) ·
[knowledge](../_knowledge/ind_labor_transition_knowledge.md) · [method](../_method/ind_labor_transition_method.md) ·
[skill](../_skill/IND_LABOR_TRANSITION/SKILL.md)
