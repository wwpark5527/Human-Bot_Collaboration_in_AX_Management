---
name: stage5_stage2_patch_instruction
description: Stage5Stage2PatchInstruction — the Stage-5 corrective directive routed to Stage 2 (identity fragmentation) for the NEXT run. One directive entry for the one consolidated formula problem. Instructs the change; applies none.
---

# Stage5Stage2PatchInstruction — corrective directives routed to Stage 2

- run: the 369-candidate AX-book identity run under runRoot `/Users/gesia/wwp_book_v0.2`
- source ledger: [Stage5FeedbackLedger](./stage5_feedback_ledger.md) — 369 rows, md5 `66fc679f6d40fec2dab81d9e9e0ca764`, consumed READ-ONLY
- consolidation: [E4 ledger-wide consolidation status](./_stage5_c2/e4_ledger_wide_consolidation_status.md) (16 formula problems run-wide; 1 routed here)
- moment: 2026-07-21
- **directive entries in this file: 1**
- this is a one-shot corrective for the NEXT run's Stage 2. Nothing here is applied by Stage 5.

## Directive entries

### `PI-S2-01` — name-keyed duplicate detection with no substance test, and no KEEP×SPLIT cross-coverage check

- **PatchInstructionID**: `PI-S2-01`
- **Target**: Stage 2 — identity fragmentation (`20260719_164605_stage2_identity_fragmentation_artifact.md` in the next run's equivalent). GIVEN by the ledger's `targets` field; not re-routed here.
- **ProblemSummary**: two candidates that cover the same source substance survive as separate identities whenever their labels differ, because the duplicate/collapse test keys on normalized-name equality. Three pairs reached Stage 4 un-reconciled in this run: `COOP_TYPE_AH_PLUS_AB` / `HYBRID_ORGANIZATION` (the author declares the two names one object at source line 316, and one node's span 386-391 sits wholly inside the other's 316-431); `AUGMENTATION` / `SPIRIT_AUGMENTATION` (sourceLines doc02 219-244 identical, same primary quote, same 판정기준 and 산출); `HUMAN_AI_ORCHESTRATION` / `HUMAN_AI_ORCHESTRATION_CAPABILITY` (source line 67 is the whole span of one and is contained in the other, 판정기준 substantively equivalent). The blind spot is provable from the pipeline's own inconsistency: the structurally identical 다양성 pair WAS collapsed because its two labels differed by a single space, while the 증강 pair survived because one label carries the extra word 실현.
- **RootCause** (GIVEN, not re-diagnosed): (a) the duplicate/collapse trigger is the normalized name — all 25 pairs the downstream detector caught cite the basis "정규화 명칭 … 일치" — so a same-substance pair under different labels is structurally outside the test's reach; and (b) a candidate confirmed KEEP by the FragmentationNeed triggers is never afterwards compared against the SplitSet children the same stage goes on to create, so a KEEP-path survivor and a SPLIT-path child covering the same span are never put side by side.
- **EvidenceLinks**:
  - ledger positions **32, 33, 125** (`FEEDBACK_TO_STAGE_2`) and **38, 39** (`FEEDBACK_TO_MULTIPLE_STAGES`, Stage-2 halves) in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifacts: [WO032](./stage4_032_COOP_TYPE_AH_PLUS_AB_concept_to_skill_closure_artifact.md) · [WO033](./stage4_033_HYBRID_ORGANIZATION_concept_to_skill_closure_artifact.md) · [WO038](./stage4_038_AUGMENTATION_concept_to_skill_closure_artifact.md) · [WO039](./stage4_039_SPIRIT_AUGMENTATION_concept_to_skill_closure_artifact.md) · [WO125](./stage4_125_HUMAN_AI_ORCHESTRATION_concept_to_skill_closure_artifact.md)
  - [Stage-2 artifact](./20260719_164605_stage2_identity_fragmentation_artifact.md) — the 증강 pair's child row at line 1322 (also 366, 2480); the parent's own Kind-based Reject list at line 1318, which shows the duplicate test running inside that parent for other siblings while skipping this one
  - [4-DIAG duplicate diagnosis](./20260719_164605_stage4diag_duplicate_and_containment_diagnosis_artifact.md) — the 25-pair table whose basis column is name equality throughout
  - **binding correction**: the Stage-2 child of `SPIRIT_AUGMENTATION` is **`S2C-0189`**. Ledger row 38's prose names `S2C-0188`, which is a *different sibling* of the same parent `S2C-0026` (인간중심 정신, same artifact line 868). Any patch derived from row 38 must aim at `S2C-0189`; inheriting `S2C-0188` would target the wrong candidate.
- **FailureMode**: a name-keyed test cannot see a substance duplicate, and an unexecuted cross-path comparison cannot produce a verdict; the pair therefore arrives at Stage 4 with no adjudication record, and Stage 4 — having nothing to inherit — writes a distinction claim of its own (see `PI-S4-13`). Severing the link means testing substance, and testing it across both survival paths.
- **ChangeSite** (one element inside the routed target): the **formula** that decides duplicate/collapse, together with its cross-path coverage step.
- **CurrentRuleOrFormula**: two candidates are compared for duplication when their normalized names match; a candidate that passes the FragmentationNeed triggers is settled KEEP without any later comparison against SplitSet children created in the same stage.
- **RequiredChange**: change the decision formula so duplication is judged by substance, not by label. Concretely: (1) test a pair as duplicate-suspect when **sourceLines overlap** (any containment or intersection) **AND** 판정기준 and 산출 are substantively equivalent — never by display-name or normalized-name string; (2) run that test across survival paths: after the SplitSet children of a parent are created, compare each child against every already-KEEP candidate whose span overlaps it, and record the verdict; (3) where the author's own text declares two labels to be one object, treat that declaration as decisive evidence of a single identity and record the collapse with the citation; (4) when a pair passes the test as distinct, write the *reason* into the settled record — an assertion of distinction with no recorded 판정기준/산출 difference is not a verdict. For this run's three pairs, the adjudication owed is: `AH + AB` vs `하이브리드 조직` (author line 316), `증강` vs `증강 실현` (`S2C-0021` vs **`S2C-0189`**, span 219-244 identical), and `인간-AI 오케스트레이션` vs `…능력` (line 67 contained).
- **AcceptanceCriteria**: in the next run, every pair whose sourceLines overlap and whose 판정기준/산출 are equivalent carries an explicit recorded verdict (collapse, or distinct-with-stated-difference); no such pair reaches Stage 4 with zero adjudication record; the three named pairs are each settled one way or the other with cited evidence.
- **NextRunExpectedEffect**: same-substance pairs are collapsed or explicitly distinguished at the stage that owns fragmentation, so Stage 4 never has to invent a distinction, and the downstream name-keyed detector stops being the last line of defence.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the duplicate/collapse decision formula and its cross-path comparison step. Do NOT retro-edit this run's sealed Stage-2 artifact, do not delete or revive candidates in this run, do not alter the excluded-OverBroadParent linkage form (which is the correct specified form), and do not touch the sealed ledger rows.
- **Status**: recorded and handed off for the next run to carry out — never applied here.

## Contributing ledger rows

| PatchInstructionID | ledger positions (READ-ONLY provenance) | candidates |
|---|---|---|
| `PI-S2-01` | 32, 33, 125, 38 (Stage-2 half), 39 (Stage-2 half) | WO032, WO033, WO125, WO038, WO039 |

Rows 38 and 39 are `FEEDBACK_TO_MULTIPLE_STAGES`; their Stage-4 halves are carried by `PI-S4-13` in the Stage-4 file, not here.

## Links

- sourceLedger -> [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
- consolidatedBy -> [E4 ledger-wide consolidation status](./_stage5_c2/e4_ledger_wide_consolidation_status.md)
- mintedBy -> [E5 directive entries record](./_stage5_c2/e5_directive_entries_record.md)
- referencedBy -> the run seed packet `stage5_next_run_seed_packet.md`, which references this file by PatchInstructionID (that packet is authored and landed downstream of this file; the resolvable direction is seed -> instruction)
- siblingFile -> [Stage5Stage1PatchInstruction](./stage5_stage1_patch_instruction.md)
- siblingFile -> [Stage5Stage3PatchInstruction](./stage5_stage3_patch_instruction.md)
- siblingFile -> [Stage5Stage4PatchInstruction](./stage5_stage4_patch_instruction.md)
