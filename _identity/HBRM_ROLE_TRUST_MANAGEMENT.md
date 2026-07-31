---
identity: HBRM_ROLE_TRUST_MANAGEMENT
displayName: "Trust Management"
class: METHOD
runID: 20260719_164605
walkOrder: 173
stage3SequenceID: S3S-0218
stage2CandidateID: S2C-0343
stage1CandidateID: S1C-079
derivedFrom:
  - "[S1C-079 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0343 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0218 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0218)"
fragmentedFrom: "[S2C-0068 HBRM](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[HBRM_ROLE_ROLE_BALANCE_MANAGEMENT](./HBRM_ROLE_ROLE_BALANCE_MANAGEMENT.md)"
sequenceNextIdentity: "[HBRM_ROLE_GOVERNANCE_LINKAGE](./HBRM_ROLE_GOVERNANCE_LINKAGE.md)"
sourceDocument: "_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md"
sourceLines: "319"
---

# HBRM_ROLE_TRUST_MANAGEMENT — Trust Management

## Concept Definition
Trust management is the sixth of the eight roles that HBRM (Human-Bot Resource Management) performs within an AX organization. It is the function that establishes collaboration standards preventing overtrust and distrust in the collaboration between humans and bots. Even when role-balance management adjusts the concentration, deficiency, and conflict of roles, the problem of a human trusting a bot's result excessively and accepting it uncritically, or conversely distrusting it excessively and thereby impeding collaboration itself, must be handled separately. Trust management is the stage that sets collaboration standards preventing these two extremes so that humans and bots collaborate at an appropriate level of trust.

## Decision Criteria
It is judged by whether collaboration standards preventing overtrust and distrust are established.

## Output
The established collaboration standards.

## Evidence (original quotation)
> "Trust management              Establish collaboration standards preventing overtrust and distrust"

Source: `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` lines 319

## Provenance
- Stage-1: [S1C-079](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — named management framework extending HRM→HBRM across member expansion / role expansion / evolution expansion; alias Human-Bot Resource Management; carries 8 HBRM roles + role-balance imbalance diagnosis
- Stage-2: [S2C-0343](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0218](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0218) — SequenceOrder 218
- fragmentedFrom: [S2C-0068 HBRM](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [HBRM_ROLE_ROLE_BALANCE_MANAGEMENT](./HBRM_ROLE_ROLE_BALANCE_MANAGEMENT.md)
- next: [HBRM_ROLE_GOVERNANCE_LINKAGE](./HBRM_ROLE_GOVERNANCE_LINKAGE.md)

## Derivation
[goal](../_goal/hbrm_role_trust_management_goal.md) · [task](../_task/hbrm_role_trust_management_task.md) ·
[knowledge](../_knowledge/hbrm_role_trust_management_knowledge.md) · [method](../_method/hbrm_role_trust_management_method.md) ·
[skill](../_skill/HBRM_ROLE_TRUST_MANAGEMENT/SKILL.md)
