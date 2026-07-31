---
identity: ROLE_VACANCY
displayName: "Role vacancy"
class: CONCEPT
runID: 20260719_164605
walkOrder: 299
stage3SequenceID: S3S-0374
stage2CandidateID: S2C-0124
stage1CandidateID: S1C-145
derivedFrom:
  - "[S1C-145 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0124 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0374 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0374)"
fragmentedFrom: none
collapsedFrom: none
sequencePreviousIdentity: "[COMMUNICATION_TYPE_AH_TO_AH](./COMMUNICATION_TYPE_AH_TO_AH.md)"
sequenceNextIdentity: "[CONTRIBUTION_CONFLICT](./CONTRIBUTION_CONFLICT.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "808-818"
---

# ROLE_VACANCY — Role vacancy

## Concept Definition
Role vacancy refers to the state in which, when an augmented human (A: human + AI + common context) and a non-augmented human (B: human alone) communicate, the interpretation, verification, recording, and response contributions are empty on side B, which lacks AI and common context. On side A there are the roles of purpose and judgment (human), analysis and generation (AI), criteria (common context), and history management (recording system), but side B lacks those roles, so B must perform understanding, interpretation, verification, memory, response, defense, and approval all alone.

## Decision Criteria
Decided by whether one side (B) lacks AI and common context, so that the interpretation, verification, recording, and response roles are empty.

## Output
Identification of role vacancy — a state defined not as mere inconvenience but as a problem of communication fairness (communication power).

## Evidence (original quotation)
> "This is role vacancy — that is, the state in which the interpretation, verification, recording, and response roles are empty on the side that has no AI."

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 808-818

## Provenance
- Stage-1: [S1C-145](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named defect-concept of asymmetric (augmented human↔human) communication — the non-augmented side lacks interpretation·verification·recording·response roles; framed as a fairness (communication power) problem
- Stage-2: [S2C-0124](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction KEEP
- Stage-3: [S3S-0374](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0374) — SequenceOrder 374
- fragmentedFrom: none

## Sequence
- previous: [COMMUNICATION_TYPE_AH_TO_AH](./COMMUNICATION_TYPE_AH_TO_AH.md)
- next: [CONTRIBUTION_CONFLICT](./CONTRIBUTION_CONFLICT.md)

## Derivation
[goal](../_goal/role_vacancy_goal.md) · [task](../_task/role_vacancy_task.md) ·
[knowledge](../_knowledge/role_vacancy_knowledge.md) · [method](../_method/role_vacancy_method.md) ·
[skill](../_skill/ROLE_VACANCY/SKILL.md)
