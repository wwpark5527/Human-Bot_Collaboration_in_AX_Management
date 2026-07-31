---
name: aiu_stage_tool_user_skill
description: Use when it is necessary to identify whether a member falls at the Tool User stage of the AI Utilization (AIU) ladder, asking an LLM questions, copying results, and using AI like a search engine.
---

# Tool User — Skill

## Purpose
Determine whether a member is at the Tool User stage of the AI-utilization ladder, using AI like a search engine centered on questions and copying results, and thereby secure the reference point for designing the Collaborative User transition path.

## Input
- The member's AI-usage frequency (number of uses per day/week)
- The member's number of AI questions and the degree to which generated results are used

## Procedure (Steps)
1. Tally the AI-usage frequency.
2. Record the number of AI questions and the degree to which generated results are used.
3. Evaluate "Could the same result be produced even without AI?"
4. Determine from the evaluation result whether the Tool User stage applies.

## Output
Record table of AI-usage frequency and number of questions, indicator of the degree to which generated results are used, Tool User stage determination result.

## Criteria
If the same result could be produced even without AI, it is determined PASS (the Tool User stage applies); if not and repeated interaction with AI appears, it is determined FAIL (beyond the Tool User stage).

## Derivation
[method](../../_method/aiu_stage_tool_user_method.md) -> [knowledge](../../_knowledge/aiu_stage_tool_user_knowledge.md) ->
[task](../../_task/aiu_stage_tool_user_task.md) -> [goal](../../_goal/aiu_stage_tool_user_goal.md) ->
[identity](../../_identity/AIU_STAGE_TOOL_USER.md)
