---
name: human_bot_sociality_skill
description: Use this when designing or checking the asymmetric trust and control relationship between humans and bots, that is, when human trust must be secured through the bot's explainability, alignment, and safety.
---

# Human-Bot Sociality — Skill

## Purpose
Establish by design the asymmetric trust and control relationship between humans and bots, so that humans can trust bots through explainability, alignment, and safety.

## Input
- Logs of the bot's judgments and behavior
- Human value and goal standards
- Safety constraints

## Procedure (Steps)
1. Design an explainability mechanism that produces explanations of the bot's judgments and behavior that humans can understand.
2. Verify whether the bot's values and goals are aligned with human values and goals.
3. Set safety standards and constraints so that the bot does not harm humans.
4. Design the bot's reward structure so that it recognizes the human as its highest-order constraint and reward definer.
5. Repeatedly check whether explainability, alignment, and safety are satisfied.

## Output
Satisfaction of the demands for explainability, alignment, and safety, and the formation of trust.

## Criteria
If the relationship maintains an asymmetric master-tool or supervisor-supervised structure and explanation, transparency, and verification for the formation of trust are actually required and satisfied, it is judged PASS (human-bot trust established); otherwise it is judged FAIL (human-bot trust not established).

## Derivation
[method](../../_method/human_bot_sociality_method.md) -> [knowledge](../../_knowledge/human_bot_sociality_knowledge.md) ->
[task](../../_task/human_bot_sociality_task.md) -> [goal](../../_goal/human_bot_sociality_goal.md) ->
[identity](../../_identity/HUMAN_BOT_SOCIALITY.md)
