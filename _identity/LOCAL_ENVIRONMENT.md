---
identity: LOCAL_ENVIRONMENT
displayName: "Local environment"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 252
stage3SequenceID: S3S-0315
stage2CandidateID: S2C-0415
stage1CandidateID: S1C-119
derivedFrom:
  - "[S1C-119 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0415 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0315 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0315)"
fragmentedFrom: "[S2C-0102 LOCAL_AND_NETWORK_ENVIRONMENT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[HUMAN_BOT_ROLE_MANAGEMENT](./HUMAN_BOT_ROLE_MANAGEMENT.md)"
sequenceNextIdentity: "[NETWORK_ENVIRONMENT](./NETWORK_ENVIRONMENT.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "34-51"
---

# LOCAL_ENVIRONMENT — Local environment

## Concept Definition
The local environment is the environment of an individual work unit where AI actually works, taking as its central concept the work context (common context) in which AI works within a specific task. It is the first of the two elements settled by the SplitSet division of `Local environment / Network environment` (S2C-0102, `LOCAL_AND_NETWORK_ENVIRONMENT`), and among the two environments that make up the operating structure of the AI era, it corresponds to the side where AI actually works. It is paired with the network environment, in which multiple local environments connect to each other.

## Decision Criteria
Can it answer "By what standards is this task performed?" Are purpose, standards, role, source, format, and feedback being managed within that task?

## Output
The operating standards of an individual task — that is, a local work context in which humans and AI work according to the same purpose, standards, role, source, and format.

## Evidence (original quotation)
> "The common context turns things into a local work context so that, within the local environment, humans and AI can work according to the same purpose, standards, role, source, and format."

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 34-51

## Provenance
- Stage-1: [S1C-119](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named two-tier operating structure that grounds the whole chapter — the local environment carries the common context, the network environment carries the governance context (comparison table at 37-45)
- Stage-2: [S2C-0415](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0315](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0315) — SequenceOrder 315
- fragmentedFrom: [S2C-0102 LOCAL_AND_NETWORK_ENVIRONMENT](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [HUMAN_BOT_ROLE_MANAGEMENT](./HUMAN_BOT_ROLE_MANAGEMENT.md)
- next: [NETWORK_ENVIRONMENT](./NETWORK_ENVIRONMENT.md)

## Derivation
[goal](../_goal/local_environment_goal.md) · [task](../_task/local_environment_task.md) ·
[knowledge](../_knowledge/local_environment_knowledge.md) · [method](../_method/local_environment_method.md) ·
[skill](../_skill/LOCAL_ENVIRONMENT/SKILL.md)
