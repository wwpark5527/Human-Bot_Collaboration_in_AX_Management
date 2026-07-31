---
identity: PIS_WORLD_MODEL
displayName: "World model"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 305
stage3SequenceID: S3S-0382
stage2CandidateID: S2C-0463
stage1CandidateID: S1C-150
derivedFrom:
  - "[S1C-150 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0463 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0382 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0382)"
fragmentedFrom: "[S2C-0129 PREDICTIVE_INTELLIGENCE_SYSTEM](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[PREDICTIVE_INTELLIGENCE](./PREDICTIVE_INTELLIGENCE.md)"
sequenceNextIdentity: "[PIS_CONTEXT_DESIGN](./PIS_CONTEXT_DESIGN.md)"
sourceDocument: "_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md"
sourceLines: "27-66"
---

# PIS_WORLD_MODEL — World model

## Concept Definition
The world model is a model structure by which AI internally represents and predicts the state of the environment, its changes, and the results of actions — the technical foundation of the predictive capability that forms the fourth layer of the predictive intelligence system. Whereas general generative AI focuses on producing plausible outputs for inputs, the world model accesses the current state of the world, state changes, the results of actions, comparison of paths, and pre-execution risk simulation.

## Decision Criteria
Decided by whether it answers the core question 'what will happen,' and whether it can simulate the current world state, future changes, the results of actions, comparison of paths, and pre-execution risk.

## Output
Prediction of future states and the results of actions, pre-execution scenario simulation, and grounds for planning and autonomous action.

## Evidence (original quotation)
> "The world model is a model structure by which AI internally represents and predicts the state of the environment, its changes, and the results of actions."

Source: `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 27-66

## Provenance
- Stage-1: [S1C-150](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — the layered (5-layer) architecture; combines world model + knowledge chain + context design into an operative "predictive intelligence system" (aliases: predictive intelligence system/stack)
- Stage-2: [S2C-0463](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0382](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0382) — SequenceOrder 382
- fragmentedFrom: [S2C-0129 PREDICTIVE_INTELLIGENCE_SYSTEM](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [PREDICTIVE_INTELLIGENCE](./PREDICTIVE_INTELLIGENCE.md)
- next: [PIS_CONTEXT_DESIGN](./PIS_CONTEXT_DESIGN.md)

## Derivation
[goal](../_goal/pis_world_model_goal.md) · [task](../_task/pis_world_model_task.md) ·
[knowledge](../_knowledge/pis_world_model_knowledge.md) · [method](../_method/pis_world_model_method.md) ·
[skill](../_skill/PIS_WORLD_MODEL/SKILL.md)
