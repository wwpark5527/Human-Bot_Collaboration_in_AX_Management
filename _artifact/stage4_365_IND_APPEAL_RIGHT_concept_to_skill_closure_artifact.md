# Stage-4 Concept-To-Skill Closure Artifact — WalkOrder 365 — IND_APPEAL_RIGHT (이의제기권)

runID `20260719_164605` · runRoot `/Users/gesia/wwp_book_v0.2` · unit `stage_4_concept_to_skill_closure_skill` (4-EXEC)

## InputAdmission
- WalkOrder: 365
- NormalizedName: `IND_APPEAL_RIGHT` / name: `ind_appeal_right`
- displayName: "이의제기권"
- class (Stage-1 C0, verbatim): `INDEX`
- Source batch pack: `packs/batch_361_366.md`
- Admitted for closure: Stage-3 row S3S-0462 carries `KnowledgeChainReady = YES`, Stage-2 fragmentationAction = SPLIT / settlement KEEP, Stage-1 C0 roster disposition KEEP. Admission criteria satisfied.
- **Class note:** `INDEX` is carried VERBATIM from the Stage-1 C0 row S1C-183 — not normalized, not substituted, not inferred. Established value in this run (precedent WO178-180, WO189-192, WO359-360, and WO361-364 earlier in this batch).

## FormSpec
Per CLOSURE_SPEC.md: 6 closure files (`_identity`, `_goal`, `_task`, `_knowledge`, `_method`, `_skill/<NAME>/SKILL.md`) + 1 per-candidate 12-section artifact + 1 appended manifest row. Identity frontmatter carries `class: INDEX` verbatim from Stage-1 C0 row S1C-183.

## Contract
- Input: Stage-1 C0 roster row S1C-183, Stage-2 SplitSet child S2C-0519 (fragmentedFrom S2C-0158), Stage-3 ordered row S3S-0462.
- Output: 6 closure files under runRoot resolving a full identity→goal→task→knowledge→method→skill chain, plus this artifact, plus one manifest row.
- Precondition: none of the 6 files pre-existed (verified by path test before authoring — all 6 reported absent). Postcondition: all 6 exist, all internal links resolve or are explicitly-permitted forward declarations.

## ConceptToSkillClosure (the 6 paths)
1. `_identity/IND_APPEAL_RIGHT.md`
2. `_goal/ind_appeal_right_goal.md`
3. `_task/ind_appeal_right_task.md`
4. `_knowledge/ind_appeal_right_knowledge.md`
5. `_method/ind_appeal_right_method.md`
6. `_skill/IND_APPEAL_RIGHT/SKILL.md`

## ProvenanceGrounding
- Stage-1 C0 roster row: S1C-183 `INCLUSIVE_TRANSITION_ESG_12_INDICATORS` — 포용전환 ESG 12지표 — class INDEX — KEEP — `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 531-548.
- Stage-1 evidence: "다음 지표(가칭 포용전환 ESG 12지표)는 조직이 AI 전환을 책임 있게 운영하는지 확인하기 위한 기본 항목이다." — structural_role: named measurement set of 12 indicators making 포용전환 ESG measurable.
- Stage-2 settled record: S2C-0519 | S1C-183 | 이의제기권 | `ind_appeal_right` | `IND_APPEAL_RIGHT` | SPLIT | KEEP | fragmentedFrom S2C-0158.
- Stage-2 SplitSet child detail: 정의 "AI 결과에 대한 재검토 요청이 실제로 접수되고 처리되는지를 보는 지표." 판정기준 "AI 결과 재검토 요청 건수와 수정·구제 처리율." 산출 "재검토 요청 건수와 수정·구제 처리율." evidence "이의제기권: AI 결과 재검토 요청 건수, 수정·구제 처리율" at line 539.
- Stage-3 row: S3S-0462, SequenceOrder 462, KnowledgeChainReady YES.
- Source-document verification (this run): line-addressed read against `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` confirms line 539 reads `- 이의제기권: AI 결과 재검토 요청 건수, 수정·구제 처리율` — the pack's evidence string matches verbatim once the `- ` list marker is dropped. Supplementary citations independently verified this run: line 531 (the transition sentence introducing the 12지표), line 492 (`- AI 이의제기권: AI 평가, 추천, 결정에 대해 재검토를 요구할 권리`, the corresponding 8대 권리 element), and line 525 (`  6. 이의제기 절차         AI 결과에 대한 설명, 재검토, 수정 요청 구조 마련            S / G`, the 9단계 step that establishes the appeal channel — quoted with leading indentation dropped, internal column spacing preserved, as it sits inside the fenced code-block table).
- Cross-reference WalkOrder claims verified on disk this run by reading the target identity frontmatter: `RIGHT_AI_APPEAL` walkOrder 347 / sourceLines 492 / displayName "AI 이의제기권", `STEP_APPEAL_PROCEDURE` walkOrder 355 / sourceLines 525 / displayName "6. 이의제기 절차". Both match the claims made in the knowledge file.
- **12지표 list-layout — THIS CANDIDATE SITS AT THE BREAK (verified this run).** The indicator list is NOT contiguous. Indicators run at lines 533-539 and **this candidate, at line 539, is the LAST item of that contiguous run**. Line 540 is blank; **line 541 is an unrelated paragraph** reading in part "EU AI Act는 위험 기반 AI 규칙을 제시하며, UNESCO와 OECD는 인간 권리, 투명성, 인간 감독, 책임성을 강조한다"; line 542 is blank. The remaining indicators resume at line 543. Both line 539 and line 543 were read directly this run and confirmed against the pack. Consequently **no line in the 540-542 range was consulted or cited as context for this candidate**, and the next candidate's line number (WO366 = 543) was verified independently rather than inferred by increment. The 4-line jump between WO365 and WO366 is the source's own layout, not a citation error; SequenceOrder nonetheless stays contiguous across the break (462 → 463).

## ResolvableLinks
- Stage-1 row: `../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member`
- Stage-1 evidence: `../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member`
- Stage-2 settled row: `../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary`
- Stage-2 SplitSet: `../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element`
- Stage-3 row: `../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0462`
- Neighbours: previous `./IND_EXPLAINABILITY.md`, next `./IND_AUDIT_RECORD.md`
- Anchor verification (this run): the four Stage-1/Stage-2 heading anchors were confirmed by reading the target headings directly (Stage-1 lines 268 and 434; Stage-2 lines 175 and 1208); each slugifies to the anchor string used above. The Stage-3 per-row anchor `id="s3s-0462"` was confirmed present by direct grep.

## Roster
- Parent (fragmentedFrom): S2C-0158 `INCLUSIVE_TRANSITION_ESG_12_INDICATORS` — 포용전환 ESG 12지표. Excluded OverBroadParent: no WalkOrder, no `_identity` file (verified absent on disk this run; holds Stage-3 SequenceOrder 455 only); linked via the Stage-2 SplitSet anchor.
- SplitSet accounting: the Stage-2 SplitSet for S2C-0158 holds **13 elements** (`S2C-0513` .. `S2C-0525`), of which only **11** are admitted roster members occupying **WO359-369**. `S2C-0523` (맥락자본, S3S-0466) and `S2C-0524` (책임운영체계, S3S-0467) were excluded as **DuplicateSkill** and carry no WalkOrder and no `_identity` file — 맥락자본 because `CONTEXT_CAPITAL` is already minted at WO324 (rationale recorded in full in the WO361 artifact). Hence the family runs 11 wide, and a SequenceOrder gap appears at the **WO368→369** seam.
- Sibling position: `IND_AI_ACCESSIBILITY` (WO359, 1st) → `IND_AI_EDUCATION` (WO360, 2nd) → `IND_AI_UTILIZATION_CAPABILITY` (WO361, 3rd) → `IND_LABOR_TRANSITION` (WO362, 4th) → `IND_HUMAN_JUDGMENT_RIGHT` (WO363, 5th) → `IND_EXPLAINABILITY` (WO364, 6th) → **`IND_APPEAL_RIGHT` (WO365, this candidate, 7th of the family)** → `IND_AUDIT_RECORD` (WO366, final candidate of this batch) → remaining admitted indicators through WO369.
- At this closure, 7 of 11 admitted fragments of S2C-0158 are minted. The SplitSet remains legitimately open; indicators 8-11 (WO366-369) follow — WO366 closes this batch, WO367-369 follow in the final batch.

## Landing
All 6 files landed under runRoot `/Users/gesia/wwp_book_v0.2`, verified present on disk by direct path test:

| # | path | on-disk |
|---|---|---|
| 1 | `_identity/IND_APPEAL_RIGHT.md` | PASS |
| 2 | `_goal/ind_appeal_right_goal.md` | PASS |
| 3 | `_task/ind_appeal_right_task.md` | PASS |
| 4 | `_knowledge/ind_appeal_right_knowledge.md` | PASS |
| 5 | `_method/ind_appeal_right_method.md` | PASS |
| 6 | `_skill/IND_APPEAL_RIGHT/SKILL.md` | PASS |

## LinkClosure
- Identity → goal/task/knowledge/method/skill: all 5 Derivation links resolve to files landed above (PASS).
- goal/task/knowledge/method → identity backlink `../_identity/IND_APPEAL_RIGHT.md`: resolves (PASS).
- skill → Derivation chain, 2-level-up prefix `../../`: all 5 targets tested from `_skill/IND_APPEAL_RIGHT/` and resolve — 5/5 (PASS).
- sequencePreviousIdentity → `./IND_EXPLAINABILITY.md`: file exists on disk (verified by path test this run; minted at WalkOrder 364 earlier in this same batch), resolves (PASS).
- **sequenceNextIdentity → `./IND_AUDIT_RECORD.md`: INTRA-BATCH forward declaration.** The file does not exist on disk at the moment of this closure (verified by path test). WalkOrder 366 lies INSIDE this batch's range (361-366) and is the very next — and final — candidate of this batch; strict-serial WalkOrder minting makes such a declaration structurally unavoidable. This link resolves later in this same batch when WO366 is minted. Correct forward declaration, NOT a dangling link, not counted against link closure.
- Back-reference closure: WO364's `sequenceNextIdentity` → `./IND_APPEAL_RIGHT.md` is now RESOLVED on disk by this closure, discharging the intra-batch forward declaration recorded in the WO364 artifact.
- fragmentedFrom → Stage-2 SplitSet anchor (parent S2C-0158 is an excluded OverBroadParent with no `_identity` file — verified absent on disk this run): resolves to the Stage-2 artifact section, the specified linkage form for excluded parents (PASS).
- Unminted-reference discipline: the Roster section names `S2C-0523` (맥락자본) and `S2C-0524` (책임운영체계) as excluded DuplicateSkill elements in prose, not as links. The knowledge file names `RIGHT_AI_APPEAL` (WO347), `STEP_APPEAL_PROCEDURE` (WO355), `IND_EXPLAINABILITY` (WO364) and `IND_HUMAN_JUDGMENT_RIGHT` (WO363) as prose NormalizedNames; all four are present on disk and their WalkOrder claims were verified this run.
- Stage-1/2/3 provenance links: all anchors verified present in the existing Stage artifact files.
- Zero unexplained dangling links. LinkClosure: **PASS** (with the one expected intra-batch forward declaration noted above).

## Interlock
- Stage-1 ↔ Stage-2: S1C-183 → S2C-0519 fragmentedFrom S2C-0158 — consistent.
- Stage-2 ↔ Stage-3: S2C-0519 → S3S-0462 — consistent (Stage-3 row cites S2C-0519 directly).
- Stage-3 ↔ Stage-4 identity: S3S-0462 SequenceOrder 462 matches walkOrder 365's position in the roster.
- class carried verbatim from Stage-1 C0 (`INDEX`) — no normalization, no substitution applied.
- fragmentedFrom explicitly populated (S2C-0158) — matches Stage-2 SPLIT action; mandatory for this SPLIT child, never `none`. collapsedFrom explicitly `none`.
- **Neighbour reconciliation.** Neighbours are the WalkOrder-adjacent roster entries from the pack, never the raw Stage-3 sequencePrevious/sequenceNext. Here both readings agree — raw Stage-3 sequencePrevious for S3S-0462 is S3S-0461 (설명 가능성 = `IND_EXPLAINABILITY`, WalkOrder 364) and raw sequenceNext is S3S-0463 (감사 기록 = `IND_AUDIT_RECORD`, WalkOrder 366); both coincide with the WalkOrder-adjacent neighbours. **SequenceOrder runs contiguously (461 → 462 → 463) even though the SOURCE LINES jump 539 → 543** — the source-layout break does not perturb the Stage-3 ordering. There is no SequenceOrder gap anywhere in batch_361_366.
- SplitSet position: 7th admitted fragment of S2C-0158, of 11 admitted. See Roster.
- **Layer discipline — collisions with both the 권리 층 and the 단계 층.** This node is an INDICATOR:
  - **권리 층** — `RIGHT_AI_APPEAL` (AI 이의제기권, WalkOrder 347, line 492): "AI 평가, 추천, 결정에 대해 재검토를 요구할 권리". An **entitlement**. The names differ by a single prefix: the indicator is 이의제기권, the right is AI 이의제기권.
  - **실행 단계 층** — `STEP_APPEAL_PROCEDURE` (6. 이의제기 절차, WalkOrder 355, line 525): "AI 결과에 대한 설명, 재검토, 수정 요청 구조 마련". The **execution step** that builds the appeal channel.
  - **측정 지표 층** — **this identity** (이의제기권, WalkOrder 365, line 539): "AI 결과 재검토 요청 건수, 수정·구제 처리율". A **measurement** — whether requests actually arrived through that channel and whether they changed outcomes.
  The relation is direct: **6단계 builds the channel; this indicator counts what came through it and what it changed.** This node's 정의/판정기준/산출 speak only in measurement terms (요청 건수, 처리율, 분자·분모 정의, 처리 소요 기간, 해석 근거, 측정 주기, 시계열) and adopt neither rights vocabulary ("~요구할 권리", "보장한다") nor construction vocabulary ("구조를 마련한다" as an action this node performs).
- **Rights-flavoured name caution (recorded, second occurrence).** The indicator's own 한글 name contains "권" (이의제기**권**), reading like an entitlement though the measured content is operational. The closure states this explicitly in the identity 개념 정의 and in the knowledge file, which also cross-notes the same caution recorded at WO363 (인간 판단권). Two of this batch's six candidates carry rights-flavoured names.
- Two-value interlock — **inflow/outcome pairing**: the source names an inflow count ("AI 결과 재검토 요청 건수") and an outcome rate ("수정·구제 처리율"). Both are carried through consistently: identity 판정기준, goal 목표, task 과업 1-8, method 절차 1-8 and 판정기준, skill 절차 1-8. The method and skill 판정기준 make reporting the 요청 건수 alone an explicit FAIL, keeping the 처리율 half from being dropped.
- **Directional ambiguity of the first value — the sharpest measurement caution in this batch.** Unlike every preceding indicator in the family, 재검토 요청 건수 has **no fixed good direction**. A high count may mean either many faulty decisions or a well-functioning, accessible channel; a low count may mean either accurate decisions or a channel people cannot find, do not know about, or believe to be futile. The closure therefore requires an interpretive basis (channel existence, accessibility, and the preceding indicator's comprehension level) to be recorded alongside the count, and makes reporting a low or zero count as a good result without that basis an explicit FAIL (condition 나). This is structurally analogous to the detectability guard introduced at WO363 but distinct in mechanism: there a zero could mean undetectable, here a zero can mean suppressed.
- **Numerator fidelity — 수정·구제, not 종결.** The source wrote "**수정·구제** 처리율", not "처리율". The closure treats those two words as constraining the numerator: only decisions actually corrected or claimants actually remedied count. Reviewing every request and rejecting them all would yield a 100% closure rate while producing a 0% 수정·구제 처리율, and conflating the two is FAIL condition (가). Processing duration is additionally required, since a remedy delivered too late does not function as a remedy.
- Family-order interlock: the preceding indicator is this one's precondition — 설명 가능성(538, WO364) measures whether recipients understood the basis of a decision, and a decision one has not understood cannot be meaningfully appealed. The knowledge file records that a low 이해도 alongside a low 요청 건수 reads as inability to mount an appeal rather than as decision accuracy, which is the concrete way the two indicators must be read together (538 → 539).
- Internal chain interlock: all six files cross-reference the same `identity: IND_APPEAL_RIGHT` / `displayName: "이의제기권"` / `runID: 20260719_164605` triple. Consistent.
- Interlock: PASS.

## Conformance

| # | condition | verdict | evidence |
|---|---|---|---|
| 1 | `_identity/IND_APPEAL_RIGHT.md` exists under runRoot | PASS | path test confirmed (Landing row 1) |
| 2 | `_goal/ind_appeal_right_goal.md` exists under runRoot | PASS | path test confirmed (Landing row 2) |
| 3 | `_task/ind_appeal_right_task.md` exists under runRoot | PASS | path test confirmed (Landing row 3) |
| 4 | `_knowledge/ind_appeal_right_knowledge.md` exists under runRoot | PASS | path test confirmed (Landing row 4) |
| 5 | `_method/ind_appeal_right_method.md` exists under runRoot | PASS | path test confirmed (Landing row 5) |
| 6 | `_skill/IND_APPEAL_RIGHT/SKILL.md` exists under runRoot | PASS | path test confirmed (Landing row 6) |
| 7 | Stage-1/2/3 provenance present as resolvable links; `fragmentedFrom`/`collapsedFrom` present | PASS | identity frontmatter carries all 3 stage links + fragmentedFrom link (S2C-0158, mandatory for this SPLIT child) + collapsedFrom `none`; all anchors verified present against the target headings |
| 8 | sequencePreviousIdentity/sequenceNextIdentity are resolvable links, never bare names | PASS | frontmatter uses `"[IND_EXPLAINABILITY](./IND_EXPLAINABILITY.md)"` / `"[IND_AUDIT_RECORD](./IND_AUDIT_RECORD.md)"` — both markdown link syntax, not bare names (the latter is an intra-batch forward declaration, still a well-formed link) |
| 9 | terminal skill Derivation links resolve to actual generated files | PASS | all 5 `../../` targets tested from `_skill/IND_APPEAL_RIGHT/` on disk — 5/5 resolve |
| 10 | link_closure PASS (zero dangling) | PASS | see LinkClosure — prev resolves (WO364, this batch); next (`IND_AUDIT_RECORD`, WO366) is the intra-batch forward declaration minted next and last in this same batch, explicitly not counted as dangling; WO364's forward declaration discharged by this closure |
| 11 | interlock PASS (Stage 1/2/3/4 + internal chain) | PASS | see Interlock, including the 권리 collision with `RIGHT_AI_APPEAL` (WO347) and the 단계 collision with `STEP_APPEAL_PROCEDURE` (WO355), the second rights-flavoured-name caution, the directional-ambiguity guard, the 수정·구제 numerator fidelity note, and the source-break record (line 539 is the last of the contiguous run; SequenceOrder unaffected) |
| 12 | conformance PASS | PASS | this table, all 12 rows PASS |

All 12 PASS conditions satisfied.

## VerifiedRecord
- WalkOrder 365 — `IND_APPEAL_RIGHT` — 이의제기권 — minted-PASS.
- Stage-3 ID: S3S-0462. Stage-2 ID: S2C-0519. Stage-1 ID: S1C-183. class `INDEX` (verbatim from Stage-1 C0).
- 6 closure files landed and verified on disk under runRoot `/Users/gesia/wwp_book_v0.2`.
- Manifest row appended: WalkOrder 365 | 이의제기권 | IND_APPEAL_RIGHT | S3S-0462 | minted-PASS.
- SplitSet note: 7 of 11 admitted fragments of `INCLUSIVE_TRANSITION_ESG_12_INDICATORS` (S2C-0158) now minted (WO359-365). The family runs 11 wide across WO359-369; a SequenceOrder gap appears at the WO368→369 seam, none within this batch.
- Layer note: this node is the 측정 지표 층 — distinct from `RIGHT_AI_APPEAL` (WO347, 권리, AI 이의제기권, differing by one prefix) and `STEP_APPEAL_PROCEDURE` (WO355, 실행 단계, 6. 이의제기 절차). The 6단계 step builds the channel this indicator measures. Recorded in Interlock.
- **Source-layout note:** this candidate's line 539 is the LAST line of the source's contiguous indicator run (533-539). Line 541 is an unrelated EU AI Act / UNESCO / OECD paragraph; the list resumes at line 543. The next candidate (WO366) cites line 543, and that jump was verified by direct read rather than inferred. SequenceOrder stays contiguous (462 → 463) across the break.
- Measurement-shape note: the first value (재검토 요청 건수) is **directionally ambiguous** — neither high nor low is good on its own — so an interpretive basis must accompany it; and the second value's numerator is constrained by the source's own wording to 수정·구제, excluding rejections and bare closures.
- runID `20260719_164605`.
