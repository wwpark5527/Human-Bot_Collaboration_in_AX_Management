---
name: stage5_stage4_patch_instruction
description: Stage5Stage4PatchInstruction — the Stage-5 corrective directives routed to Stage 4 (concept_to_skill closure) for the NEXT run. Thirteen directive entries, one per consolidated formula problem. Instructs changes; applies none.
---

# Stage5Stage4PatchInstruction — corrective directives routed to Stage 4

- run: the 369-candidate AX-book identity run under runRoot `/Users/gesia/wwp_book_v0.2`
- source ledger: [Stage5FeedbackLedger](./stage5_feedback_ledger.md) — 369 rows, md5 `66fc679f6d40fec2dab81d9e9e0ca764`, consumed READ-ONLY
- consolidation: [E4 ledger-wide consolidation status](./_stage5_c2/e4_ledger_wide_consolidation_status.md) (16 formula problems run-wide; 13 routed here)
- moment: 2026-07-21
- **directive entries in this file: 13**
- all thirteen are one-shot correctives for the NEXT run's Stage 4. Nothing here is applied by Stage 5. Every entry below concerns how the closure artifact *records* what it checked; none concerns a minted node's identity, and no minted node in this run is disturbed.

**Family note.** `PI-S4-01`, `PI-S4-03` and `PI-S4-04` are three distinct members of one citation-record-integrity family: a locator offset onto a neighbouring non-content line (01), a quote colon-attached to an otherwise-correct coordinate (03), and a declared citation inventory that does not match the cited file (04). They are kept as three directives because the severing change differs in each; they cross-reference each other and may be executed together.

## Directive entries

### `PI-S4-01` — quote locator lands on an adjacent non-content line

- **PatchInstructionID**: `PI-S4-01`
- **Target**: Stage 4 — concept_to_skill closure (the closure artifact and its `_knowledge` file). GIVEN by the ledger's `targets`; not re-routed.
- **ProblemSummary**: a supporting quotation is attributed to a line the quotation is not on — the bold subheading that opens the section (source line 365 for a quote at 367), a blank line (356 for a quote at 357), a heading two lines off (67 for a heading at 65), the wrong list line 14 apart (64 for a quote at 50), a subtitle line (68 for a quote at 70). In each case the primary evidence line and `sourceLines` are correct, so element identity is unaffected and severity is low — but the locator does not lead a reader to the text it claims.
- **RootCause** (GIVEN): the closure step records the line where the *section* starts, or a nearby line inferred from a neighbouring block's numbering, instead of the line the quoted string actually occupies; the artifact then declares that citation independently re-read. The check demonstrably exists — one element self-caught the same error before sealing — but it is applied unevenly.
- **EvidenceLinks**:
  - ledger positions **51, 54, 254, 305, 306** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifacts: [WO051](./stage4_051_HBS_PREV_FINAL_RESPONSIBILITY_concept_to_skill_closure_artifact.md) · [WO054](./stage4_054_HBS_PREV_NO_HUMAN_COMPONENTIZATION_concept_to_skill_closure_artifact.md) · [WO254](./stage4_254_COMMON_CONTEXT_ELEMENT_PURPOSE_concept_to_skill_closure_artifact.md) · [WO305](./stage4_305_PIS_WORLD_MODEL_concept_to_skill_closure_artifact.md) · [WO306](./stage4_306_PIS_CONTEXT_DESIGN_concept_to_skill_closure_artifact.md)
  - sealed knowledge files carrying the same wrong locator: [hbs_prev_final_responsibility_knowledge.md](../_knowledge/hbs_prev_final_responsibility_knowledge.md) line 21 · [hbs_prev_no_human_componentization_knowledge.md](../_knowledge/hbs_prev_no_human_componentization_knowledge.md) line 21
  - control cases proving the check is available and works: ledger positions 52, 53, 55 and 255 (same families, same citation style, zero misattribution)
- **FailureMode**: a locator that is written from the section's position rather than the string's position produces a pointer that fails on follow; sealing it into both the artifact and the knowledge file doubles the error's reach. Severing the link means deriving the number from the string, not from the section.
- **ChangeSite**: the **rule** governing how a supporting quotation's line number is obtained in `ProvenanceGrounding` / `InputAdmission` and in the `_knowledge` file's citation list.
- **CurrentRuleOrFormula**: the citation records the line at which the quoted material's section or nearest landmark begins, and the artifact asserts the citation was independently re-read.
- **RequiredChange**: obtain every quotation's line number by locating the quoted string itself (grep the literal text in the source and take the hit line); never take it from a section heading, a bold subtitle, a blank line, a list marker, or an offset inferred from an adjacent block. If a claim of "independently re-read" is written, it must be written only for citations obtained this way. Apply the rule to secondary and supporting citations exactly as to the primary one — the unevenness, not the absence, is what failed here.
- **AcceptanceCriteria**: for every citation in a closure artifact and its knowledge file, the cited line contains the cited string. A spot-audit of secondary citations returns zero locators pointing at headings, blank lines, or non-quoting prose.
- **NextRunExpectedEffect**: locators resolve on follow; the artifact-plus-knowledge double sealing can no longer propagate a wrong line.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the quote-locator rule. Do NOT alter `sourceLines`, the primary evidence line, the element's 판정기준/산출, or any family placement — all verified correct; do not re-run Stage 1–3.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-02` — Stage-2 coordinate recorded without reading the cited line

- **PatchInstructionID**: `PI-S4-02`
- **Target**: Stage 4 — concept_to_skill closure. GIVEN; not re-routed.
- **ProblemSummary**: a Stage-2 artifact line number is recorded as the location of a candidate's record without the line having been read. Three shapes occurred: (a) the right candidate, the wrong table — a settled-records row cited with a SplitSet-detail line number (1652 for a row that lives at 466; 1653 for 467; 1663 for 468); (b) a line belonging to an entirely different candidate — SplitSet detail rows cited as 457, 458, 468, 469, 470, which are settled-records rows of other candidates, while the real detail rows are 1664, 1665, 1675, 1676, 1677, with the wrong numbers marching sequentially as they were carried forward; (c) a non-record line — a table's column-header row (1939, whose record is at 1941), a previous SplitSet's last child row mistaken for the next block's head (1943), and a spec-preamble prose line cited as a settled row, then re-asserted as resolving YES in the artifact's own link table.
- **RootCause** (GIVEN): the closure step takes a line number from a grep hit, from the start of a table block, or from the previous element's number plus one, and records it without opening the line to confirm which candidate it carries and which table it belongs to. The Stage-2 document holds each candidate in two places (settled-records table and SplitSet detail section), so an unverified hit lands in the wrong one at high rate.
- **EvidenceLinks**:
  - ledger positions **142, 143, 144, 145, 146, 148, 149, 150, 239** and the Stage-4 halves of **240** and **267** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifacts: [WO142](./stage4_142_AX_ETHICS_NECESSARY_CONDITION_concept_to_skill_closure_artifact.md) · [WO143](./stage4_143_AX_ETHICS_ADDITIONAL_CONDITION_concept_to_skill_closure_artifact.md) · [WO144](./stage4_144_ROBOT_LAW_HUMAN_SAFETY_concept_to_skill_closure_artifact.md) · [WO145](./stage4_145_ROBOT_LAW_OBEDIENCE_concept_to_skill_closure_artifact.md) · [WO146](./stage4_146_ROBOT_LAW_SELF_PRESERVATION_concept_to_skill_closure_artifact.md) · [WO148](./stage4_148_HR_NON_HARM_concept_to_skill_closure_artifact.md) · [WO149](./stage4_149_HR_AUTONOMY_concept_to_skill_closure_artifact.md) · [WO150](./stage4_150_HR_FAIRNESS_concept_to_skill_closure_artifact.md) · [WO239](./stage4_239_TRB_STAGE_HUMAN_ONLY_concept_to_skill_closure_artifact.md) · [WO240](./stage4_240_ARBI_concept_to_skill_closure_artifact.md) · [WO267](./stage4_267_AI_GOVERNANCE_concept_to_skill_closure_artifact.md)
  - [Stage-2 artifact](./20260719_164605_stage2_identity_fragmentation_artifact.md) — settled-records table (header at line 175) vs SplitSet detail sections (e.g. headers at 1643, 1655, 1667); the specific pairs listed above
  - control cases: ledger positions 153-156 and 241-250, where the same citation sentence pattern lands on the correct row every time
- **FailureMode**: an unread coordinate is a claim about a document made without consulting it; because the document repeats each candidate in two tables, the claim is wrong roughly whenever it is unchecked, and the error propagates by increment to the next element. Severing the link means making the read mandatory before the number is written.
- **ChangeSite**: the **rule** for recording an upstream Stage-2 coordinate in `InputAdmission` / `ProvenanceGrounding` / the resolvable-links table.
- **CurrentRuleOrFormula**: a Stage-2 line number is recorded from a grep hit or a block's start position and is declared "independently grepped and confirmed" / "confirmed byte-identical to the pack" without a per-line read; consecutive elements inherit the previous number incremented by one.
- **RequiredChange**: before recording any Stage-2 line number, open that exact line and confirm two things — the **candidate ID it carries** matches the element being closed, and the **table/section it belongs to** matches the one the sentence names. Never derive a coordinate by incrementing the previous element's number, never take a table's header or separator row as the record row, and never re-assert an unread coordinate as resolving in the links table. If a candidate appears in several places, cite each with its own verified number and name which table each belongs to.
- **AcceptanceCriteria**: every Stage-2 coordinate in every closure artifact opens onto a line carrying that element's candidate ID inside the named table; zero coordinates land on header rows, separators, block boundaries, preamble prose, or other candidates' rows.
- **NextRunExpectedEffect**: the family-by-family drift seen here (three consecutive elements in one batch, then five in the next) cannot start, because each number is verified at the point of writing rather than inherited.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the coordinate-recording rule. Do NOT alter the elements' identities, parents, spans or verdicts — all verified correct; do not edit the sealed Stage-2 artifact; do not re-run Stage 2.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-03` — Keep-rationale quote colon-attributed to the settled-records row line

- **PatchInstructionID**: `PI-S4-03`
- **Target**: Stage 4 — concept_to_skill closure. GIVEN; not re-routed.
- **ProblemSummary**: the artifact writes `settled-records row confirmed at line <N> of Stage-2 artifact: "<Keep rationale quote>"`, so the colon attributes the quotation to line N — but line N is only the settled-records row (a KEEP/KEEP row with dashes in the parent columns), and the quoted rationale lives roughly 500 lines away in the Split-rationale block: 267→767, 269→769, 330→830. The coordinate itself is correct for the row; the quote attribution is not. The quotation is also silently abridged, without ellipsis.
- **RootCause** (GIVEN): two distinct coordinates — the settled-record's row number and the Keep-rationale's line number — are collapsed into one sentence, and the quote is attached by colon to whichever number was already there. Upstream Stage-1/2/3 data are correct in all three cases; this is a Stage-4 recording slip, not a spec gap, as shown by sibling artifacts that record the same pair of facts correctly.
- **EvidenceLinks**:
  - ledger positions **211, 212, 336** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md) — consolidated into this ONE problem by binding harness ruling
  - closure artifacts: [WO211](./stage4_211_BEHAVIOR_TYPE_concept_to_skill_closure_artifact.md) line 26 · [WO212](./stage4_212_ROLE_BASED_HRM_concept_to_skill_closure_artifact.md) line 26 · [WO336](./stage4_336_INCLUSIVE_AI_TRANSITION_ESG_concept_to_skill_closure_artifact.md) line 26
  - [Stage-2 artifact](./20260719_164605_stage2_identity_fragmentation_artifact.md) — settled rows 267, 269, 330; the actual Keep rationales at 767, 769, 830 (each reading 「8개 FragmentationNeed 트리거 모두 미발동 + 후보 자체가 건전(부모가 독립 역할을 가지며 mere bundle이 아님) → Keep, stop (step 1)」)
  - control case: ledger position 193, whose artifact records the same two facts with the two coordinates kept apart
- **FailureMode**: a colon is an attribution operator; attaching a quotation to a line that does not contain it makes the sentence false even though every fact in it is individually true. Severing the link means never letting one sentence carry two coordinates with one quotation.
- **ChangeSite**: the **document** pattern — the closure artifact's settled-record citation sentence.
- **CurrentRuleOrFormula**: `settled-records row confirmed at line <settled-row-number> of Stage-2 artifact: "<rationale quote>"` — one number, one quote, one colon.
- **RequiredChange**: split the sentence into its two coordinates and quote only from the line that carries the text: state the settled-records row number as the row's location, and cite the Split-rationale line number as the quotation's location, e.g. `settled-records row at line 267; Keep rationale quoted from line 767: "…"`. Where the quotation is shortened, mark the elision. Never attach a quotation by colon to a coordinate that was verified for a different fact.
- **AcceptanceCriteria**: no closure artifact contains a quotation attributed to a line that does not contain it; every settled-record citation names the row line and the rationale line separately.
- **NextRunExpectedEffect**: this template stops producing false attributions; the pattern is currently a local slip in 3 of 369 artifacts and would otherwise recur wherever the same sentence is reused.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the citation sentence pattern. Do NOT change the KEEP verdicts, the candidate IDs, or the elements' content — all verified correct. See also `PI-S4-01` and `PI-S4-04`, the family's other members.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-04` — declared supplementary-citation inventory does not match the cited file

- **PatchInstructionID**: `PI-S4-04`
- **Target**: Stage 4 — concept_to_skill closure. GIVEN; not re-routed.
- **ProblemSummary**: the artifact declares `Supplementary knowledge-file citations (lines 398, 550) independently verified`, asserting two verified supplementary citations in the knowledge file. The knowledge file contains **one** (line 398). The string `550` exists only inside an `_identity` file, as inherited Stage-1 `structural_role` text (`…recurs at 194, 211, 358, 550`) — a different file class and not a citation this stage created. The declared location, count and nature are all wrong; worse, source line 550 enumerates five rights and omits the very right this element is about, so the false citation invites a misreading that 550 supports the element.
- **RootCause** (GIVEN): at the point of declaring verification, the citations the stage actually created (one, in the knowledge file) and a line-number list inherited verbatim into an identity file's `structural_role` were merged into a single claim of "two verified knowledge-file citations", without separating what was authored from what was inherited or checking which file each string lives in.
- **EvidenceLinks**:
  - ledger position **348** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifact: [WO348 `RIGHT_AI_TRANSITION`](./stage4_348_RIGHT_AI_TRANSITION_concept_to_skill_closure_artifact.md) line 35
  - [_identity/RIGHT_AI_TRANSITION.md](../_identity/RIGHT_AI_TRANSITION.md) line 39 — the inherited Stage-1 `structural_role` string containing 550
  - contrast case: ledger position 349, whose declared citation inventory matches its knowledge file exactly
- **FailureMode**: a verification claim that names citations the file does not contain converts an audit statement into a fabrication, and it does so in the one field a later reader would trust to avoid re-checking. Severing the link means binding the declaration to an enumeration of what is actually in the file.
- **ChangeSite**: the **rule** governing the supplementary-citation verification declaration in `ProvenanceGrounding`.
- **CurrentRuleOrFormula**: the artifact may declare a set of supplementary citations "independently verified" by listing line numbers gathered from the element's materials, without distinguishing citations authored into the knowledge file from line numbers inherited into other file classes.
- **RequiredChange**: derive the declaration from the file it names — enumerate the supplementary citations actually present in the `_knowledge` file, state that count, and verify each against the source before declaring verification. Line numbers that appear in an `_identity` file's inherited Stage-1 `structural_role` are **not** citations of this stage and must not be counted; if such an inherited list is worth mentioning, name it separately as inherited text with its own file. Where a listed source line does not support the element, say so rather than listing it as support.
- **AcceptanceCriteria**: every "supplementary citations verified" declaration matches, one-for-one, the citations present in the named file; zero declarations name a line that is absent from that file or that lives in another file class.
- **NextRunExpectedEffect**: the closure record's citation inventory becomes checkable against the file it names, so a reader who trusts it is not misled.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the inventory-declaration rule. Do NOT alter the element's primary evidence (source line 493), `sourceLines`, 판정기준/산출, parent, or either sequence edge — all verified correct. Related but distinct from `PI-S4-03` (quote attribution) and `PI-S4-01` (locator offset); executing one does not discharge the others.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-05` — family-inherited enumeration narrative transcribed without recounting

- **PatchInstructionID**: `PI-S4-05`
- **Target**: Stage 4 — concept_to_skill closure. GIVEN; not re-routed.
- **ProblemSummary**: four sibling artifacts each state that source line 143 is "the earlier, unparenthesized first mention of the same 4-way enumeration" as line 207. Line 143 lists **five** nouns (정체성·통제·신뢰·책임·존재가치); only line 207 carries the determinate 「다음 4가지」 with exactly four items. The first artifact even quotes line 143's five-item text immediately after calling it a four-way enumeration — a self-contradiction on its face — and the three later artifacts drop the quotation, keeping only the false assertion. Line 143 is not incidental: it is half of every one of these four elements' `sourceLines` and appears as the knowledge file's cited source.
- **RootCause** (GIVEN): a narrative frame established for the first element of a family — "line 143 is the earlier mention of the same enumeration" — was transcribed to the siblings without recounting the items, and the abridgement in the later three removed the quotation that would have exposed the mismatch. The reason the fifth item was not promoted is on record upstream (a Stage-2 kind-based Reject as RelationOnly) and was never carried into the artifacts' provenance narrative.
- **EvidenceLinks**:
  - ledger positions **70, 71, 72, 73** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifacts: [WO070](./stage4_070_AXSTRESS_IDENTITY_concept_to_skill_closure_artifact.md) · [WO071](./stage4_071_AXSTRESS_TRUST_concept_to_skill_closure_artifact.md) · [WO072](./stage4_072_AXSTRESS_CONTROL_concept_to_skill_closure_artifact.md) · [WO073](./stage4_073_AXSTRESS_RESPONSIBILITY_concept_to_skill_closure_artifact.md)
  - scope closure recorded in row 73: a run-wide grep for the phrase returns exactly these four artifacts
  - [Stage-2 artifact](./20260719_164605_stage2_identity_fragmentation_artifact.md) — the `S2C-0037` SplitSet section's kind-based Reject recording 존재가치 as RelationOnly (the uncited reconciliation)
- **FailureMode**: a description written once and copied across a family turns a single unchecked sentence into a family-wide false record, and abridging it on the way removes the evidence that would have caught it. Severing the link means recounting against the cited line in each artifact, and citing the upstream reconciliation that explains the difference.
- **ChangeSite**: the **document** element — the `ProvenanceGrounding` narrative describing the family's source enumeration.
- **CurrentRuleOrFormula**: the family's provenance narrative is inherited from the first sibling's artifact and re-asserted per element, with `InputAdmission` recording that both cited lines were re-read.
- **RequiredChange**: when an artifact asserts that two source lines carry the same enumeration, count the items on both lines in that artifact's own pass and state the counts; if they differ, describe the relation truthfully (an earlier, wider mention rather than the same enumeration) and cite the upstream record that reconciles the difference — here, the Stage-2 kind-based Reject of the fifth item as RelationOnly. Never inherit a family narrative into a sibling without redoing its count, and never abridge a claim by removing the quotation that supports it.
- **AcceptanceCriteria**: no artifact describes an N-item line as an M-item enumeration; where a family's members share a cited line, each states its own verified count, and the reason for any non-promoted item is cited.
- **NextRunExpectedEffect**: a template error can no longer propagate across a family, because each sibling's count is its own.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the enumeration narrative and its counting step. Do NOT alter these four elements' 판정기준/산출, parent, or spans — all correct, each matching line 207's parenthesised question one-to-one; do not promote 존재가치 (its exclusion is upstream and correct).
- **Status**: recorded and handed off — never applied here.

### `PI-S4-06` — neighbour-edge node identified by display name instead of NormalizedKey

- **PatchInstructionID**: `PI-S4-06`
- **Target**: Stage 4 — concept_to_skill closure (`Interlock` / `ProvenanceGrounding`). GIVEN; not re-routed.
- **ProblemSummary**: the artifact resolves a raw Stage-3 neighbour by its display name and so binds the right ID to the wrong node, concluding "matches WalkOrder-adjacent NEXT exactly · no substitution needed" where a substitution was in fact required: `S3S-0112` is `STRESS_BY_COOPERATION_TYPE` (an excluded SplitSet parent), not `COOP_H_B` (which is `S3S-0113`); `S3S-0167` is `BOT_SOCIALITY` (an excluded parent), not `HUMAN_BOT_SOCIALITY` (which is `S3S-0168`); `S3S-0386` is `CONTEXT_DESIGN` (excluded as a DuplicateSkill, owner `S3S-0384`), not `PIS_CONTEXT_DESIGN`. In each case the landed link is nevertheless correct, so severity is low — what is wrong is the recorded verdict about the edge.
- **RootCause** (GIVEN): the neighbour comparison is done on display-name similarity, and parent and child names share a stem (협력 유형별 스트레스 contains the child's H+B token; 봇의 사회성 vs 인간-봇 사회성; 컨텍스트 설계 vs its PIS-prefixed sibling), so a name-level partial match passes while the `NormalizedKey` — which would have separated them — is never read from the Stage-3 artifact. The same run records the correct "SUBSTITUTION, NOTED" form elsewhere, so the form exists and was simply not reached.
- **EvidenceLinks**:
  - ledger positions **90, 132, 307** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifacts: [WO090](./stage4_090_INTERACTION_STRESS_concept_to_skill_closure_artifact.md) · [WO132](./stage4_132_AB_LEARNING_AUGMENTATION_concept_to_skill_closure_artifact.md) · [WO307](./stage4_307_CONTEXT_DESIGNER_concept_to_skill_closure_artifact.md)
  - [Stage-3 artifact](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md) — lines 194/195 (`S3S-0112` / `S3S-0113`), 249/250 (`S3S-0167` / `S3S-0168`), 466/468 (`S3S-0384` / `S3S-0386`)
  - [4-DIAG duplicate diagnosis](./20260719_164605_stage4diag_duplicate_and_containment_diagnosis_artifact.md) — the `S3S-0386` DuplicateSkill exclusion with owner `S3S-0384`
  - control cases: ledger positions 167, 182, 183, 188, 189, where the substitution claim was verified true by key
- **FailureMode**: matching by label where the graph is keyed by `NormalizedKey` produces a confident verdict about the wrong node; because the landed link happens to be right, nothing downstream contradicts the false record. Severing the link means resolving every neighbour by key, read from the source of truth.
- **ChangeSite**: the **rule** for neighbour-edge identity resolution in the `Interlock` section.
- **CurrentRuleOrFormula**: the raw Stage-3 `sequencePrevious`/`sequenceNext` value is compared to the WalkOrder-adjacent neighbour by display name, and a name-level match is recorded as identity with "no substitution needed".
- **RequiredChange**: resolve every raw neighbour ID by opening its row in the Stage-3 artifact and reading its `NormalizedKey`; compare keys, never display names. Then classify explicitly: identity (keys equal) or substitution (raw neighbour is an excluded SplitSet parent or a DuplicateSkill-excluded node, with the exclusion record cited and the owner named). Record the ID, the key, and the classification together, so the verdict is checkable without re-deriving it.
- **AcceptanceCriteria**: every `Interlock` neighbour statement names the raw ID, the `NormalizedKey` read from Stage 3, and the classification; zero statements assert identity between an ID and a key that Stage 3 assigns to a different ID.
- **NextRunExpectedEffect**: excluded-parent and duplicate-owner substitutions are recorded as substitutions, and the run's own correct form becomes uniform.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the neighbour-identity resolution rule. Do NOT rewire any landed sequence link — all three resolve correctly today; do not re-run Stage 3; do not revive the excluded parents or duplicates.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-07` — PREV and NEXT bundled in one compound phrase, substitution applied to both directions

- **PatchInstructionID**: `PI-S4-07`
- **Target**: Stage 4 — concept_to_skill closure (`Interlock`). GIVEN; not re-routed.
- **ProblemSummary**: the artifact writes `sequencePrevious/Next … point at <excluded parent>` as a single compound clause and treats the substitution as one event, so a direction where no substitution occurred is described as substituted. Three consecutive elements did this: one where the raw NEXT was in fact a minted sibling requiring no substitution; one where **both** directions were untouched yet both were declared intentional substitutions; one where only NEXT was a genuine excluded parent while PREV — a promoted, minted sibling — was folded into an "excluded SPLIT-parent chain". The mirror image of `PI-S4-06`: there a real substitution was missed, here unreal ones are asserted.
- **RootCause** (GIVEN): the batch's `Interlock` template describes both edges in one sentence and carries the excluded-parent substitution wording as a default, so whichever direction is checked supplies the verdict for both; a promoted sibling can then be mislabelled as part of an excluded chain.
- **EvidenceLinks**:
  - ledger positions **157, 158, 159** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md) (rows 158 and 159 each explicitly ask that C2 treat this as one template-level problem)
  - closure artifacts: [WO157](./stage4_157_HUMAN_ILLOGICALITY_concept_to_skill_closure_artifact.md) line 53 · [WO158](./stage4_158_HUMAN_AI_RELATED_STRESS_concept_to_skill_closure_artifact.md) line 53 · [WO159](./stage4_159_SOCIAL_COOPERATION_NORM_LEARNING_concept_to_skill_closure_artifact.md) line 53
  - [Stage-3 artifact](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md) — lines 282, 283 (`S3S-0200`, `S3S-0201` raw prev/next), 284 (`S3S-0202`, the one genuine excluded parent)
- **FailureMode**: one clause cannot carry two independent verdicts; defaulting the substitution wording turns "we did not check this direction" into "this direction was substituted", and can promote a minted sibling into an exclusion chain in the record. Severing the link means judging and writing each direction separately.
- **ChangeSite**: the **document** element — the `Interlock` PREV/NEXT statement template.
- **CurrentRuleOrFormula**: `raw Stage-3 sequencePrevious/Next which point at <node> … this substitution` — one compound subject, one verdict, applied to both edges.
- **RequiredChange**: write PREV and NEXT as two separate statements, each naming its own raw ID, its `NormalizedKey`, and its own classification (identity / substitution-with-cited-exclusion). Remove the default substitution wording: substitution is asserted only where the raw neighbour is verified excluded. Never describe a promoted, minted sibling as part of an excluded SPLIT-parent chain, and use `SPLIT` and `Merge`/`collapsed` vocabulary distinctly — this run performed zero Merges, so `collapsed` is not an available description of a SPLIT parent.
- **AcceptanceCriteria**: every `Interlock` section carries two direction-specific statements; zero substitution claims exist for a direction whose raw neighbour is a minted sibling; zero minted siblings are described as excluded parents.
- **NextRunExpectedEffect**: the template can no longer export one direction's verdict onto the other, and the three-in-a-row recurrence pattern cannot start.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the PREV/NEXT statement template. Do NOT rewire any landed edge — the actual links are correct; do not re-run Stage 3.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-08` — parent SplitSet cardinality taken from the batch's child count

- **PatchInstructionID**: `PI-S4-08`
- **Target**: Stage 4 — concept_to_skill closure (`Roster`). GIVEN; not re-routed.
- **ProblemSummary**: three artifacts describe their parent as a **3-way** SPLIT and enumerate three children, and the third goes further and declares the split set closed — twice, in `Roster` and again in `Interlock`. The Stage-2 SplitSet header for that parent says **4 elements**, four child rows exist, and four settled records carry that parent; the fourth child (`봇의 행복`, minted immediately afterwards) is simply outside the authoring batch. Declaring an unfinished family finished is the heaviest form of the error; nothing was actually mis-minted, so severity stays low.
- **RootCause** (GIVEN): the artifact counts the children present in its own batch and reports that number as the family's split cardinality, because the parent's Stage-2 SplitSet header is never consulted; when the batch boundary cuts a family, the batch's end is mistaken for the family's end.
- **EvidenceLinks**:
  - ledger positions **160, 161, 162** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifacts: [WO160](./stage4_160_BOT_AS_PATTERN_DETECTOR_concept_to_skill_closure_artifact.md) line 44 · [WO161](./stage4_161_BOT_FUNCTIONAL_SATISFACTION_concept_to_skill_closure_artifact.md) line 44 · [WO162](./stage4_162_BOT_DESIRE_HIERARCHY_concept_to_skill_closure_artifact.md) lines 44 and 53
  - [Stage-2 artifact](./20260719_164605_stage2_identity_fragmentation_artifact.md) — SplitSet header at line 1708 (`4 elements`), child rows 1719-1722, settled records 483-486, and line 1710 recording that 4 is itself the post-axis-purity corrected count
  - correction basis on the ledger: position 163 (`BOT_HAPPINESS`), the fourth child
- **FailureMode**: reporting a batch-local count as a structural fact makes the record contradict the upstream split it describes, and a false closure declaration tells later readers a family needs no further children. Severing the link means reading the cardinality from the parent's own record.
- **ChangeSite**: the **rule** for stating a parent's split cardinality in the `Roster` section.
- **CurrentRuleOrFormula**: the artifact states the parent's split as N-way where N is the number of that parent's children handled in the current authoring batch, and may declare the split set closed when the batch ends.
- **RequiredChange**: take the split cardinality from the parent's Stage-2 SplitSet header (and cross-check the count of settled records carrying that parent), never from the batch's contents. State children outside the batch explicitly as out-of-batch-but-in-family, with their WalkOrder if known. Declare a split set closed only when the number of minted children equals the header's count; a batch ending is not a family closing.
- **AcceptanceCriteria**: every stated split cardinality equals its Stage-2 header count; zero artifacts declare a split set closed while an unminted child remains.
- **NextRunExpectedEffect**: batch boundaries stop leaking into structural statements; a family cut across batches is described correctly by every member.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the cardinality-sourcing rule. Do NOT re-partition the family or alter any minted child — all four children exist and are correctly wired; do not re-run Stage 2.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-09` — source re-read range inherited across a family boundary

- **PatchInstructionID**: `PI-S4-09`
- **Target**: Stage 4 — concept_to_skill closure (`InputAdmission`). GIVEN; not re-routed.
- **ProblemSummary**: two consecutive artifacts state `Source document independently re-read: lines 27-51` and then claim to have verified, inside that range, a paragraph at line 59 and line 61 respectively — lines that are outside it. The first compounds the problem by adding a third, unsupported range in parentheses ("offset within the re-read range 25-65 used across this batch"), a range no other element of that batch uses; the second leaves the contradiction bare. The correct range for the new parent is 51-99, confirmed upstream in both Stage-1 and Stage-2.
- **RootCause** (GIVEN): when the authoring crosses a family boundary, the re-read range is inherited from the previous family's parent span instead of being re-derived from the new parent's span; and when the inconsistency was noticed, it was patched by adding narrative rather than by re-reading the source.
- **EvidenceLinks**:
  - ledger positions **101, 102** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifacts: [WO101](./stage4_101_PROBLEM_FRAMING_CAPABILITY_concept_to_skill_closure_artifact.md) line 8 · [WO102](./stage4_102_MEANING_DESIGN_CAPABILITY_concept_to_skill_closure_artifact.md) line 8
  - upstream span of the new parent: [Stage-2 artifact](./20260719_164605_stage2_identity_fragmentation_artifact.md) line 1491 and [Stage-1 artifact](./20260719_164605_stage1_source_linked_identity_extraction_artifact.md) line 104 — both give 51-99
  - contamination path recorded in row 102: 27-51 is the previous batch's range for a different parent (span 29-49)
- **FailureMode**: an admission record that names a range excluding the element's own line asserts a reading that cannot have happened as described; patching it with a third range hides the inconsistency instead of resolving it. Severing the link means deriving the range from the current parent and treating a detected mismatch as a trigger to re-read.
- **ChangeSite**: the **rule** for declaring the source re-read range in `InputAdmission`.
- **CurrentRuleOrFormula**: the re-read range is carried forward from the preceding element unless changed, and a mismatch between the range and the element's own line may be reconciled in prose.
- **RequiredChange**: derive the re-read range from the current element's own parent span (as recorded upstream) at every family boundary, and check that the element's own line falls inside the declared range before writing it. When the check fails, re-read the source and correct the range — never add a supplementary range, and never state a range that the element's line sits outside of.
- **AcceptanceCriteria**: in every closure artifact, the element's own source line lies inside the declared re-read range, and the range matches the parent span recorded upstream; zero artifacts declare more than one re-read range.
- **NextRunExpectedEffect**: range values stop migrating across family boundaries, and detected mismatches produce corrections rather than narrative patches.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the range-declaration rule. Do NOT alter `sourceLines`, the knowledge files, or the quotations — all verified correct in both elements; the fault is in the recorded reading range alone.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-10` — excluded sibling described as an unresolved forward declaration

- **PatchInstructionID**: `PI-S4-10`
- **Target**: Stage 4 — concept_to_skill closure (`Roster`). GIVEN; not re-routed.
- **ProblemSummary**: the artifact lists the parent's three children as 방법 (WalkOrder 176), 의미 (177) and 측정 — the third written as "out of this batch, follows later as `S3S-0224`", i.e. as a sibling that will receive a WalkOrder later. It never does: the manifest contains no such element, because 4-DIAG excluded `S3S-0224` as a DuplicateSkill of an identically-named node with the same 판정기준 and 산출. A forward declaration is therefore left unresolved at sweep end, and the family's count is described as 3 when only 2 were minted.
- **RootCause** (GIVEN): the split-set description is written from the Stage-2 child rows alone; the 4-DIAG exclusion record is not consulted, so an excluded sibling is deferred as future work instead of recorded as excluded. The same batch shows the habit in a neighbouring artifact, which mentions the same sibling only as "out of this batch's scope" without recording the exclusion.
- **EvidenceLinks**:
  - ledger position **176** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifact: [WO176 `HBRM_3M_METHOD`](./stage4_176_HBRM_3M_METHOD_concept_to_skill_closure_artifact.md) line 44
  - [4-DIAG duplicate diagnosis](./20260719_164605_stage4diag_duplicate_and_containment_diagnosis_artifact.md) line 145 — `S3S-0224` 측정 excluded as a DuplicateSkill of `S3S-0110` 측정
  - [closure manifest](./stage4_concept_to_skill_closure_manifest.md) — zero rows for that normalized name
  - correction basis on the ledger: position 177, whose artifact records the same sibling correctly
- **FailureMode**: describing an excluded node as a pending one leaves a promise the run cannot keep, and it survives to sweep end because nothing later looks for it. Severing the link means consulting the exclusion record when describing a split set.
- **ChangeSite**: the **rule** for describing split-set siblings in the `Roster` section.
- **CurrentRuleOrFormula**: siblings are enumerated from the parent's Stage-2 child rows; a sibling not in the current batch is described as following later.
- **RequiredChange**: before describing any sibling as forthcoming, check the 4-DIAG duplicate/containment diagnosis and the manifest. Record an excluded sibling explicitly as excluded, naming the exclusion basis and the owning node it was merged into; reserve "follows later" for siblings that actually carry a WalkOrder. State the family's minted count alongside the parent's declared count when the two differ, with the reason.
- **AcceptanceCriteria**: zero forward declarations remain unresolved at sweep end; every sibling described as forthcoming appears in the manifest, and every excluded sibling is recorded with its exclusion basis and owner.
- **NextRunExpectedEffect**: split-set descriptions match the population actually minted, and no artifact promises an element that the diagnosis already excluded.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the sibling-description rule. Do NOT revive the excluded sibling — the exclusion itself is upstream, recorded and correct; do not re-run 4-DIAG.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-11` — supporting cross-reference attributed to the wrong upstream record

- **PatchInstructionID**: `PI-S4-11`
- **Target**: Stage 4 — concept_to_skill closure (`ProvenanceGrounding`). GIVEN; not re-routed.
- **ProblemSummary**: the artifact asserts that a framing sentence from source line 53 is quoted on the sibling candidate `S1C-090`'s Stage-1 row and that this confirms the book-internal consistency of the two concepts. The named row contains no such string; the framing actually lives on a different candidate's evidence row (`S1C-092`). The source reading itself is correct; the attribution of where it is corroborated upstream is not, so the consistency claim rests on a row that does not carry it.
- **RootCause** (GIVEN): at closure, the framing was attributed to whichever sibling was in narrative focus rather than to the row that actually carries the string, and the row was not opened to confirm.
- **EvidenceLinks**:
  - ledger position **198** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifact: [WO198 `TEAM_ROLE`](./stage4_198_TEAM_ROLE_concept_to_skill_closure_artifact.md) line 28
  - [Stage-1 artifact](./20260719_164605_stage1_source_linked_identity_extraction_artifact.md) — line 515 (`S1C-090`'s evidence/structural_role row, zero occurrences of the framing) and line 517 (`S1C-092`'s evidence row, which carries it)
- **FailureMode**: a corroboration claim pointed at the wrong record is unverifiable at the place it names, so a reader either mistrusts a true reading or accepts an unchecked one. Severing the link means resolving the corroborating row by grep before naming it.
- **ChangeSite**: the **rule** for attributing a supporting cross-reference to an upstream candidate record in `ProvenanceGrounding`.
- **CurrentRuleOrFormula**: a supporting framing may be attributed to a sibling candidate's upstream row on contextual grounds, and the artifact then states that the attribution confirms internal consistency.
- **RequiredChange**: locate the corroborating row by searching the upstream artifact for the quoted string, and name the candidate ID and line the search actually returns. If several rows carry it, name them all; if none does, do not assert the corroboration. Never infer the owning record from narrative proximity.
- **AcceptanceCriteria**: every cross-reference attribution names a row that contains the cited string, verified by search; zero consistency claims rest on a row that does not carry the quoted text.
- **NextRunExpectedEffect**: corroboration statements can be checked at the coordinates they name.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the cross-reference attribution rule. Do NOT alter the element's own reading of source line 53, its `sourceLines`, or its relation to its sibling — Stage-1/2/3 outputs are correct here.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-12` — hand-narrated sibling roster with an off-by-one WalkOrder and a misplaced `sic`

- **PatchInstructionID**: `PI-S4-12`
- **Target**: Stage 4 — concept_to_skill closure (`InputAdmission`). GIVEN; not re-routed.
- **ProblemSummary**: the artifact re-narrates the already-minted siblings inside its sealed `InputAdmission` as `(권한/261, 보안/261 sic — 260, 검증/262, 승인/263, 기록/264 …)`. In the manifest 권한 is WalkOrder 260 and 보안 is 261, so the first token is shifted by one; the `sic — 260` correction marker is then attached to 보안, the token that was already right. Under either reading the assignment stays wrong: read 260 as 권한 and the marker points at the wrong item; read it as 보안 and 보안 becomes wrong.
- **RootCause** (GIVEN): the sibling roster was re-typed by hand into the sealed section rather than taken from the manifest, one WalkOrder was written one position off, and the correction the author noticed was inserted next to the neighbouring token instead of the one being corrected — then sealed.
- **EvidenceLinks**:
  - ledger position **265** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
  - closure artifact: [WO265 `GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY`](./stage4_265_GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY_concept_to_skill_closure_artifact.md) line 6
  - [closure manifest](./stage4_concept_to_skill_closure_manifest.md) — 권한 at WalkOrder 260, 보안 at 261
  - control case: ledger position 266, whose artifact narrates the same roster correctly
- **FailureMode**: a hand-copied roster inside a sealed section has no source to be checked against, and a correction marker attached to the wrong token leaves the record self-inconsistent in a way no reading resolves. Severing the link means generating the roster from the manifest and applying corrections to the token they correct.
- **ChangeSite**: the **document** element — the sibling-roster sentence in the sealed `InputAdmission`.
- **CurrentRuleOrFormula**: already-minted siblings are listed by hand as `<name>/<WalkOrder>` pairs, with in-line `sic` markers permitted for corrections.
- **RequiredChange**: take every `<name>/<WalkOrder>` pair from the manifest rather than typing it, and verify each pair against the manifest row before sealing. Never seal an in-line `sic` correction: fix the token itself before the record is finalized; if a correction must be recorded, attach it to the token it corrects and state what the wrong value was.
- **AcceptanceCriteria**: every WalkOrder cited in a sibling roster matches the manifest; zero sealed artifacts contain an unresolved `sic` marker.
- **NextRunExpectedEffect**: sibling rosters inside sealed sections agree with the manifest, and corrections are completed rather than annotated.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the roster-sentence rule. Do NOT alter the element itself or its siblings' minted order — the manifest is correct; only the artifact's narration is wrong.
- **Status**: recorded and handed off — never applied here.

### `PI-S4-13` — distinction asserted in the sealed record while 판정기준 and 산출 are identical

- **PatchInstructionID**: `PI-S4-13`
- **Target**: Stage 4 — concept_to_skill closure (`Contract` / `Interlock`). GIVEN; not re-routed.
- **ProblemSummary**: for a pair whose spans are identical (doc02 219-244) and whose primary quotation is the same sentence, the two artifacts write an affirmative claim that the nodes are distinguished from each other, while writing 판정기준 and 산출 that are substantively the same. An unadjudicated duplicate therefore reads as adjudicated. The same run also shows the opposite treatment of a structurally identical pair, which was recorded as duplicate extraction — the two descriptions cannot both be right.
- **RootCause** (GIVEN): Stage 4 inherited an unsettled duplicate from Stage 2 (see `PI-S2-01`) and, rather than recording the unsettled state, wrote a positive distinction claim without testing it against the artifact's own 판정기준 and 산출.
- **EvidenceLinks**:
  - ledger positions **38** and **39** in [Stage5FeedbackLedger](./stage5_feedback_ledger.md) — the Stage-4 halves of two `FEEDBACK_TO_MULTIPLE_STAGES` rows (their Stage-2 halves are `PI-S2-01`)
  - closure artifacts: [WO038 `AUGMENTATION`](./stage4_038_AUGMENTATION_concept_to_skill_closure_artifact.md) · [WO039 `SPIRIT_AUGMENTATION`](./stage4_039_SPIRIT_AUGMENTATION_concept_to_skill_closure_artifact.md)
  - [Stage-2 artifact](./20260719_164605_stage2_identity_fragmentation_artifact.md) — the child row at line 1322 (also 366, 2480) for **`S2C-0189`**; note the binding correction: row 38's prose names `S2C-0188`, a different sibling (인간중심 정신, line 868) of the same parent, and must not be inherited
  - the run's contrary description of the structurally identical 다양성 pair, recorded in the same batch's artifacts
- **FailureMode**: an assertion of distinction with no stated difference converts "not yet decided" into "decided", removing the signal that would have sent the pair back upstream. Severing the link means requiring the distinction to be demonstrated in the same record that claims it.
- **ChangeSite**: the **rule** governing distinction claims in the `Contract` / `Interlock` sections.
- **CurrentRuleOrFormula**: the artifact may state that a candidate is distinguished from a neighbour as prose, with no requirement that the artifact's own 판정기준/산출 differ from the neighbour's.
- **RequiredChange**: permit a distinction claim only when the record shows the difference — quote the two 판정기준 and the two 산출 and state where they diverge. When spans overlap and the two are substantively the same, do not claim distinction: record the pair as an unresolved duplicate suspect, name the counterpart's ID and WalkOrder, and route it back rather than sealing an assertion. Where the run has handled an identical pattern in the opposite way, cite that case and reconcile the two descriptions.
- **AcceptanceCriteria**: every distinction claim in a closure artifact carries the demonstrated 판정기준/산출 difference; zero pairs with overlapping spans and equivalent criteria are sealed with a bare distinction claim.
- **NextRunExpectedEffect**: with `PI-S2-01` fixed upstream, few such pairs reach Stage 4 at all; those that do are recorded as unresolved rather than closed by assertion.
- **DoNotChange**: one-shot, one-problem, instructs-not-performs. Change only the distinction-claim rule at Stage 4. Do NOT collapse, delete or re-mint either node in this run — Stage 5 never manipulates the candidate population; the collapse decision belongs to Stage 2 under `PI-S2-01`.
- **Status**: recorded and handed off — never applied here.

## Contributing ledger rows

| PatchInstructionID | ledger positions (READ-ONLY provenance) | candidates |
|---|---|---|
| `PI-S4-01` | 51, 54, 254, 305, 306 | WO051, WO054, WO254, WO305, WO306 |
| `PI-S4-02` | 142, 143, 144, 145, 146, 148, 149, 150, 239, 240 (Stage-4 half), 267 (Stage-4 half) | WO142-WO146, WO148-WO150, WO239, WO240, WO267 |
| `PI-S4-03` | 211, 212, 336 | WO211, WO212, WO336 |
| `PI-S4-04` | 348 | WO348 |
| `PI-S4-05` | 70, 71, 72, 73 | WO070-WO073 |
| `PI-S4-06` | 90, 132, 307 | WO090, WO132, WO307 |
| `PI-S4-07` | 157, 158, 159 | WO157, WO158, WO159 |
| `PI-S4-08` | 160, 161, 162 | WO160, WO161, WO162 |
| `PI-S4-09` | 101, 102 | WO101, WO102 |
| `PI-S4-10` | 176 | WO176 |
| `PI-S4-11` | 198 | WO198 |
| `PI-S4-12` | 265 | WO265 |
| `PI-S4-13` | 38 (Stage-4 half), 39 (Stage-4 half) | WO038, WO039 |

Rows 240 and 267 also charge Stage 1 (`PI-S1-01`); rows 38 and 39 also charge Stage 2 (`PI-S2-01`). Each dual-stage row contributes one directive per stage and no more.

## Links

- sourceLedger -> [Stage5FeedbackLedger](./stage5_feedback_ledger.md)
- consolidatedBy -> [E4 ledger-wide consolidation status](./_stage5_c2/e4_ledger_wide_consolidation_status.md)
- mintedBy -> [E5 directive entries record](./_stage5_c2/e5_directive_entries_record.md)
- referencedBy -> the run seed packet `stage5_next_run_seed_packet.md`, which references this file by PatchInstructionID (that packet is authored and landed downstream of this file; the resolvable direction is seed -> instruction)
- siblingFile -> [Stage5Stage1PatchInstruction](./stage5_stage1_patch_instruction.md)
- siblingFile -> [Stage5Stage2PatchInstruction](./stage5_stage2_patch_instruction.md)
- siblingFile -> [Stage5Stage3PatchInstruction](./stage5_stage3_patch_instruction.md)
