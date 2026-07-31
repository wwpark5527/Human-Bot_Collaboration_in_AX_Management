---
identity: DIGITAL_WORKER_SUBAGENT
displayName: "Subagent"
class: STRUCTURE
runID: 20260719_164605
walkOrder: 27
stage3SequenceID: S3S-0034
stage2CandidateID: S2C-0178
stage1CandidateID: S1C-026
derivedFrom:
  - "[S1C-026 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0178 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0034 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0034)"
fragmentedFrom: "[S2C-0020 AGENT_AUTONOMY_TAXONOMY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[DIGITAL_WORKER_AI_AGENT](./DIGITAL_WORKER_AI_AGENT.md)"
sequenceNextIdentity: "[DIGITAL_WORKER_BOT](./DIGITAL_WORKER_BOT.md)"
sourceDocument: "_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md"
sourceLines: "352-362"
---

# DIGITAL_WORKER_SUBAGENT — Subagent

## Concept Definition
The middle item in the digital-worker autonomy classification table—a specialized agent that supports a higher agent. It occupies the intermediate status between AI agent and Bot and corresponds to the mid-grade bot.

## Decision Criteria
Judged by the values of middle autonomy, goals assigned by a higher agent, limited and specialized role scope, limited decision-making capability, collaboration internal to the agent, and partial memory/context retention. It is distinguished from the AI agent in that it does not set its own goals, and from the Bot in that specialized judgment is possible.

## Output
Produces limited, specialized execution results for a goal assigned by a higher agent. An example is a research subagent.

## Evidence (original quotation)
> "Category           AI agent          Subagent            Bot / Basic concept   goal-oriented autonomous execution subject   specialized agent supporting a higher agent   automation program performing a specific function"

> "Role scope           comprehensive and complex                   limited and specialized          simple and repetitive"

Source: `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` lines 352-362

## Provenance
- Stage-1: [S1C-026](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — taxonomy of digital workers by autonomy (AI agent > Subagent > Bot, or high/mid/low-grade bots) across autonomy, goal-setting, role scope, decision-making, collaboration, and memory
- Stage-2: [S2C-0178](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0034](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0034) — SequenceOrder 34
- fragmentedFrom: [S2C-0020 AGENT_AUTONOMY_TAXONOMY](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [DIGITAL_WORKER_AI_AGENT](./DIGITAL_WORKER_AI_AGENT.md)
- next: [DIGITAL_WORKER_BOT](./DIGITAL_WORKER_BOT.md)

## Derivation
[goal](../_goal/digital_worker_subagent_goal.md) · [task](../_task/digital_worker_subagent_task.md) ·
[knowledge](../_knowledge/digital_worker_subagent_knowledge.md) · [method](../_method/digital_worker_subagent_method.md) ·
[skill](../_skill/DIGITAL_WORKER_SUBAGENT/SKILL.md)
