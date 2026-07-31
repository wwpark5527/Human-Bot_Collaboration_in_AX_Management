---
name: stage5_stage1_patch_instruction
description: Stage5Stage1PatchInstruction — the Stage-5 corrective directives routed to Stage 1 (source-linked identity extraction) for the NEXT run. Two directive entries, one per consolidated formula problem. Instructs changes; applies none.
---

# Stage5Stage1PatchInstruction — corrective directives routed to Stage 1

- run: the 369-candidate AX-book identity run under runRoot `/Users/gesia/wwp_book_v0.2`
- source ledger: [Stage5FeedbackLedger](./stage5_feedback_ledger.md) — 369 rows, md5 `66fc679f6d40fec2dab81d9e9e0ca764`, consumed READ-ONLY
- consolidation: [E4 ledger-wide consolidation status](./_stage5_c2/e4_ledger_wide_consolidation_status.md) (16 formula problems run-wide; 2 routed here)
- moment: 2026-07-21
- **directive entries in this file: 2**
- these are one-shot correctives for the NEXT run's Stage 1. Nothing here is applied by Stage 5.

## Directive entries

### `PI-S1-01` — unresolved `SD-??` source-document placeholder in provenance fields

- **PatchInstructionID**: `PI-S1-01`
- **Target**: Stage 1 — source-linked identity extraction (`20260719_164605_stage1_source_linked_identity_extraction_artifact.md` in the next run's equivalent). GIVEN by the ledger's `targets` field; not re-routed here.
- **ProblemSummary**: Stage 1 writes the literal token `SD-??` where a SourceDocumentID belongs, in the SourceUnit (SU) registry rows and in the C0 roster's `sourceLines` secondary-source segments. Because a real registry `SD-01`..`SD-12` exists in the same artifact, `??` is an unfilled reference, not a notation convention. Stage 4 then transcribes the token verbatim into closure artifacts, so an unresolved placeholder is sealed into provenance.
- **RootCause** (GIVEN, not re-diagnosed): the extraction formula that fills a secondary/cross-document reference does not look the document up in Stage-1's own `SD-01`..`SD-12` registry; it emits `SD-??` and the record is confirmed in that state. This is a run-wide formula defect, not a per-element typo — the same shape recurs across the whole SU/SP channel.
- **EvidenceLinks**:
  - ledger positions **168, 195, 197, 240, 267, 280** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md) (right-indexed fields; each row's evidence cell carries the artifact line and the Stage-1 line it came from)
  - charged closure artifacts: [WO168](./stage4_168_HBRM_ROLE_MEMBER_DEFINITION_concept_to_skill_closure_artifact.md) · [WO195](./stage4_195_AUGMENTED_HUMAN_CAPABILITY_INDEX_concept_to_skill_closure_artifact.md) · [WO197](./stage4_197_TEAM_ROLE_BALANCE_concept_to_skill_closure_artifact.md) · [WO240](./stage4_240_ARBI_concept_to_skill_closure_artifact.md) · [WO267](./stage4_267_AI_GOVERNANCE_concept_to_skill_closure_artifact.md) · [WO280](./stage4_280_KNOWLEDGE_ACTION_CHAIN_NODE_KNOWLEDGE_concept_to_skill_closure_artifact.md)
  - in-scope but uncharged (appended before the charging policy existed, NO_FEEDBACK_NEEDED on the immutable ledger — a recorded inconsistency): [WO017](./stage4_017_DOMAIN_CONTEXT_concept_to_skill_closure_artifact.md) · [WO043](./stage4_043_SUPPLEMENTARY_FIT_concept_to_skill_closure_artifact.md) · [WO044](./stage4_044_COMPFIT_COGNITIVE_concept_to_skill_closure_artifact.md)
  - source of the token and of the registry: [Stage-1 artifact](./20260719_164605_stage1_source_linked_identity_extraction_artifact.md) — registry rows `SD-01`..`SD-12` at lines 27-38; roster/SU rows carrying the token include lines 128-130, 157-162, 174, 183, 234, 341, 348, 351, 370, 380, 388
- **FailureMode**: an extraction step that records a reference without resolving it leaves a provenance field that cannot be followed; every downstream stage that transcribes provenance verbatim (Stage 4 does) seals the unresolved token into artifacts it declares verified. Severing the link means resolving the ID at the moment the reference is written, so nothing downstream can inherit `??`.
- **ChangeSite** (one element inside the routed target): the **formula** that composes the source-document reference for SU-registry rows and for C0-roster `sourceLines` secondary segments.
- **CurrentRuleOrFormula**: the secondary-source segment is emitted as `SD-??:<line-range>` whenever the writing step does not already hold the document ID in hand; the row is then confirmed and frozen with the placeholder in place.
- **RequiredChange**: change the formula so a source-document reference is never emitted unresolved. Concretely: (1) before writing any `SD-` segment, resolve the referenced document against the artifact's own `SD-01`..`SD-12` registry and write the resolved ID; (2) make `SD-??` a hard stop in Stage-1's own pre-seal check — a Stage-1 artifact containing the literal `SD-??` does not pass its own conformance; (3) where a reference genuinely cannot be resolved, record it explicitly as an unresolved reference with a stated reason in the record's own text, never as a silent `??`. Apply the same resolution to the SU index columns, not only to the roster rows. The corrected values for this run's known instances, adjudicated and binding, are: **WO168 → `SD-03`** · **WO195 → `SD-08`** · **WO197 → `SD-06` and `SD-04`** · **WO240 → `SD-06`** · **WO267 → `SD-03` and `SD-09`** · **WO280 → `SD-10`**.
- **AcceptanceCriteria**: a corpus-wide grep for the literal `SD-??` over the next run's Stage-1 artifact returns **0** hits, and every `SD-` token in it resolves to a row of that artifact's own registry.
- **NextRunExpectedEffect**: no closure artifact can transcribe an unresolved placeholder, because none exists upstream. Scope closed by this run's measurement: **9 artifacts · 209 occurrences · 203 lines** — the true scope, larger than the 6 rows that charged it.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the reference-composition formula and its pre-seal check. Do NOT alter the primary `sourceDocument` field or any line number (both are correct and resolve), do not re-extract candidates, do not renumber the SD registry, and do not touch the sealed ledger rows that carry the inconsistency.
- **Status**: recorded and handed off for the next run to carry out — never applied here.

### `PI-S1-02` — display-name acronym expansion that the corpus does not contain

- **PatchInstructionID**: `PI-S1-02`
- **Target**: Stage 1 — source-linked identity extraction. GIVEN by the ledger's `targets` field; not re-routed here.
- **ProblemSummary**: the display name `HBRM (Human-Bot Role Management)` supplies an English expansion that does not occur anywhere in the corpus, and it contradicts the same Stage-1 record's own `structural_role`, which states that the acronym is not expanded in the text. One record's two fields assert opposite things, and the fabricated expansion then propagates verbatim to Stage-2, Stage-3, the manifest, `_identity`, and the 4-DIAG alias table.
- **RootCause** (GIVEN, not re-diagnosed): Stage 1 composed a display name by inventing an acronym expansion instead of carrying the author's own wording, while separately recording — correctly — that the text contains no expansion. The pipeline's own better reading exists in a sibling record: another Stage-1 record for the same acronym takes the display name from the source's own Korean gloss.
- **EvidenceLinks**:
  - ledger position **251** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifact: [WO251 `HUMAN_BOT_ROLE_MANAGEMENT`](./stage4_251_HUMAN_BOT_ROLE_MANAGEMENT_concept_to_skill_closure_artifact.md)
  - [Stage-1 artifact](./20260719_164605_stage1_source_linked_identity_extraction_artifact.md) — line 372 (the roster row supplying the expansion), line 536 (the same record's `structural_role`: "Acronym not expanded in text."), line 341 (the sibling record `S1C-079`, display name taken from the source's own gloss)
  - corpus check recorded in the row: a case/space/hyphen-insensitive regex for the expansion over all 9 source documents returns 0 hits
- **FailureMode**: a display name is the identity's public label; when it asserts a source expansion the source never gives, every downstream stage inherits an unsourced claim and no downstream check can catch it, because each stage is faithfully transcribing. Severing the link means binding the display name to text that exists.
- **ChangeSite** (one element inside the routed target): the **rule** governing display-name composition for acronym candidates.
- **CurrentRuleOrFormula**: the display name may carry a parenthetical acronym expansion supplied by the extractor when the source does not give one; no check reconciles the display name against the same record's `structural_role`.
- **RequiredChange**: change the rule so a display name contains only strings that occur in the source. Concretely: (1) an acronym expansion may be placed in a display name only when it is quotable from the corpus — otherwise the display name carries the acronym alone or the author's own Korean gloss; (2) add a same-record consistency check: if `structural_role` states the acronym is not expanded in the text, the display name must not contain an expansion; (3) for this specific candidate the display name is to be recomposed without the invented English expansion, following the sibling record's precedent of using the source's own gloss.
- **AcceptanceCriteria**: every display name containing a parenthetical expansion in the next run's Stage-1 artifact is grep-verifiable in the corpus; no record contains a display name whose expansion its own `structural_role` denies.
- **NextRunExpectedEffect**: the unsourced expansion is not minted, so Stage 2, Stage 3, the manifest, `_identity` and the alias table have nothing to inherit.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the display-name composition rule and its same-record check. Do NOT change the candidate's normalized key, its `sourceLines`, its evidence, or its family placement — all are correct; do not merge or split the candidate; do not touch the sealed ledger row.
- **Status**: recorded and handed off for the next run to carry out — never applied here.

## Contributing ledger rows

| PatchInstructionID | ledger positions (READ-ONLY provenance) | candidates |
|---|---|---|
| `PI-S1-01` | 168, 195, 197, 240 (Stage-1 half of a dual-stage row), 267 (Stage-1 half of a dual-stage row), 280 | WO168, WO195, WO197, WO240, WO267, WO280 — plus uncharged in-scope WO017, WO043, WO044 |
| `PI-S1-02` | 251 | WO251 |

Rows 240 and 267 are `FEEDBACK_TO_MULTIPLE_STAGES`; their Stage-4 halves are carried by `PI-S4-02` in the Stage-4 file, not here.

## Links

- sourceLedger -> [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
- consolidatedBy -> [E4 ledger-wide consolidation status](./_stage5_c2/e4_ledger_wide_consolidation_status.md)
- mintedBy -> [E5 directive entries record](./_stage5_c2/e5_directive_entries_record.md)
- referencedBy -> the run seed packet `stage5_next_run_seed_packet.md`, which references this file by PatchInstructionID (that packet is authored and landed downstream of this file; the resolvable direction is seed -> instruction)
- siblingFile -> [Stage5Stage2PatchInstruction](./stage5_stage2_patch_instruction.md)
- siblingFile -> [Stage5Stage3PatchInstruction](./stage5_stage3_patch_instruction.md)
- siblingFile -> [Stage5Stage4PatchInstruction](./stage5_stage4_patch_instruction.md)
