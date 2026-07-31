# Stage-4 Concept-To-Skill Closure Artifact — WalkOrder 355 — STEP_APPEAL_PROCEDURE (6. 이의제기 절차)

runID `20260719_164605` · runRoot `/Users/gesia/wwp_book_v0.2` · unit `stage_4_concept_to_skill_closure_skill` (4-EXEC)

## InputAdmission
- WalkOrder: 355
- NormalizedName: `STEP_APPEAL_PROCEDURE` / name: `step_appeal_procedure`
- displayName: "6. 이의제기 절차"
- class (Stage-1 C0, verbatim): `METHOD`
- Source batch pack: `packs/batch_355_360.md`
- Admitted for closure: Stage-3 row S3S-0451 carries `KnowledgeChainReady = YES`, Stage-2 fragmentationAction = SPLIT / settlement KEEP, Stage-1 C0 roster disposition KEEP. Admission criteria satisfied.

## FormSpec
Per CLOSURE_SPEC.md: 6 closure files (`_identity`, `_goal`, `_task`, `_knowledge`, `_method`, `_skill/<NAME>/SKILL.md`) + 1 per-candidate 12-section artifact + 1 appended manifest row. Identity frontmatter carries `class: METHOD` verbatim from Stage-1 C0 row S1C-182 — carried, not normalized, not substituted.

## Contract
- Input: Stage-1 C0 roster row S1C-182, Stage-2 SplitSet child S2C-0509 (fragmentedFrom S2C-0157), Stage-3 ordered row S3S-0451.
- Output: 6 closure files under runRoot resolving a full identity→goal→task→knowledge→method→skill chain, plus this artifact, plus one manifest row.
- Precondition: none of the 6 files pre-existed (verified by path test before authoring — all 6 reported absent). Postcondition: all 6 exist, all internal links resolve or are explicitly-permitted forward declarations.

## ConceptToSkillClosure (the 6 paths)
1. `_identity/STEP_APPEAL_PROCEDURE.md`
2. `_goal/step_appeal_procedure_goal.md`
3. `_task/step_appeal_procedure_task.md`
4. `_knowledge/step_appeal_procedure_knowledge.md`
5. `_method/step_appeal_procedure_method.md`
6. `_skill/STEP_APPEAL_PROCEDURE/SKILL.md`

## ProvenanceGrounding
- Stage-1 C0 roster row: S1C-182 `ESG_EXECUTION_STRUCTURE` — ESG 실행 구조 (AI 포용전환 ESG 실행 모델, 9단계) — class METHOD — KEEP — `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` lines 514-529.
- Stage-1 evidence: "AI 포용전환 ESG는 철학 선언에 머물러서는 안 된다. 조직 안에서 실행 가능한 운영 모델로 내려와야 한다." — structural_role: named 9-step operating model, each step tagged E/S/G.
- Stage-2 settled record: S2C-0509 | S1C-182 | 6. 이의제기 절차 | `step_appeal_procedure` | `STEP_APPEAL_PROCEDURE` | SPLIT | KEEP | fragmentedFrom S2C-0157.
- Stage-2 SplitSet child detail: 정의 "AI 결과에 대한 설명, 재검토, 수정 요청 구조를 마련하는 단계." 판정기준 "AI 결과에 대해 설명·재검토·수정을 요청할 구조가 마련되어 있는가. (ESG 연결: S / G)" 산출 "이의제기 절차와 재검토·수정·구제 처리 결과." evidence "6. 이의제기 절차         AI 결과에 대한 설명, 재검토, 수정 요청 구조 마련            S / G" at line 525.
- Stage-3 row: S3S-0451, SequenceOrder 451, KnowledgeChainReady YES.
- Source-document verification (this run): line-addressed read against `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` confirms line 525 reads `  6. 이의제기 절차         AI 결과에 대한 설명, 재검토, 수정 요청 구조 마련            S / G` — the pack's evidence string matches verbatim once the row's leading indentation is dropped; all internal column spacing is preserved as it actually reads. **Layout note:** lines 518-529 are a fenced code block laid out as a 3-column table (`단계 / 실행 내용 / ESG 연결`, header at line 519), so the evidence is quoted as a table row, not as prose. Supplementary citations independently verified this run: line 516 (framing sentence), line 485 (S 확장 문단, "…AI를 이해하고 활용하고 통제하고 이의를 제기하며 그 성과에 참여할 수 있는 사회적 역량을 … 보장하는 책임이다"), line 492 (`- AI 이의제기권: AI 평가, 추천, 결정에 대해 재검토를 요구할 권리`, the corresponding 8대 권리 element), line 508 (`- 리스크 관리와 이의제기 절차`, the corresponding AI 거버넌스 항목), line 539 (`- 이의제기권: AI 결과 재검토 요청 건수, 수정·구제 처리율`, the corresponding 12지표 element).

## ResolvableLinks
- Stage-1 row: `../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member`
- Stage-1 evidence: `../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member`
- Stage-2 settled row: `../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary`
- Stage-2 SplitSet: `../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element`
- Stage-3 row: `../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0451`
- Neighbours: previous `./STEP_HUMAN_APPROVAL_CRITERIA.md`, next `./STEP_AUDIT_RECORD.md`
- Anchor verification (this run): all four Stage-1/Stage-2 heading anchors and the Stage-3 per-row anchor `id="s3s-0451"` confirmed present in the target artifact files by direct grep.

## Roster
- Parent (fragmentedFrom): S2C-0157 `ESG_EXECUTION_STRUCTURE` — ESG 실행 구조 (AI 포용전환 ESG 실행 모델, 9단계), 9 elements. Excluded OverBroadParent: no WalkOrder, no `_identity` file (holds Stage-3 SequenceOrder 445 only); linked via the Stage-2 SplitSet anchor.
- Sibling fragments (same parent, 9 elements): STEP_AI_IMPACT_ASSESSMENT (WO350, minted), STEP_AI_CONTEXT_CAPITAL_BUILD (WO351, minted), STEP_AUTHORITY_DESIGN (WO352, minted), STEP_LABOR_TRANSITION (WO353, minted), STEP_HUMAN_APPROVAL_CRITERIA (WO354, minted — previous batch closed here), STEP_APPEAL_PROCEDURE (WO355, this candidate — **first candidate of batch_355_360**), STEP_AUDIT_RECORD (WO356, this batch), STEP_BENEFIT_DISTRIBUTION (WO357, this batch), STEP_IMPROVEMENT_LOOP (WO358, this batch).
- This candidate occupies WalkOrder 355, the 6th of 9 sibling fragments. At this closure, 6 of 9 fragments of S2C-0157 are minted; steps 7-9 (WO356-358) follow within this same batch, which will close the SplitSet at 9/9.

## Landing
All 6 files landed under runRoot `/Users/gesia/wwp_book_v0.2`, verified present on disk by direct path test:

| # | path | on-disk |
|---|---|---|
| 1 | `_identity/STEP_APPEAL_PROCEDURE.md` | PASS |
| 2 | `_goal/step_appeal_procedure_goal.md` | PASS |
| 3 | `_task/step_appeal_procedure_task.md` | PASS |
| 4 | `_knowledge/step_appeal_procedure_knowledge.md` | PASS |
| 5 | `_method/step_appeal_procedure_method.md` | PASS |
| 6 | `_skill/STEP_APPEAL_PROCEDURE/SKILL.md` | PASS |

## LinkClosure
- Identity → goal/task/knowledge/method/skill: all 5 Derivation links resolve to files landed above (PASS).
- goal/task/knowledge/method → identity backlink `../_identity/STEP_APPEAL_PROCEDURE.md`: resolves (PASS).
- skill → Derivation chain, 2-level-up prefix `../../`: all 5 targets tested from `_skill/STEP_APPEAL_PROCEDURE/` and resolve — 5/5 (PASS).
- sequencePreviousIdentity → `./STEP_HUMAN_APPROVAL_CRITERIA.md`: file exists on disk (verified by path test; minted at WalkOrder 354 in the previous batch, batch_349_354), resolves (PASS).
- sequenceNextIdentity → `./STEP_AUDIT_RECORD.md`: INTRA-BATCH forward declaration. Not on disk at the moment of this closure (verified by path test), because WalkOrder 356 is minted next under strict-serial discipline; it lies INSIDE this batch's range (355-360) and therefore self-resolves before batch close. Not a dangling link.
- Back-reference closure: WO354's `sequenceNextIdentity` → `./STEP_APPEAL_PROCEDURE.md` is now RESOLVED on disk by this closure, discharging the cross-batch forward declaration recorded in the WO354 artifact at the close of batch_349_354.
- fragmentedFrom → Stage-2 SplitSet anchor (parent S2C-0157 is an excluded OverBroadParent with no `_identity` file): resolves to the Stage-2 artifact section, the specified linkage form for excluded parents (PASS).
- Unminted-reference discipline: the knowledge file names `IND_APPEAL_RIGHT` (WalkOrder 365, not yet minted — verified absent on disk) as a prose NormalizedName, not as a markdown link, so it creates no link obligation. `RIGHT_AI_APPEAL` (WalkOrder 347) is likewise prose, and is in any case present on disk.
- Stage-1/2/3 provenance links: anchors verified present in the existing Stage artifact files by grep.
- Zero unexplained dangling links. LinkClosure: **PASS**.

## Interlock
- Stage-1 ↔ Stage-2: S1C-182 → S2C-0509 fragmentedFrom S2C-0157 — consistent.
- Stage-2 ↔ Stage-3: S2C-0509 → S3S-0451 — consistent (Stage-3 row cites S2C-0509 directly).
- Stage-3 ↔ Stage-4 identity: S3S-0451 SequenceOrder 451 matches walkOrder 355's position in the roster.
- class carried verbatim from Stage-1 C0 (`METHOD`) — no normalization, no substitution applied.
- fragmentedFrom explicitly populated (S2C-0157) — matches Stage-2 SPLIT action; mandatory for this SPLIT child, never `none`. collapsedFrom explicitly `none`.
- **Neighbour reconciliation.** Neighbours are the WalkOrder-adjacent roster entries from the pack, never the raw Stage-3 sequencePrevious/sequenceNext. Here both readings agree — raw Stage-3 sequencePrevious for S3S-0451 is S3S-0450 (5. 인간 승인 기준 = `STEP_HUMAN_APPROVAL_CRITERIA`, WalkOrder 354) and raw sequenceNext is S3S-0452 (7. 감사 기록 = `STEP_AUDIT_RECORD`, WalkOrder 356); both coincide with the WalkOrder-adjacent neighbours. No divergence to reconcile — SequenceOrder runs contiguously (450 → 451 → 452) inside the S2C-0157 SplitSet.
- SplitSet position: 6th of 9 fragments of S2C-0157, in the order 영향평가(350) → 맥락자본 구축(351) → 권한 설계(352) → 노동 전환(353) → 인간 승인 기준(354) → **이의제기 절차(355)** → 감사 기록(356) → 성과배분(357) → 개선 루프(358). The batch boundary of the previous batch fell between 354 and 355; this closure crosses it.
- ESG-tag interlock: `S / G` (both axes), carried verbatim from the source table's third column, recorded consistently in identity 판정기준, goal 성공 판정, method 판정기준 and skill 판정기준. Unlike the preceding step (5. 인간 승인 기준, G alone), this step is dual-tagged; the knowledge file grounds each axis separately against the source — S against the 사회적 역량 보장 문단 (line 485, which names 이의 제기 as one of the guaranteed capacities) and G against the AI 거버넌스 항목 list (line 508, `- 리스크 관리와 이의제기 절차`) — rather than asserting the dual tag editorially.
- **Name-collision disambiguation (required for this candidate).** The 한글 stem 이의제기 appears at three distinct layers of the chapter, and this identity is written strictly as one of them:
  - **권리 층** — `RIGHT_AI_APPEAL` (AI 이의제기권, WalkOrder 347, line 492, already minted): "AI 평가, 추천, 결정에 대해 재검토를 요구할 권리." What the individual is guaranteed.
  - **실행 단계 층** — **this identity**, `STEP_APPEAL_PROCEDURE` (6. 이의제기 절차, WalkOrder 355, line 525): the procedure-building step that makes that right exercisable inside the organization. What the organization must construct.
  - **측정 지표 층** — `IND_APPEAL_RIGHT` (이의제기권, WalkOrder 365, line 539, not yet minted): "AI 결과 재검토 요청 건수, 수정·구제 처리율." How much it actually operated.
  Distinct NormalizedNames, distinct Stage-2 candidates, distinct source lines, distinct WalkOrders. The 권리 vocabulary ("권리", "요구할 권리") and the 지표 vocabulary ("건수", "처리율") are deliberately kept OUT of this node's 정의/판정기준/산출, which speak only in procedure-construction terms (창구, 접수 경로, 처리 주체, 처리 기한, 구제 처리). No blending across layers.
- Ordering-principle interlock: the step's position between 인간 승인 기준 and 감사 기록 is load-bearing — 승인 관문을 세운 뒤(5단계) 그 승인을 통과한 결과에 대해서도 재검토 통로를 열고(6단계), 그 요청과 처리 이력을 보존한다(7단계). The method's step 5 explicitly hands the 이의제기 접수·처리 이력 기록 지점 forward to the 감사 기록 단계, keeping the chain continuous into WO356.
- Internal chain interlock: all six files cross-reference the same `identity: STEP_APPEAL_PROCEDURE` / `displayName: "6. 이의제기 절차"` / `runID: 20260719_164605` triple. Consistent.
- Interlock: PASS.

## Conformance

| # | condition | verdict | evidence |
|---|---|---|---|
| 1 | `_identity/STEP_APPEAL_PROCEDURE.md` exists under runRoot | PASS | path test confirmed (Landing row 1) |
| 2 | `_goal/step_appeal_procedure_goal.md` exists under runRoot | PASS | path test confirmed (Landing row 2) |
| 3 | `_task/step_appeal_procedure_task.md` exists under runRoot | PASS | path test confirmed (Landing row 3) |
| 4 | `_knowledge/step_appeal_procedure_knowledge.md` exists under runRoot | PASS | path test confirmed (Landing row 4) |
| 5 | `_method/step_appeal_procedure_method.md` exists under runRoot | PASS | path test confirmed (Landing row 5) |
| 6 | `_skill/STEP_APPEAL_PROCEDURE/SKILL.md` exists under runRoot | PASS | path test confirmed (Landing row 6) |
| 7 | Stage-1/2/3 provenance present as resolvable links; `fragmentedFrom`/`collapsedFrom` present | PASS | identity frontmatter carries all 3 stage links + fragmentedFrom link (S2C-0157, mandatory for this SPLIT child) + collapsedFrom `none`; all anchors grep-verified present |
| 8 | sequencePreviousIdentity/sequenceNextIdentity are resolvable links, never bare names | PASS | frontmatter uses `"[STEP_HUMAN_APPROVAL_CRITERIA](./STEP_HUMAN_APPROVAL_CRITERIA.md)"` / `"[STEP_AUDIT_RECORD](./STEP_AUDIT_RECORD.md)"` — both markdown link syntax, not bare names |
| 9 | terminal skill Derivation links resolve to actual generated files | PASS | all 5 `../../` targets tested from `_skill/STEP_APPEAL_PROCEDURE/` on disk — 5/5 resolve |
| 10 | link_closure PASS (zero dangling) | PASS | see LinkClosure — prev resolves (WO354, previous batch); next (`STEP_AUDIT_RECORD`, WO356) is an intra-batch forward declaration minted next in this same batch, not dangling; WO354's cross-batch forward declaration discharged by this closure |
| 11 | interlock PASS (Stage 1/2/3/4 + internal chain) | PASS | see Interlock, including neighbour agreement, the S/G dual-tag grounding, and the 권리→단계→지표 three-layer name-collision disambiguation |
| 12 | conformance PASS | PASS | this table, all 12 rows PASS |

All 12 PASS conditions satisfied.

## VerifiedRecord
- WalkOrder 355 — `STEP_APPEAL_PROCEDURE` — 6. 이의제기 절차 — minted-PASS.
- Stage-3 ID: S3S-0451. Stage-2 ID: S2C-0509. Stage-1 ID: S1C-182. class `METHOD` (verbatim).
- 6 closure files landed and verified on disk under runRoot `/Users/gesia/wwp_book_v0.2`.
- Manifest row appended: WalkOrder 355 | 6. 이의제기 절차 | STEP_APPEAL_PROCEDURE | S3S-0451 | minted-PASS.
- SplitSet note: 6 of 9 fragments of `ESG_EXECUTION_STRUCTURE` (S2C-0157) now minted (WO350-355); steps 7-9 (WO356-358) follow within this same batch and will close the SplitSet at 9/9.
- Name-collision note: distinct from `RIGHT_AI_APPEAL` (WO347, 권리) and `IND_APPEAL_RIGHT` (WO365, 지표); this node is the 실행 단계 층. Recorded in Interlock.
- **Batch-open note:** this is the FIRST candidate of batch_355_360. It discharges the cross-batch forward declaration left open by WO354 at the close of batch_349_354.
- runID `20260719_164605`.
