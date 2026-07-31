---
name: communication_type_ah_to_h_skill
description: Use this when it is necessary to judge whether the six fairness requirements (disclosing AI intervention, distinguishing judgment, notifying recording, etc.) are satisfied in asymmetric communication between an augmented human and a non-augmented human.
---

# AH-H communication — Skill

## Purpose
Judge whether the fairness requirements are satisfied in asymmetric communication between an augmented human (A) and a non-augmented human (B), so that a role vacancy is not concealed.

## Input
- The target communication situation (an exchange of messages between augmented human A and non-augmented human B)

## Procedure (Steps)
1. Identify the participants as an augmented human (A) and a non-augmented human (B).
2. Disclose to B whether AI intervened.
3. Present AI-generated content and human judgment as distinct.
4. Notify whether B's utterances are recorded and limit the scope of analysis.
5. Have a human re-confirm important agreements and specify the party bearing final responsibility.

## Output
Asymmetric communication and the six fairness requirements that follow from it (disclosing whether AI intervened, distinguishing AI-generated content from human judgment, notifying whether the counterpart's utterances are recorded, limiting the scope of analysis of the counterpart's utterances, human re-confirmation of important agreements, specifying the party bearing final responsibility).

## Criteria
A PASS judgment is made when all six fairness requirements are satisfied; a FAIL judgment is made when even one is not satisfied.

## Derivation
[method](../../_method/communication_type_ah_to_h_method.md) -> [knowledge](../../_knowledge/communication_type_ah_to_h_knowledge.md) ->
[task](../../_task/communication_type_ah_to_h_task.md) -> [goal](../../_goal/communication_type_ah_to_h_goal.md) ->
[identity](../../_identity/COMMUNICATION_TYPE_AH_TO_H.md)
