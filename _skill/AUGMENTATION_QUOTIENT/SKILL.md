---
name: augmentation_quotient_skill
description: Use this when the Augmentation Quotient (AQ), which combines the degree of role-centered use, the level of collaboration, and the level of governance compliance that a member's AI Utilization (AIU) alone does not capture, must be produced.
---

# Augmentation Quotient (AQ) — Skill

## Purpose
It extends AI Utilization (AIU) into the higher-order indicator, the Augmentation Quotient (AQ), to measure "how well one collaborates with AI", and secures the input for calculating the Augmented Human Index (AHI).

## Input
- The member's AIU (AI Utilization) value
- Evaluation data for Role Alignment (the degree of role-centered use)
- Evaluation data for Collaboration (the level of human-bot collaboration)
- Evaluation data for Governance (the level of ethics/security/approval compliance)

## Procedure (Steps)
1. Confirm the AIU value.
2. Evaluate Role Alignment.
3. Evaluate Collaboration.
4. Evaluate Governance.
5. Multiply the four values to compute AQ = AIU x Role Alignment x Collaboration x Governance.

## Output
An AQ calculation table (including the evaluation records of the four components) and the AQ value for input to the AHI calculation.

## Criteria
If all four components are secured and AQ is produced by the product operation, it is judged PASS; if even one is missing, it is judged FAIL (re-measurement needed).

## Derivation
[method](../../_method/augmentation_quotient_method.md) -> [knowledge](../../_knowledge/augmentation_quotient_knowledge.md) ->
[task](../../_task/augmentation_quotient_task.md) -> [goal](../../_goal/augmentation_quotient_goal.md) ->
[identity](../../_identity/AUGMENTATION_QUOTIENT.md)
