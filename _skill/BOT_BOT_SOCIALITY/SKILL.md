---
name: bot_bot_sociality_skill
description: Use this when designing or checking symmetric cooperation strategies, reputation, and hierarchy between bots, that is, when the game-theoretic reward structure of bot-bot interaction and its internal risks (collusion, reward hacking, and so on) must be handled.
---

# Bot-Bot Sociality — Skill

## Purpose
Establish symmetric interaction between bots as a game-theoretic and strategic cooperation system, so that a natural hierarchy and cooperation strategies based on reward and reputation form.

## Input
- Interaction logs between bots
- Reward and penalty rules
- Reputation history data

## Procedure (Steps)
1. Design a game-theoretic reward structure for interaction between bots in which cooperation increases reward and defection incurs a penalty.
2. Build a system that accumulates the history of a bot's past behavior and reflects it in a reputation score.
3. Ensure that a planner/executor/verifier-style role hierarchy forms naturally within interaction.
4. Detect and block signs of collusion, system distortion, and reward hacking.
5. Repeatedly check whether cooperation strategies, reputation, and hierarchy actually operate.

## Output
Cooperation strategies and reputation, and the formation of a natural planner/executor/verifier-style hierarchy.

## Criteria
If the relationship is maintained as symmetric and cooperation strategies, reputation, and hierarchy based on efficiency, reward, and optimization actually form, it is judged PASS (bot-bot cooperation established); if signs of internal collapse such as collusion, distortion, or reward hacking appear, it is judged FAIL (bot-bot cooperation collapsed).

## Derivation
[method](../../_method/bot_bot_sociality_method.md) -> [knowledge](../../_knowledge/bot_bot_sociality_knowledge.md) ->
[task](../../_task/bot_bot_sociality_task.md) -> [goal](../../_goal/bot_bot_sociality_goal.md) ->
[identity](../../_identity/BOT_BOT_SOCIALITY.md)
