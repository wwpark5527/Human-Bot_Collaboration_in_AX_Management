---
name: bot_level4_verifier_governor_skill
description: Used when designing and deploying the top-level hierarchy role in a multi-bot/agent ecosystem, and a Verifier/Governor function is needed that verifies the output results of lower agents, judges whether something is factual (true), and controls policy.
---

# Level 4 Verifier/Governor — Skill

## Purpose
Implement, at the top level of the bot hierarchy, the functions of verifying the results of lower agents, judging factuality, and controlling policy.

## Input
- Deliverables of lower-hierarchy agents (Level 1-3)
- The organization's verification criteria and policy criteria

## Procedure (Steps)
1. Collect the deliverables produced by lower-hierarchy agents.
2. Judge whether the deliverables are factual (true) according to the verification criteria.
3. If the judgment result falls short of the criteria, reject it or request revision; if it meets the criteria, approve it.
4. Control the authority and behavioral scope of lower agents in accordance with organizational policy.
5. Record the verification and control history.

## Output
Verification judgment records, policy control logs, error and hallucination rejection/revision history.

## Criteria
It is judged PASS (the Verifier/Governor role is performed) when the functions of verifying results, judging factuality, and controlling policy are actually performed, and FAIL (the role is not performed) when verification and control do not take place.

## Derivation
[method](../../_method/bot_level4_verifier_governor_method.md) -> [knowledge](../../_knowledge/bot_level4_verifier_governor_knowledge.md) ->
[task](../../_task/bot_level4_verifier_governor_task.md) -> [goal](../../_goal/bot_level4_verifier_governor_goal.md) ->
[identity](../../_identity/BOT_LEVEL4_VERIFIER_GOVERNOR.md)
