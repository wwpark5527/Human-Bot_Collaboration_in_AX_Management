---
identity: KNOWLEDGE_ACTION_CHAIN_NODE_SKILL
displayName: "skill"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 281
stage3SequenceID: S3S-0349
stage2CandidateID: S2C-0441
stage1CandidateID: S1C-133
derivedFrom:
  - "[S1C-133 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0441 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0349 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0349)"
fragmentedFrom: "[S2C-0115 KNOWLEDGE_ACTION_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[KNOWLEDGE_ACTION_CHAIN_NODE_KNOWLEDGE](./KNOWLEDGE_ACTION_CHAIN_NODE_KNOWLEDGE.md)"
sequenceNextIdentity: "[KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME](./KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "518-524"
---

# KNOWLEDGE_ACTION_CHAIN_NODE_SKILL — skill

## Concept Definition
A skill is the unit of execution of the AI era. Unlike a document, which is meant to be read, it is meant to be executed — the node that has turned knowledge into an executable form. As the second node of the `knowledge-action chain` (S2C-0115, `KNOWLEDGE_ACTION_CHAIN`), it is located after the knowledge node and before the runtime node.

## Decision Criteria
It is judged by what skill that knowledge was turned into. It is distinguished by whether it is a document meant to be read or a skill meant to be executed.

## Output
A skill as a unit of execution (policy-based answer verification, contract risk analysis, meeting summary and action derivation, etc.).

## Evidence (original quotation)
> "In the AI era, the important unit is not the document but the skill. A document is meant to be read; a skill is meant to be executed."

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 518-524

## Provenance
- Stage-1: [S1C-133](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named execution/operating chain (knowledge→skill→runtime→action→outcome→review/feedback→context, line 625) contrasted with the knowledge chain (knowing vs. executing; head vs. hands-and-feet/learning); GP-company-formed (footnote 52)
- Stage-2: [S2C-0441](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0349](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0349) — SequenceOrder 349
- fragmentedFrom: [S2C-0115 KNOWLEDGE_ACTION_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [KNOWLEDGE_ACTION_CHAIN_NODE_KNOWLEDGE](./KNOWLEDGE_ACTION_CHAIN_NODE_KNOWLEDGE.md)
- next: [KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME](./KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME.md)

## Derivation
[goal](../_goal/knowledge_action_chain_node_skill_goal.md) · [task](../_task/knowledge_action_chain_node_skill_task.md) ·
[knowledge](../_knowledge/knowledge_action_chain_node_skill_knowledge.md) · [method](../_method/knowledge_action_chain_node_skill_method.md) ·
[skill](../_skill/KNOWLEDGE_ACTION_CHAIN_NODE_SKILL/SKILL.md)
