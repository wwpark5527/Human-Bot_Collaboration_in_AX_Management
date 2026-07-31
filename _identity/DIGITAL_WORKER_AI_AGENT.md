---
identity: DIGITAL_WORKER_AI_AGENT
displayName: "AI agent"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 26
stage3SequenceID: S3S-0033
stage2CandidateID: S2C-0177
stage1CandidateID: S1C-026
derivedFrom:
  - "[S1C-026 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0177 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0033 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0033)"
fragmentedFrom: "[S2C-0020 AGENT_AUTONOMY_TAXONOMY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[BOT_MEMBER](./BOT_MEMBER.md)"
sequenceNextIdentity: "[DIGITAL_WORKER_SUBAGENT](./DIGITAL_WORKER_SUBAGENT.md)"
sourceDocument: "_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md"
sourceLines: "349-362"
---

# DIGITAL_WORKER_AI_AGENT — AI agent

## Concept Definition
The top item in the table that subdivides digital workers (bots) along the autonomy axis into three levels (AI agent > Subagent > Bot, or high/mid/low-grade bots). It is not mere automation but "an autonomous AI actor that understands goals, plans on its own, and executes," and in the table its basic concept is defined as a "goal-oriented autonomous execution subject." It corresponds to the high-grade bot.

## Decision Criteria
Judged by the top values across the six axes: high autonomy, partially capable goal-setting, comprehensive and complex role scope, capable of decision-making, collaborating with humans and other agents, and strong memory/context retention.

## Output
Produces comprehensive and complex execution and decision-making according to plans it sets itself. Examples are an AI assistant and an autonomous research agent.

## Evidence (original quotation)
> "In the table below, an AI agent is not mere automation but 'an autonomous AI actor that understands goals, plans on its own, and executes,' whereas a bot is 'a digital worker that automatically performs set tasks,' distinguishing the two by whether the degree of autonomy is high or low."

> "Basic concept       goal-oriented autonomous execution subject / Autonomy    high / Goal-setting   partially possible / Role scope   comprehensive and complex / Decision-making   possible / Collaboration   collaborates with humans and other agents / Memory/context retention   strong / Example   AI assistant, autonomous research agent"

Source: `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` lines 349-362

## Provenance
- Stage-1: [S1C-026](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — taxonomy of digital workers by autonomy (AI agent > Subagent > Bot, or high/mid/low-grade bots) across autonomy, goal-setting, role scope, decision-making, collaboration, and memory
- Stage-2: [S2C-0177](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0033](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0033) — SequenceOrder 33
- fragmentedFrom: [S2C-0020 AGENT_AUTONOMY_TAXONOMY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [BOT_MEMBER](./BOT_MEMBER.md)
- next: [DIGITAL_WORKER_SUBAGENT](./DIGITAL_WORKER_SUBAGENT.md)

## Derivation
[goal](../_goal/digital_worker_ai_agent_goal.md) · [task](../_task/digital_worker_ai_agent_task.md) ·
[knowledge](../_knowledge/digital_worker_ai_agent_knowledge.md) · [method](../_method/digital_worker_ai_agent_method.md) ·
[skill](../_skill/DIGITAL_WORKER_AI_AGENT/SKILL.md)
