---
identity: AX_ROLE_AI_WORKFLOW_ORCHESTRATOR
displayName: "AI Workflow Orchestrator"
class: ROLE
runID: 20260719_164605
walkOrder: 228
stage3SequenceID: S3S-0284
stage2CandidateID: S2C-0392
stage1CandidateID: S1C-107
derivedFrom:
  - "[S1C-107 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0392 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0284 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0284)"
fragmentedFrom: "[S2C-0092 AX_NEW_ROLES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[AX_ROLE_PROMPT_ARCHITECT](./AX_ROLE_PROMPT_ARCHITECT.md)"
sequenceNextIdentity: "[AX_ROLE_HUMAN_MEANING_INTEGRATOR](./AX_ROLE_HUMAN_MEANING_INTEGRATOR.md)"
sourceDocument: "_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md"
sourceLines: "74-74"
---

# AX_ROLE_AI_WORKFLOW_ORCHESTRATOR — AI Workflow Orchestrator

## Concept Definition
This is a new AX role that designs the collaboration flow between humans and AI. Following the AI Governor, AI Auditor, and Prompt Architect, it is the fourth of the seven new roles that appear in the additional mode of TR by bots, a role that did not exist in human-centered organizations.

## Decision Criteria
It is judged by whether the role is responsible for designing the human-AI collaboration workflow.

## Output
A design of the human-AI collaboration flow is produced.

## Evidence (original quotation)
> "AI Workflow Orchestrator                 human-AI collaboration flow design"

Source: `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` lines 74-74

## Provenance
- Stage-1: [S1C-107](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — Named set of new organizational role/member-types that AX orgs add beyond the human-only Belbin roster (the "additional" mode made concrete).
- Stage-2: [S2C-0392](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0284](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0284) — SequenceOrder 284
- fragmentedFrom: [S2C-0092 AX_NEW_ROLES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [AX_ROLE_PROMPT_ARCHITECT](./AX_ROLE_PROMPT_ARCHITECT.md)
- next: [AX_ROLE_HUMAN_MEANING_INTEGRATOR](./AX_ROLE_HUMAN_MEANING_INTEGRATOR.md)

## Derivation
[goal](../_goal/ax_role_ai_workflow_orchestrator_goal.md) · [task](../_task/ax_role_ai_workflow_orchestrator_task.md) ·
[knowledge](../_knowledge/ax_role_ai_workflow_orchestrator_knowledge.md) · [method](../_method/ax_role_ai_workflow_orchestrator_method.md) ·
[skill](../_skill/AX_ROLE_AI_WORKFLOW_ORCHESTRATOR/SKILL.md)
