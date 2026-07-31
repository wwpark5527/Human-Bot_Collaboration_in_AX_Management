---
name: role_vacancy_skill
description: Use this when it must be determined whether, in communication between an augmented human and a non-augmented human (AH-H), a role vacancy exists in which the interpretation, verification, recording, and response roles are empty on the non-augmented side.
---

# Role vacancy — Skill

## Purpose
This determines whether a role vacancy in which the interpretation, verification, recording, and response roles are lacking exists on the non-augmented side (B) in AH-H communication, and defines it as a fairness problem.

## Input
- The target communication situation (message exchange between augmented human A and non-augmented human B)

## Procedure (Steps)
1. Divide the participants into A (augmented) and B (non-augmented).
2. Confirm whether the four roles on side A (purpose and judgment · analysis and generation · criteria · history management) are in place.
3. Check whether the interpretation, verification, recording, and response roles are lacking on side B.
4. When a deficiency is confirmed, judge it as role vacancy and record it as a fairness problem.

## Output
Identification of role vacancy — a state defined not as mere inconvenience but as a problem of communication fairness (communication power).

## Criteria
It is judged PASS (role vacancy exists) if one or more of interpretation, verification, recording, and response is empty on side B, and FAIL (no role vacancy) if all are filled.

## Derivation
[method](../../_method/role_vacancy_method.md) -> [knowledge](../../_knowledge/role_vacancy_knowledge.md) ->
[task](../../_task/role_vacancy_task.md) -> [goal](../../_goal/role_vacancy_goal.md) ->
[identity](../../_identity/ROLE_VACANCY.md)
