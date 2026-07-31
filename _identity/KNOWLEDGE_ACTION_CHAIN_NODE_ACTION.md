---
identity: KNOWLEDGE_ACTION_CHAIN_NODE_ACTION
displayName: "action (execution)"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 283
stage3SequenceID: S3S-0351
stage2CandidateID: S2C-0443
stage1CandidateID: S1C-133
derivedFrom:
  - "[S1C-133 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0443 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0351 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0351)"
fragmentedFrom: "[S2C-0115 KNOWLEDGE_ACTION_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME](./KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME.md)"
sequenceNextIdentity: "[KNOWLEDGE_ACTION_CHAIN_NODE_OUTCOME](./KNOWLEDGE_ACTION_CHAIN_NODE_OUTCOME.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "475-483"
---

# KNOWLEDGE_ACTION_CHAIN_NODE_ACTION — action (execution)

## Concept Definition
action (execution) is the node where a skill is actually performed following the defined runtime. It is the point that carries the knowledge-action chain from a structure of knowing into a structure of execution. As the fourth node of the `knowledge-action chain` (S2C-0115, `KNOWLEDGE_ACTION_CHAIN`), it is located after the runtime node and before the outcome node.

## Decision Criteria
It is judged by whether this knowledge was actually used and by who executed it.

## Output
The actual action and its deliverable.

## Evidence (original quotation)
> "The knowledge-action chain goes one step further, into the execution of knowledge."

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 475-483

## Provenance
- Stage-1: [S1C-133](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named execution/operating chain (knowledge→skill→runtime→action→outcome→review/feedback→context, line 625) contrasted with the knowledge chain (knowing vs. executing; head vs. hands-and-feet/learning); GP-company-formed (footnote 52)
- Stage-2: [S2C-0443](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0351](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0351) — SequenceOrder 351
- fragmentedFrom: [S2C-0115 KNOWLEDGE_ACTION_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME](./KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME.md)
- next: [KNOWLEDGE_ACTION_CHAIN_NODE_OUTCOME](./KNOWLEDGE_ACTION_CHAIN_NODE_OUTCOME.md)

## Derivation
[goal](../_goal/knowledge_action_chain_node_action_goal.md) · [task](../_task/knowledge_action_chain_node_action_task.md) ·
[knowledge](../_knowledge/knowledge_action_chain_node_action_knowledge.md) · [method](../_method/knowledge_action_chain_node_action_method.md) ·
[skill](../_skill/KNOWLEDGE_ACTION_CHAIN_NODE_ACTION/SKILL.md)
