---
identity: AX_ROLE_PROVENANCE_CONTROLLER
displayName: "Provenance Controller"
class: ROLE
runID: 20260719_164605
walkOrder: 231
stage3SequenceID: S3S-0287
stage2CandidateID: S2C-0395
stage1CandidateID: S1C-107
derivedFrom:
  - "[S1C-107 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0395 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0287 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0287)"
fragmentedFrom: "[S2C-0092 AX_NEW_ROLES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[AX_ROLE_TRUST_MANAGER](./AX_ROLE_TRUST_MANAGER.md)"
sequenceNextIdentity: "[DYNAMIC_ROLE_BALANCE](./DYNAMIC_ROLE_BALANCE.md)"
sourceDocument: "_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md"
sourceLines: "77-77"
---

# AX_ROLE_PROVENANCE_CONTROLLER — Provenance Controller

## Concept Definition
This is a new AX role that manages the provenance and traceability of data. Following the AI Governor, AI Auditor, Prompt Architect, AI Workflow Orchestrator, Human Meaning Integrator, and Trust Manager, it is the seventh and last of the seven new roles that appear in the additional mode of TR by bots, a role that did not exist in human-centered organizations.

## Decision Criteria
It is judged by whether the role is responsible for managing data provenance and traceability.

## Output
A record of data provenance and traceability is produced.

## Evidence (original quotation)
> "Provenance Controller                   data provenance·traceability management"

Source: `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` lines 77-77

## Provenance
- Stage-1: [S1C-107](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — Named set of new organizational role/member-types that AX orgs add beyond the human-only Belbin roster (the "additional" mode made concrete).
- Stage-2: [S2C-0395](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0287](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0287) — SequenceOrder 287
- fragmentedFrom: [S2C-0092 AX_NEW_ROLES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [AX_ROLE_TRUST_MANAGER](./AX_ROLE_TRUST_MANAGER.md)
- next: [DYNAMIC_ROLE_BALANCE](./DYNAMIC_ROLE_BALANCE.md)

## Derivation
[goal](../_goal/ax_role_provenance_controller_goal.md) · [task](../_task/ax_role_provenance_controller_task.md) ·
[knowledge](../_knowledge/ax_role_provenance_controller_knowledge.md) · [method](../_method/ax_role_provenance_controller_method.md) ·
[skill](../_skill/AX_ROLE_PROVENANCE_CONTROLLER/SKILL.md)
