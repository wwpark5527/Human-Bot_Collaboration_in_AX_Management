---
identity: SKILL_RUNTIME_SLOT_REVIEWER_APPROVER
displayName: "Reviewer/Approver"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 293
stage3SequenceID: S3S-0363
stage2CandidateID: S2C-0453
stage1CandidateID: S1C-135
derivedFrom:
  - "[S1C-135 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0453 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0363 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0363)"
fragmentedFrom: "[S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[SKILL_RUNTIME_SLOT_RESULT_FORMAT](./SKILL_RUNTIME_SLOT_RESULT_FORMAT.md)"
sequenceNextIdentity: "[SKILL_RUNTIME_SLOT_RECORD_LOCATION](./SKILL_RUNTIME_SLOT_RECORD_LOCATION.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "533"
---

# SKILL_RUNTIME_SLOT_REVIEWER_APPROVER — Reviewer/Approver

## Concept Definition
Reviewer/Approver is the SkillRuntime definition slot that specifies who reviews and approves the results of a skill's execution. It is the sixth of the seven slots defined by `SkillRuntime` (S2C-0117, `SKILL_RUNTIME`), positioned after the result format slot and before the record location slot.

## Decision Criteria
Judged by whether who reviews and approves is specified.

## Output
The designated reviewer/approver and the approval history.

## Evidence (original quotation)
> "Who reviews and approves"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 533

## Provenance
- Stage-1: [S1C-135](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named runtime structure that makes a skill executable (defines input, material, tool, prohibition, result format, reviewer/approver, record location)
- Stage-2: [S2C-0453](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0363](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0363) — SequenceOrder 363
- fragmentedFrom: [S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [SKILL_RUNTIME_SLOT_RESULT_FORMAT](./SKILL_RUNTIME_SLOT_RESULT_FORMAT.md)
- next: [SKILL_RUNTIME_SLOT_RECORD_LOCATION](./SKILL_RUNTIME_SLOT_RECORD_LOCATION.md)

## Derivation
[goal](../_goal/skill_runtime_slot_reviewer_approver_goal.md) · [task](../_task/skill_runtime_slot_reviewer_approver_task.md) ·
[knowledge](../_knowledge/skill_runtime_slot_reviewer_approver_knowledge.md) · [method](../_method/skill_runtime_slot_reviewer_approver_method.md) ·
[skill](../_skill/SKILL_RUNTIME_SLOT_REVIEWER_APPROVER/SKILL.md)
