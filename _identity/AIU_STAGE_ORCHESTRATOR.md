---
identity: AIU_STAGE_ORCHESTRATOR
displayName: "AI Orchestrator"
class: INDEX
runID: 20260719_164605
walkOrder: 191
stage3SequenceID: S3S-0241
stage2CandidateID: S2C-0362
stage1CandidateID: S1C-083
derivedFrom:
  - "[S1C-083 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0362 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0241 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0241)"
fragmentedFrom: "[S2C-0072 AI_UTILIZATION](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[AIU_STAGE_COLLABORATIVE_USER](./AIU_STAGE_COLLABORATIVE_USER.md)"
sequenceNextIdentity: "[AIU_STAGE_AUGMENTATION_USER](./AIU_STAGE_AUGMENTATION_USER.md)"
sourceDocument: "_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md"
sourceLines: "430-434"
---

# AIU_STAGE_ORCHESTRATOR — AI Orchestrator

## Concept Definition
The AI Orchestrator is the third stage of the four-stage evolution ladder defined in the measurement of AI Utilization (AIU), an AI-usage stage in which one uses multiple AIs and agents and designs work processes. Going beyond the Collaborative User (who repeatedly converses with AI, revises results, and explores alternatives), it is a state that has reached a level where the member, rather than performing the work directly, designs the very process by which AIs do the work, and it leads to the next stage, the Augmentation User.

## Decision Criteria
Judged by whether I do the work directly or design so that AIs do the work.

## Output
Indicators of the proportion of work handled by AI, the number of agents, and the level of automation.

## Evidence (original quotation)
> "Orchestrator — Using multiple AIs, — Do I do the work directly?"

Source: `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` lines 430-434

## Provenance
- Stage-1: [S1C-083](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named first-level index of AI usage; components frequency/depth/automation/outcome each with formulas; staged Tool User → Collaborative User → Orchestrator → Augmentation User
- Stage-2: [S2C-0362](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0241](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0241) — SequenceOrder 241
- fragmentedFrom: [S2C-0072 AI_UTILIZATION](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [AIU_STAGE_COLLABORATIVE_USER](./AIU_STAGE_COLLABORATIVE_USER.md)
- next: [AIU_STAGE_AUGMENTATION_USER](./AIU_STAGE_AUGMENTATION_USER.md)

## Derivation
[goal](../_goal/aiu_stage_orchestrator_goal.md) · [task](../_task/aiu_stage_orchestrator_task.md) ·
[knowledge](../_knowledge/aiu_stage_orchestrator_knowledge.md) · [method](../_method/aiu_stage_orchestrator_method.md) ·
[skill](../_skill/AIU_STAGE_ORCHESTRATOR/SKILL.md)
