---
name: bstress_computational_overload_skill
description: Used to determine whether a case falls under the computational overload stress a bot enters when it exceeds the limits of its processing capacity, and to produce mitigation measures.
---

# Computational Overload — Skill

## Purpose
Determine whether a bot's anomaly falls under computational overload among the bot stress types (5 types), and provide the grounds for cause-specific mitigation measures.

## Input
- Logs of the bot's parallel task throughput, context window utilization, memory utilization, token consumption, and response latency
- Observed indicators of bot output quality (response quality, occurrence of hallucination, reasoning failure, whether task collapse occurred)

## Procedure (Steps)
1. Confirm whether the bot anomaly is associated with one or more of excessive parallel processing, context overflow, memory saturation, token limitation, or increased latency.
2. Confirm whether the results of degraded response quality, increased hallucination, reasoning failure, or task collapse accompany it.
3. If both conditions are confirmed, judge it computational overload.
4. Produce the priority of mitigation measures per cause of overload (parallel processing, context, memory, token, latency).

## Output
The judgment result of whether the target bot's state falls under computational overload, and the priority of mitigation measures per cause.

## Criteria
It is judged PASS (computational overload) when one or more of excessive parallel processing, context overflow, memory saturation, token limitation, or increased latency is confirmed together with one or more of degraded response quality, hallucination, reasoning failure, or task collapse, and FAIL (another bot stress type) otherwise.

## Derivation
[method](../../_method/bstress_computational_overload_method.md) -> [knowledge](../../_knowledge/bstress_computational_overload_knowledge.md) ->
[task](../../_task/bstress_computational_overload_task.md) -> [goal](../../_goal/bstress_computational_overload_goal.md) ->
[identity](../../_identity/BSTRESS_COMPUTATIONAL_OVERLOAD.md)
