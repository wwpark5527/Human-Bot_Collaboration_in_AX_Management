---
identity: AIU_STAGE_TOOL_USER
displayName: "Tool User"
class: INDEX
runID: 20260719_164605
walkOrder: 189
stage3SequenceID: S3S-0239
stage2CandidateID: S2C-0360
stage1CandidateID: S1C-083
derivedFrom:
  - "[S1C-083 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0360 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0239 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0239)"
fragmentedFrom: "[S2C-0072 AI_UTILIZATION](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[HA_STAGE_AH3_SYMBIOTIC_LEADER](./HA_STAGE_AH3_SYMBIOTIC_LEADER.md)"
sequenceNextIdentity: "[AIU_STAGE_COLLABORATIVE_USER](./AIU_STAGE_COLLABORATIVE_USER.md)"
sourceDocument: "_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md"
sourceLines: "423-424"
---

# AIU_STAGE_TOOL_USER — Tool User

## Concept Definition
The Tool User is the first stage of the four-stage evolution ladder defined in the measurement of AI Utilization (AIU), an AI-usage stage in which one asks an LLM questions, copies results, and uses AI like a search engine. The AI-utilization level measures "how well I use AI," and it means the degree of evolution in the process of moving from H0 to H1, H2, and eventually becoming an augmented human (AH); the Tool User is the starting point of that evolution. It leads to the next stage, the Collaborative User.

## Decision Criteria
Judged by whether I could produce the same result even without AI.

## Output
Indicators of AI-usage frequency, number of questions, and the degree to which generated results are used.

## Evidence (original quotation)
> "Tool User — Asks an LLM questions, copies results, — AI-usage frequency, number of questions, — The same [result] even without AI"

Source: `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` lines 423-424

## Provenance
- Stage-1: [S1C-083](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named first-level index of AI usage; components frequency/depth/automation/outcome each with formulas; staged Tool User → Collaborative User → Orchestrator → Augmentation User
- Stage-2: [S2C-0360](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0239](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0239) — SequenceOrder 239
- fragmentedFrom: [S2C-0072 AI_UTILIZATION](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [HA_STAGE_AH3_SYMBIOTIC_LEADER](./HA_STAGE_AH3_SYMBIOTIC_LEADER.md)
- next: [AIU_STAGE_COLLABORATIVE_USER](./AIU_STAGE_COLLABORATIVE_USER.md)

## Derivation
[goal](../_goal/aiu_stage_tool_user_goal.md) · [task](../_task/aiu_stage_tool_user_task.md) ·
[knowledge](../_knowledge/aiu_stage_tool_user_knowledge.md) · [method](../_method/aiu_stage_tool_user_method.md) ·
[skill](../_skill/AIU_STAGE_TOOL_USER/SKILL.md)
