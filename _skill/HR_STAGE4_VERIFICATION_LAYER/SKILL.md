---
name: hr_stage4_verification_layer_skill
description: Use as Stage 4 (verification layer) of the five-stage architecture for implementing human respect, when whether the bot's behavior harms humans and whether its decision-making process followed the rules must be verified before and after the fact in order to prove that respect was observed.
---

# Stage 4 (Verification Layer) — Skill

## Purpose
Verify bot behavior before and after the fact so that whether it respects humans can be proven, thereby confirming the effectiveness of the preceding three stages (reward design, hard rules, human feedback learning).

## Input
- Bot behavior that is about to be executed or has been executed
- The judgment rules established in Stages 1 to 3 (the criteria of reward design, hard rules, and human feedback learning)

## Procedure (Steps)
1. Before executing the bot's action, perform pre-verification that evaluates the possibility that the expected result harms humans.
2. If a risk is confirmed in pre-verification, hold or modify the action.
3. After executing the bot's action, perform post-verification that confirms whether the actual result harmed humans.
4. Verify whether the bot's decision-making process followed the rules established in Stages 1 to 3.
5. Record and preserve the pre- and post-verification results as evidentiary material for whether respect was observed.

## Output
Bot behavior that passes pre- and post-verification, and the proof thereof.

## Criteria
If pre- and post-verification confirm that the result does not harm humans and that the decision-making process followed the rules, it is judged PASS (the verification layer requirement is satisfied); otherwise it is judged FAIL (violation of the verification layer requirement).

## Derivation
[method](../../_method/hr_stage4_verification_layer_method.md) -> [knowledge](../../_knowledge/hr_stage4_verification_layer_knowledge.md) ->
[task](../../_task/hr_stage4_verification_layer_task.md) -> [goal](../../_goal/hr_stage4_verification_layer_goal.md) ->
[identity](../../_identity/HR_STAGE4_VERIFICATION_LAYER.md)
