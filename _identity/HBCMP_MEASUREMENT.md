---
identity: HBCMP_MEASUREMENT
displayName: "Measurement"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 89
stage3SequenceID: S3S-0110
stage2CandidateID: S2C-0243
stage1CandidateID: S1C-047
derivedFrom:
  - "[S1C-047 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0243 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0110 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0110)"
fragmentedFrom: "[S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[HBCMP_RISK](./HBCMP_RISK.md)"
sequenceNextIdentity: "[INTERACTION_STRESS](./INTERACTION_STRESS.md)"
sourceDocument: "_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md"
sourceLines: "134-136"
---

# HBCMP_MEASUREMENT — Measurement

## Concept Definition
The comparison axis contrasting by what a stress state is observed and quantified. It is the sixth and last comparison item of the "human stress vs bot stress comparison" table, closing the comparison table by summarizing which indicators the preceding five items (essence, root cause, result, recovery method, risk) can actually be confirmed by.

## Decision Criteria
Whether the measurement indicator is an emotional/behavioral indicator or a system indicator of response speed, accuracy, and stability.

## Output
Produces the contrast that humans have emotional/behavioral indicators while bots have Latency, Accuracy, and Stability.

## Evidence (original quotation)
> "Measurement                Emotional/behavioral indicators"

Source: `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` lines 134-136

## Provenance
- Stage-1: [S1C-047](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — comparative structure contrasting essence/root-cause/result/recovery-method/risk/measurement of human vs bot stress
- Stage-2: [S2C-0243](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0110](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0110) — SequenceOrder 110
- fragmentedFrom: [S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [HBCMP_RISK](./HBCMP_RISK.md)
- next: [INTERACTION_STRESS](./INTERACTION_STRESS.md)

## Derivation
[goal](../_goal/hbcmp_measurement_goal.md) · [task](../_task/hbcmp_measurement_task.md) ·
[knowledge](../_knowledge/hbcmp_measurement_knowledge.md) · [method](../_method/hbcmp_measurement_method.md) ·
[skill](../_skill/HBCMP_MEASUREMENT/SKILL.md)
