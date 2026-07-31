---
identity: KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME
displayName: "runtime (SkillRuntime)"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 282
stage3SequenceID: S3S-0350
stage2CandidateID: S2C-0442
stage1CandidateID: S1C-133
derivedFrom:
  - "[S1C-133 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0442 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0350 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0350)"
fragmentedFrom: "[S2C-0115 KNOWLEDGE_ACTION_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[KNOWLEDGE_ACTION_CHAIN_NODE_SKILL](./KNOWLEDGE_ACTION_CHAIN_NODE_SKILL.md)"
sequenceNextIdentity: "[KNOWLEDGE_ACTION_CHAIN_NODE_ACTION](./KNOWLEDGE_ACTION_CHAIN_NODE_ACTION.md)"
sourceDocument: "_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md"
sourceLines: "526-536"
---

# KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME — runtime (SkillRuntime)

## Concept Definition
runtime (SkillRuntime) is the node that turns a skill into an actual execution structure. It defines input, materials, tools, prohibitions, result format, review approver, and record location. As the third node of the `knowledge-action chain` (S2C-0115, `KNOWLEDGE_ACTION_CHAIN`), it is located after the skill node and before the action node.

## Decision Criteria
It is judged by the fact that only when this structure is defined does a skill actually work in real tasks.

## Output
An executable skill-execution structure (for the detailed definition slots, see idx 135).

## Evidence (original quotation)
> "The knowledge-action chain turns knowledge into a skill, and turns that skill into an actual execution structure."

Source: `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` lines 526-536

## Provenance
- Stage-1: [S1C-133](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named execution/operating chain (knowledge→skill→runtime→action→outcome→review/feedback→context, line 625) contrasted with the knowledge chain (knowing vs. executing; head vs. hands-and-feet/learning); GP-company-formed (footnote 52)
- Stage-2: [S2C-0442](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0350](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0350) — SequenceOrder 350
- fragmentedFrom: [S2C-0115 KNOWLEDGE_ACTION_CHAIN](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [KNOWLEDGE_ACTION_CHAIN_NODE_SKILL](./KNOWLEDGE_ACTION_CHAIN_NODE_SKILL.md)
- next: [KNOWLEDGE_ACTION_CHAIN_NODE_ACTION](./KNOWLEDGE_ACTION_CHAIN_NODE_ACTION.md)

## Derivation
[goal](../_goal/knowledge_action_chain_node_runtime_goal.md) · [task](../_task/knowledge_action_chain_node_runtime_task.md) ·
[knowledge](../_knowledge/knowledge_action_chain_node_runtime_knowledge.md) · [method](../_method/knowledge_action_chain_node_runtime_method.md) ·
[skill](../_skill/KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME/SKILL.md)
