---
name: os_privacy_sovereignty_skill
description: Used to check whether the OS for organizational AX blocks the risk of internal information (data and context) leaking in the course of connecting to external LLMs (ChatGPT, Claude, Gemini, and the like) and thereby preserves the organization's data sovereignty.
---

# Privacy & sovereignty — Skill

## Purpose
Discern whether external AI is leveraged without losing the organization's data and decision-making sovereignty — that is, whether the risk of internal information leaking through external LLM connections is blocked.

## Input
- The list of external LLMs to which the organization connects and the modes of connection
- The results of checking the possibility of internal data and context exposure along each connection path

## Procedure (Steps)
1. Identify all the external LLM connection points.
2. Check the possibility of internal information (data and context) leaking at each connection point.
3. Confirm whether blocking measures have been applied to the paths where leakage is possible.
4. Judge comprehensively whether the benefits of leveraging external AI and the preservation of organizational sovereignty hold at the same time.

## Output
The result of the privacy and sovereignty check (no leakage risk | leakage risk present, blocking measures required), and the judgment on the preservation of organizational sovereignty.

## Criteria
PASS is judged when the possibility of internal information leakage is substantially blocked and the organization's sovereignty is preserved.

## Derivation
[method](../../_method/os_privacy_sovereignty_method.md) -> [knowledge](../../_knowledge/os_privacy_sovereignty_knowledge.md) ->
[task](../../_task/os_privacy_sovereignty_task.md) -> [goal](../../_goal/os_privacy_sovereignty_goal.md) ->
[identity](../../_identity/OS_PRIVACY_SOVEREIGNTY.md)
