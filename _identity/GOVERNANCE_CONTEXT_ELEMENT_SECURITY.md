---
identity: GOVERNANCE_CONTEXT_ELEMENT_SECURITY
displayName: "Security"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 261
stage3SequenceID: S3S-0326
stage2CandidateID: S2C-0424
stage1CandidateID: S1C-122
derivedFrom:
  - "[S1C-122 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0424 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0326 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0326)"
fragmentedFrom: "[S2C-0105 GOVERNANCE_CONTEXT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY](./GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY.md)"
sequenceNextIdentity: "[GOVERNANCE_CONTEXT_ELEMENT_VALIDATION](./GOVERNANCE_CONTEXT_ELEMENT_VALIDATION.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "170, 193-195, 230"
---

# GOVERNANCE_CONTEXT_ELEMENT_SECURITY — Security

## Concept Definition
Security is the governance-context element that sets the criteria for handling information that must not be entered and sensitive information. It is the second of the seven elements (authority, security, verification, approval, record, accountability, improvement) of `governance context`(S2C-0105, `GOVERNANCE_CONTEXT`).

## Decision Criteria
Judges which information must not be entered, shared, or generated.

## Output
Protection of sensitive information and confidentiality (corresponding to ISO/IEC 42001 data/asset management, NIST Map/Manage, and Article 10 data governance of the EU AI Act).

## Evidence (original quotation)
> "Security management: criteria for handling information that must not be entered and sensitive information"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 170, 193-195, 230

## Provenance
- Stage-1: [S1C-122](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named network-operation structure connecting multiple common contexts; carries a 7-element component structure authority/security/verification/approval/record/accountability/improvement (table 188-209)
- Stage-2: [S2C-0424](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0326](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0326) — SequenceOrder 326
- fragmentedFrom: [S2C-0105 GOVERNANCE_CONTEXT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY](./GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY.md)
- next: [GOVERNANCE_CONTEXT_ELEMENT_VALIDATION](./GOVERNANCE_CONTEXT_ELEMENT_VALIDATION.md)

## Derivation
[goal](../_goal/governance_context_element_security_goal.md) · [task](../_task/governance_context_element_security_task.md) ·
[knowledge](../_knowledge/governance_context_element_security_knowledge.md) · [method](../_method/governance_context_element_security_method.md) ·
[skill](../_skill/GOVERNANCE_CONTEXT_ELEMENT_SECURITY/SKILL.md)
