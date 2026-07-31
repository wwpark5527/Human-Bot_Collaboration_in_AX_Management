---
identity: GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY
displayName: "Authority"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 260
stage3SequenceID: S3S-0325
stage2CandidateID: S2C-0423
stage1CandidateID: S1C-122
derivedFrom:
  - "[S1C-122 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0423 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0325 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0325)"
fragmentedFrom: "[S2C-0105 GOVERNANCE_CONTEXT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[COMMON_CONTEXT_ELEMENT_FEEDBACK](./COMMON_CONTEXT_ELEMENT_FEEDBACK.md)"
sequenceNextIdentity: "[GOVERNANCE_CONTEXT_ELEMENT_SECURITY](./GOVERNANCE_CONTEXT_ELEMENT_SECURITY.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "169, 190-192, 229"
---

# GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY — Authority

## Concept Definition
Authority is the governance-context element that sets the scope of materials and tools AI can access. It is the first of the seven elements (authority, security, verification, approval, record, accountability, improvement) of `governance context`(S2C-0105, `GOVERNANCE_CONTEXT`).

## Decision Criteria
Judges which context can access which materials and tools.

## Output
Management of access and execution scope (corresponding to ISO/IEC 42001 role/access control, NIST AI RMF Govern, and Article 14 human oversight of the EU AI Act).

## Evidence (original quotation)
> "Authority management: the scope of materials and tools AI can access"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 169, 190-192, 229

## Provenance
- Stage-1: [S1C-122](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named network-operation structure connecting multiple common contexts; carries a 7-element component structure authority/security/verification/approval/record/accountability/improvement (table 188-209)
- Stage-2: [S2C-0423](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0325](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0325) — SequenceOrder 325
- fragmentedFrom: [S2C-0105 GOVERNANCE_CONTEXT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [COMMON_CONTEXT_ELEMENT_FEEDBACK](./COMMON_CONTEXT_ELEMENT_FEEDBACK.md)
- next: [GOVERNANCE_CONTEXT_ELEMENT_SECURITY](./GOVERNANCE_CONTEXT_ELEMENT_SECURITY.md)

## Derivation
[goal](../_goal/governance_context_element_authority_goal.md) · [task](../_task/governance_context_element_authority_task.md) ·
[knowledge](../_knowledge/governance_context_element_authority_knowledge.md) · [method](../_method/governance_context_element_authority_method.md) ·
[skill](../_skill/GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY/SKILL.md)
