---
name: e5_directive_entries_record
description: E5 member-5 record — the minted corrective directive entries. Exactly ONE entry per CONSOLIDATED problem from E4 (never per raw duplicate, never for HUMAN_REVIEW_REQUIRED), each carrying a PatchInstructionID + EvidenceLinks and recorded INTO the routed stage's patch instruction, which holds the authoritative full text.
---

# E5 · prescription_authoring — minted directive entries (register)

- consolidated set consumed as **GIVEN** from [E4](./e4_ledger_wide_consolidation_status.md): 16 formula problems. Nothing is re-consolidated here; no route is re-decided; no verdict is re-judged.
- **Givenness gate**: every one of the 16 arrived carrying BOTH a diagnosed cause (E4's formula statement, itself derived from the ledger's sealed root-cause fields) and a routed target (the ledger's sealed `targets` field). None was missing either. Zero problems stopped at the gate.
- **HUMAN_REVIEW exclusion**: positions 12, 124, 359 carry `targets: HumanReview`. They are blockers, not corrections; **zero** directives were minted for them. They are not present in this register.
- **Authoritative text**: each entry's full field block (`PatchInstructionID`, `Target`, `ProblemSummary`, `RootCause`, `EvidenceLinks`, `FailureMode`, `ChangeSite`, `CurrentRuleOrFormula`, `RequiredChange`, `AcceptanceCriteria`, `NextRunExpectedEffect`, `DoNotChange`, `Status`) is recorded INTO the routed stage's patch instruction file — the single source. This register is the mint ledger, not a second copy.

## Minted entries — 16, one per consolidated problem

| PatchInstructionID | from | routed target | change site (kind) | contributing ledger positions |
|---|---|---|---|---|
| `PI-S1-01` | FP-01 | Stage 1 | the source-document reference formula of the SourceUnit table and C0 roster (**formula**) | 168, 195, 197, 240, 267, 280 (+ true scope: WO017, WO043, WO044) |
| `PI-S1-02` | FP-02 | Stage 1 | the display-name composition rule for acronym candidates (**rule**) | 251 |
| `PI-S2-01` | FP-03 | Stage 2 | the duplicate/collapse decision formula + the KEEP×SPLIT cross-coverage step (**formula**) | 32, 33, 125, 38, 39 |
| `PI-S4-01` | FP-04 | Stage 4 | the quote-locator rule in `ProvenanceGrounding` / knowledge-file citation (**rule**) | 51, 54, 254, 305, 306 |
| `PI-S4-02` | FP-05 | Stage 4 | the Stage-2 coordinate recording rule in `InputAdmission` / `ProvenanceGrounding` (**rule**) | 142, 143, 144, 145, 146, 148, 149, 150, 239, 240, 267 |
| `PI-S4-03` | FP-06 | Stage 4 | the Keep-rationale citation template (**document** — the closure artifact's citation sentence pattern) | 211, 212, 336 |
| `PI-S4-04` | FP-07 | Stage 4 | the supplementary-citation inventory declaration in `ProvenanceGrounding` (**rule**) | 348 |
| `PI-S4-05` | FP-08 | Stage 4 | the family-inherited enumeration narrative in `ProvenanceGrounding` (**document**) | 70, 71, 72, 73 |
| `PI-S4-06` | FP-09 | Stage 4 | the neighbour-edge identity resolution step in `Interlock` (**rule**) | 90, 132, 307 |
| `PI-S4-07` | FP-10 | Stage 4 | the PREV/NEXT substitution sentence template in `Interlock` (**document**) | 157, 158, 159 |
| `PI-S4-08` | FP-11 | Stage 4 | the parent-cardinality statement in `Roster` (**rule**) | 160, 161, 162 |
| `PI-S4-09` | FP-12 | Stage 4 | the source re-read range declaration in `InputAdmission` (**rule**) | 101, 102 |
| `PI-S4-10` | FP-13 | Stage 4 | the split-set sibling description in `Roster` (**rule**) | 176 |
| `PI-S4-11` | FP-14 | Stage 4 | the upstream cross-reference attribution in `ProvenanceGrounding` (**rule**) | 198 |
| `PI-S4-12` | FP-15 | Stage 4 | the hand-narrated sibling roster in `InputAdmission` (**document**) | 265 |
| `PI-S4-13` | FP-16 | Stage 4 | the distinction assertion in `Contract` / `Interlock` (**rule**) | 38, 39 |

Count check: 16 minted / 16 consolidated problems / 0 for HUMAN_REVIEW / 0 per-raw-duplicate. Routing check: Stage 1 → 2 entries, Stage 2 → 1, Stage 3 → 0, Stage 4 → 13.

## Bounds fixed on every entry (written into each entry's own text)

Each entry is ONE directive keyed to exactly ONE consolidated problem; a one-shot corrective, never a standing rule or contract; it **instructs** a change and does not perform one; it authorizes the named change site's stated change and nothing beyond it. No entry applies a fix, re-runs a stage, mints or revives a candidate, or touches the ledger.

## Status

RECORDED and handed off — the entries hand into E6, the ASSEMBLY SEAT, which finalizes the four per-stage files. Nothing is applied here; the corrections are carried out by the NEXT run.

## Links

- consumes -> [E4 ledger-wide consolidation status](./e4_ledger_wide_consolidation_status.md)
- recordsInto -> [Stage5Stage1PatchInstruction](../stage5_stage1_patch_instruction.md)
- recordsInto -> [Stage5Stage2PatchInstruction](../stage5_stage2_patch_instruction.md)
- recordsInto -> [Stage5Stage3PatchInstruction](../stage5_stage3_patch_instruction.md)
- recordsInto -> [Stage5Stage4PatchInstruction](../stage5_stage4_patch_instruction.md)
- handsOffTo -> [E7 link confirmation record](./e7_link_confirmation_record.md)
