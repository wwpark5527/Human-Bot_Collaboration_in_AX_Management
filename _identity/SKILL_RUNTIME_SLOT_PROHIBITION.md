---
identity: SKILL_RUNTIME_SLOT_PROHIBITION
displayName: "Prohibition"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 291
stage3SequenceID: S3S-0361
stage2CandidateID: S2C-0451
stage1CandidateID: S1C-135
derivedFrom:
  - "[S1C-135 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0451 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0361 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0361)"
fragmentedFrom: "[S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[SKILL_RUNTIME_SLOT_TOOL](./SKILL_RUNTIME_SLOT_TOOL.md)"
sequenceNextIdentity: "[SKILL_RUNTIME_SLOT_RESULT_FORMAT](./SKILL_RUNTIME_SLOT_RESULT_FORMAT.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "531"
---

# SKILL_RUNTIME_SLOT_PROHIBITION — Prohibition

## Concept Definition
Prohibition is the SkillRuntime definition slot that specifies what must not be done during skill execution. It is the fourth of the seven slots defined by `SkillRuntime` (S2C-0117, `SKILL_RUNTIME`), positioned after the tool slot and before the result format slot.

## Decision Criteria
Judged by whether what must not be done is stated.

## Output
Prohibition rules (the execution boundary of restrictions).

## Evidence (original quotation)
> "What must not be done"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 531

## Provenance
- Stage-1: [S1C-135](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named runtime structure that makes a skill executable (defines input, material, tool, prohibition, result format, reviewer/approver, record location)
- Stage-2: [S2C-0451](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0361](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0361) — SequenceOrder 361
- fragmentedFrom: [S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [SKILL_RUNTIME_SLOT_TOOL](./SKILL_RUNTIME_SLOT_TOOL.md)
- next: [SKILL_RUNTIME_SLOT_RESULT_FORMAT](./SKILL_RUNTIME_SLOT_RESULT_FORMAT.md)

## Derivation
[goal](../_goal/skill_runtime_slot_prohibition_goal.md) · [task](../_task/skill_runtime_slot_prohibition_task.md) ·
[knowledge](../_knowledge/skill_runtime_slot_prohibition_knowledge.md) · [method](../_method/skill_runtime_slot_prohibition_method.md) ·
[skill](../_skill/SKILL_RUNTIME_SLOT_PROHIBITION/SKILL.md)
