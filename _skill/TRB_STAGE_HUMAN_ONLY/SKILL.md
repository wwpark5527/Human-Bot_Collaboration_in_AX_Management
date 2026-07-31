---
name: trb_stage_human_only_skill
description: Use when diagnosing an organization's TRB (Team Role Balance) evolution stage, in order to determine whether it is the starting stage (Human-only TRB) in which the object of role balance is limited to a human + human team and no bot has entered as a role actor.
---

# Human-only TRB — Skill

## Purpose
It identifies whether an organization's TRB is at the starting stage of the evolution path, that is, in the state of a human-centered TRB that deals only with role balance among humans.

## Input
- The list of the team's role actors (human/bot distinction)
- Information on the team's role assignment and organizational structure

## Procedure (Steps)
1. Confirm the list of the team's role actors.
2. Check whether any bot is included as a role actor.
3. Limit the scope of the role balance analysis to a human + human team.
4. Produce human role balance on the basis of a job-based organization, static roles, and individual capability.

## Output
A human role balance output having the characteristics of a job-based organization, static roles, and individual capability.

## Criteria
If the object of role balance is limited to a human + human team and no bot has entered as a role actor, it is judged PASS; if a bot is confirmed as a role actor, it is judged FAIL.

## Derivation
[method](../../_method/trb_stage_human_only_method.md) -> [knowledge](../../_knowledge/trb_stage_human_only_knowledge.md) ->
[task](../../_task/trb_stage_human_only_task.md) -> [goal](../../_goal/trb_stage_human_only_goal.md) ->
[identity](../../_identity/TRB_STAGE_HUMAN_ONLY.md)
