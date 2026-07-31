---
name: compfit_ethical_skill
description: Use this when, in ethically sensitive work, the bot's rule-based consistency and the human's judgment of rule legitimacy, value judgment, and social responsibility are to be divided in accordance with the ethical complementation type.
---

# Ethical complementation — Skill

## Purpose
By dividing ethical work into a bot-assigned part (the consistent application of rules) and a human-assigned part (the legitimacy of the rules themselves, value judgment, social responsibility, and context-based adjustment), ensure that the final authority to judge rule legitimacy remains with the human.

## Input
- The content of the ethically sensitive work
- The rules to be applied and the level of consistency they require
- The points at which rule legitimacy, value judgment, and social responsibility are required

## Procedure (Steps)
1. Decompose the work into elements of the consistent application of rules and elements of judging the legitimacy of the rules.
2. Assign the consistent application of rules to the bot.
3. Assign the legitimacy of the rules themselves, value judgment, social responsibility, and context-based adjustment to the human.
4. Have the bot's rule-application results pass through a final human approval procedure.

## Output
An ethical complementation result in which the bot's rule-application results are combined with the human's final judgment of rule legitimacy.

## Criteria
PASS if the bot takes charge of rule application and the human takes charge of the final judgment of rule legitimacy; FAIL if the bot autonomously decides legitimacy as well.

## Derivation
[method](../../_method/compfit_ethical_method.md) -> [knowledge](../../_knowledge/compfit_ethical_knowledge.md) ->
[task](../../_task/compfit_ethical_task.md) -> [goal](../../_goal/compfit_ethical_goal.md) ->
[identity](../../_identity/COMPFIT_ETHICAL.md)
