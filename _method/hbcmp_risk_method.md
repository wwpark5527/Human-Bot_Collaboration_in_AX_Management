---
identity: HBCMP_RISK
displayName: "Risk"
runID: 20260719_164605
derivedFromIdentity: ../_identity/HBCMP_RISK.md
---

# Risk — Method

## Method / Procedure
1. Confirm whether the agent whose state has not improved even after a recovery prescription was applied is a human or a bot.
2. If human, confirm which risk sign among depression, intent to leave, or resistance has appeared.
3. If a bot, confirm which risk sign between Hallucination and system failure has appeared.
4. Once a risk sign is confirmed, escalate immediately to the higher intervention procedure.

## Criteria
If one of depression, turnover, or resistance is confirmed, it is judged PASS (escalation required) as a human stress risk, and if one of hallucination or system failure is confirmed, it is judged PASS (escalation required) as a bot stress risk. If no risk sign is confirmed, it is judged FAIL (risk undetermined, continued observation).

## Derivation
[identity](../_identity/HBCMP_RISK.md)
