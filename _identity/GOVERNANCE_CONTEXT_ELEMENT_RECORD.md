---
identity: GOVERNANCE_CONTEXT_ELEMENT_RECORD
displayName: "Record"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 264
stage3SequenceID: S3S-0329
stage2CandidateID: S2C-0427
stage1CandidateID: S1C-122
derivedFrom:
  - "[S1C-122 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0427 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0329 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0329)"
fragmentedFrom: "[S2C-0105 GOVERNANCE_CONTEXT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[GOVERNANCE_CONTEXT_ELEMENT_APPROVAL](./GOVERNANCE_CONTEXT_ELEMENT_APPROVAL.md)"
sequenceNextIdentity: "[GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY](./GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "174, 202-204, 233"
---

# GOVERNANCE_CONTEXT_ELEMENT_RECORD — Record

## Concept Definition
Record is the governance-context element that sets where and how the history of prompts, materials, results, revisions, and approvals is kept. It is the fifth of the seven elements (authority, security, verification, approval, record, accountability, improvement) of `governance context`(S2C-0105, `GOVERNANCE_CONTEXT`).

## Decision Criteria
Judges where the history of instructions, materials, results, revisions, and approvals is kept.

## Output
Securing traceability and auditability (corresponding to ISO/IEC 42001 documentation requirements, NIST Govern/Measure, and Article 12 automatic logging/record-keeping of the EU AI Act).

## Evidence (original quotation)
> "Record management: the history of prompts, materials, results, revisions, and approvals"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 174, 202-204, 233

## Provenance
- Stage-1: [S1C-122](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named network-operation structure connecting multiple common contexts; carries a 7-element component structure authority/security/verification/approval/record/accountability/improvement (table 188-209)
- Stage-2: [S2C-0427](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0329](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0329) — SequenceOrder 329
- fragmentedFrom: [S2C-0105 GOVERNANCE_CONTEXT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [GOVERNANCE_CONTEXT_ELEMENT_APPROVAL](./GOVERNANCE_CONTEXT_ELEMENT_APPROVAL.md)
- next: [GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY](./GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY.md)

## Derivation
[goal](../_goal/governance_context_element_record_goal.md) · [task](../_task/governance_context_element_record_task.md) ·
[knowledge](../_knowledge/governance_context_element_record_knowledge.md) · [method](../_method/governance_context_element_record_method.md) ·
[skill](../_skill/GOVERNANCE_CONTEXT_ELEMENT_RECORD/SKILL.md)
