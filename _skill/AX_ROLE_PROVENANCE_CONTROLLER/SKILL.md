---
name: ax_role_provenance_controller_skill
description: Used to perform the Provenance Controller role when the provenance and processing path (traceability) of the data AI uses and generates in an AX organization must be recorded and verified.
---

# Provenance Controller — Skill

## Purpose
Secure verifiable data governance by managing the provenance and traceability of the data AI uses and generates.

## Input
- A list of the input data sources used by AI
- Logs of the processing path of the AI output generation process

## Procedure (Steps)
1. Collect the provenance metadata of the input data.
2. Record the processing path of the AI output generation process.
3. Keep the provenance and traceability records in a verifiable form.
4. Regularly check the records for omissions and errors and supplement them.

## Output
Records of data provenance and traceability.

## Criteria
If records of data provenance and traceability are produced and kept in a verifiable form, it is judged PASS; otherwise it is judged FAIL.

## Derivation
[method](../../_method/ax_role_provenance_controller_method.md) -> [knowledge](../../_knowledge/ax_role_provenance_controller_knowledge.md) ->
[task](../../_task/ax_role_provenance_controller_task.md) -> [goal](../../_goal/ax_role_provenance_controller_goal.md) ->
[identity](../../_identity/AX_ROLE_PROVENANCE_CONTROLLER.md)
