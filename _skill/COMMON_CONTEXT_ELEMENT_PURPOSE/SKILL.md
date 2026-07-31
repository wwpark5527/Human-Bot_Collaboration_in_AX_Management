---
name: common_context_element_purpose_skill
description: Use this when it is necessary to inspect whether the reason the organization uses AI is defined in advance in the organization's language, that is, whether the purpose component of the common context is in place.
---

# Purpose — Skill

## Purpose
Judge whether a purpose standard is in place that specifies, in the organization's own language, the reason the organization uses AI, so that AI does not have to guess the purpose of the work every time.

## Input
- A list of the organization's areas of work (customer service, education, legal affairs, marketing, development, management reporting, etc.)
- Materials related to the purpose of AI use by area of work

## Procedure (Steps)
1. Identify the areas of work in which the organization uses AI.
2. Collect the reasons AI is used in each area of work.
3. Organize the collected reasons in the organization's own language and turn them into a purpose statement.
4. Judge whether the purpose statement is defined in advance in the organization's language.

## Output
The judgment result on the organization's own AI-use purpose statement (a purpose standard so that AI does not have to guess with every request).

## Criteria
A PASS judgment is made when, for the work assigned to AI, 'why this work is done' is defined in advance in the organization's language; a FAIL judgment is made when it is not defined.

## Derivation
[method](../../_method/common_context_element_purpose_method.md) -> [knowledge](../../_knowledge/common_context_element_purpose_knowledge.md) ->
[task](../../_task/common_context_element_purpose_task.md) -> [goal](../../_goal/common_context_element_purpose_goal.md) ->
[identity](../../_identity/COMMON_CONTEXT_ELEMENT_PURPOSE.md)
