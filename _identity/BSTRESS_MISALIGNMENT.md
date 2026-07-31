---
identity: BSTRESS_MISALIGNMENT
displayName: "Misalignment"
class: CONCEPT
runID: 20260719_164605
walkOrder: 81
stage3SequenceID: S3S-0101
stage2CandidateID: S2C-0235
stage1CandidateID: S1C-046
derivedFrom:
  - "[S1C-046 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0235 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0101 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0101)"
fragmentedFrom: "[S2C-0039 BOT_STRESS_TYPES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[BSTRESS_GOAL_CONFLICT](./BSTRESS_GOAL_CONFLICT.md)"
sequenceNextIdentity: "[BSTRESS_CONTINUOUS_UPDATE](./BSTRESS_CONTINUOUS_UPDATE.md)"
sourceDocument: "_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md"
sourceLines: "117"
---

# BSTRESS_MISALIGNMENT — Misalignment

## Concept Definition
Bot stress arising when the AI fails to align with human values. It is the third of the 'bot stress types (5 types)', positioned after goal conflict, and refers to the unstable state a bot experiences when its alignment with human values breaks down.

## Decision Criteria
Whether data bias, incomplete rules, conflicting commands, or governance ambiguity exist.

## Output
It brings about increased unpredictability, emergent behavior, and the risk of policy violation.

## Evidence (original quotation)
> "Misalignment: The AI must align with human values. But when 'data bias, incomplete rules, conflicting commands, and governance ambiguity' exist, the bot becomes unstable, resulting in 'increased unpredictability, emergent behavior, and the risk of policy violation.'"

Source: `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` line 117

## Provenance
- Stage-1: [S1C-046](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — typology of bot (functional/computational) stress, presented as the mirror of human stress (a functional analogue)
- Stage-2: [S2C-0235](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0101](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0101) — SequenceOrder 101
- fragmentedFrom: [S2C-0039 BOT_STRESS_TYPES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [BSTRESS_GOAL_CONFLICT](./BSTRESS_GOAL_CONFLICT.md)
- next: [BSTRESS_CONTINUOUS_UPDATE](./BSTRESS_CONTINUOUS_UPDATE.md)

## Derivation
[goal](../_goal/bstress_misalignment_goal.md) · [task](../_task/bstress_misalignment_task.md) ·
[knowledge](../_knowledge/bstress_misalignment_knowledge.md) · [method](../_method/bstress_misalignment_method.md) ·
[skill](../_skill/BSTRESS_MISALIGNMENT/SKILL.md)
