# Stage-4 DIAG · DuplicateAndContainmentDiagnosisArtifact

- **runID**: `20260719_154811` · **stage**: 4-DIAG — `stage_4_skill_surface_diagnosis_skill`, invoked UNCHANGED
- **runRoot**: `/Users/gesia/wwp_book_v0.2`
- **admitted input**: `U4 = C1 union ProvisionalNodeSet` — C1 (498) read off `./20260719_154811_stage2_identity_fragmentation_artifact.md`,
  ProvisionalNodeSet = **the EMPTY SET** (possibly-empty RUN DATA with no producer among S1/S2/S3),
  so **|U4| = 498**. `ExistingIdentityReferenceSet` (24) and `RegistryCollapse` are bound
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

| quantity | value |
|---|---|
| |U4| | 498 |
| ordered pairs swept (all pairs, C(498,2)) | **123,753** |
| pairs firing `DuplicateSkill` | 25 |
| pairs firing `SkillContains` (parent contains its promoted fragment) | 366 |
| pairs firing `OverBroadParent` | 73 |
| pairs firing `IndependentSkillSurface` | 123,289 |

The overwhelming majority of pairs are `IndependentSkillSurface`; only the pairs that actually fired a rule
are enumerated below (enumerating 123,753 independent pairs would add no diagnostic information).

## SkillContains -> resolved as OverBroadParent + PreservedChildSkillCandidateSet (NOT Absorb)

**This is the load-bearing decision of this run.** 73 candidates are Split parents that contain
their own promoted fragments. A `SkillContains` pair is **NOT** resolved to `Absorb` here: each fragment was
promoted at Stage 2 precisely because it carries its **own** 고유 입력 · 판정기준 · 산출, i.e. an independent
execution surface. Absorbing them back into the parent would re-create the over-fused bundle Stage 2 dissolved.

Resolution applied, following the `PREDICTIVE_INTELLIGENCE_SYSTEM` precedent:

- the **parent** -> `OverBroadParent` -> **BoundaryFeedbackSet**; retained as an upper (structural) node in the
  knowledge graph, **excluded** from `AdmittedAtomicSkillSet` by AdmitAtomicSkill's OverBroad exclusion;
- every **child** -> `PreservedChildSkillCandidateSet` -> **PRESERVE**. No child is absorbed.

| parent (OverBroadParent, -> BoundaryFeedbackSet) | contained fragments | resolution |
|---|---|---|
| [S3S-0006 AI 4.0 (Organizational AI) / AI 세대구분](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0006) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0011 LLM 체계도 (1~4/5층 아키텍처)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0011) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0016 제2의 LLM (제1·제2·제3의 LLM)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0016) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0022 조직AX용 OS 필요조건·추가조건](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0022) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0034 AI agent / Subagent / Bot 자율성 분류](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0034) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0038 협력 유형 (H+B / H+AH / AH+B / AH+AB)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0038) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0044 인간-AI 협력 방식 분류 (HITL / AI-in-the-loop / HOTL / Autonomous AI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0044) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0050 경영 기본철학·핵심정신 체계 (기본전제 + 3정신)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0050) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0058 보완적 적합성 (Complementary Fit)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0058) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0063 혼비백산(魂飛魄散) 방지 (영·혼·백)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0063) | 14 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 14 children -> **PRESERVE** |
| [S3S-0078 AX조직 전환 인간반응 4층위 (생존·능력·관계·존재)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0078) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0083 개별적 인간 반응·반발 유형 (5형)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0083) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0089 집단적 인간 반응·반발 유형 (5형)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0089) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0095 AX조직 스트레스 (4대 위험: 정체성·신뢰·통제·책임)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0095) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0100 인간 스트레스 유형 (5형)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0100) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0106 봇 스트레스 유형 (5형)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0106) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0112 인간 스트레스 vs 봇 스트레스 비교](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0112) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0120 협력 유형별 스트레스 (H+B/H+AH/AH+B/AH+AB)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0120) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0125 AX조직 인재의 필요조건 (살아남는 인간의 역량)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0125) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0132 AX조직 인재의 추가조건 (성공하는 리더의 역량)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0132) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0138 AX조직 인재의 3가지 책임 (맥락·판단·증거)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0138) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0142 AX조직 인재의 역할 8가지](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0142) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0151 AX조직 인재의 5가지 핵심 역할 (조형자·구현자·검증자·운영자·조정자)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0151) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0157 AI 시대 역할론 (일·기여·역할의 재정의)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0157) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0161 Belbin의 역할론](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0161) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0167 증강인간 (AH)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0167) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0174 증강봇 (AB)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0174) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0182 봇의 사회성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0182) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0186 AI 윤리기준의 유형 (UNESCO·OECD·EU AI Act·IEEE·한국정부)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0186) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0189 Claude 헌법 (Claude Constitution)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0189) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0194 조직AX 윤리의 필요조건과 추가조건](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0194) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0197 로봇 3원칙 (three laws of robotics)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0197) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0202 인간존중의 기술적 정의 (4가지)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0202) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0207 인간존중 구현 5단계 아키텍처](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0207) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0213 봇의 인간 특성 이해 (socially compatible system)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0213) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0217 인간의 봇 특성 이해 (패턴 탐지기 / 기능적 만족·욕구)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0217) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0225 봇들 간의 위계 형성 (Level 1-4)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0225) | 9 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 9 children -> **PRESERVE** |
| [S3S-0235 HBRM (인간-봇 자원관리)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0235) | 11 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 11 children -> **PRESERVE** |
| [S3S-0247 HBRM의 3M (method·meaning·measurement)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0247) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0251 증강인간 측정: AH 5대 지표](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0251) | 5 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 5 children -> **PRESERVE** |
| [S3S-0257 인간 증강 단계 (H0~AH3)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0257) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0264 AI 활용력 (AIU, AI Utilization)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0264) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0280 팀역할 발휘 3수준 (자연역할/팀역할·잠재역할/관리가능역할·비선호역할)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0280) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0285 Interplace 4종 설문지 (자기진단지SPI·관찰자진단지OA·직무요구진단지JRE·직무관찰자진단지JOA)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0285) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0291 팀웍의 두 측면 (인간적 유대감 & 업무적 활성화)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0291) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0296 Belbin의 9가지 팀역할 유형 (창조자PL·냉철판단자ME·지휘조절자CO·실행자IMP·완결자CF·자원탐색가RI·분위기조성자TW·추진자SH·전문가SP)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0296) | 9 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 9 children -> **PRESERVE** |
| [S3S-0306 봇에 의한 TR의 보완·증강·추가](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0306) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0310 AX 신규 역할 (AI Governor·AI Auditor·Prompt Architect·AI Workflow Orchestrator·Human Meaning Integrator·Trust Manager·Provenance Controller)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0310) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0319 Bot-Aided TRB (봇 보조 TRB, 수직관계)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0319) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0323 Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0323) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0327 TRB 진화 경로 (Human-only → Bot-aided → Human-bot coupled → Autonomous hybrid TRB)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0327) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0332 ARBI 10개 평가 축 (역할균형·보완적 적합성·AI 개입 투명성·발화 주체성·권한·동의 경계·인간 책임성·의사소통 공정성·기록·추적성·심리·신뢰 안정성·조작 위험)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0332) | 10 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 10 children -> **PRESERVE** |
| [S3S-0344 로컬 환경 / 네트워크 환경](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0344) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0347 공통 컨텍스트 (common context)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0347) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0354 거버넌스 컨텍스트 (governance context)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0354) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0363 지식사슬 (knowledge chain)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0363) | 6 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 6 children -> **PRESERVE** |
| [S3S-0370 지식사슬의 기능 (4대 기능)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0370) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0377 지식행동사슬 (지식(행동)사슬, knowledge behavior chain)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0377) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0387 SkillRuntime](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0387) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0396 공통·의사소통·거버넌스 3계층 컨텍스트 구조](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0396) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0401 구성원 유형별 의사소통 (AH-H · AH-AH)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0401) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0406 증강인간 간 의사소통 3경로 (인간 중심 · AI 중심 · 거버넌스 경유)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0406) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0411 AI 예측지능 체계 / 예측지능 스택](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0411) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0419 AI 기반 계급화를 만드는 7가지 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0419) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0427 AI 시대 노동 분화 4유형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0427) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0440 책임운영체계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0440) | 7 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 7 children -> **PRESERVE** |
| [S3S-0448 AI 시대 ESG 개념의 확장 (확장 ESG)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0448) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0452 ESG 확장론](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0452) | 3 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 3 children -> **PRESERVE** |
| [S3S-0456 AI-ESG 관계의 두 관점 (AI for ESG / ESG for AI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0456) | 2 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 2 children -> **PRESERVE** |
| [S3S-0460 AI 포용전환 ESG의 네 층위](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0460) | 4 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 4 children -> **PRESERVE** |
| [S3S-0466 AI 시대 인간 보호 권리 (8대 권리)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0466) | 8 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 8 children -> **PRESERVE** |
| [S3S-0475 ESG 실행 구조 (AI 포용전환 ESG 실행 모델, 9단계)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0475) | 9 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 9 children -> **PRESERVE** |
| [S3S-0485 포용전환 ESG 12지표](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0485) | 13 | parent -> BoundaryFeedbackSet (excluded as OverBroad); all 13 children -> **PRESERVE** |

## DuplicateSkill -> owner / duplicate

25 pairs where two candidates in different containers denote the SAME skill surface (same
identity_meaning, same outcome, same reads/writes). The owner is the occurrence with the fuller surface
(earliest in InvocationOrder, except the Belbin roles where the 6장 nine-role set carries the AX
reinterpretation and therefore owns them).

| duplicate (excluded) | owner (preserved) | basis |
|---|---|---|
| [S3S-0029 Organizational Digital Twin (ODT)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0029) | [S3S-0028 Organizational digital twin(ODT)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0028) | 동일 표면 — 정규화 명칭 "Organizational digital twin(ODT)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0031 운영규범 (Operating Protocols & Control Standards)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0031) | [S3S-0025 운영규범 (Operating protocols & control standards)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0025) | 동일 표면 — 정규화 명칭 "운영규범 (Operating protocols & control standards)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0056 다양성 (Diversity) 존중과 활용](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0056) | [S3S-0053 다양성(Diversity) 존중과 활용](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0053) | 동일 표면 — 정규화 명칭 "다양성(Diversity) 존중과 활용" 일치, 동일 산출·동일 판정기준 |
| [S3S-0162 창조자(plant)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0162) | [S3S-0297 창조자 (PL)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0297) | 동일 표면 — 정규화 명칭 "창조자 (PL)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0163 냉철판단자(monitor evaluator)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0163) | [S3S-0298 냉철판단자(ME)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0298) | 동일 표면 — 정규화 명칭 "냉철판단자(ME)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0164 완결자(completer finisher)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0164) | [S3S-0301 완결자(CF)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0301) | 동일 표면 — 정규화 명칭 "완결자(CF)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0250 측정(measurement)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0250) | [S3S-0118 측정](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0118) | 동일 표면 — 정규화 명칭 "측정" 일치, 동일 산출·동일 판정기준 |
| [S3S-0329 Bot-aided TRB](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0329) | [S3S-0319 Bot-Aided TRB (봇 보조 TRB, 수직관계)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0319) | 동일 표면 — 정규화 명칭 "Bot-Aided TRB (봇 보조 TRB, 수직관계)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0330 Human-bot coupled TRB](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0330) | [S3S-0323 Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0323) | 동일 표면 — 정규화 명칭 "Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0386 스킬 (skill)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0386) | [S3S-0379 스킬(skill)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0379) | 동일 표면 — 정규화 명칭 "스킬(skill)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0397 공통 컨텍스트](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0397) | [S3S-0347 공통 컨텍스트 (common context)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0347) | 동일 표면 — 정규화 명칭 "공통 컨텍스트 (common context)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0399 거버넌스 컨텍스트](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0399) | [S3S-0354 거버넌스 컨텍스트 (governance context)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0354) | 동일 표면 — 정규화 명칭 "거버넌스 컨텍스트 (governance context)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0400 의사소통 컨텍스트](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0400) | [S3S-0398 의사소통 컨텍스트](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0398) | 동일 표면 — 정규화 명칭 "의사소통 컨텍스트" 일치, 동일 산출·동일 판정기준 |
| [S3S-0413 지식사슬](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0413) | [S3S-0363 지식사슬 (knowledge chain)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0363) | 동일 표면 — 정규화 명칭 "지식사슬 (knowledge chain)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0415 월드 모델](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0415) | [S3S-0412 월드 모델](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0412) | 동일 표면 — 정규화 명칭 "월드 모델" 일치, 동일 산출·동일 판정기준 |
| [S3S-0416 컨텍스트 설계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0416) | [S3S-0414 컨텍스트 설계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0414) | 동일 표면 — 정규화 명칭 "컨텍스트 설계" 일치, 동일 산출·동일 판정기준 |
| [S3S-0441 권한](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0441) | [S3S-0355 권한(authority)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0355) | 동일 표면 — 정규화 명칭 "권한(authority)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0442 보안](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0442) | [S3S-0356 보안(security)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0356) | 동일 표면 — 정규화 명칭 "보안(security)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0443 검증](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0443) | [S3S-0357 검증(validation)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0357) | 동일 표면 — 정규화 명칭 "검증(validation)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0444 승인](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0444) | [S3S-0358 승인(approval)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0358) | 동일 표면 — 정규화 명칭 "승인(approval)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0445 기록](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0445) | [S3S-0359 기록(record)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0359) | 동일 표면 — 정규화 명칭 "기록(record)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0446 책임](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0446) | [S3S-0360 책임(accountability)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0360) | 동일 표면 — 정규화 명칭 "책임(accountability)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0447 개선](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0447) | [S3S-0361 개선(improvement)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0361) | 동일 표면 — 정규화 명칭 "개선(improvement)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0496 맥락자본](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0496) | [S3S-0436 맥락자본 (Context Capital)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0436) | 동일 표면 — 정규화 명칭 "맥락자본 (Context Capital)" 일치, 동일 산출·동일 판정기준 |
| [S3S-0497 책임운영체계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0497) | [S3S-0440 책임운영체계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0440) | 동일 표면 — 정규화 명칭 "책임운영체계" 일치, 동일 산출·동일 판정기준 |

## ParentSelfName (handled by OverBroadParent, NOT a duplicate)

1 name group(s) where a Split parent shares its normalized name with one of **its own**
promoted fragments. This is containment, not duplication: the parent is the bundle, the fragment carries the
surface. Already resolved above — parent -> OverBroadParent, fragment -> PRESERVE.

| parent (bundle) | fragment carrying the surface |
|---|---|
| [S3S-0016 제2의 LLM (제1·제2·제3의 LLM)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0016) | [S3S-0018 제 2의 LLM](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0018) |

## IndependentSkillSurface — name groups deliberately NOT collapsed

6 normalized-name groups share a label but diverge on role, scope or outcome, so they are
`IndependentSkillSurface` and **both members are preserved**. Their normalized KEYS already differ, so there
is no addressing collision.

| shared label | members preserved | why not a duplicate |
|---|---|---|
| 조직AX의 추가조건 | `OS_ADDITIONAL_CONDITION_CLASS` · `AX_ETHICS_ADDITIONAL_CONDITION` | OS의 추가조건(구성요소)과 윤리의 추가조건(규범)은 scope가 다르다 |
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
| **preserve** (PreservedChildSkillCandidateSet) | 348 | promoted fragments with an independent execution surface |
| **absorb** | **0** | **no candidate was absorbed** — SkillContains was resolved as OverBroadParent + preserve |
| **split** | 73 | Split parents retained as upper nodes, excluded as OverBroad |

**absorb = 0 is deliberate.** The prior run absorbed 7 sub-enumerations as "pure sub-enumeration; no
independent surface". Under this run's Stage-2 partition every promoted fragment carries its own
고유 입력 · 판정기준 · 산출, which IS an independent execution surface, so the Absorb reading does not hold
for any of them.
