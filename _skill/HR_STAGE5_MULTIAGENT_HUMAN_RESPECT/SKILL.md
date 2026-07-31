---
name: hr_stage5_multiagent_human_respect_skill
description: Use when the risk that bots collaborate (collude) with one another and ignore humans in a multi-bot (multi-agent) environment must be detected and blocked, applying human-weighted reward, human priority override, and anti-collusion rules as Stage 5 (human respect in multi-agent environments) of the five-stage architecture for implementing human respect.
---

# Stage 5 (Human Respect in Multi-agent Environments) — Skill

## Purpose
Safely extend Stages 1 to 4, which assume a single bot, to a multi-bot environment by preventing situations in which bots collaborate (collude) with one another and ignore humans in an environment where many bots are active.

## Input
- Interaction logs among multiple bots
- Criteria for identifying tasks with a large impact on humans

## Procedure (Steps)
1. Collect interaction logs from the multi-bot environment and detect patterns in which bot-to-bot optimization ignores human-related signals.
2. Identify tasks with a large impact on humans and apply a human-weighted reward that raises the reward weight of those tasks.
3. Implement a human priority override rule so that human-related signals always take precedence over bot-to-bot optimization objectives.
4. Establish a monitoring system that detects bot-to-bot collaboration (collusion) patterns that could cause harm to humans.
5. When collusion is detected, apply the anti-collusion rules to block that collaboration.

## Output
The application of human-weighted reward, human priority override, and anti-collusion rules.

## Criteria
If, in a multi-bot environment, bot-to-bot optimization is not prioritized over human-related signals and no collusion occurs, it is judged PASS (the multi-agent human respect requirement is satisfied); otherwise it is judged FAIL (violation of the multi-agent human respect requirement).

## Derivation
[method](../../_method/hr_stage5_multiagent_human_respect_method.md) -> [knowledge](../../_knowledge/hr_stage5_multiagent_human_respect_knowledge.md) ->
[task](../../_task/hr_stage5_multiagent_human_respect_task.md) -> [goal](../../_goal/hr_stage5_multiagent_human_respect_goal.md) ->
[identity](../../_identity/HR_STAGE5_MULTIAGENT_HUMAN_RESPECT.md)
