---
identity: SKILL_RUNTIME_SLOT_INPUT
displayName: "Input"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 288
stage3SequenceID: S3S-0358
stage2CandidateID: S2C-0448
stage1CandidateID: S1C-135
derivedFrom:
  - "[S1C-135 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0448 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0358 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0358)"
fragmentedFrom: "[S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[KNOWLEDGE_ACTION_CHAIN_NODE_CONTEXT](./KNOWLEDGE_ACTION_CHAIN_NODE_CONTEXT.md)"
sequenceNextIdentity: "[SKILL_RUNTIME_SLOT_MATERIAL](./SKILL_RUNTIME_SLOT_MATERIAL.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "526-528"
---

# SKILL_RUNTIME_SLOT_INPUT — Input

## Concept Definition
Input is the SkillRuntime definition slot that specifies what a skill must receive when it is executed. It is the first of the seven slots defined by `SkillRuntime` (S2C-0117, `SKILL_RUNTIME`), positioned before the material slot.

## Decision Criteria
Decided by whether what the input is has been specified in advance.

## Output
A finalized input specification.

## Evidence (original quotation)
> "What is the input"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 526-528

## Provenance
- Stage-1: [S1C-135](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named runtime structure that makes a skill executable (defines input·material·tool·prohibition·result format·review approver·record location)
- Stage-2: [S2C-0448](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0358](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0358) — SequenceOrder 358
- fragmentedFrom: [S2C-0117 SKILL_RUNTIME](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [KNOWLEDGE_ACTION_CHAIN_NODE_CONTEXT](./KNOWLEDGE_ACTION_CHAIN_NODE_CONTEXT.md)
- next: [SKILL_RUNTIME_SLOT_MATERIAL](./SKILL_RUNTIME_SLOT_MATERIAL.md)

## Derivation
[goal](../_goal/skill_runtime_slot_input_goal.md) · [task](../_task/skill_runtime_slot_input_task.md) ·
[knowledge](../_knowledge/skill_runtime_slot_input_knowledge.md) · [method](../_method/skill_runtime_slot_input_method.md) ·
[skill](../_skill/SKILL_RUNTIME_SLOT_INPUT/SKILL.md)
