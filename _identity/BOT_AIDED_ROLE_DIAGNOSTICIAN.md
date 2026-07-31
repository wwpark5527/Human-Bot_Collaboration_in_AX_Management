---
identity: BOT_AIDED_ROLE_DIAGNOSTICIAN
displayName: "Role Diagnostician"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 233
stage3SequenceID: S3S-0290
stage2CandidateID: S2C-0396
stage1CandidateID: S1C-109
derivedFrom:
  - "[S1C-109 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0396 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0290 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0290)"
fragmentedFrom: "[S2C-0094 BOT_AIDED_TRB](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[DYNAMIC_ROLE_BALANCE](./DYNAMIC_ROLE_BALANCE.md)"
sequenceNextIdentity: "[BOT_AIDED_COLLABORATION_FACILITATOR](./BOT_AIDED_COLLABORATION_FACILITATOR.md)"
sourceDocument: "_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md"
sourceLines: "138-149"
---

# BOT_AIDED_ROLE_DIAGNOSTICIAN — Role Diagnostician

## Concept Definition
One of the roles the bot takes on in Bot-Aided TRB, diagnosing the state of roles within the human team. It corresponds to the first column of the source table. Within the Bot-Aided TRB (bot-assisted TRB, vertical relationship) structure, it is the first of the three roles the bot performs — Role Diagnostician, Collaboration Facilitator, and Cognitive Augmenter.

## Decision Criteria
Judged by whether it performs detection of role gaps and analysis of role concentration within the team.

## Output
Produces the results of in-team role diagnosis. Examples given include a shortage of the Monitor-Evaluator (ME) role, an excess of the Plant (PL) role, and increased conflict among Shapers (SH).

## Evidence (original quotation)
> "Role Diagnostician                    Collaboration Facilitator                      Cognitive Augmenter      (Role Diagnostician)    (Collaboration Facilitator)   Cognitive Augmenter)"

Source: `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` lines 138-149

## Provenance
- Stage-1: [S1C-109](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — First of the two named TRB evolution modes — a vertical, human-primary/bot-subordinate structure (bot as Role Diagnostician, Collaboration Facilitator, and Cognitive Augmenter).
- Stage-2: [S2C-0396](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0290](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0290) — SequenceOrder 290
- fragmentedFrom: [S2C-0094 BOT_AIDED_TRB](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [DYNAMIC_ROLE_BALANCE](./DYNAMIC_ROLE_BALANCE.md)
- next: [BOT_AIDED_COLLABORATION_FACILITATOR](./BOT_AIDED_COLLABORATION_FACILITATOR.md)

## Derivation
[goal](../_goal/bot_aided_role_diagnostician_goal.md) · [task](../_task/bot_aided_role_diagnostician_task.md) ·
[knowledge](../_knowledge/bot_aided_role_diagnostician_knowledge.md) · [method](../_method/bot_aided_role_diagnostician_method.md) ·
[skill](../_skill/BOT_AIDED_ROLE_DIAGNOSTICIAN/SKILL.md)
