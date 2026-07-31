---
name: ai_sovereignty_skill
description: Use when discriminating whether the organization's data and decision sovereignty is being preserved in a technically demonstrable way (e.g., ZKP-based patented technology) even while using external AI (LLMs).
---

# AI Sovereignty (Sovereignty) — Skill

## Purpose
Discriminate whether the organization's data and decision sovereignty is actually preserved while taking the benefit of using external AI, and whether there is a technical basis to demonstrate this objectively.

## Input
- List of external LLMs the organization connects to and their connection methods
- Technology introduced for the preservation of sovereignty (e.g., ZKP-based methods) and its patent/certification grounds

## Procedure (Steps)
1. Identify the risk points of data and context outflow arising from the use of external LLMs.
2. Confirm whether sovereignty-preserving technology (e.g., a zero-knowledge proof based method) is applied.
3. Confirm whether there are objective demonstrative grounds such as patents and certifications for that technology.
4. Comprehensively determine whether the benefit of using external AI and the preservation of organizational sovereignty hold simultaneously.

## Output
Determination of AI sovereignty preservation (not preserved | technically demonstrated preservation), list of related patent and certification grounds.

## Criteria
It is determined PASS when the possibility of data and context outflow through connection with external LLMs is blocked in a technically demonstrable way so that organizational sovereignty is preserved.

## Derivation
[method](../../_method/ai_sovereignty_method.md) -> [knowledge](../../_knowledge/ai_sovereignty_knowledge.md) ->
[task](../../_task/ai_sovereignty_task.md) -> [goal](../../_goal/ai_sovereignty_goal.md) ->
[identity](../../_identity/AI_SOVEREIGNTY.md)
