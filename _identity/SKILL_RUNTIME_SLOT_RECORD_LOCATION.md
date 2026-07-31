---
identity: SKILL_RUNTIME_SLOT_RECORD_LOCATION
displayName: "Record Location"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 294
stage3SequenceID: S3S-0364
stage2CandidateID: S2C-0454
stage1CandidateID: S1C-135
derivedFrom:
  - "[S1C-135 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0454 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0364 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0364)"
fragmentedFrom: "[S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[SKILL_RUNTIME_SLOT_REVIEWER_APPROVER](./SKILL_RUNTIME_SLOT_REVIEWER_APPROVER.md)"
sequenceNextIdentity: "[KNOWLEDGE_ACTION_NODE_ONTOLOGY](./KNOWLEDGE_ACTION_NODE_ONTOLOGY.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "534-536"
---

# SKILL_RUNTIME_SLOT_RECORD_LOCATION — Record Location

## Concept Definition
Record Location is the SkillRuntime definition slot that specifies where the skill's execution process and results are to be recorded. It is the seventh and last of the seven slots defined by `SkillRuntime` (S2C-0117, `SKILL_RUNTIME`), positioned after the reviewer/approver slot, and it completes this seven-slot structure.

## Decision Criteria
Judged by whether the place of recording is specified.

## Output
The settled record location (a traceable execution history).

## Evidence (original quotation)
> "Where it is recorded"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 534-536

## Provenance
- Stage-1: [S1C-135](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named runtime structure that makes a skill executable (defines input, material, tool, prohibition, result format, reviewer/approver, record location)
- Stage-2: [S2C-0454](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0364](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0364) — SequenceOrder 364
- fragmentedFrom: [S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [SKILL_RUNTIME_SLOT_REVIEWER_APPROVER](./SKILL_RUNTIME_SLOT_REVIEWER_APPROVER.md)
- next: [KNOWLEDGE_ACTION_NODE_ONTOLOGY](./KNOWLEDGE_ACTION_NODE_ONTOLOGY.md)

## Derivation
[goal](../_goal/skill_runtime_slot_record_location_goal.md) · [task](../_task/skill_runtime_slot_record_location_task.md) ·
[knowledge](../_knowledge/skill_runtime_slot_record_location_knowledge.md) · [method](../_method/skill_runtime_slot_record_location_method.md) ·
[skill](../_skill/SKILL_RUNTIME_SLOT_RECORD_LOCATION/SKILL.md)
