# C1 Execution Spec — Stage-5 per-element feedback pass (member 3 CULMINATION harness)

Binding spec for EVERY C1 batch agent. Read in full before appending anything.
Unit: `stage_5_candidate_feedback_ledger_append_skill` — invoked exactly ONCE per element.

- **runRoot**: `/Users/gesia/wwp_book_v0.2` — all writes under here. NEVER write to
  `/Users/gesia/wwp_book_v0.1` or any `~/.claude/skills/` path.
- **accumulator (ledger)**: `/Users/gesia/wwp_book_v0.2/_artifact/stage5_feedback_ledger.md`
  Append-only / immutable. Created zero-content (no schema, no header, 0 rows).
- **element set**: minted-PASS 369, manifest order, from
  `_artifact/stage4_concept_to_skill_closure_manifest.md` (WalkOrder 1..369).
- **per-element input slice**: `_artifact/stage4_<WO3>_<NormalizedName>_concept_to_skill_closure_artifact.md`

## 1. Ledger row format — EXACTLY ONE LINE per element, no header

```
| <pos> | WO<nnn> | <NormalizedName> | <한글 display name> | <DECISION> | <problem-or-absence> | <root-cause> | <targets> | <evidence> |
```

Hard rules:
- `<pos>` is the 1-based entry position and MUST equal the file line number. Gap-free.
  First append lands at position 1 (empty tail = position 0).
- ONE physical line. No embedded newlines. No `|` inside field text — use `/` or `·`.
- `<root-cause>` = `—` on the absence branch (no cause exists or is required).
- `<targets>` = `—` on NO_FEEDBACK_NEEDED; `HumanReview` on HUMAN_REVIEW_REQUIRED (NEVER a stage
  token — these become C2 blockers, not directives, and a stage token would misrepresent them as
  directive-eligible); otherwise the stage(s), e.g. `Stage2` / `Stage1+Stage2`.
- `<evidence>` = checkable pointers: artifact filename + section, source doc + line, manifest WO.
  Never empty. NO_FEEDBACK_NEEDED MUST carry the evidence that settles the absence —
  a bare PASS is FORBIDDEN (spec section 8).
- 한글 preserved verbatim in display name, problem text, and cause text. UTF-8.

## 2. Append protocol (per element, strict serial)

1. Read the element's Stage-4 closure artifact in full.
2. Evaluate (section 3). Render EXACTLY ONE of the 7 enum values.
3. Conformance-check the rendered line BEFORE appending: one line; pos == next line number;
   decision in the 7-enum; branch-wise givens honored (signal ⇒ problem+cause; absence ⇒
   problem field states what was checked + evidence, cause `—`); evidence non-empty.
4. **CITATION VERIFICATION (mandatory — every ID *and* every line number).** Before you append,
   open/grep each thing you cite and confirm it says what you claim:
   - Every `S1C-`, `S2C-`, `S3S-` ID, in ANY field including prose.
   - Every artifact/source **line number** you cite.
   **Never pattern-shift.** Do not infer an ID or a line number from a neighbouring block's
   offset — read it. This has already produced TWO unrepairable errata on an immutable ledger:
   batch 03 wrote `S2C-0188` where `S2C-0189` was correct (a different sibling of the same
   parent); batch 05 cited stage-2 line 1390 where 1389 was correct (1390 is blank). Both were
   inferred from an adjacent block's numbering rather than read. Verify, then append.
4. Append with `>>` ONLY. Never rewrite, reorder, or edit the file. Never use Write/Edit on it.
5. Verify: line count increased by exactly 1, and the new last line is yours.

If conformance FAILS for an element: do NOT append. Record the failure, STOP the batch
immediately, and report the failure + which elements were not reached. Do not continue.

## 3. Decision rubric — 7-enum (render exactly one)

Stage-4 sealed every element at 12/12 conformance, so the closure files exist and links resolve.
That is NOT sufficient for NO_FEEDBACK_NEEDED. Evaluate the CONTENT quality against the source.

- **NO_FEEDBACK_NEEDED** — checked and clean. Must state WHAT was checked (parent link, sibling
  boundary, axis purity, source count) and the evidence that settles it.
- **FEEDBACK_TO_STAGE_1** — source-extraction defect: wrong/missing evidence, wrong line range,
  mis-stated structural_role, a count read wrongly off the source text, a back-reference to a
  section that does not exist in the cited chapter.
- **FEEDBACK_TO_STAGE_2** — fragmentation defect: split element count ≠ source enumeration;
  parent node missing while its children exist (or vice versa); sibling boundary overlap /
  duplicate coverage; axis purity violation (siblings at mismatched levels or mixed axes);
  collapse / DuplicateSkill exclusion mis-decided; `fragmentedFrom` parent unresolved.
- **FEEDBACK_TO_STAGE_3** — ordering defect: SequenceOrder gap or inconsistency not reconciled;
  prev/next mis-wired; knowledge-chain position wrong for the concept's dependencies.
- **FEEDBACK_TO_STAGE_4** — closure defect: a closure file thin/stubbed or not grounded in the
  book; a link recorded as resolving that does not; interlock/conformance recorded weakly;
  a forward declaration left unresolved at sweep end.
- **FEEDBACK_TO_MULTIPLE_STAGES** — defects genuinely rooted in ≥2 stages. Use `targets` to name
  them. Do not use this as a hedge — only when each named stage owns a distinct defect.
- **HUMAN_REVIEW_REQUIRED** — the pipeline cannot settle it: the author's own text is internally
  inconsistent (stated count ≠ the author's own enumeration), or two concepts carry an IDENTICAL
  한글명 and only the author can choose the canonical naming. These become BLOCKERS in C2, never
  directives — reserve for genuine editorial ambiguity, not for pipeline defects.

Judge honestly. Do not manufacture defects to look thorough, and do not wave through a real one.

## 4. Systemic checklist — apply to EVERY element

Most of this run's elements are children split out of container parents. Check:

1. **Parent–child link (`fragmentedFrom`)** — does the recorded parent resolve? Excluded
   OverBroadParents legitimately have no `_identity` file and link via the Stage-2 SplitSet
   anchor — that form is CORRECT, not a defect. A defect is: a parent that resolves to nothing,
   or a family where the source names a parent concept but no node carries it while its children
   exist as name-prefixed siblings.
2. **Sibling boundary overlap** — do two siblings cover the same source span / same claim?
   **Detect duplicates by SUBSTANCE, not by name (batch-03 finding, applies run-wide).** The
   4-DIAG DuplicateSkill detector is NAME-KEYED — all 25 pairs it caught cite basis
   "정규화 명칭 … 일치". Two nodes covering the same source span under different labels are
   structurally invisible to it. Proof that this is a real blind spot, not a hypothesis: the
   다양성 pair (S3S-0050 / S3S-0053) WAS collapsed because its two labels differed by a single
   space, while the structurally identical 증강 pair (WO038 `AUGMENTATION` / WO039
   `SPIRIT_AUGMENTATION`) survived because one label carries the extra word 실현.
   So test duplicates by: **sourceLines overlap + 판정기준/산출 identity**, never by display-name
   string. A Stage-4 artifact asserting in prose that it "is distinguished from" a neighbour does
   NOT settle this — check whether 판정기준 and 산출 actually differ.
3. **Axis purity** — are siblings at the SAME level and on the SAME axis? A baseline state
   sitting beside two evolution forms, or a mix of rights/steps/indicators in one family, is a
   violation.
4. **Source count vs actual element count** — if the source says "N개/N층/N단계/N지표", count the
   minted siblings. Mismatch is a real defect unless the artifact already reconciles it with
   evidence.
5. **Citation line accuracy (batch-04 finding — check every element).** Open the source at each
   cited line number and confirm it actually contains the quoted text. Two confirmed instances so
   far (WO051 cites 365 for a quote at 367; WO054 cites 356 — a BLANK line — for a quote at 357),
   both pointing at the non-content line just before the real quote. Note the check demonstrably
   exists but was applied inconsistently: WO048 self-caught this same error before sealing. When
   the misattribution is in a secondary/supporting citation while the primary evidence line and
   `sourceLines` are correct, element identity is unaffected → FEEDBACK_TO_STAGE_4, low severity.
6. **Name collision** — identical or near-identical 한글명 across families. If the Stage-4
   artifact already separates them by layer with explicit reconciliation, that is handled; if
   the 한글명 is COMPLETELY identical and unreconciled, it is a HUMAN_REVIEW candidate.

## 5. Known-suspect WalkOrders (verified by the harness — evaluate, do not assume)

These were confirmed against the source before the run. The owning batch MUST examine them.
Elements NOT listed here are still evaluated on their own merits.

- **WO 233–239 (TRB 진화 family) — ⚠️ THIS HARNESS HYPOTHESIS WAS REFUTED. DO NOT CHASE IT.**
  The harness originally flagged: "source line 131 enumerates two forms (Bot-Aided TRB, Human-Bot
  Coupled TRB) but neither parent has an identity node, while a non-enumerated baseline
  `TRB_STAGE_HUMAN_ONLY` (WO239) got one — level/axis mismatch."
  **Batch 14 disproved this with evidence:** both forms DO have nodes — `S2C-0094`/`S3S-0289` and
  `S2C-0095`/`S3S-0293` — as excluded SPLIT parents, which is the §5b-CORRECT form, not an
  omission. And WO239 does not sit beside the two forms at all: it belongs to a THIRD family under
  `S2C-0096 TRB_EVOLUTION_PATH` (source line 191). There is no level mismatch.
  The batch owning WO233-239 should verify this inheritance holds for its own elements and then
  move on — do not re-raise the refuted claim. Recorded here as a correction to the harness's own
  §5, kept visible rather than deleted so the reasoning trail stays honest.
- **WO 304–306 (예측지능)** — `08_4부_8장...ESG_확장.md` line 87 back-references "앞서 1장에서
  언급하였듯이, AI 예측지능 체계도 상 5층까지 완비되면". Chapter 1 contains NO 예측지능 mention
  (verified: zero grep hits in `01_*.md`). `PREDICTIVE_INTELLIGENCE` (WO304) has only 2 children
  (`PIS_WORLD_MODEL`, `PIS_CONTEXT_DESIGN`), not 5 layers. Check the relationship to the
  `LLM_LAYER_*` family (WO10-13), which carries 5층 in 4 nodes ("1~2층" merged).
- **WO 10–13 (LLM_LAYER)** — 5 layers carried by 4 nodes; layers 1 and 2 merged into one node.
  Verify the merge is source-warranted, and check overlap with WO304-306.
- **WO 359–369 (12지표)** — source says "12지표"; the Stage-2 SplitSet produced 13 elements
  (S2C-0513..0525); only 11 were admitted (2 excluded as DuplicateSkill). 12 ≠ 13 ≠ 11.
  See `_handoff/sweep_status.md` batches 060-062 for the recorded reconciliation.
- **Name collisions — corrected and made precise (batch 02 finding, harness-verified):**
  - RAW-STRING exact duplicate across all 369 display names: **`역할` at WO124 and WO256** — the
    ONLY exact pair in the manifest. **ADJUDICATED by batch 09**: NOT duplicate coverage — different
    source documents, disjoint spans, different parents and class, 판정기준 at different layers
    (ontological vs operational). But the 한글명 is a raw-string exact match and neither artifact
    mentions the other, which meets §4 item 6 exactly → WO124 carries **HUMAN_REVIEW_REQUIRED**
    (`targets: HumanReview`). Not a Stage-2 fault; the author uses the bare word twice.
    **The batch owning WO256 must RECORD the collision, not double-file it** — judge WO256 on its
    own merits and reference WO124's row rather than raising a second HUMAN_REVIEW for one issue.
  - ORDINAL-PREFIXED collisions (identical once the `N. ` prefix is stripped, so a naive
    raw-string scan misses them): **WO353 `4. 노동 전환` vs WO362 `노동 전환`**, and
    **WO356 `7. 감사 기록` vs WO366 `감사 기록`**. The concept names ARE identical; only the
    numbering differs. `sweep_status.md` records these as 한글명 완전 동일 and states they were
    separated by layer (단계 vs 지표) with explicit reconciliation — verify that reconciliation
    actually holds in the artifacts rather than assuming it.
  - WO348 is `AI 전환권` (a right), NOT `노동 전환` — it is a related-but-distinct node.
  - When scanning for collisions, strip leading `N. ` ordinals before comparing.
- **ROS_\* (책임운영체계 7원소)** — excluded via a 2-hop DuplicateSkill chain; content carried by
  `GOVERNANCE_CONTEXT_ELEMENT_*` (WO260-266). No citable `ROS_*` WalkOrder exists.

## 5b. Precedents established by earlier batches (follow for consistency)

These were adjudicated with evidence by a prior batch. Do not re-litigate them; apply them.
If your range gives you NEW evidence that overturns one, say so explicitly in your report.

- **Stage-1 class vocabulary broader than the Stage-4 pick-list** — `STRUCTURE` (~41 uses),
  `METHOD`, `INDEX` are not in `CONCEPT|ROLE|PRINCIPLE|INDICATOR|PROCESS|ARTIFACT`, so artifacts
  infer a pick-list class. This is a spec-sanctioned carve-out ("pick from Stage-1 class, else
  infer") and is recorded in each artifact's FormSpec. NOT a defect — do not raise it.
- **`LLM_LAYER` 5층/4노드** — the "1~2층" merge IS source-warranted (line 151 predicates over
  "1~2층" as one band; corpus-wide grep finds zero passages giving 1층 and 2층 distinct content).
  A reconciled count, not a mismatch.
- **Stage-1 MANUAL/TupleOnly holds** — a source enumeration cell with no minted node is NOT a
  count defect when Stage-1 recorded it as MANUAL with a rationale (e.g. WO003's 2×2 table:
  4 cells, 3 minted, the 4th held as S1C-007 "may be TupleOnly"). Check for the Stage-1 hold
  before calling a missing cell a defect.
- **`targets` on HUMAN_REVIEW_REQUIRED = `HumanReview`**, never a stage token.
- **Excluded OverBroadParent linkage** — a `fragmentedFrom` pointing at an excluded parent that
  has no `_identity` file, linked via the Stage-2 SplitSet anchor, is the CORRECT specified form.
  Not a dangling link, not a defect.
- **`CORE_MANAGEMENT_SPIRITS` (S2C-0026) = 3 children, not 4** — settled by batch 03b with six
  independent confirmations. 4-DIAG line 63 says 4 because it copied the parent's own un-updated
  Split rationale (Stage-2 line 706, 「하위 원소 4개를 열거」); the axis-purity correction at line
  1313 moved 인간중심주의 out to be its own C0 node (`S2C-0027`, `fragmentedFrom: none`). Stale
  bookkeeping with no operative effect — nothing wrongly minted or excluded. Do not re-open.
- **`collapsedFrom: none` on all 369 is CORRECT** — Stage-2 performed zero Merges; the 4-DIAG
  DuplicateSkill exclusions are not Merges. Not an omission.

### CHARGE THIS when you meet it: `SD-??` unresolved provenance placeholder

Stage-1 carries **203** instances of the literal token `SD-??` where a source-document ID belongs.
A real registry `SD-01`..`SD-12` exists, so `??` is an unfilled reference, not a notation choice.
It is transcribed verbatim into **9** Stage-4 artifacts: **WO017, 043, 044, 168, 195, 197, 240,
267, 280**.

Policy (set by the harness after batches 01-03b): if one of those WOs is in YOUR range, render
**FEEDBACK_TO_STAGE_1** for it, citing the `SD-??` occurrences in its artifact plus the Stage-1
artifact. Severity is low — the primary `sourceDocument` field is correct and the line numbers
resolve — but an unresolved placeholder in a provenance field is not clean, and C2 will consolidate
all such rows into ONE Stage-1 formula problem.

Known inconsistency, recorded honestly: **WO017, WO043, WO044 were appended BEFORE this policy**
and carry NO_FEEDBACK_NEEDED. The ledger is immutable so those rows stand. C2 is told separately
that the true scope is 9 artifacts / 203 instances, not merely the rows that charge it.

## 6. Never-do

- Never append before the conformance check passes.
- Never mutate, reorder, or delete a prior ledger row.
- Never author patch instructions or seed packets (that is C2, after the barrier).
- Never mint identity candidates or revive excluded candidates.
- Never write outside runRoot.
- Never process elements out of manifest order; never run elements in parallel.
