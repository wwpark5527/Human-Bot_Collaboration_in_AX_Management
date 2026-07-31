---
identity: BOT_FUNCTIONAL_SATISFACTION
displayName: "Functional satisfaction/dissatisfaction"
class: CONCEPT
runID: 20260719_164605
walkOrder: 161
stage3SequenceID: S3S-0204
stage2CandidateID: S2C-0320
stage1CandidateID: S1C-077
derivedFrom:
  - "[S1C-077 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0320 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0204 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0204)"
fragmentedFrom: "[S2C-0066 HUMAN_UNDERSTANDING_BOTS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[BOT_AS_PATTERN_DETECTOR](./BOT_AS_PATTERN_DETECTOR.md)"
sequenceNextIdentity: "[BOT_DESIRE_HIERARCHY](./BOT_DESIRE_HIERARCHY.md)"
sourceDocument: "_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md"
sourceLines: "162-182"
---

# BOT_FUNCTIONAL_SATISFACTION — Functional satisfaction/dissatisfaction

## Concept Definition
Functional satisfaction/dissatisfaction is the concept that although a bot does not feel real satisfaction/dissatisfaction, a pseudo-state can be designed that is computed as maintain/reinforce or revise/avoid according to the rise and fall of a goal-attainment score. It is offered as the answer to the second basic question humans have about bots ("Does a bot feel emotions, satisfaction/dissatisfaction?").

## Decision Criteria
Judged by whether the state is an emotional/conscious/nervous-system response, or the computed result of data processing and objective-function optimization.

## Output
Behavioral change: maintaining and reinforcing a strategy when the goal-attainment score rises, and revising or avoiding it when the score falls.

## Evidence (original quotation)
> "The AI is computed such that when the goal-attainment score rises it is maintained/reinforced, and when the goal-attainment score falls it is revised/avoided. This can be viewed as functional satisfaction/dissatisfaction."

Source: `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` lines 162-182

## Provenance
- Stage-1: [S1C-077](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named concept clarifying bot nature — functional satisfaction/dissatisfaction, desire hierarchy (goal/reward hierarchy, Hierarchical RL), the three drivers of motivation, the bot's happiness = performance + alignment + efficiency
- Stage-2: [S2C-0320](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0204](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0204) — SequenceOrder 204
- fragmentedFrom: [S2C-0066 HUMAN_UNDERSTANDING_BOTS](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [BOT_AS_PATTERN_DETECTOR](./BOT_AS_PATTERN_DETECTOR.md)
- next: [BOT_DESIRE_HIERARCHY](./BOT_DESIRE_HIERARCHY.md)

## Derivation
[goal](../_goal/bot_functional_satisfaction_goal.md) · [task](../_task/bot_functional_satisfaction_task.md) ·
[knowledge](../_knowledge/bot_functional_satisfaction_knowledge.md) · [method](../_method/bot_functional_satisfaction_method.md) ·
[skill](../_skill/BOT_FUNCTIONAL_SATISFACTION/SKILL.md)
