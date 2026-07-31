---
name: contribution_conflict_skill
description: Use this when it must be determined whether, in communication between augmented human and augmented human (AH-AH), there exists a contribution conflict in which the criteria, interpretation, verification state, and responsibility judgment for the same message differ.
---

# Contribution conflict — Skill

## Purpose
Determine whether, in AH-AH communication, there exists a contribution conflict in which the criteria, interpretation, verification state, and responsibility judgment for the same message diverge among participants, and provide the grounds for choosing an adjustment path.

## Input
- The target communication situation (the judgments of augmented human A and augmented human B on the same message)

## Procedure (Steps)
1. Compare the criteria and interpretation of side A and side B for the same message.
2. Confirm the difference in the judgment of the verification state.
3. Confirm the difference in the responsibility judgment as to whether it can be shared.
4. If a difference is confirmed, judge it a contribution conflict.

## Output
The identification of contribution conflict — the definition of the conflict point that becomes important in AH-AH communication, superseding the role vacancy.

## Criteria
It is judged PASS (a contribution conflict exists) when one or more of the criteria, interpretation, verification state, and responsibility judgment diverge between side A and side B, and FAIL (no contribution conflict) when they all agree.

## Derivation
[method](../../_method/contribution_conflict_method.md) -> [knowledge](../../_knowledge/contribution_conflict_knowledge.md) ->
[task](../../_task/contribution_conflict_task.md) -> [goal](../../_goal/contribution_conflict_goal.md) ->
[identity](../../_identity/CONTRIBUTION_CONFLICT.md)
