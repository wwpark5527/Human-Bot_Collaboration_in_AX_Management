# Stage-4 DIAG · DuplicateAndContainmentDiagnosisArtifact

- **runID**: `20260719_164605` · **stage**: 4-DIAG — `stage_4_skill_surface_diagnosis_skill`, invoked UNCHANGED
- **runRoot**: `/Users/gesia/wwp_book_v0.2`
- **admitted input**: `U4 = C1 union ProvisionalNodeSet` — C1 (468) read off `./20260719_164605_stage2_identity_fragmentation_artifact.md`,
  ProvisionalNodeSet = **the EMPTY SET** (possibly-empty RUN DATA with no producer among S1/S2/S3),
  so **|U4| = 468**. `ExistingIdentityReferenceSet` (24) and `RegistryCollapse` are bound
  **COMPARISON/REFERENCE-only** — NOT admitted as skill candidates.
- **RUN-DATA NOTE (value-level only)**: ProvisionalNodeSet is empty and every `## CandidateSetForStage4` row
  is a C1 name, so U4 **equals** Stage-3's CandidateSetForStage4 **as a per-run value**; the S3 roster was
  used only as a read-only cross-check. U4 is NEVER *defined* as CandidateSetForStage4.
- **SIMULATION ONLY** — this predicts what `concept_to_skill` WOULD produce. concept_to_skill is NOT a member,
  was NOT run, and **NO closure file was created for any candidate**.

`whole_system_audit` (member 9) is the SET-LEVEL orchestrator: it composes `constraint_checking` (per-pair
rule) and `interlock_check` (cross-piece) over **ALL PAIRS** of U4 inside this one owning context — not a
fan-out, not a per-candidate loop — and rolls the results into set partitions.

## All-pairs sweep

> **축 순수성 (upstream, non-gating)**: U4 = 468, not the superseded run's 498 — Stage 2 re-partitioned
> 9 containers under its 축 순수성 rule. One member, `HONBIBAEKSAN_PREVENTION_MEASURES` (S3S-0064), is a
> newly established axis-separation parent and is diagnosed as an `OverBroadParent` like every other container.
> The name group 「조직AX의 추가조건」 that the superseded run listed under `IndependentSkillSurface` is gone:
> `OS_ADDITIONAL_CONDITION_CLASS` was a 부차-축 member and is no longer a candidate, so only
> `AX_ETHICS_ADDITIONAL_CONDITION` carries that label. **No DuplicateSkill pair was affected** — all 25
> pairs stand exactly as the superseded run rendered them.

| quantity | value |
|---|---|
| |U4| | 468 |
| ordered pairs swept (all pairs, C(468,2)) | **109,278** |
| pairs firing `DuplicateSkill` | 25 |
| pairs firing `SkillContains` (parent contains its promoted fragment) | 335 |
| pairs firing `OverBroadParent` | 74 |
| pairs firing `IndependentSkillSurface` | 108,844 |

The overwhelming majority of pairs are `IndependentSkillSurface`; only the pairs that actually fired a rule
are enumerated below (enumerating 109,278 independent pairs would add no diagnostic information).

## SkillContains -> resolved as OverBroadParent + PreservedChildSkillCandidateSet (NOT Absorb)

**This is the load-bearing decision of this run.** 74 candidates are Split parents that contain
their own promoted fragments. A `SkillContains` pair is **NOT** resolved to `Absorb` here: each fragment was
promoted at Stage 2 precisely because it carries its **own** 고유 입력 · 판정기준 · 산출, i.e. an independent
execution surface. Absorbing them back into the parent would re-create the over-fused bundle Stage 2 dissolved.

Resolution applied, following the `PREDICTIVE_INTELLIGENCE_SYSTEM` precedent:

- the **parent** -> `OverBroadParent` -> **BoundaryFeedbackSet**; retained as an upper (structural) node in the
  knowledge graph, **excluded** from `AdmittedAtomicSkillSet` by AdmitAtomicSkill's OverBroad exclusion;
- every **child** -> `PreservedChildSkillCandidateSet` -> **PRESERVE**. No child is absorbed.

| parent (OverBroadParent, -> BoundaryFeedbackSet) | contained fragments | resolution |
|---|---|---|
| [S3S-0006 AI 4.0 (Organizational AI) / AI 세대구분](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0006) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0011 LLM 체계도 (1~4/5층 아키텍처)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0011) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0016 제2의 LLM (제1·제2·제3의 LLM)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0016) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0022 조직AX용 OS 필요조건·추가조건](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0022) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0032 AI agent / Subagent / Bot 자율성 분류](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0032) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0036 협력 유형 (H+B / H+AH / AH+B / AH+AB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0036) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0042 인간-AI 협력 방식 분류 (HITL / AI-in-the-loop / HOTL / Autonomous AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0042) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0048 경영 기본철학·핵심정신 체계 (기본전제 + 3정신)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0048) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0055 보완적 적합성 (Complementary Fit)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0055) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0060 혼비백산(魂飛魄散) 방지 (영·혼·백)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0060) | 14 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 14 children -> **PRESERVE** |
| [S3S-0070 AX조직 전환 인간반응 4층위 (생존·능력·관계·존재)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0070) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0075 개별적 인간 반응·반발 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0075) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0081 집단적 인간 반응·반발 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0081) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0087 AX조직 스트레스 (4대 위험: 정체성·신뢰·통제·책임)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0087) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0092 인간 스트레스 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0092) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0098 봇 스트레스 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0098) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0104 인간 스트레스 vs 봇 스트레스 비교](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0104) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0112 협력 유형별 스트레스 (H+B/H+AH/AH+B/AH+AB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0112) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0117 AX조직 인재의 필요조건 (살아남는 인간의 역량)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0117) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0124 AX조직 인재의 추가조건 (성공하는 리더의 역량)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0124) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0130 AX조직 인재의 3가지 책임 (맥락·판단·증거)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0130) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0134 AX조직 인재의 역할 8가지](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0134) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0143 AX조직 인재의 5가지 핵심 역할 (조형자·구현자·검증자·운영자·조정자)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0143) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0149 AI 시대 역할론 (일·기여·역할의 재정의)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0149) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0153 Belbin의 역할론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0153) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0159 증강인간 (AH)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0159) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0163 증강봇 (AB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0163) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0167 봇의 사회성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0167) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0171 AI 윤리기준의 유형 (UNESCO·OECD·EU AI Act·IEEE·한국정부)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0171) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0174 Claude 헌법 (Claude Constitution)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0174) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0179 조직AX 윤리의 필요조건과 추가조건](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0179) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0182 로봇 3원칙 (three laws of robotics)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0182) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0187 인간존중의 기술적 정의 (4가지)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0187) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0192 인간존중 구현 5단계 아키텍처](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0192) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0198 봇의 인간 특성 이해 (socially compatible system)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0198) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0202 인간의 봇 특성 이해 (패턴 탐지기 / 기능적 만족·욕구)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0202) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0207 봇들 간의 위계 형성 (Level 1-4)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0207) | 9 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 9 children -> **PRESERVE** |
| [S3S-0212 HBRM (인간-봇 자원관리)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0212) | 11 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 11 children -> **PRESERVE** |
| [S3S-0221 HBRM의 3M (method·meaning·measurement)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0221) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0225 증강인간 측정: AH 5대 지표](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0225) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0231 인간 증강 단계 (H0~AH3)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0231) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0238 AI 활용력 (AIU, AI Utilization)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0238) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0250 팀역할 발휘 3수준 (자연역할/팀역할·잠재역할/관리가능역할·비선호역할)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0250) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0255 Interplace 4종 설문지 (자기진단지SPI·관찰자진단지OA·직무요구진단지JRE·직무관찰자진단지JOA)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0255) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0261 팀웍의 두 측면 (인간적 유대감 & 업무적 활성화)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0261) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0266 Belbin의 9가지 팀역할 유형 (창조자PL·냉철판단자ME·지휘조절자CO·실행자IMP·완결자CF·자원탐색가RI·분위기조성자TW·추진자SH·전문가SP)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0266) | 9 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 9 children -> **PRESERVE** |
| [S3S-0276 봇에 의한 TR의 보완·증강·추가](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0276) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0280 AX 신규 역할 (AI Governor·AI Auditor·Prompt Architect·AI Workflow Orchestrator·Human Meaning Integrator·Trust Manager·Provenance Controller)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0280) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0289 Bot-Aided TRB (봇 보조 TRB, 수직관계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0289) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0293 Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0293) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0297 TRB 진화 경로 (Human-only → Bot-aided → Human-bot coupled → Autonomous hybrid TRB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0297) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0302 ARBI 10개 평가 축 (역할균형·보완적 적합성·AI 개입 투명성·발화 주체성·권한·동의 경계·인간 책임성·의사소통 공정성·기록·추적성·심리·신뢰 안정성·조작 위험)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0302) | 10 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 10 children -> **PRESERVE** |
| [S3S-0314 로컬 환경 / 네트워크 환경](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0314) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0317 공통 컨텍스트 (common context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0317) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0324 거버넌스 컨텍스트 (governance context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0324) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0333 지식사슬 (knowledge chain)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0333) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0340 지식사슬의 기능 (4대 기능)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0340) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0347 지식행동사슬 (지식(행동)사슬, knowledge behavior chain)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0347) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0357 SkillRuntime](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0357) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0366 공통·의사소통·거버넌스 3계층 컨텍스트 구조](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0366) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0371 구성원 유형별 의사소통 (AH-H · AH-AH)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0371) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0376 증강인간 간 의사소통 3경로 (인간 중심 · AI 중심 · 거버넌스 경유)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0376) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0381 AI 예측지능 체계 / 예측지능 스택](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0381) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0389 AI 기반 계급화를 만드는 7가지 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0389) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0397 AI 시대 노동 분화 4유형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0397) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0410 책임운영체계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0410) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0418 AI 시대 ESG 개념의 확장 (확장 ESG)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0418) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0422 ESG 확장론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0422) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0426 AI-ESG 관계의 두 관점 (AI for ESG / ESG for AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0426) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0430 AI 포용전환 ESG의 네 층위](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0430) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0436 AI 시대 인간 보호 권리 (8대 권리)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0436) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0445 ESG 실행 구조 (AI 포용전환 ESG 실행 모델, 9단계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0445) | 9 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 9 children -> **PRESERVE** |
| [S3S-0455 포용전환 ESG 12지표](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0455) | 13 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 13 children -> **PRESERVE** |

## DuplicateSkill -> owner / duplicate

25 pairs where two candidates in different containers denote the SAME skill surface (same
identity_meaning, same outcome, same reads/writes). The owner is the occurrence with the fuller surface
(earliest in InvocationOrder, except the Belbin roles where the 6장 nine-role set carries the AX
reinterpretation and therefore owns them).

| duplicate (excluded) | owner (preserved) | basis |
|---|---|---|
| [S3S-0027 Organizational Digital Twin (ODT)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0027) | [S3S-0026 Organizational digital twin(ODT)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0026) | 동일 표면 — 정규화 명칭 "Organizational digital twin(ODT)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0029 운영규범 (Operating Protocols & Control Standards)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0029) | [S3S-0023 운영규범 (Operating protocols & control standards)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0023) | 동일 표면 — 정규화 명칭 "운영규범 (Operating protocols & control standards)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0053 다양성 (Diversity) 존중과 활용](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0053) | [S3S-0050 다양성(Diversity) 존중과 활용](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0050) | 동일 표면 — 정규화 명칭 "다양성(Diversity) 존중과 활용" 일치, 동일 산출·동일 판정기준 |
| [S3S-0154 창조자(plant)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0154) | [S3S-0267 창조자 (PL)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0267) | 동일 표면 — 정규화 명칭 "창조자 (PL)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0155 냉철판단자(monitor evaluator)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0155) | [S3S-0268 냉철판단자(ME)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0268) | 동일 표면 — 정규화 명칭 "냉철판단자(ME)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0156 완결자(completer finisher)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0156) | [S3S-0271 완결자(CF)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0271) | 동일 표면 — 정규화 명칭 "완결자(CF)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0224 측정(measurement)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0224) | [S3S-0110 측정](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0110) | 동일 표면 — 정규화 명칭 "측정" 일치, 동일 산출·동일 판정기준 |
| [S3S-0299 Bot-aided TRB](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0299) | [S3S-0289 Bot-Aided TRB (봇 보조 TRB, 수직관계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0289) | 동일 표면 — 정규화 명칭 "Bot-Aided TRB (봇 보조 TRB, 수직관계)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0300 Human-bot coupled TRB](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0300) | [S3S-0293 Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0293) | 동일 표면 — 정규화 명칭 "Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0356 스킬 (skill)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0356) | [S3S-0349 스킬(skill)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0349) | 동일 표면 — 정규화 명칭 "스킬(skill)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0367 공통 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0367) | [S3S-0317 공통 컨텍스트 (common context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0317) | 동일 표면 — 정규화 명칭 "공통 컨텍스트 (common context)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0369 거버넌스 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0369) | [S3S-0324 거버넌스 컨텍스트 (governance context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0324) | 동일 표면 — 정규화 명칭 "거버넌스 컨텍스트 (governance context)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0370 의사소통 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0370) | [S3S-0368 의사소통 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0368) | 동일 표면 — 정규화 명칭 "의사소통 컨텍스트" 일치, 동일 산출·동일 판정기준 |
| [S3S-0383 지식사슬](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0383) | [S3S-0333 지식사슬 (knowledge chain)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0333) | 동일 표면 — 정규화 명칭 "지식사슬 (knowledge chain)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0385 월드 모델](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0385) | [S3S-0382 월드 모델](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0382) | 동일 표면 — 정규화 명칭 "월드 모델" 일치, 동일 산출·동일 판정기준 |
| [S3S-0386 컨텍스트 설계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0386) | [S3S-0384 컨텍스트 설계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0384) | 동일 표면 — 정규화 명칭 "컨텍스트 설계" 일치, 동일 산출·동일 판정기준 |
| [S3S-0411 권한](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0411) | [S3S-0325 권한(authority)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0325) | 동일 표면 — 정규화 명칭 "권한(authority)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0412 보안](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0412) | [S3S-0326 보안(security)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0326) | 동일 표면 — 정규화 명칭 "보안(security)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0413 검증](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0413) | [S3S-0327 검증(validation)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0327) | 동일 표면 — 정규화 명칭 "검증(validation)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0414 승인](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0414) | [S3S-0328 승인(approval)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0328) | 동일 표면 — 정규화 명칭 "승인(approval)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0415 기록](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0415) | [S3S-0329 기록(record)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0329) | 동일 표면 — 정규화 명칭 "기록(record)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0416 책임](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0416) | [S3S-0330 책임(accountability)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0330) | 동일 표면 — 정규화 명칭 "책임(accountability)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0417 개선](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0417) | [S3S-0331 개선(improvement)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0331) | 동일 표면 — 정규화 명칭 "개선(improvement)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0466 맥락자본](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0466) | [S3S-0406 맥락자본 (Context Capital)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0406) | 동일 표면 — 정규화 명칭 "맥락자본 (Context Capital)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0467 책임운영체계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0467) | [S3S-0410 책임운영체계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0410) | 동일 표면 — 정규화 명칭 "책임운영체계" 일치, 동일 산출·동일 판정기준 |

## ParentSelfName (handled by OverBroadParent, NOT a duplicate)

1 name group(s) where a Split parent shares its normalized name with one of **its own**
promoted fragments. This is containment, not duplication: the parent is the bundle, the fragment carries the
surface. Already resolved above — parent -> OverBroadParent, fragment -> PRESERVE.

| parent (bundle) | fragment carrying the surface |
|---|---|
| [S3S-0016 제2의 LLM (제1·제2·제3의 LLM)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0016) | [S3S-0018 제 2의 LLM](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0018) |

## IndependentSkillSurface — name groups deliberately NOT collapsed

5 normalized-name groups share a label but diverge on role, scope or outcome, so they are
`IndependentSkillSurface` and **both members are preserved**. Their normalized KEYS already differ, so there
is no addressing collision.

| shared label | members preserved | why not a duplicate |
|---|---|---|
| 보완적 적합성 (Complementary Fit) | `COMPLEMENTARY_FIT` · `ARBI_AXIS_COMPLEMENTARY_FIT` | 개념으로서의 보완적 적합성과 ARBI의 평가 축은 input(측정 데이터)·output(축 점수)이 다르다 |
| 검증자 | `ROLE_VALIDATOR_OF_EIGHT` · `CORE_ROLE_VALIDATOR` | 8역할 프레임과 5핵심역할 프레임은 책이 별도로 유지하는 두 체계이며 판정기준이 다르다 |
| 역할 | `ROLE_AS_CONTRIBUTION_POSITION` · `COMMON_CONTEXT_ELEMENT_ROLE` | 역할론의 '기여의 위치'와 공통 컨텍스트의 구성요소 '역할' 슬롯은 abstraction_level이 다르다 |
| 학습 증강 | `AB_LEARNING_AUGMENTATION` · `AH_INDICATOR_LEARNING` | 증강봇(B->AB) 측 학습 증강과 증강인간(AH) 5대 지표의 학습 증강은 대상 구성원이 다르다 |
| HBRM (인간-봇 자원관리) | `HBRM` · `HUMAN_BOT_ROLE_MANAGEMENT` | 동일 약어의 두 확장(인간-봇 자원관리 / Human-Bot Role Management) — AliasOvermerge로 이미 분리 보존 |

## Set partitions (rolled up by whole_system_audit)

| partition | size | members |
|---|---|---|
| **owner** | 25 | the preserved side of each DuplicateSkill pair |
| **duplicate** (excluded) | 25 | the excluded side of each DuplicateSkill pair |
| **preserve** (PreservedChildSkillCandidateSet) | 317 | promoted fragments with an independent execution surface |
| **absorb** | **0** | **no candidate was absorbed** — SkillContains was resolved as OverBroadParent + preserve |
| **split** | 74 | Split parents retained as upper nodes, excluded as OverBroad (73 containers + 1 axis-separation parent) |

**absorb = 0 is deliberate.** The prior run absorbed 7 sub-enumerations as "pure sub-enumeration; no
independent surface". Under this run's Stage-2 partition every promoted fragment carries its own
고유 입력 · 판정기준 · 산출, which IS an independent execution surface, so the Absorb reading does not hold
for any of them.
