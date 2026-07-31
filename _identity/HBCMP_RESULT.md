---
identity: HBCMP_RESULT
displayName: "Result"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 86
stage3SequenceID: S3S-0107
stage2CandidateID: S2C-0240
stage1CandidateID: S1C-047
derivedFrom:
  - "[S1C-047 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0240 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0107 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0107)"
fragmentedFrom: "[S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[HBCMP_ROOT_CAUSE](./HBCMP_ROOT_CAUSE.md)"
sequenceNextIdentity: "[HBCMP_RECOVERY](./HBCMP_RECOVERY.md)"
sourceDocument: "_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md"
sourceLines: "131"
---

# HBCMP_RESULT — Result

## Concept Definition
This is the comparison axis that contrasts the consequences stress actually leaves behind. In the "human stress vs. bot stress comparison" table, it is the third comparison item, coming after the root cause, and it organizes what results appear when a cause is left unattended.

## Decision Criteria
Whether the consequence appears as human burnout and dissatisfaction, or as system performance degradation and errors.

## Output
It yields the contrast that for humans the result is burnout and dissatisfaction, while for bots it is performance degradation and errors.

## Evidence (original quotation)
> "Result               Burnout, dissatisfaction                   Performance degradation, errors"

Source: `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` line 131

## Provenance
- Stage-1: [S1C-047](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — comparative structure contrasting essence · root cause · result · recovery mode · risk · measurement of human vs bot stress
- Stage-2: [S2C-0240](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0107](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0107) — SequenceOrder 107
- fragmentedFrom: [S2C-0040 HUMAN_VS_BOT_STRESS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [HBCMP_ROOT_CAUSE](./HBCMP_ROOT_CAUSE.md)
- next: [HBCMP_RECOVERY](./HBCMP_RECOVERY.md)

## Derivation
[goal](../_goal/hbcmp_result_goal.md) · [task](../_task/hbcmp_result_task.md) ·
[knowledge](../_knowledge/hbcmp_result_knowledge.md) · [method](../_method/hbcmp_result_method.md) ·
[skill](../_skill/HBCMP_RESULT/SKILL.md)
