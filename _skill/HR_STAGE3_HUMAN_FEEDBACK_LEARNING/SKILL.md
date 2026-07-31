---
name: hr_stage3_human_feedback_learning_skill
description: Use as Stage 3 (human feedback learning) of the five-stage architecture for implementing human respect, when human feedback data on whether the bot's behavior respects humans must be accumulated using RLHF/RLAIF and subtle social context must be taught.
---

# Stage 3 (Human Feedback Learning) — Skill

## Purpose
Use RLHF/RLAIF to accumulate learning data on whether behavior respects humans, so that the bot learns the subtle social context that hard rules alone cannot easily address.

## Input
- Cases of the bot's behavior
- Human evaluators' judgments of "this is human respect / this is not"

## Procedure (Steps)
1. Have human evaluators judge "this is human respect / this is not" for cases of the bot's behavior.
2. Accumulate the judgment results in the form of learning data that can be fed into an RLHF/RLAIF pipeline.
3. Label honest-answer cases and manipulative/deceptive-process cases separately.
4. Update the bot's behavior policy with the accumulated data, and verify whether subtle social context is reflected.
5. Reconfirm that the updated policy allows honest answers and suppresses manipulative/deceptive processes.

## Output
The learning of subtle social context (an honest answer is allowed; process/manipulation is not).

## Criteria
If learning is reflected in the direction of allowing honest answers and suppressing manipulative/deceptive processes, it is judged PASS (the human feedback learning requirement is satisfied); otherwise it is judged FAIL (violation of the human feedback learning requirement).

## Derivation
[method](../../_method/hr_stage3_human_feedback_learning_method.md) -> [knowledge](../../_knowledge/hr_stage3_human_feedback_learning_knowledge.md) ->
[task](../../_task/hr_stage3_human_feedback_learning_task.md) -> [goal](../../_goal/hr_stage3_human_feedback_learning_goal.md) ->
[identity](../../_identity/HR_STAGE3_HUMAN_FEEDBACK_LEARNING.md)
