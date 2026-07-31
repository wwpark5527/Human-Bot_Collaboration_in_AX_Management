---
identity: IND_AI_UTILIZATION_CAPABILITY
displayName: "AI Utilization Capability"
class: INDEX
runID: 20260719_164605
walkOrder: 361
stage3SequenceID: S3S-0458
stage2CandidateID: S2C-0515
stage1CandidateID: S1C-183
derivedFrom:
  - "[S1C-183 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0515 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0458 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0458)"
fragmentedFrom: "[S2C-0158 INCLUSIVE_TRANSITION_ESG_12_INDICATORS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[IND_AI_EDUCATION](./IND_AI_EDUCATION.md)"
sequenceNextIdentity: "[IND_LABOR_TRANSITION](./IND_LABOR_TRANSITION.md)"
sourceDocument: "_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md"
sourceLines: "535"
---

# IND_AI_UTILIZATION_CAPABILITY — AI Utilization Capability

## Concept Definition
An indicator that looks at the degree to which AI has been converted into actual work improvement and productivity gains, and the distribution thereof. As the third item of the 12 Inclusive Transition ESG indicators, it is a basic measurement item for confirming whether an organization operates its AI transition responsibly. This indicator too looks at two values together — the **cases** in which work was actually improved by using AI, and the **distribution of the productivity gains** that resulted. Whereas the first two indicators asked whether one can reach the tools (AI accessibility) and whether the capability to handle them was built (AI education), this indicator asks whether the access and education thus secured have been converted into actual work performance. That the source specifies 'distribution' is the core of this indicator — reporting only the average productivity-gain rate can create the illusion that improvements concentrated in a few departments or jobs are the performance of the whole organization.

## Decision Criteria
AI-utilization work-improvement cases and productivity-gain distribution.

## Output
Tally of work-improvement cases and productivity-gain distribution.

## Evidence (original quotation)
> "AI utilization capability: AI-utilization work-improvement cases, productivity-gain distribution"

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 535 (In the source it is presented as a `- ` list item, and the quotation above transcribes the item body verbatim, excluding the list marker.)

## Provenance
- Stage-1: [S1C-183](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named measurement set of 12 indicators (AI accessibility, education, utilization capability, labor transition, human right to judge, explainability, right to appeal, audit record, accountability structure, benefit sharing, context capital, accountable operating system, environmental responsibility) making Inclusive Transition ESG measurable.
- Stage-2: [S2C-0515](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0458](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0458) — SequenceOrder 458
- fragmentedFrom: [S2C-0158 INCLUSIVE_TRANSITION_ESG_12_INDICATORS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [IND_AI_EDUCATION](./IND_AI_EDUCATION.md)
- next: [IND_LABOR_TRANSITION](./IND_LABOR_TRANSITION.md)

## Derivation
[goal](../_goal/ind_ai_utilization_capability_goal.md) · [task](../_task/ind_ai_utilization_capability_task.md) ·
[knowledge](../_knowledge/ind_ai_utilization_capability_knowledge.md) · [method](../_method/ind_ai_utilization_capability_method.md) ·
[skill](../_skill/IND_AI_UTILIZATION_CAPABILITY/SKILL.md)
