---
name: e2_artifact_form_specification
description: E2 member-2 record — the required FORM of the Stage-5 C2 run artifacts: the four per-stage patch instruction file shapes (Stage5Stage1..4PatchInstruction) and the seed packet shape (Stage5NextRunSeedPacket). Form only, never content.
---

# E2 · artifact_form_specification — fixed shapes of the run artifacts

Form only. This record fixes which parts exist, in what order, and whether each is mandatory or optional. It never fixes what any part says, and it does not bind the enforceable conformance condition (that is E3's contract).

## Kind A — `Stage5StageNPatchInstruction` (four instances: N = 1, 2, 3, 4)

Parts, in this order:

| # | part | mandatory | shape |
|---|---|---|---|
| A1 | frontmatter `name` + `description` | mandatory | YAML block at the top |
| A2 | `# ` title naming the stage the file routes to | mandatory | one H1 |
| A3 | provenance header block | mandatory | run identity, runRoot, source ledger reference, moment, directive count |
| A4 | `## Directive entries` | mandatory | a section; contains zero or more directive-entry blocks |
| A4.x | one directive-entry block per entry | optional as a set (may be zero); each present block's own fields are mandatory | `### <PatchInstructionID> — <short problem name>` followed by the fixed field list A4f |
| A5 | `## Emptiness evidence` | mandatory **only when** A4 holds zero entries | a section stating the evidence that settles the emptiness; forbidden to be a bare "none" |
| A6 | `## Contributing ledger rows` | mandatory | a table mapping each entry to the ledger positions that contributed |
| A7 | `## Links` | mandatory | Markdown links that resolve from this file's own location |

Field list **A4f** inside each directive-entry block (each mandatory, in this order):
`PatchInstructionID` · `Target` · `ProblemSummary` · `RootCause` · `EvidenceLinks` · `FailureMode` · `ChangeSite` (one element: rule | formula | skill | document) · `CurrentRuleOrFormula` · `RequiredChange` · `AcceptanceCriteria` · `NextRunExpectedEffect` · `DoNotChange` · `Status`.

Shape rules (form, not content):
- A file of this kind is recognizable by A1–A4 + A6 + A7 alone; the presence of A5 marks the explicitly-empty variant of the same kind.
- A zero-entry file is still a full instance of the kind: it keeps every mandatory part and adds A5.
- Korean display names and Korean evidence text are carried verbatim (UTF-8) beside normalized keys wherever a part holds either.

## Kind B — `Stage5NextRunSeedPacket` (exactly one instance)

Parts, in this order:

| # | part | mandatory | shape |
|---|---|---|---|
| B1 | frontmatter `name` + `description` | mandatory | YAML block at the top |
| B2 | `# ` title | mandatory | one H1 |
| B3 | packet header block | mandatory | `SeedPacketID`, `SourceRunID`, `SourceFeedbackLedger`, `IncludedPatchInstructions`, `Status` |
| B4 | `## Application order` | mandatory | the fixed Stage 1 → 2 → 3 → 4 statement |
| B5 | `## Stage 1 seed` … `## Stage 4 seed` (four sections, always all four) | mandatory | each holds zero or more REFERENCES; a reference names the per-stage file AND the directive entry's `PatchInstructionID`, never a forked copy of its content |
| B5.x | one reference row per included directive entry | optional as a set | fixed columns: `PatchInstructionID` · file link · one-line problem label · `ProvenanceLinks` (ledger positions) |
| B6 | `## Review blockers (HUMAN_REVIEW_REQUIRED — not executable seeds)` | mandatory | a section listing blockers APART from the corrections, each with provenance; present even when empty |
| B7 | `## ExpectedNextRunEffect` | mandatory | what the seed asserts for the next run |
| B8 | `## Links` | mandatory | Markdown links that resolve from this file's own location |

Shape rules (form, not content):
- The packet has no candidate-roster part. No part of this kind may hold a candidate population; that channel is the separate Stage-4 `Stage5HandoffPacket`.
- B5 always shows all four stage views, including any that hold zero references.
- The evidenced no-change variant replaces B5's reference rows with a positive evidenced assertion; it is the same kind, recognizable by the same parts.

## Links

- consumes -> [E1 input admission record](./e1_input_admission_record.md)
- handsOffTo -> [E3 run contract](./e3_run_contract.md)
- shapes -> [Stage5Stage1PatchInstruction](../stage5_stage1_patch_instruction.md)
- shapes -> [Stage5Stage2PatchInstruction](../stage5_stage2_patch_instruction.md)
- shapes -> [Stage5Stage3PatchInstruction](../stage5_stage3_patch_instruction.md)
- shapes -> [Stage5Stage4PatchInstruction](../stage5_stage4_patch_instruction.md)
- shapes -> [Stage5NextRunSeedPacket](../stage5_next_run_seed_packet.md)
