---
identity: DOMAIN_CONTEXT
displayName: "Domain Context"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 17
stage3SequenceID: S3S-0020
stage2CandidateID: S2C-0011
stage1CandidateID: S1C-014
derivedFrom:
  - "[S1C-014 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0011 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0020 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0020)"
fragmentedFrom: none
collapsedFrom: none
sequencePreviousIdentity: "[LLM_GEN_THIRD_FULL_STACK](./LLM_GEN_THIRD_FULL_STACK.md)"
sequenceNextIdentity: "[ORG_AX_OS](./ORG_AX_OS.md)"
sourceDocument: "_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md"
sourceLines: "248-256"
---

# DOMAIN_CONTEXT — Domain Context

## Concept Definition
One of the additional conditions for an organizational AX OS. If the common context is the standard of work criteria, the domain context is the execution structure that concretizes those criteria to fit actual work units. It is the stage that reconfigures the common context into an actually applicable form so that humans and AI can work together in a specific work area, and it corresponds to the intermediate execution structure that bridges common context and skill derivation in the flow "common context structure → domain context → skill derivation → field execution."

## Decision Criteria
Judged by whether the general criteria of the common context have been reconfigured into an execution structure concretized to fit a specific work area (domain). That is, the criterion is whether it has been converted into a form applicable to actual work units rather than remaining at the abstract-standard level.

## Output
Produces an execution structure in which humans and AI can work together in a specific work area, serving as the link that leads to the subsequent stages of skill derivation and field execution.

## Evidence (original quotation)
> "The domain context is the execution structure that concretizes those criteria to fit actual work units."

Source: `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` lines 248-256

## Provenance
- Stage-1: [S1C-014](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — domain-level operationalization of common context into an executable structure (common→domain→skill derivation→execution flow)
- Stage-2: [S2C-0011](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction KEEP
- Stage-3: [S3S-0020](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0020) — SequenceOrder 20
- fragmentedFrom: none

## Sequence
- previous: [LLM_GEN_THIRD_FULL_STACK](./LLM_GEN_THIRD_FULL_STACK.md)
- next: [ORG_AX_OS](./ORG_AX_OS.md)

## Derivation
[goal](../_goal/domain_context_goal.md) · [task](../_task/domain_context_task.md) ·
[knowledge](../_knowledge/domain_context_knowledge.md) · [method](../_method/domain_context_method.md) ·
[skill](../_skill/DOMAIN_CONTEXT/SKILL.md)
