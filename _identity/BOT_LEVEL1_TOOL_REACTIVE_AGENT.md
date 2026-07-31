---
identity: BOT_LEVEL1_TOOL_REACTIVE_AGENT
displayName: "Level 1 Tool/Reactive Agent"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 167
stage3SequenceID: S3S-0211
stage2CandidateID: S2C-0329
stage1CandidateID: S1C-078
derivedFrom:
  - "[S1C-078 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0329 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0211 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0211)"
fragmentedFrom: "[S2C-0067 BOT_HIERARCHY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[BOT_LEVEL2_SPECIALIST_EXECUTOR](./BOT_LEVEL2_SPECIALIST_EXECUTOR.md)"
sequenceNextIdentity: "[HBRM_ROLE_MEMBER_DEFINITION](./HBRM_ROLE_MEMBER_DEFINITION.md)"
sourceDocument: "_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md"
sourceLines: "266"
---

# BOT_LEVEL1_TOOL_REACTIVE_AGENT — Level 1 Tool/Reactive Agent

## Concept Definition
Level 1 Tool/Reactive Agent is the role level at the bottom of the bot hierarchy. Without any independent judgment or strategy, it performs only simple reactions and API calls, handling a tool-like function that responds immediately to requests from higher levels of the hierarchy (Specialist/Executor and above).

## Decision Criteria
Judged by whether it stops at simple reactions and API calls.

## Output
Simple reaction results and API-call responses.

## Evidence (original quotation)
> "Level 1        Tool/Reactive Agent        simple reaction, API call"

Source: `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` lines 266

## Provenance
- Stage-1: [S1C-078](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named 4-level emergent hierarchy (L1 Tool/Reactive, L2 Specialist/Executor, L3 Planner/Strategist, L4 Verifier/Governor) with 5 determination criteria (decision-making authority, information asymmetry, performance, reliability, network centrality, verification ability)
- Stage-2: [S2C-0329](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0211](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0211) — SequenceOrder 211
- fragmentedFrom: [S2C-0067 BOT_HIERARCHY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [BOT_LEVEL2_SPECIALIST_EXECUTOR](./BOT_LEVEL2_SPECIALIST_EXECUTOR.md)
- next: [HBRM_ROLE_MEMBER_DEFINITION](./HBRM_ROLE_MEMBER_DEFINITION.md)

## Derivation
[goal](../_goal/bot_level1_tool_reactive_agent_goal.md) · [task](../_task/bot_level1_tool_reactive_agent_task.md) ·
[knowledge](../_knowledge/bot_level1_tool_reactive_agent_knowledge.md) · [method](../_method/bot_level1_tool_reactive_agent_method.md) ·
[skill](../_skill/BOT_LEVEL1_TOOL_REACTIVE_AGENT/SKILL.md)
