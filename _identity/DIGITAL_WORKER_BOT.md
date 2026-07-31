---
identity: DIGITAL_WORKER_BOT
displayName: "Bot"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 28
stage3SequenceID: S3S-0035
stage2CandidateID: S2C-0179
stage1CandidateID: S1C-026
derivedFrom:
  - "[S1C-026 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0179 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0035 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0035)"
fragmentedFrom: "[S2C-0020 AGENT_AUTONOMY_TAXONOMY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[DIGITAL_WORKER_SUBAGENT](./DIGITAL_WORKER_SUBAGENT.md)"
sequenceNextIdentity: "[COOP_TYPE_H_PLUS_B](./COOP_TYPE_H_PLUS_B.md)"
sourceDocument: "_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md"
sourceLines: "349-362"
---

# DIGITAL_WORKER_BOT — Bot

## Concept Definition
The lowest item in the digital-worker autonomy classification table—"a digital worker that automatically performs set tasks," whose basic concept is defined in the table as an "automation program that performs a specific function." It corresponds to the low-grade bot. This item refers to the same bot concept as "B: Bot" (member type, `BOT_MEMBER`) in the AX-organization member-type table, but here it is treated with a separate structural status as the lowest autonomy grade within the AI agent/Subagent/Bot autonomy-subdivision table.

## Decision Criteria
Judged by the lowest values across the six axes: low autonomy, almost no goal-setting, simple and repetitive role scope, primarily rule-based decision-making, limited collaboration, and weak memory/context retention.

## Output
Produces simple, repetitive automatic-execution results according to set rules. Examples are a chatbot and a reservation bot.

## Evidence (original quotation)
> "In the table below, an AI agent is not mere automation but 'an autonomous AI actor that understands goals, plans on its own, and executes,' whereas a bot is 'a digital worker that automatically performs set tasks,' distinguishing the two by whether the degree of autonomy is high or low."

> "Basic concept ... automation program that performs a specific function / Autonomy ... low / Goal-setting ... almost none / Decision-making ... primarily rule-based / Example ... chatbot, reservation bot"

Source: `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` lines 349-362

## Provenance
- Stage-1: [S1C-026](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — taxonomy of digital workers by autonomy (AI agent > Subagent > Bot, or high/mid/low-grade bots) across autonomy, goal-setting, role scope, decision-making, collaboration, and memory
- Stage-2: [S2C-0179](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0035](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0035) — SequenceOrder 35
- fragmentedFrom: [S2C-0020 AGENT_AUTONOMY_TAXONOMY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [DIGITAL_WORKER_SUBAGENT](./DIGITAL_WORKER_SUBAGENT.md)
- next: [COOP_TYPE_H_PLUS_B](./COOP_TYPE_H_PLUS_B.md)

## Derivation
[goal](../_goal/digital_worker_bot_goal.md) · [task](../_task/digital_worker_bot_task.md) ·
[knowledge](../_knowledge/digital_worker_bot_knowledge.md) · [method](../_method/digital_worker_bot_method.md) ·
[skill](../_skill/DIGITAL_WORKER_BOT/SKILL.md)
