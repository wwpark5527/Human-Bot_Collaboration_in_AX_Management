---
identity: IND_BENEFIT_SHARING
displayName: "Benefit Sharing"
class: INDEX
runID: 20260719_164605
walkOrder: 368
stage3SequenceID: S3S-0465
stage2CandidateID: S2C-0522
stage1CandidateID: S1C-183
derivedFrom:
  - "[S1C-183 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0522 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0465 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0465)"
fragmentedFrom: "[S2C-0158 INCLUSIVE_TRANSITION_ESG_12_INDICATORS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[IND_ACCOUNTABILITY_STRUCTURE](./IND_ACCOUNTABILITY_STRUCTURE.md)"
sequenceNextIdentity: "[IND_ENVIRONMENTAL_RESPONSIBILITY](./IND_ENVIRONMENTAL_RESPONSIBILITY.md)"
sourceDocument: "_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md"
sourceLines: "545"
---

# IND_BENEFIT_SHARING — Benefit Sharing

## Concept Definition
An indicator that looks at whether AI productivity gains flow back to members. As the tenth item of the 12 Inclusive Transition ESG indicators, it is a basic measurement item for confirming whether an organization operates its AI transition responsibly. This indicator measures the share returned through three reinvestment channels — compensation, education, welfare — as a proportion of the gains. All three channels the source enumerates are channels that accrue **to people**, and the share returned to the organization's own capabilities does not enter the numerator of this indicator, because the definition asks whether it "flows back to members." The vulnerability of the measurement lies not in the numerator but in the denominator — since setting the gains low automatically raises the reinvestment rate, a reinvestment rate submitted without a basis for computing the denominator cannot be interpreted.

## Decision Criteria
Reinvestment rate of AI productivity gains into compensation, education, and welfare.

## Output
The reinvestment-rate figure.

## Evidence (original quotation)
> "Benefit sharing: reinvestment rate of AI productivity gains into compensation, education, and welfare"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 545 (In the source it is presented as a `- ` list item, and the quotation above transcribes the item body verbatim, excluding the list marker.)

## Provenance
- Stage-1: [S1C-183](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named measurement set of 12 indicators (AI accessibility, education, utilization capability, labor transition, human right to judge, explainability, right to appeal, audit record, accountability structure, benefit sharing, context capital, accountable operating system, environmental responsibility) making Inclusive Transition ESG measurable.
- Stage-2: [S2C-0522](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0465](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0465) — SequenceOrder 465
- fragmentedFrom: [S2C-0158 INCLUSIVE_TRANSITION_ESG_12_INDICATORS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [IND_ACCOUNTABILITY_STRUCTURE](./IND_ACCOUNTABILITY_STRUCTURE.md)
- next: [IND_ENVIRONMENTAL_RESPONSIBILITY](./IND_ENVIRONMENTAL_RESPONSIBILITY.md)

## Derivation
[goal](../_goal/ind_benefit_sharing_goal.md) · [task](../_task/ind_benefit_sharing_task.md) ·
[knowledge](../_knowledge/ind_benefit_sharing_knowledge.md) · [method](../_method/ind_benefit_sharing_method.md) ·
[skill](../_skill/IND_BENEFIT_SHARING/SKILL.md)
