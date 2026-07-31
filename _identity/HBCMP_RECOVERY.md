---
identity: HBCMP_RECOVERY
displayName: "Recovery Method"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 87
stage3SequenceID: S3S-0108
stage2CandidateID: S2C-0241
stage1CandidateID: S1C-047
derivedFrom:
  - "[S1C-047 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0241 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0108 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0108)"
fragmentedFrom: "[S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[HBCMP_RESULT](./HBCMP_RESULT.md)"
sequenceNextIdentity: "[HBCMP_RISK](./HBCMP_RISK.md)"
sourceDocument: "_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md"
sourceLines: "132"
---

# HBCMP_RECOVERY — Recovery Method

## Concept Definition
The comparison axis contrasting how one escapes from a stress state. It is the fourth comparison item, coming after result, in the "human stress vs bot stress comparison" table, and summarizes that the prescriptions for reversing a worsened state differ from each other.

## Decision Criteria
Whether recovery is achieved through human prescriptions such as rest, empathy, and motivation, or through technical prescriptions such as recalibration and retraining.

## Output
Produces the contrast that humans use rest, empathy, and motivation while bots use recalibration and retraining.

## Evidence (original quotation)
> "Recovery method              Rest, empathy, motivation                        Recalibration/retraining"

Source: `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` line 132

## Provenance
- Stage-1: [S1C-047](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — comparative structure contrasting essence/root-cause/result/recovery-method/risk/measurement of human vs bot stress
- Stage-2: [S2C-0241](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0108](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0108) — SequenceOrder 108
- fragmentedFrom: [S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [HBCMP_RESULT](./HBCMP_RESULT.md)
- next: [HBCMP_RISK](./HBCMP_RISK.md)

## Derivation
[goal](../_goal/hbcmp_recovery_goal.md) · [task](../_task/hbcmp_recovery_task.md) ·
[knowledge](../_knowledge/hbcmp_recovery_knowledge.md) · [method](../_method/hbcmp_recovery_method.md) ·
[skill](../_skill/HBCMP_RECOVERY/SKILL.md)
