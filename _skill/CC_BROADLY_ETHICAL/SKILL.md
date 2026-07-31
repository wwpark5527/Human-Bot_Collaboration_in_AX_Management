---
name: cc_broadly_ethical_skill
description: Used when the judgment and behavior of a bot (AI model) must be designed or inspected for whether it satisfies the broadly ethical core value of the Claude Constitution.
---

# Broadly Ethical — Skill

## Purpose
Discipline the bot to make ethical judgments on its own, and thereby realize broadly ethical, one of the four core values required by the Claude Constitution.

## Input
- Scenarios of the bot's judgment and behavior
- The criteria of the four core values of the Claude Constitution (broadly safe, broadly ethical, helpfulness, compliance with guidelines)

## Procedure (Steps)
1. Review broadly the various situations to which the bot's judgment may be exposed, and define the ethical requirements.
2. Design ethical judgment logic that explicitly expresses the reason for a behavior.
3. Verify whether the designed judgment logic conforms to the broadly ethical requirement in actual situations.
4. Confirm that it does not conflict with the remaining core values such as broadly safe, helpfulness, and compliance with guidelines.
5. Reflect a constitutional design so that the bot can learn and explain on its own the reason why it must be ethical.

## Output
Ethical judgment grounded in the reason why the behavior should be taken.

## Criteria
It is judged PASS (broadly ethical satisfied) when the model's behavior conforms to the broadly ethical requirement and ethical judgment grounded in that reason is confirmed, and FAIL (violation of broadly ethical) when behavior that does not conform to the requirement is found.

## Derivation
[method](../../_method/cc_broadly_ethical_method.md) -> [knowledge](../../_knowledge/cc_broadly_ethical_knowledge.md) ->
[task](../../_task/cc_broadly_ethical_task.md) -> [goal](../../_goal/cc_broadly_ethical_goal.md) ->
[identity](../../_identity/CC_BROADLY_ETHICAL.md)
