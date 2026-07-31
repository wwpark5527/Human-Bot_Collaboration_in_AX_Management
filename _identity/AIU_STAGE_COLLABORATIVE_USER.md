---
identity: AIU_STAGE_COLLABORATIVE_USER
displayName: "Collaborative User"
class: INDEX
runID: 20260719_164605
walkOrder: 190
stage3SequenceID: S3S-0240
stage2CandidateID: S2C-0361
stage1CandidateID: S1C-083
derivedFrom:
  - "[S1C-083 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0361 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0240 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0240)"
fragmentedFrom: "[S2C-0072 AI_UTILIZATION](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[AIU_STAGE_TOOL_USER](./AIU_STAGE_TOOL_USER.md)"
sequenceNextIdentity: "[AIU_STAGE_ORCHESTRATOR](./AIU_STAGE_ORCHESTRATOR.md)"
sourceDocument: "_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md"
sourceLines: "425-429"
---

# AIU_STAGE_COLLABORATIVE_USER — Collaborative User

## Concept Definition
The Collaborative User is the second stage of the four-stage evolution ladder defined in the measurement of AI Utilization (AIU), an AI-usage stage in which one repeatedly converses with AI to revise results and explore alternatives. Going beyond the Tool User (who asks an LLM questions and copies results), it is a state that has reached a level of using AI not as a one-off search tool but as a partner for repeated interaction, and it leads to the next stage, the AI Orchestrator.

## Decision Criteria
Judged by whether AI expands my thinking.

## Output
Indicators of the number of prompt improvements, the degree to which AI feedback is incorporated, and the number of repeated interactions with AI.

## Evidence (original quotation)
> "Collaborative User — Number of prompt improvements, AI"

Source: `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` lines 425-429

## Provenance
- Stage-1: [S1C-083](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named first-level index of AI usage; components frequency/depth/automation/outcome each with formulas; staged Tool User → Collaborative User → Orchestrator → Augmentation User
- Stage-2: [S2C-0361](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0240](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0240) — SequenceOrder 240
- fragmentedFrom: [S2C-0072 AI_UTILIZATION](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [AIU_STAGE_TOOL_USER](./AIU_STAGE_TOOL_USER.md)
- next: [AIU_STAGE_ORCHESTRATOR](./AIU_STAGE_ORCHESTRATOR.md)

## Derivation
[goal](../_goal/aiu_stage_collaborative_user_goal.md) · [task](../_task/aiu_stage_collaborative_user_task.md) ·
[knowledge](../_knowledge/aiu_stage_collaborative_user_knowledge.md) · [method](../_method/aiu_stage_collaborative_user_method.md) ·
[skill](../_skill/AIU_STAGE_COLLABORATIVE_USER/SKILL.md)
