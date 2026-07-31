---
identity: BOT_MEMBER
displayName: "B: Bot"
class: ROLE
runID: 20260719_164605
walkOrder: 25
stage3SequenceID: S3S-0031
stage2CandidateID: S2C-0019
stage1CandidateID: S1C-025
derivedFrom:
  - "[S1C-025 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0019 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0031 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0031)"
fragmentedFrom: none
collapsedFrom: none
sequencePreviousIdentity: "[HUMAN_MEMBER](./HUMAN_MEMBER.md)"
sequenceNextIdentity: "[DIGITAL_WORKER_AI_AGENT](./DIGITAL_WORKER_AI_AGENT.md)"
sourceDocument: "_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md"
sourceLines: "306-335"
---

# BOT_MEMBER — B: Bot

## Concept Definition
One of the four member types of an AX organization (H·AH·AB·B), referring to a bot that has undergone no physical or mental augmentation — that is, a 'Bot centered on automating specific tasks.' As the equation "general-purpose AI (Tech) + Identity + Governance = bot" shows, a bot is an account-type (identity) input/output channel that lets the AI interact within the workspace; the AI does not participate in the workspace directly but connects only through the bot. If the AI is the engine, the bot is the whole car driving toward a destination, and intelligence and execution are handled not by the bot itself but by the AI model and the context.

## Decision Criteria
Judged by whether the entity is a bot, has undergone no augmentation of physical or mental capability, and has not been converted into an AB (augmented bot) by having common & governance context and AI governance built in. Contrasted with AB, B is characterized by function-centered, command-following, output-generating, automation-centered, weak accountability structure, and an individual-tool nature; it is distinguished from AB (role-centered, context-based performance, verifiable output generation, collaboration-centered, operating within a governance structure, an organizational-member-type AI) on all six of these axes.

## Output
Produces the results of automating a fixed, specific task. Some organizations, such as Samsung, use the expression 'digital worker,' but this book uses the commonly used traditional, plain term 'bot.'

## Evidence (original quotation)
> "B: Bot         a non-augmented bot       Bot centered on automating specific tasks"

> "Equation: general-purpose AI (Tech) + Identity + Governance = bot"

Source: `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` lines 306-307, 330-335

## Provenance
- Stage-1: [S1C-025](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — member type — non-augmented automation bot; the account/identity interface channel through which AI participates in the workspace (synonymous with Samsung's 'digital worker' etc.)
- Stage-2: [S2C-0019](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction KEEP
- Stage-3: [S3S-0031](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0031) — SequenceOrder 31
- fragmentedFrom: none

## Sequence
- previous: [HUMAN_MEMBER](./HUMAN_MEMBER.md)
- next: [DIGITAL_WORKER_AI_AGENT](./DIGITAL_WORKER_AI_AGENT.md)

## Derivation
[goal](../_goal/bot_member_goal.md) · [task](../_task/bot_member_task.md) ·
[knowledge](../_knowledge/bot_member_knowledge.md) · [method](../_method/bot_member_method.md) ·
[skill](../_skill/BOT_MEMBER/SKILL.md)
