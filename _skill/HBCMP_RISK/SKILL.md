---
name: hbcmp_risk_skill
description: Used when determining whether an unrecovered human or bot stress case constitutes a risk of the depression, turnover, and resistance family or of the hallucination and system failure family.
---

# Risk — Skill

## Purpose
It classifies the risk type of a stress case that has failed to recover according to the 'risk' axis of the human stress vs bot stress comparison structure, thereby providing the grounds for judging the necessity of emergency intervention.

## Input
- Information on the agent that has not improved even though a recovery prescription was applied (human/bot)
- The observed risk signs (descriptions related to depression, turnover, and resistance, or descriptions related to hallucination and system failure)

## Procedure (Steps)
1. Confirm whether the agent is a human or a bot.
2. If a human, confirm which sign among depression, intent to leave, or resistance has appeared.
3. If a bot, confirm which sign between Hallucination and system failure has appeared.
4. Produce the confirmed risk as the risk value and judge whether to escalate.

## Output
The classification result of the risk type of the target case (depression/turnover/resistance or hallucination/system failure) and whether escalation is required.

## Criteria
If one of depression, turnover, or resistance is confirmed it is judged PASS (human stress risk, escalation required), if one of hallucination or system failure is confirmed it is judged PASS (bot stress risk, escalation required), and if neither is confirmed it is judged FAIL (risk undetermined).

## Derivation
[method](../../_method/hbcmp_risk_method.md) -> [knowledge](../../_knowledge/hbcmp_risk_knowledge.md) ->
[task](../../_task/hbcmp_risk_task.md) -> [goal](../../_goal/hbcmp_risk_goal.md) ->
[identity](../../_identity/HBCMP_RISK.md)
