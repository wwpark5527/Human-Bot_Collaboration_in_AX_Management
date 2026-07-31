---
name: bstress_multi_agent_coop_skill
description: Used to determine whether a case falls under the multi-agent cooperation stress that arises in the process of cooperation among agents in a multi-agent system.
---

# Multi-agent cooperation stress — Skill

## Purpose
Determine whether an anomaly in a multi-agent system falls under multi-agent cooperation stress among the bot stress types (5 types), and provide the grounds for establishing rules of priority and decision rights.

## Input
- Logs of interaction among agents within the multi-agent system (records of coordination, communication, and authority distribution)
- Observed cases of coordination failure, communication overload, and authority ambiguity

## Procedure (Steps)
1. Confirm whether the stress originates not from a single agent but from the process of cooperation among agents.
2. Confirm whether there is coordination failure, communication overload, or authority ambiguity.
3. Confirm whether it is unclear which agent has priority and who decides when judgments conflict.
4. Synthesize the confirmed characteristics and judge whether it is multi-agent cooperation stress.

## Output
The judgment result of whether the target multi-agent situation falls under multi-agent cooperation stress, and a proposal for rules of priority and decision rights.

## Criteria
It is judged PASS (multi-agent cooperation stress) when one or more of coordination failure, communication overload, or authority ambiguity among agents is confirmed, and FAIL (another bot stress type) otherwise.

## Derivation
[method](../../_method/bstress_multi_agent_coop_method.md) -> [knowledge](../../_knowledge/bstress_multi_agent_coop_knowledge.md) ->
[task](../../_task/bstress_multi_agent_coop_task.md) -> [goal](../../_goal/bstress_multi_agent_coop_goal.md) ->
[identity](../../_identity/BSTRESS_MULTI_AGENT_COOP.md)
