---
identity: KNOWLEDGE_CHAIN_STAGE_CONTEXT_REFERENCE
displayName: "Organizational Context Reference"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 269
stage3SequenceID: S3S-0335
stage2CandidateID: S2C-0431
stage1CandidateID: S1C-125
derivedFrom:
  - "[S1C-125 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0431 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0335 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0335)"
fragmentedFrom: "[S2C-0108 KNOWLEDGE_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[KNOWLEDGE_CHAIN_STAGE_QUESTION](./KNOWLEDGE_CHAIN_STAGE_QUESTION.md)"
sequenceNextIdentity: "[KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION](./KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "254-256"
---

# KNOWLEDGE_CHAIN_STAGE_CONTEXT_REFERENCE — Organizational Context Reference

## Concept Definition
Organizational context reference is the stage that interprets a question against the organization's common context (purpose, standards, roles, sources, format). It is the node that brings in the "organization's history, intent, norms, and memory" that existing LLMs lack, and it is the second stage of the `knowledge chain` (S2C-0108, `KNOWLEDGE_CHAIN`).

## Decision Criteria
It is judged by whether the answer was produced by referencing the organization's standards, without being swayed by per-user differences in interpretation.

## Output
An interpretation context in which organizational standards are reflected.

## Evidence (original quotation)
> "By contrast, a common/governance-context-based AX system has a circulation/accumulation structure of 'question → organizational context reference → governance validation → response generation → result recording → re-reflection into organizational knowledge → reuse by the next AI/human.'"

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 254-256

## Provenance
- Stage-1: [S1C-125](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named accumulation/circulation structure (question → context reference → validation → recording → re-reflection → reuse) that observes the path to an answer, not just the answer
- Stage-2: [S2C-0431](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0335](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0335) — SequenceOrder 335
- fragmentedFrom: [S2C-0108 KNOWLEDGE_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [KNOWLEDGE_CHAIN_STAGE_QUESTION](./KNOWLEDGE_CHAIN_STAGE_QUESTION.md)
- next: [KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION](./KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION.md)

## Derivation
[goal](../_goal/knowledge_chain_stage_context_reference_goal.md) · [task](../_task/knowledge_chain_stage_context_reference_task.md) ·
[knowledge](../_knowledge/knowledge_chain_stage_context_reference_knowledge.md) · [method](../_method/knowledge_chain_stage_context_reference_method.md) ·
[skill](../_skill/KNOWLEDGE_CHAIN_STAGE_CONTEXT_REFERENCE/SKILL.md)
