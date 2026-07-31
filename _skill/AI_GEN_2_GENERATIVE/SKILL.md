---
name: ai_gen_2_generative_skill
description: Use when discriminating whether a target AI system/function falls at the AI 2.0 (Generative AI, generative type) stage of the AI generational-classification table, and when diagnosing the hallucination and security-leakage limitations accompanying its generative ability.
---

# AI 2.0 (Generative AI) — Skill

## Purpose
Discriminate, on the basis of the AI generational-classification table, whether the target AI is at the generative (Generative AI) stage, and diagnose its limitations.

## Input
- List of the actual operations of the target AI system/function (including generated output)
- AI generational-classification table (function definitions for AI 1.0–4.0)

## Procedure (Steps)
1. Confirm whether the target AI generates new content such as sentences and images.
2. Check whether it sets goals on its own and plans and executes them (whether it is Agentic).
3. If it has only a generative function and no autonomous execution, classify it as AI 2.0 (Generative AI).
4. If autonomous execution is also confirmed, reclassify it into a higher generation (AI 3.0/4.0).
5. Check the hallucination phenomena and security-leakage risk of the generated output and record them in the diagnostic report.

## Output
AI generation discrimination result, diagnostic report on the limits of generative ability (hallucination, security leakage).

## Criteria
If the discrimination result accurately conforms to the table's standard (generation only vs. autonomous execution/organization operation) and the limitation items are recorded without omission, it is determined PASS.

## Derivation
[method](../../_method/ai_gen_2_generative_method.md) -> [knowledge](../../_knowledge/ai_gen_2_generative_knowledge.md) ->
[task](../../_task/ai_gen_2_generative_task.md) -> [goal](../../_goal/ai_gen_2_generative_goal.md) ->
[identity](../../_identity/AI_GEN_2_GENERATIVE.md)
