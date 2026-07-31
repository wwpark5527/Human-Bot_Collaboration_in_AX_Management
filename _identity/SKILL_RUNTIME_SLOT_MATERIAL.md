---
identity: SKILL_RUNTIME_SLOT_MATERIAL
displayName: "Material"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 289
stage3SequenceID: S3S-0359
stage2CandidateID: S2C-0449
stage1CandidateID: S1C-135
derivedFrom:
  - "[S1C-135 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0449 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0359 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0359)"
fragmentedFrom: "[S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[SKILL_RUNTIME_SLOT_INPUT](./SKILL_RUNTIME_SLOT_INPUT.md)"
sequenceNextIdentity: "[SKILL_RUNTIME_SLOT_TOOL](./SKILL_RUNTIME_SLOT_TOOL.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "529"
---

# SKILL_RUNTIME_SLOT_MATERIAL — Material

## Concept Definition
Material is the SkillRuntime definition slot that specifies which materials a skill will use when it executes. It is the second of the seven slots defined by `SkillRuntime` (S2C-0117, `SKILL_RUNTIME`), positioned after the input slot and before the tool slot.

## Decision Criteria
Judged by whether the materials to be used are specified.

## Output
A list of usable materials (the reference scope).

## Evidence (original quotation)
> "Which materials will be used"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 529

## Provenance
- Stage-1: [S1C-135](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named runtime structure that makes a skill executable (defines input, material, tool, prohibition, result format, reviewer/approver, record location)
- Stage-2: [S2C-0449](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0359](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0359) — SequenceOrder 359
- fragmentedFrom: [S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [SKILL_RUNTIME_SLOT_INPUT](./SKILL_RUNTIME_SLOT_INPUT.md)
- next: [SKILL_RUNTIME_SLOT_TOOL](./SKILL_RUNTIME_SLOT_TOOL.md)

## Derivation
[goal](../_goal/skill_runtime_slot_material_goal.md) · [task](../_task/skill_runtime_slot_material_task.md) ·
[knowledge](../_knowledge/skill_runtime_slot_material_knowledge.md) · [method](../_method/skill_runtime_slot_material_method.md) ·
[skill](../_skill/SKILL_RUNTIME_SLOT_MATERIAL/SKILL.md)
