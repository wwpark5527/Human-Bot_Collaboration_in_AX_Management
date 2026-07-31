---
name: e11_interlock_check_record
description: E11 member-11 record — the REQUIRED-FOR-SOUND-SEAL seat. The ledger → directives → seed wiring swept for dangling and phantom PatchInstructionIDs; every output consumed, every input sourced, both ends agreeing. The ledger read READ-ONLY.
---

# E11 · interlock_check — ledger → directives → seed wiring

- seat class: **REQUIRED for a sound seal.** verified_record names this seat as a precondition.
- checks the pieces against **each other**, not each piece against its own contract (that is E12).
- the ledger was read READ-ONLY throughout; it is unchanged.
- moment: 2026-07-21

## 1 · The whole set enumerated first

**Pieces (7)**: the completed ledger (369 rows) · the four per-stage patch instruction files (2 + 1 + 0 + 13 = 16 entries) · the seed packet (16 references + 3 blockers) · the E5 mint register (16 ids).
**Connections (4 kinds)**: ledger row → directive (a charged row resolves to a `PatchInstructionID`) · directive → ledger (an entry's `ProvenanceLinks` name the rows it consolidates) · directive → seed (an entry is referenced by file + id) · seed → directive (a reference resolves to an entry that exists in the named file).

## 2 · Every output consumed — no ORPHAN output

| producer output | consumer | result |
|---|---|---|
| 48 directive-eligible ledger charges (51 charged − 3 HUMAN_REVIEW) | directive entries' provenance | **48 / 48 consumed.** Zero unconsumed charges |
| 16 directive entries | seed packet references | **16 / 16 consumed.** Zero entries unreferenced |
| 16 mint-register ids (E5) | the four instruction files | **16 / 16** — register and files are id-identical (set diff empty both ways) |
| 3 HUMAN_REVIEW rows | seed packet blocker section | **3 / 3** carried as blockers B1, B2, B3 — and consumed by nothing else |

## 3 · Every input sourced — no ORPHAN input

| consumer input | source | result |
|---|---|---|
| each seed reference's `PatchInstructionID` | a `### <id>` entry in the named instruction file | **16 / 16 sourced**; each names the correct file for its stage |
| each directive's `ProvenanceLinks` position | a real row of the 369-row ledger | **48 distinct positions, all real, all directive-eligible.** Zero cited positions outside the eligible set |
| each blocker's provenance | a ledger row with `HUMAN_REVIEW_REQUIRED` | **3 / 3** (positions 12, 124, 359) |
| each directive's evidence link | a file on disk under runRoot | **126 links across the four files resolve; zero dangling** |

## 4 · Both ends agree

- **Direction**: ledger → directive → seed throughout; no back-edge writes into the ledger, and no seed reference reaches past its instruction file into raw ledger text.
- **Form**: a seed reference emits `(file, PatchInstructionID)` and an instruction file accepts exactly that pair — the entry headings are the ids the seed names. No copied directive body appears in the seed, so there is no second version of any correction.
- **Cardinality**: 16 entries ↔ 16 references, one-to-one. Provenance multiplicity is one-to-many by design and totals 52 charge-links over 48 distinct positions; the 4 extra links are exactly the four dual-stage rows — 38 and 39 (`PI-S2-01` + `PI-S4-13`), 240 and 267 (`PI-S1-01` + `PI-S4-02`) — each contributing once per stage and never twice within one stage.
- **Per-entry provenance counts**: `PI-S1-01` 6 · `PI-S1-02` 1 · `PI-S2-01` 5 · `PI-S4-01` 5 · `PI-S4-02` 11 · `PI-S4-03` 3 · `PI-S4-04` 1 · `PI-S4-05` 4 · `PI-S4-06` 3 · `PI-S4-07` 3 · `PI-S4-08` 3 · `PI-S4-09` 2 · `PI-S4-10` 1 · `PI-S4-11` 1 · `PI-S4-12` 1 · `PI-S4-13` 2 = 52.

## 5 · Every reference resolved — DANGLING / PHANTOM sweep

| break kind | definition | found |
|---|---|---|
| **DANGLING** `PatchInstructionID` | an id referenced by the seed (or the register) that is absent from the instruction files | **0** — set difference seed − files is empty |
| **PHANTOM** `PatchInstructionID` | an id that exists in no piece at all, or an entry referenced nowhere | **0** — set difference files − seed is empty; every id appears in exactly one entry heading, one register row, and one seed reference |
| **ORPHAN** output/input | see sections 2 and 3 | **0** |
| **both-ends mismatch** | a reference whose file does not hold the entry, or a stage view holding an entry routed elsewhere | **0** — every `PI-S1-*` sits in the Stage-1 file and the Stage-1 seed view, every `PI-S2-*` in Stage 2, every `PI-S4-*` in Stage 4 |
| HUMAN_REVIEW leakage | a blocker position appearing in any directive's provenance | **0** — positions 12, 124, 359 appear only in the blocker section |
| ledger-hygiene leakage | position 368's `\|` erratum, or position 65's line-number erratum, appearing as a defect in any patch instruction | **0** — neither appears in any instruction file; both are recorded only in the E4 audit as excluded |

## 6 · Coverage — the whole connected set, not a sample

All 369 ledger rows were classified; all 51 charged rows were traced to either a directive (48) or a blocker (3); all 16 entries and all 16 seed references were walked individually; all 228 links in the bundle were followed. No piece and no connection was skipped.

## Result

**INTERLOCK CLEAN.** Zero dangling, zero phantom, zero orphan, zero both-ends mismatch. Dangling/phantom `PatchInstructionID` count: **0**.

## Links

- consumes -> [E10 link closure check record](./e10_link_closure_check_record.md)
- sweeps -> [Stage5FeedbackLedger](../stage5_feedback_ledger.md) (READ-ONLY)
- sweeps -> [Stage5Stage1PatchInstruction](../stage5_stage1_patch_instruction.md)
- sweeps -> [Stage5Stage2PatchInstruction](../stage5_stage2_patch_instruction.md)
- sweeps -> [Stage5Stage3PatchInstruction](../stage5_stage3_patch_instruction.md)
- sweeps -> [Stage5Stage4PatchInstruction](../stage5_stage4_patch_instruction.md)
- sweeps -> [Stage5NextRunSeedPacket](../stage5_next_run_seed_packet.md)
- handsOffTo -> [E12 conformance check record](./e12_conformance_check_record.md)
