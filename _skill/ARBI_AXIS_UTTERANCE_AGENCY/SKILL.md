---
name: arbi_axis_utterance_agency_skill
description: Use this when evaluating whether the agent of judgment and utterance is the human, the AI, or a joint output in a collaboration the AI intervened in, that is, ARBI's Utterance Agency axis.
---

# Utterance Agency — Skill

## Purpose
It traces the generation process of the individual utterances and judgments made in the collaboration and attributes their agent to the human, the AI, or a joint output.

## Input
- Records of the collaboration's utterances and judgments
- Information on the generation process of each utterance and judgment (who drafted it, who finalized it)

## Procedure (Steps)
1. Separate the individual utterance and judgment units.
2. Trace the generation process of each unit.
3. Classify each as human alone, AI alone, or joint output.
4. Produce a judgment on the attribution of the agent of the utterance.

## Output
A judgment on the attribution of the agent of an utterance or judgment.

## Criteria
If the agent of every utterance and judgment is clearly attributed, it is judged PASS; if the attribution is unclear, it is judged FAIL.

## Derivation
[method](../../_method/arbi_axis_utterance_agency_method.md) -> [knowledge](../../_knowledge/arbi_axis_utterance_agency_knowledge.md) ->
[task](../../_task/arbi_axis_utterance_agency_task.md) -> [goal](../../_goal/arbi_axis_utterance_agency_goal.md) ->
[identity](../../_identity/ARBI_AXIS_UTTERANCE_AGENCY.md)
