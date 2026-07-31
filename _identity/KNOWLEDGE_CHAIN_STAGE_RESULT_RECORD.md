---
identity: KNOWLEDGE_CHAIN_STAGE_RESULT_RECORD
displayName: "Result Recording"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 271
stage3SequenceID: S3S-0337
stage2CandidateID: S2C-0433
stage1CandidateID: S1C-125
derivedFrom:
  - "[S1C-125 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0433 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0337 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0337)"
fragmentedFrom: "[S2C-0108 KNOWLEDGE_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION](./KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION.md)"
sequenceNextIdentity: "[KNOWLEDGE_CHAIN_STAGE_REINTEGRATION](./KNOWLEDGE_CHAIN_STAGE_REINTEGRATION.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "254-256"
---

# KNOWLEDGE_CHAIN_STAGE_RESULT_RECORD — Result Recording

## Concept Definition
Result recording is the stage that leaves the generated result and its grounds and process within the organization. It turns a response from a "scattered response" into an asset that can be accumulated. As the fifth stage of the `knowledge chain` (S2C-0108, `KNOWLEDGE_CHAIN`), it is located after response generation and before re-reflection into organizational knowledge.

## Decision Criteria
It is judged by whether the grounds of the result are recorded so that one can later trace why it is correct, where it went wrong, and what premises were used.

## Output
A traceable record (grounds, process, version).

## Evidence (original quotation)
> "By contrast, a common/governance-context-based AX system has a circulation/accumulation structure of 'question → organizational context reference → governance validation → response generation → result recording → re-reflection into organizational knowledge → reuse by the next AI/human.'"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 254-256

## Provenance
- Stage-1: [S1C-125](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named accumulation/circulation structure (question → context reference → validation → recording → re-reflection → reuse) that observes the path to an answer, not just the answer
- Stage-2: [S2C-0433](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0337](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0337) — SequenceOrder 337
- fragmentedFrom: [S2C-0108 KNOWLEDGE_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION](./KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION.md)
- next: [KNOWLEDGE_CHAIN_STAGE_REINTEGRATION](./KNOWLEDGE_CHAIN_STAGE_REINTEGRATION.md)

## Derivation
[goal](../_goal/knowledge_chain_stage_result_record_goal.md) · [task](../_task/knowledge_chain_stage_result_record_task.md) ·
[knowledge](../_knowledge/knowledge_chain_stage_result_record_knowledge.md) · [method](../_method/knowledge_chain_stage_result_record_method.md) ·
[skill](../_skill/KNOWLEDGE_CHAIN_STAGE_RESULT_RECORD/SKILL.md)
