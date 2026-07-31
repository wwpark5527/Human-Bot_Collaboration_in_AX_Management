---
name: e3_run_contract
description: E3 member-3 record — the run-level PASS contract for Stage-5 COMPOSITE 2. The binding obligation record that E12's conformance_check holds EACH landed artifact against; references the E2 shapes rather than restating them.
---

# E3 · contract_statement_authoring — the run-level PASS contract

Binding, not advisory. An unmet output is a broken obligation surfaced as a contract failure, never a silent omission. Shapes are referenced, not restated: see [E2 artifact form specification](./e2_artifact_form_specification.md). Order of work is referenced, not restated: the composite's E1→E12 spine.

## Party set 1 — the member seats (who owes what to whom)

| party | seat class | input it expects | output it owes | condition | responsibility boundary (duty ends at) |
|---|---|---|---|---|---|
| 1 input_admission | flow-producer | completed ledger + accumulated per-candidate outputs + runRoot, across the barrier | finalized admission record, ledger bound READ-ONLY | barrier already satisfied externally | binding the input; it never produces or verifies content |
| 2 artifact_form_specification | flow-producer | finalized admission | the five fixed shapes (form only) | admission complete | form; never content, never the conformance condition |
| 3 contract_statement_authoring | flow-producer | finalized shapes | THIS contract | shapes finalized | stating obligations; it never orders work nor shapes artifacts |
| 4 whole_system_audit | flow-producer | this contract + the READ-ONLY ledger | the CONSOLIDATED problem set, moment-stamped and reproducible | sweep covers EVERY one of the 369 rows, not a sample | consolidation; it mints no directive |
| 5 prescription_authoring | flow-producer | the CONSOLIDATED set as GIVEN | exactly ONE directive entry per consolidated problem, each with PatchInstructionID + EvidenceLinks, routed | consolidation finalized FIRST; never for HUMAN_REVIEW items | authoring entries; it never re-consolidates, never applies a fix |
| 6 file_finalization | flow-producer (ASSEMBLY SEAT) | the finalized directive entries | the FOUR per-stage files, each written incl. links, read back, links verified, finalized | fixed 4-step static unroll; a zero-directive stage still finalized, explicitly empty and evidence-backed | the four files; nothing edits them afterwards |
| 7 followable_link_authoring | recommended, confirm-only | the four finalized files | a finalized link-confirmation record | runs in order on the spine; its absence would be recorded, not failing | confirming links; it authors/fixes nothing else |
| 8 seed_packet_authoring | flow-producer | link confirmation + READ-ONLY ledger + the FOUR files (PRESENCE GATE) | the seed packet CONTENT, authored-and-handed-off | STOP on any absence, never guess | content; it never lands or seals, never re-decides routes |
| 9 artifact_landing | flow-producer | the finalized authored content | run artifacts landed at addressable runRoot paths, each read-back-confirmed | never the clean vault | landing + read-back evidence |
| 10 link_closure_check | recommended closure seat | the landed bundle | closure result: no dangling link, no orphan node, paths compose | runs in order on the spine | closure over the bundle |
| 11 interlock_check | REQUIRED for sound seal | the closure-checked bundle | interlock report: clean, or each break named by kind with the specific pieces | ledger read READ-ONLY | ledger→directives→seed wiring; both ends must agree |
| 12 conformance_check | REQUIRED for sound seal | the interlock report | a verdict record walking EVERY obligation of this contract per landed artifact, as re-readable evidence | never a bare verdict | conformance; it does not seal |
| 13 verified_record | terminal sink | a finalized conformance **PASS** | the sealed RUN record under runRoot | PASS-ONLY; on FAIL it does not run | the RUN record's own claim, never per-candidate claims (those are C1's sealed rows) |

## Party set 2 — the landed artifacts (what each owes to be conformant)

| artifact | owes |
|---|---|
| [Stage5FeedbackLedger](../stage5_feedback_ledger.md) | to be byte-for-byte unchanged: 1373524 bytes, md5 `66fc679f6d40fec2dab81d9e9e0ca764`, 369 rows, pos==line |
| [Stage5Stage1PatchInstruction](../stage5_stage1_patch_instruction.md) | E2 Kind A shape; every entry carries the full A4f field list; every EvidenceLink resolves; entry count equals the count of consolidated problems routed to Stage 1 |
| [Stage5Stage2PatchInstruction](../stage5_stage2_patch_instruction.md) | as above, for Stage 2 |
| [Stage5Stage3PatchInstruction](../stage5_stage3_patch_instruction.md) | as above, for Stage 3 — and, holding zero entries, the mandatory `## Emptiness evidence` part, evidence-backed, never a bare "none" |
| [Stage5Stage4PatchInstruction](../stage5_stage4_patch_instruction.md) | as above, for Stage 4 |
| [Stage5NextRunSeedPacket](../stage5_next_run_seed_packet.md) | E2 Kind B shape; corrections-only; every reference = file + PatchInstructionID, never a forked copy; provenance attached; duplicates collapsed by reference; blockers separated; Stage 1→2→3→4 order; NO candidate roster |
| the RUN record `stage5_run_record.md` (sealed at `_artifact/stage5_run_record.md` on PASS only; not yet in existence when this contract is authored) | exists only on conformance PASS; names interlock (11) and conformance (12) as preconditions of the seal |

## Conditions of cooperation — the 8 PASS criteria (all must hold to seal)

1. Invoked exactly ONCE for this run, after the barrier; the completed ledger admitted finalize-then-read (STOP if not complete).
2. The audit consolidated repeats over the COMPLETE 369-row ledger BEFORE any directive was minted; the consolidation is recorded and traceable.
3. Exactly one directive entry per consolidated problem, recorded INTO the routed stage's patch instruction, each with PatchInstructionID + evidence provenance; **zero** directives for HUMAN_REVIEW items.
4. All FOUR per-stage files finalized (write, read-back, links resolve) — including the explicitly-empty, evidence-backed file for a stage with zero directives.
5. The seed packet is corrections-only; references = file + PatchInstructionID; blockers separated; no candidate roster; the no-change form used only if it applies.
6. The run artifacts landed under runRoot at addressable paths, each read-back-confirmed.
7. Interlock holds: zero dangling/phantom PatchInstructionIDs anywhere in ledger → directives → seed wiring; closure clean where the seat ran.
8. Every landed artifact passed conformance against this contract BEFORE verified_record sealed. On any FAIL: finalize the failure record and STOP — nothing sealed.

## Standing prohibitions (breach = contract failure)

No ledger append/mutation/reorder/re-decision · no HUMAN_REVIEW directive · no fix applied · no Stage 1–4 or concept_to_skill rerun · no candidate minted or revived · no candidate roster in the seed · no write outside runRoot · no member run in parallel · no hand-authoring around the composite · no seal on FAIL.

## Completeness check of this contract

Every named party above has an input, an output, a condition, and a responsibility boundary; the terms are binding. The contract is accepted as complete.

## Links

- consumes -> [E2 artifact form specification](./e2_artifact_form_specification.md)
- handsOffTo -> [E4 ledger-wide consolidation status](./e4_ledger_wide_consolidation_status.md)
- heldAgainstBy -> the conformance record `e12_conformance_check_record.md` in this folder (produced downstream of this contract; the resolvable direction is conformance -> contract)
