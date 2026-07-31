---
name: hbs_prev_human_as_reviewer_skill
description: Use this when determining whether the human adopts AI output as it is, or treats it as a judge and verifier through interpretation, verification, and adjustment.
---

# Humans must be reviewers of AI output, not consumers — Skill

## Purpose
Confirm whether the human, rather than accepting AI-produced results as they are, carries out the reviewer role of interpreting, verifying, and adjusting them, and thereby prevent the 'consumer' attitude of accepting AI results uncritically.

## Input
- The AI output that arose in the target work
- Whether the human's interpretation, verification, and adjustment of that output were carried out, and the records thereof

## Procedure (Steps)
1. Confirm the points in the target work where AI output arises.
2. Confirm whether there is a step in which the human interprets that output.
3. Confirm whether there is a step in which the human verifies that output.
4. Confirm whether there is a step in which the human adjusts it when necessary, and make an overall judgment.

## Output
The status of the human's interpretation, verification, and adjustment of AI output and the result of judging the reviewer/consumer role.

## Criteria
If interpretation, verification, and adjustment are all carried out, it is judged PASS (reviewer); if the output is adopted as it is, it is judged FAIL (consumer).

## Derivation
[method](../../_method/hbs_prev_human_as_reviewer_method.md) -> [knowledge](../../_knowledge/hbs_prev_human_as_reviewer_knowledge.md) ->
[task](../../_task/hbs_prev_human_as_reviewer_task.md) -> [goal](../../_goal/hbs_prev_human_as_reviewer_goal.md) ->
[identity](../../_identity/HBS_PREV_HUMAN_AS_REVIEWER.md)
