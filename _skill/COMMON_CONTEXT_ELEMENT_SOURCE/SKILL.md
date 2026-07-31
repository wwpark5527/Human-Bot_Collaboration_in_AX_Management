---
name: common_context_element_source_skill
description: Use this when it is necessary to inspect whether the source of the materials AI relied on as grounds is verifiable and whether the source, standards, revisions, and approval process can be traced after the fact, that is, whether the source component of the common context is in place.
---

# Source — Skill

## Purpose
Inspect the sources of the grounding materials of AI outputs and whether they have been verified, and judge whether verifiability is secured.

## Input
- A list of the materials AI outputs relied on as grounds
- Materials on the verification status of each source and its revision and approval history

## Procedure (Steps)
1. Identify the sources of the grounding materials of the AI outputs.
2. Confirm whether each source has been verified.
3. Inspect whether the source, standards, revisions, and approval process can be traced.
4. Judge whether verifiability is secured.

## Output
The judgment result on verifiability (outputs whose grounds and citations can be traced).

## Criteria
A PASS judgment is made when the source, standards, revisions, and approval process can be confirmed after the fact and the accurate source and the original-text confirmation process are built into the system; otherwise, a FAIL judgment is made.

## Derivation
[method](../../_method/common_context_element_source_method.md) -> [knowledge](../../_knowledge/common_context_element_source_knowledge.md) ->
[task](../../_task/common_context_element_source_task.md) -> [goal](../../_goal/common_context_element_source_goal.md) ->
[identity](../../_identity/COMMON_CONTEXT_ELEMENT_SOURCE.md)
