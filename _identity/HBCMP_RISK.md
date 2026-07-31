---
identity: HBCMP_RISK
displayName: "Risk"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 88
stage3SequenceID: S3S-0109
stage2CandidateID: S2C-0242
stage1CandidateID: S1C-047
derivedFrom:
  - "[S1C-047 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0242 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0109 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0109)"
fragmentedFrom: "[S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[HBCMP_RECOVERY](./HBCMP_RECOVERY.md)"
sequenceNextIdentity: "[HBCMP_MEASUREMENT](./HBCMP_MEASUREMENT.md)"
sourceDocument: "_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md"
sourceLines: "133"
---

# HBCMP_RISK — Risk

## Concept Definition
This is the comparison axis that contrasts the worst-case state that arises when stress is left unattended. In the "human stress vs. bot stress comparison" table, it is the fifth comparison item, coming after the recovery method, and it organizes the extreme outcome reached when recovery fails.

## Decision Criteria
Whether the risk appears as human disengagement in the form of depression, turnover, and resistance, or as functional collapse in the form of hallucination and system failure.

## Output
It yields the contrast that for humans it is depression, turnover, and resistance, while for bots it is hallucination and system failure.

## Evidence (original quotation)
> "Risk               Depression, turnover, resistance               Hallucination, system failure"

Source: `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` line 133

## Provenance
- Stage-1: [S1C-047](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — comparative structure contrasting essence · root cause · result · recovery mode · risk · measurement of human vs bot stress
- Stage-2: [S2C-0242](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0109](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0109) — SequenceOrder 109
- fragmentedFrom: [S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [HBCMP_RECOVERY](./HBCMP_RECOVERY.md)
- next: [HBCMP_MEASUREMENT](./HBCMP_MEASUREMENT.md)

## Derivation
[goal](../_goal/hbcmp_risk_goal.md) · [task](../_task/hbcmp_risk_task.md) ·
[knowledge](../_knowledge/hbcmp_risk_knowledge.md) · [method](../_method/hbcmp_risk_method.md) ·
[skill](../_skill/HBCMP_RISK/SKILL.md)
