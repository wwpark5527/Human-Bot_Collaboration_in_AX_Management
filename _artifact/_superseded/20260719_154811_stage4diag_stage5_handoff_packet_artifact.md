# Stage-4 DIAG · Stage5HandoffPacketArtifact

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

This packet carries **ONLY** `AdmittedAtomicSkillSet` + `ExpectedClosureManifest` + `InvocationOrder` + itself.
Nothing else is passed to Stage 5.

## AdmitAtomicSkill — how the set was computed

`AdmittedAtomicSkillSet` = U4 minus every exclusion:

| exclusion | count | note |
|---|---|---|
| Duplicate | 25 | excluded side of each DuplicateSkill pair |
| Absorbed | **0** | nothing was absorbed (SkillContains -> OverBroadParent + preserve) |
| OverBroad | 73 | Split parents; retained as upper nodes, not atomic skills |
| RegistryCollapse | 0 admitted | the 24 references were COMPARE-only, never in U4 |
| ManualReviewOnly | 0 admitted | the 24 ManualReview rows were never promoted past Stage 2 |
| ConceptThinningRisk | 73 (same rows as OverBroad) | parents -> BoundaryFeedbackSet |
| collisions | 0 | all 498 NormalizedKeys are globally unique |
| **|AdmittedAtomicSkillSet|** | **400** | 498 - 73 OverBroad - 25 Duplicate |

## AdmittedAtomicSkillSet (400)

| InvocationOrder | Stage3SequenceID | candidate (한글 보존) | NormalizedKey | agent_role |
|---|---|---|---|---|
| 1 | [S3S-0001 AX (AI Transformation)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0001) | AX (AI Transformation) | `AI_TRANSFORMATION` | `ax_paradigm_architect` |
| 2 | [S3S-0002 DX (Digital Transformation)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0002) | DX (Digital Transformation) | `DIGITAL_TRANSFORMATION` | `ax_paradigm_architect` |
| 3 | [S3S-0003 조직AX](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0003) | 조직AX | `ORGANIZATIONAL_AX` | `ax_paradigm_architect` |
| 4 | [S3S-0004 AX조직](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0004) | AX조직 | `AX_ORGANIZATION` | `ax_paradigm_architect` |
| 5 | [S3S-0005 개인AX](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0005) | 개인AX | `PERSONAL_AX` | `ax_paradigm_architect` |
| 6 | [S3S-0007 AI 1.0 (Perceptional AI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0007) | AI 1.0 (Perceptional AI) | `AI_GEN_1_PERCEPTIONAL` | `ax_paradigm_architect` |
| 7 | [S3S-0008 AI 2.0 (Generative AI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0008) | AI 2.0 (Generative AI) | `AI_GEN_2_GENERATIVE` | `ax_paradigm_architect` |
| 8 | [S3S-0009 AI 3.0 (Agentic AI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0009) | AI 3.0 (Agentic AI) | `AI_GEN_3_AGENTIC` | `ax_paradigm_architect` |
| 9 | [S3S-0010 AI 4.0 (Organizational AI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0010) | AI 4.0 (Organizational AI) | `AI_GEN_4_ORGANIZATIONAL` | `ax_paradigm_architect` |
| 10 | [S3S-0012 1~2층 (DX의 영역)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0012) | 1~2층 (DX의 영역) | `LLM_LAYER_1_2_DX_DOMAIN` | `ax_paradigm_architect` |
| 11 | [S3S-0013 3층 (공통 & 거버넌스 컨텍스트 기반 지식사슬)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0013) | 3층 (공통 & 거버넌스 컨텍스트 기반 지식사슬) | `LLM_LAYER_3_KNOWLEDGE_CHAIN` | `ax_paradigm_architect` |
| 12 | [S3S-0014 4층 (이미 세상에 나와 있는 LLM = '제 1의 LLM')](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0014) | 4층 (이미 세상에 나와 있는 LLM = '제 1의 LLM') | `LLM_LAYER_4_FIRST_LLM_SUPPLY` | `ax_paradigm_architect` |
| 13 | [S3S-0015 5층 (8장에서 추가되는 층)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0015) | 5층 (8장에서 추가되는 층) | `LLM_LAYER_5_EXTENSION` | `ax_paradigm_architect` |
| 14 | [S3S-0017 제 1의 LLM](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0017) | 제 1의 LLM | `LLM_GEN_FIRST_UNIVERSAL` | `ax_paradigm_architect` |
| 15 | [S3S-0018 제 2의 LLM](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0018) | 제 2의 LLM | `LLM_GEN_SECOND_ENTERPRISE` | `ax_paradigm_architect` |
| 16 | [S3S-0019 제 3의 LLM](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0019) | 제 3의 LLM | `LLM_GEN_THIRD_FULL_STACK` | `ax_paradigm_architect` |
| 17 | [S3S-0020 도메인 컨텍스트 (Domain Context)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0020) | 도메인 컨텍스트 (Domain Context) | `DOMAIN_CONTEXT` | `ax_paradigm_architect` |
| 18 | [S3S-0021 조직AX용 OS](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0021) | 조직AX용 OS | `ORG_AX_OS` | `ax_paradigm_architect` |
| 19 | [S3S-0023 조직AX의 필요조건](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0023) | 조직AX의 필요조건 | `OS_NECESSARY_CONDITION_CLASS` | `ax_paradigm_architect` |
| 20 | [S3S-0024 조직AX의 추가조건](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0024) | 조직AX의 추가조건 | `OS_ADDITIONAL_CONDITION_CLASS` | `ax_paradigm_architect` |
| 21 | [S3S-0025 운영규범 (Operating protocols & control standards)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0025) | 운영규범 (Operating protocols & control standards) | `OS_OPERATING_PROTOCOLS` | `ax_paradigm_architect` |
| 22 | [S3S-0026 정보 보안 (Privacy & sovereignty)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0026) | 정보 보안 (Privacy & sovereignty) | `OS_PRIVACY_SOVEREIGNTY` | `ax_paradigm_architect` |
| 23 | [S3S-0027 공통 컨텍스트와 거버넌스 컨텍스트 (Common & Governance context)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0027) | 공통 컨텍스트와 거버넌스 컨텍스트 (Common & Governance context) | `OS_COMMON_GOVERNANCE_CONTEXT` | `ax_paradigm_architect` |
| 24 | [S3S-0028 Organizational digital twin(ODT)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0028) | Organizational digital twin(ODT) | `OS_ORGANIZATIONAL_DIGITAL_TWIN` | `ax_paradigm_architect` |
| 25 | [S3S-0030 AI 주권 (Sovereignty)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0030) | AI 주권 (Sovereignty) | `AI_SOVEREIGNTY` | `ax_paradigm_architect` |
| 26 | [S3S-0032 H: 인간 (Human)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0032) | H: 인간 (Human) | `HUMAN_MEMBER` | `ax_paradigm_architect` |
| 27 | [S3S-0033 B: 봇 (Bot)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0033) | B: 봇 (Bot) | `BOT_MEMBER` | `ax_paradigm_architect` |
| 28 | [S3S-0035 AI agent](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0035) | AI agent | `DIGITAL_WORKER_AI_AGENT` | `ax_paradigm_architect` |
| 29 | [S3S-0036 Subagent](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0036) | Subagent | `DIGITAL_WORKER_SUBAGENT` | `ax_paradigm_architect` |
| 30 | [S3S-0037 Bot (봇)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0037) | Bot (봇) | `DIGITAL_WORKER_BOT` | `ax_paradigm_architect` |
| 31 | [S3S-0039 H + B (도구형 협력)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0039) | H + B (도구형 협력) | `COOP_TYPE_H_PLUS_B` | `ax_paradigm_architect` |
| 32 | [S3S-0040 H + AH (증강인간 중심 협력)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0040) | H + AH (증강인간 중심 협력) | `COOP_TYPE_H_PLUS_AH` | `ax_paradigm_architect` |
| 33 | [S3S-0041 AH + B (지능형 작업 분업)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0041) | AH + B (지능형 작업 분업) | `COOP_TYPE_AH_PLUS_B` | `ax_paradigm_architect` |
| 34 | [S3S-0042 AH + AB (진정한 AX조직)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0042) | AH + AB (진정한 AX조직) | `COOP_TYPE_AH_PLUS_AB` | `ax_paradigm_architect` |
| 35 | [S3S-0043 진정한 AX조직 / 하이브리드 조직 (AH+AB)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0043) | 진정한 AX조직 / 하이브리드 조직 (AH+AB) | `HYBRID_ORGANIZATION` | `ax_paradigm_architect` |
| 36 | [S3S-0045 Human-in-the-loop (인간 승인 중심)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0045) | Human-in-the-loop (인간 승인 중심) | `COLLAB_MODE_HUMAN_IN_THE_LOOP` | `ax_paradigm_architect` |
| 37 | [S3S-0046 AI-in-the-loop (인간 중심 + AI 보조)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0046) | AI-in-the-loop (인간 중심 + AI 보조) | `COLLAB_MODE_AI_IN_THE_LOOP` | `ax_paradigm_architect` |
| 38 | [S3S-0047 Human-on-the-loop (AI 자율 + 인간 감독)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0047) | Human-on-the-loop (AI 자율 + 인간 감독) | `COLLAB_MODE_HUMAN_ON_THE_LOOP` | `ax_paradigm_architect` |
| 39 | [S3S-0048 Autonomous AI (AI 자율 수행)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0048) | Autonomous AI (AI 자율 수행) | `COLLAB_MODE_AUTONOMOUS_AI` | `ax_paradigm_architect` |
| 40 | [S3S-0049 증강 (Augmentation)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0049) | 증강 (Augmentation) | `AUGMENTATION` | `ax_management_philosopher` |
| 41 | [S3S-0051 기본 전제: 인간중심주의(Human Centrality)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0051) | 기본 전제: 인간중심주의(Human Centrality) | `PREMISE_HUMAN_CENTRALITY` | `ax_management_philosopher` |
| 42 | [S3S-0052 증강(Augmentation) 실현](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0052) | 증강(Augmentation) 실현 | `SPIRIT_AUGMENTATION` | `ax_management_philosopher` |
| 43 | [S3S-0053 다양성(Diversity) 존중과 활용](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0053) | 다양성(Diversity) 존중과 활용 | `SPIRIT_DIVERSITY_RESPECT` | `ax_management_philosopher` |
| 44 | [S3S-0054 보완적 적합성(Complementary Fit) 추구](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0054) | 보완적 적합성(Complementary Fit) 추구 | `SPIRIT_COMPLEMENTARY_FIT` | `ax_management_philosopher` |
| 45 | [S3S-0055 인간중심주의 (Human Centrality)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0055) | 인간중심주의 (Human Centrality) | `HUMAN_CENTRALITY` | `ax_management_philosopher` |
| 46 | [S3S-0057 유사적합성 (Supplementary Fit)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0057) | 유사적합성 (Supplementary Fit) | `SUPPLEMENTARY_FIT` | `ax_management_philosopher` |
| 47 | [S3S-0059 인지적(cognitive) 보완](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0059) | 인지적(cognitive) 보완 | `COMPFIT_COGNITIVE` | `ax_management_philosopher` |
| 48 | [S3S-0060 정서적(emotional) 보완](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0060) | 정서적(emotional) 보완 | `COMPFIT_EMOTIONAL` | `ax_management_philosopher` |
| 49 | [S3S-0061 행동적(behavioral) 보완](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0061) | 행동적(behavioral) 보완 | `COMPFIT_BEHAVIORAL` | `ax_management_philosopher` |
| 50 | [S3S-0062 윤리적(ethical) 보완](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0062) | 윤리적(ethical) 보완 | `COMPFIT_ETHICAL` | `ax_management_philosopher` |
| 51 | [S3S-0064 혼(魂)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0064) | 혼(魂) | `HBS_DIM_HON` | `ax_management_philosopher` |
| 52 | [S3S-0065 백(魄)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0065) | 백(魄) | `HBS_DIM_BAEK` | `ax_management_philosopher` |
| 53 | [S3S-0066 영(靈)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0066) | 영(靈) | `HBS_DIM_YEONG` | `ax_management_philosopher` |
| 54 | [S3S-0067 혼비(魂飛) — 판단 주권의 상실](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0067) | 혼비(魂飛) — 판단 주권의 상실 | `HBS_STATE_HONBI` | `ax_management_philosopher` |
| 55 | [S3S-0068 백산(魄散) — 신체와 노동의 시스템화](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0068) | 백산(魄散) — 신체와 노동의 시스템화 | `HBS_STATE_BAEKSAN` | `ax_management_philosopher` |
| 56 | [S3S-0069 혼의 외주화 (AI에게 맡겨지는 판단)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0069) | 혼의 외주화 (AI에게 맡겨지는 판단) | `HBS_OUTSOURCE_HON` | `ax_management_philosopher` |
| 57 | [S3S-0070 백의 외주화 (로봇에게 맡겨지는 실행)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0070) | 백의 외주화 (로봇에게 맡겨지는 실행) | `HBS_OUTSOURCE_BAEK` | `ax_management_philosopher` |
| 58 | [S3S-0071 인간 백 + AI 혼](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0071) | 인간 백 + AI 혼 | `HBS_COMBINE_HUMANBODY_AIMIND` | `ax_management_philosopher` |
| 59 | [S3S-0072 기계 백 + 인간 혼](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0072) | 기계 백 + 인간 혼 | `HBS_COMBINE_MACHINEBODY_HUMANMIND` | `ax_management_philosopher` |
| 60 | [S3S-0073 최종 책임은 인간과 조직에 남아야 한다](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0073) | 최종 책임은 인간과 조직에 남아야 한다 | `HBS_PREV_FINAL_RESPONSIBILITY` | `ax_management_philosopher` |
| 61 | [S3S-0074 AI의 판단 과정은 기록되어야 한다](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0074) | AI의 판단 과정은 기록되어야 한다 | `HBS_PREV_DECISION_LOGGING` | `ax_management_philosopher` |
| 62 | [S3S-0075 인간은 AI 결과의 소비자가 아니라 검토자가 되어야 한다](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0075) | 인간은 AI 결과의 소비자가 아니라 검토자가 되어야 한다 | `HBS_PREV_HUMAN_AS_REVIEWER` | `ax_management_philosopher` |
| 63 | [S3S-0076 자동화는 인간을 부품화해서는 안 된다](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0076) | 자동화는 인간을 부품화해서는 안 된다 | `HBS_PREV_NO_HUMAN_COMPONENTIZATION` | `ax_management_philosopher` |
| 64 | [S3S-0077 기술 도입에는 거버넌스가 함께 설계되어야 한다](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0077) | 기술 도입에는 거버넌스가 함께 설계되어야 한다 | `HBS_PREV_GOVERNANCE_BY_DESIGN` | `ax_management_philosopher` |
| 65 | [S3S-0079 생존 층위](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0079) | 생존 층위 | `LAYER_SURVIVAL` | `ax_management_philosopher` |
| 66 | [S3S-0080 능력 층위](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0080) | 능력 층위 | `LAYER_CAPABILITY` | `ax_management_philosopher` |
| 67 | [S3S-0081 관계 층위](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0081) | 관계 층위 | `LAYER_RELATIONSHIP` | `ax_management_philosopher` |
| 68 | [S3S-0082 존재 층위](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0082) | 존재 층위 | `LAYER_EXISTENCE` | `ax_management_philosopher` |
| 69 | [S3S-0084 생존불안형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0084) | 생존불안형 | `IND_SURVIVAL_ANXIETY` | `ax_management_philosopher` |
| 70 | [S3S-0085 역량열등형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0085) | 역량열등형 | `IND_COMPETENCE_INFERIORITY` | `ax_management_philosopher` |
| 71 | [S3S-0086 통제상실형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0086) | 통제상실형 | `IND_CONTROL_LOSS` | `ax_management_philosopher` |
| 72 | [S3S-0087 감시공포형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0087) | 감시공포형 | `IND_SURVEILLANCE_FEAR` | `ax_management_philosopher` |
| 73 | [S3S-0088 인간성방어형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0088) | 인간성방어형 | `IND_HUMANITY_DEFENSE` | `ax_management_philosopher` |
| 74 | [S3S-0090 노동조합형 반발](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0090) | 노동조합형 반발 | `COL_LABOR_UNION` | `ax_management_philosopher` |
| 75 | [S3S-0091 전문직 집단 저항](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0091) | 전문직 집단 저항 | `COL_PROFESSIONAL_GROUP` | `ax_management_philosopher` |
| 76 | [S3S-0092 사회문화적 반발](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0092) | 사회문화적 반발 | `COL_SOCIOCULTURAL` | `ax_management_philosopher` |
| 77 | [S3S-0093 정치·정책적 반발](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0093) | 정치·정책적 반발 | `COL_POLITICAL_POLICY` | `ax_management_philosopher` |
| 78 | [S3S-0094 존재론적 반발](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0094) | 존재론적 반발 | `COL_ONTOLOGICAL` | `ax_management_philosopher` |
| 79 | [S3S-0096 정체성(identity) 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0096) | 정체성(identity) 스트레스 | `AXSTRESS_IDENTITY` | `ax_management_philosopher` |
| 80 | [S3S-0097 신뢰(trust) 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0097) | 신뢰(trust) 스트레스 | `AXSTRESS_TRUST` | `ax_management_philosopher` |
| 81 | [S3S-0098 통제(control) 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0098) | 통제(control) 스트레스 | `AXSTRESS_CONTROL` | `ax_management_philosopher` |
| 82 | [S3S-0099 책임(responsibility) 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0099) | 책임(responsibility) 스트레스 | `AXSTRESS_RESPONSIBILITY` | `ax_management_philosopher` |
| 83 | [S3S-0101 역할 모호성(Role Ambiguity)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0101) | 역할 모호성(Role Ambiguity) | `HSTRESS_ROLE_AMBIGUITY` | `ax_management_philosopher` |
| 84 | [S3S-0102 역량 대체 불안(Replacement Anxiety)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0102) | 역량 대체 불안(Replacement Anxiety) | `HSTRESS_REPLACEMENT_ANXIETY` | `ax_management_philosopher` |
| 85 | [S3S-0103 인지 과부하(Cognitive Overload)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0103) | 인지 과부하(Cognitive Overload) | `HSTRESS_COGNITIVE_OVERLOAD` | `ax_management_philosopher` |
| 86 | [S3S-0104 AI 불신 혹은 과신에서 오는 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0104) | AI 불신 혹은 과신에서 오는 스트레스 | `HSTRESS_AI_DISTRUST_OVERTRUST` | `ax_management_philosopher` |
| 87 | [S3S-0105 사회적·관계적 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0105) | 사회적·관계적 스트레스 | `HSTRESS_SOCIAL_RELATIONAL` | `ax_management_philosopher` |
| 88 | [S3S-0107 계산 과부하(Computational Overload)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0107) | 계산 과부하(Computational Overload) | `BSTRESS_COMPUTATIONAL_OVERLOAD` | `ax_management_philosopher` |
| 89 | [S3S-0108 목표 충돌(Goal Conflict)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0108) | 목표 충돌(Goal Conflict) | `BSTRESS_GOAL_CONFLICT` | `ax_management_philosopher` |
| 90 | [S3S-0109 정렬 실패(Misalignment)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0109) | 정렬 실패(Misalignment) | `BSTRESS_MISALIGNMENT` | `ax_management_philosopher` |
| 91 | [S3S-0110 지속적 업데이트 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0110) | 지속적 업데이트 스트레스 | `BSTRESS_CONTINUOUS_UPDATE` | `ax_management_philosopher` |
| 92 | [S3S-0111 다중 Agent 협력 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0111) | 다중 Agent 협력 스트레스 | `BSTRESS_MULTI_AGENT_COOP` | `ax_management_philosopher` |
| 93 | [S3S-0113 본질](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0113) | 본질 | `HBCMP_ESSENCE` | `ax_management_philosopher` |
| 94 | [S3S-0114 핵심 원인](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0114) | 핵심 원인 | `HBCMP_ROOT_CAUSE` | `ax_management_philosopher` |
| 95 | [S3S-0115 결과](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0115) | 결과 | `HBCMP_RESULT` | `ax_management_philosopher` |
| 96 | [S3S-0116 회복 방식](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0116) | 회복 방식 | `HBCMP_RECOVERY` | `ax_management_philosopher` |
| 97 | [S3S-0117 위험](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0117) | 위험 | `HBCMP_RISK` | `ax_management_philosopher` |
| 98 | [S3S-0118 측정](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0118) | 측정 | `HBCMP_MEASUREMENT` | `ax_management_philosopher` |
| 99 | [S3S-0119 관계(상호작용) 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0119) | 관계(상호작용) 스트레스 | `INTERACTION_STRESS` | `ax_management_philosopher` |
| 100 | [S3S-0121 H + B 유형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0121) | H + B 유형 | `COOP_H_B` | `ax_management_philosopher` |
| 101 | [S3S-0122 H + AH 유형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0122) | H + AH 유형 | `COOP_H_AH` | `ax_management_philosopher` |
| 102 | [S3S-0123 AH + B 유형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0123) | AH + B 유형 | `COOP_AH_B` | `ax_management_philosopher` |
| 103 | [S3S-0124 AH + AB 유형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0124) | AH + AB 유형 | `COOP_AH_AB` | `ax_management_philosopher` |
| 104 | [S3S-0126 AI 이해력과 친화성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0126) | AI 이해력과 친화성 | `AI_LITERACY_AND_AFFINITY` | `ax_talent_role_designer` |
| 105 | [S3S-0127 인간-AI 협업능력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0127) | 인간-AI 협업능력 | `HUMAN_AI_COLLABORATION_ABILITY` | `ax_talent_role_designer` |
| 106 | [S3S-0128 지속적 학습능력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0128) | 지속적 학습능력 | `CONTINUOUS_LEARNING_ABILITY` | `ax_talent_role_designer` |
| 107 | [S3S-0129 데이터·디지털 문해력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0129) | 데이터·디지털 문해력 | `DATA_DIGITAL_LITERACY` | `ax_talent_role_designer` |
| 108 | [S3S-0130 비판적 사고](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0130) | 비판적 사고 | `CRITICAL_THINKING_COMPETENCY` | `ax_talent_role_designer` |
| 109 | [S3S-0131 조직변화 적응력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0131) | 조직변화 적응력 | `ORG_CHANGE_ADAPTABILITY` | `ax_talent_role_designer` |
| 110 | [S3S-0133 문제 정의 능력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0133) | 문제 정의 능력 | `PROBLEM_FRAMING_CAPABILITY` | `ax_talent_role_designer` |
| 111 | [S3S-0134 의미(meaning) 설계 능력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0134) | 의미(meaning) 설계 능력 | `MEANING_DESIGN_CAPABILITY` | `ax_talent_role_designer` |
| 112 | [S3S-0135 시스템 사고](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0135) | 시스템 사고 | `SYSTEMS_THINKING_CAPABILITY` | `ax_talent_role_designer` |
| 113 | [S3S-0136 인간-AI 오케스트레이션 능력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0136) | 인간-AI 오케스트레이션 능력 | `HUMAN_AI_ORCHESTRATION_CAPABILITY` | `ax_talent_role_designer` |
| 114 | [S3S-0137 거버넌스 & 윤리적 판단력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0137) | 거버넌스 & 윤리적 판단력 | `GOVERNANCE_AND_ETHICAL_JUDGMENT` | `ax_talent_role_designer` |
| 115 | [S3S-0139 맥락 책임](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0139) | 맥락 책임 | `CONTEXT_RESPONSIBILITY` | `ax_talent_role_designer` |
| 116 | [S3S-0140 판단 책임](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0140) | 판단 책임 | `JUDGMENT_RESPONSIBILITY` | `ax_talent_role_designer` |
| 117 | [S3S-0141 증거 책임](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0141) | 증거 책임 | `EVIDENCE_RESPONSIBILITY` | `ax_talent_role_designer` |
| 118 | [S3S-0143 문제 정의자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0143) | 문제 정의자 | `ROLE_PROBLEM_DEFINER` | `ax_talent_role_designer` |
| 119 | [S3S-0144 맥락 구성자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0144) | 맥락 구성자 | `ROLE_CONTEXT_BUILDER` | `ax_talent_role_designer` |
| 120 | [S3S-0145 AI 실행 지시자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0145) | AI 실행 지시자 | `ROLE_AI_EXECUTION_DIRECTOR` | `ax_talent_role_designer` |
| 121 | [S3S-0146 결과 해석자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0146) | 결과 해석자 | `ROLE_RESULT_INTERPRETER` | `ax_talent_role_designer` |
| 122 | [S3S-0147 검증자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0147) | 검증자 | `ROLE_VALIDATOR_OF_EIGHT` | `ax_talent_role_designer` |
| 123 | [S3S-0148 책임 판단자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0148) | 책임 판단자 | `ROLE_ACCOUNTABILITY_JUDGE` | `ax_talent_role_designer` |
| 124 | [S3S-0149 증거 관리자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0149) | 증거 관리자 | `ROLE_EVIDENCE_KEEPER` | `ax_talent_role_designer` |
| 125 | [S3S-0150 개선 반영자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0150) | 개선 반영자 | `ROLE_IMPROVEMENT_REFLECTOR` | `ax_talent_role_designer` |
| 126 | [S3S-0152 조형자 (Shaper/Designer)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0152) | 조형자 (Shaper/Designer) | `CORE_ROLE_SHAPER` | `ax_talent_role_designer` |
| 127 | [S3S-0153 구현자 (Implementer)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0153) | 구현자 (Implementer) | `CORE_ROLE_IMPLEMENTER` | `ax_talent_role_designer` |
| 128 | [S3S-0154 검증자 (Validator)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0154) | 검증자 (Validator) | `CORE_ROLE_VALIDATOR` | `ax_talent_role_designer` |
| 129 | [S3S-0155 운영자 (Operator)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0155) | 운영자 (Operator) | `CORE_ROLE_OPERATOR` | `ax_talent_role_designer` |
| 130 | [S3S-0156 조정자 (Coordinator)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0156) | 조정자 (Coordinator) | `CORE_ROLE_COORDINATOR` | `ax_talent_role_designer` |
| 131 | [S3S-0158 일](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0158) | 일 | `WORK_AS_PERFORMED_ACT` | `ax_talent_role_designer` |
| 132 | [S3S-0159 기여](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0159) | 기여 | `CONTRIBUTION_AS_VALID_CHANGE` | `ax_talent_role_designer` |
| 133 | [S3S-0160 역할](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0160) | 역할 | `ROLE_AS_CONTRIBUTION_POSITION` | `ax_talent_role_designer` |
| 134 | [S3S-0165 인간-AI 오케스트레이션 (orchestration)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0165) | 인간-AI 오케스트레이션 (orchestration) | `HUMAN_AI_ORCHESTRATION` | `ax_talent_role_designer` |
| 135 | [S3S-0166 인간성 수호 (humanity)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0166) | 인간성 수호 (humanity) | `HUMANITY_PROTECTION` | `ax_talent_role_designer` |
| 136 | [S3S-0168 신체적 증강](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0168) | 신체적 증강 | `AH_PHYSICAL_AUGMENTATION` | `ax_bot_governance_steward` |
| 137 | [S3S-0169 정신적 증강](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0169) | 정신적 증강 | `AH_MENTAL_AUGMENTATION` | `ax_bot_governance_steward` |
| 138 | [S3S-0170 역할·맥락 증강](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0170) | 역할·맥락 증강 | `AH_ROLE_CONTEXT_AUGMENTATION` | `ax_bot_governance_steward` |
| 139 | [S3S-0171 목적을 정하는 힘](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0171) | 목적을 정하는 힘 | `AH_POWER_SET_PURPOSE` | `ax_bot_governance_steward` |
| 140 | [S3S-0172 기준을 세우는 힘](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0172) | 기준을 세우는 힘 | `AH_POWER_SET_CRITERIA` | `ax_bot_governance_steward` |
| 141 | [S3S-0173 최종 판단과 책임을 지는 힘](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0173) | 최종 판단과 책임을 지는 힘 | `AH_POWER_FINAL_JUDGMENT` | `ax_bot_governance_steward` |
| 142 | [S3S-0175 검증 가능성 (verifiability)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0175) | 검증 가능성 (verifiability) | `AB_VERIFIABILITY` | `ax_bot_governance_steward` |
| 143 | [S3S-0176 권한 준수 (boundary compliance)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0176) | 권한 준수 (boundary compliance) | `AB_BOUNDARY_COMPLIANCE` | `ax_bot_governance_steward` |
| 144 | [S3S-0177 기준 내재화 (criteria internalization)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0177) | 기준 내재화 (criteria internalization) | `AB_CRITERIA_INTERNALIZATION` | `ax_bot_governance_steward` |
| 145 | [S3S-0178 개선 루프 (improvement loop)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0178) | 개선 루프 (improvement loop) | `AB_IMPROVEMENT_LOOP` | `ax_bot_governance_steward` |
| 146 | [S3S-0179 맥락 증강](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0179) | 맥락 증강 | `AB_CONTEXT_AUGMENTATION` | `ax_bot_governance_steward` |
| 147 | [S3S-0180 거버넌스 증강](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0180) | 거버넌스 증강 | `AB_GOVERNANCE_AUGMENTATION` | `ax_bot_governance_steward` |
| 148 | [S3S-0181 학습 증강](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0181) | 학습 증강 | `AB_LEARNING_AUGMENTATION` | `ax_bot_governance_steward` |
| 149 | [S3S-0183 인간-봇 사회성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0183) | 인간-봇 사회성 | `HUMAN_BOT_SOCIALITY` | `ax_bot_governance_steward` |
| 150 | [S3S-0184 봇-봇 사회성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0184) | 봇-봇 사회성 | `BOT_BOT_SOCIALITY` | `ax_bot_governance_steward` |
| 151 | [S3S-0185 봇의 윤리성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0185) | 봇의 윤리성 | `BOT_ETHICS` | `ax_bot_governance_steward` |
| 152 | [S3S-0187 UNESCO의 AI 윤리권고 (Recommendation on the Ethics of AI, 2021)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0187) | UNESCO의 AI 윤리권고 (Recommendation on the Ethics of AI, 2021) | `UNESCO_AI_ETHICS_RECOMMENDATION` | `ax_bot_governance_steward` |
| 153 | [S3S-0188 한국 정부 (사람이 중심이 되는 AI 윤리기준)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0188) | 한국 정부 (사람이 중심이 되는 AI 윤리기준) | `KOREA_HUMAN_CENTERED_AI_ETHICS` | `ax_bot_governance_steward` |
| 154 | [S3S-0190 포괄적 안전성 (broadly safe)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0190) | 포괄적 안전성 (broadly safe) | `CC_BROADLY_SAFE` | `ax_bot_governance_steward` |
| 155 | [S3S-0191 포괄적 윤리성 (broadly ethical)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0191) | 포괄적 윤리성 (broadly ethical) | `CC_BROADLY_ETHICAL` | `ax_bot_governance_steward` |
| 156 | [S3S-0192 유용성 (helpfulness)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0192) | 유용성 (helpfulness) | `CC_HELPFULNESS` | `ax_bot_governance_steward` |
| 157 | [S3S-0193 가이드라인 준수 (compliance with guidelines)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0193) | 가이드라인 준수 (compliance with guidelines) | `CC_GUIDELINE_COMPLIANCE` | `ax_bot_governance_steward` |
| 158 | [S3S-0195 조직AX의 윤리적 필요조건](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0195) | 조직AX의 윤리적 필요조건 | `AX_ETHICS_NECESSARY_CONDITION` | `ax_bot_governance_steward` |
| 159 | [S3S-0196 조직AX의 추가조건](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0196) | 조직AX의 추가조건 | `AX_ETHICS_ADDITIONAL_CONDITION` | `ax_bot_governance_steward` |
| 160 | [S3S-0198 ① 인간의 안전과 생명 존중(보호)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0198) | ① 인간의 안전과 생명 존중(보호) | `ROBOT_LAW_HUMAN_SAFETY` | `ax_bot_governance_steward` |
| 161 | [S3S-0199 ② 인간에 대한 복종(존엄성 및 시열 인정)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0199) | ② 인간에 대한 복종(존엄성 및 시열 인정) | `ROBOT_LAW_OBEDIENCE` | `ax_bot_governance_steward` |
| 162 | [S3S-0200 ③ 로봇 스스로 자기보호(존재의 유지)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0200) | ③ 로봇 스스로 자기보호(존재의 유지) | `ROBOT_LAW_SELF_PRESERVATION` | `ax_bot_governance_steward` |
| 163 | [S3S-0201 인간존중의 내재화](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0201) | 인간존중의 내재화 | `HUMAN_RESPECT_INTERNALIZATION` | `ax_bot_governance_steward` |
| 164 | [S3S-0203 비해(Non-harm)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0203) | 비해(Non-harm) | `HR_NON_HARM` | `ax_bot_governance_steward` |
| 165 | [S3S-0204 자율성 존중(Autonomy)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0204) | 자율성 존중(Autonomy) | `HR_AUTONOMY` | `ax_bot_governance_steward` |
| 166 | [S3S-0205 공정성(Fairness)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0205) | 공정성(Fairness) | `HR_FAIRNESS` | `ax_bot_governance_steward` |
| 167 | [S3S-0206 책임성(Accountability)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0206) | 책임성(Accountability) | `HR_ACCOUNTABILITY` | `ax_bot_governance_steward` |
| 168 | [S3S-0208 1단계(보상 설계)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0208) | 1단계(보상 설계) | `HR_STAGE1_REWARD_DESIGN` | `ax_bot_governance_steward` |
| 169 | [S3S-0209 2단계(강제 규칙)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0209) | 2단계(강제 규칙) | `HR_STAGE2_HARD_RULES` | `ax_bot_governance_steward` |
| 170 | [S3S-0210 3단계(인간 피드백 학습)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0210) | 3단계(인간 피드백 학습) | `HR_STAGE3_HUMAN_FEEDBACK_LEARNING` | `ax_bot_governance_steward` |
| 171 | [S3S-0211 4단계(검증 Layer)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0211) | 4단계(검증 Layer) | `HR_STAGE4_VERIFICATION_LAYER` | `ax_bot_governance_steward` |
| 172 | [S3S-0212 5단계(Multi-agent 환경의 인간존중)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0212) | 5단계(Multi-agent 환경의 인간존중) | `HR_STAGE5_MULTIAGENT_HUMAN_RESPECT` | `ax_bot_governance_steward` |
| 173 | [S3S-0214 인간의 비논리성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0214) | 인간의 비논리성 | `HUMAN_ILLOGICALITY` | `ax_bot_governance_steward` |
| 174 | [S3S-0215 AI 관련 인간의 스트레스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0215) | AI 관련 인간의 스트레스 | `HUMAN_AI_RELATED_STRESS` | `ax_bot_governance_steward` |
| 175 | [S3S-0216 사회적 협력 규범 학습](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0216) | 사회적 협력 규범 학습 | `SOCIAL_COOPERATION_NORM_LEARNING` | `ax_bot_governance_steward` |
| 176 | [S3S-0218 거대한 패턴 탐지기로서의 봇](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0218) | 거대한 패턴 탐지기로서의 봇 | `BOT_AS_PATTERN_DETECTOR` | `ax_bot_governance_steward` |
| 177 | [S3S-0219 기능적 만족/불만족](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0219) | 기능적 만족/불만족 | `BOT_FUNCTIONAL_SATISFACTION` | `ax_bot_governance_steward` |
| 178 | [S3S-0220 봇의 욕구 위계(hierarchy) 형성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0220) | 봇의 욕구 위계(hierarchy) 형성 | `BOT_DESIRE_HIERARCHY` | `ax_bot_governance_steward` |
| 179 | [S3S-0221 목표(Goal)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0221) | 목표(Goal) | `BOT_DRIVER_GOAL` | `ax_bot_governance_steward` |
| 180 | [S3S-0222 보상 함수(Reward Function)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0222) | 보상 함수(Reward Function) | `BOT_DRIVER_REWARD_FUNCTION` | `ax_bot_governance_steward` |
| 181 | [S3S-0223 최적화 알고리즘(Optimization)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0223) | 최적화 알고리즘(Optimization) | `BOT_DRIVER_OPTIMIZATION_ALGORITHM` | `ax_bot_governance_steward` |
| 182 | [S3S-0224 봇의 행복](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0224) | 봇의 행복 | `BOT_HAPPINESS` | `ax_bot_governance_steward` |
| 183 | [S3S-0226 Level 4 Verifier/Governor](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0226) | Level 4 Verifier/Governor | `BOT_LEVEL4_VERIFIER_GOVERNOR` | `ax_bot_governance_steward` |
| 184 | [S3S-0227 Level 3 Planner/Strategist](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0227) | Level 3 Planner/Strategist | `BOT_LEVEL3_PLANNER_STRATEGIST` | `ax_bot_governance_steward` |
| 185 | [S3S-0228 Level 2 Specialist/Executor](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0228) | Level 2 Specialist/Executor | `BOT_LEVEL2_SPECIALIST_EXECUTOR` | `ax_bot_governance_steward` |
| 186 | [S3S-0229 Level 1 Tool/Reactive Agent](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0229) | Level 1 Tool/Reactive Agent | `BOT_LEVEL1_TOOL_REACTIVE_AGENT` | `ax_bot_governance_steward` |
| 187 | [S3S-0230 의사결정 권한(Decision Authority)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0230) | 의사결정 권한(Decision Authority) | `HIER_CRITERION_DECISION_AUTHORITY` | `ax_bot_governance_steward` |
| 188 | [S3S-0231 정보 비대칭(Information Asymmetry)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0231) | 정보 비대칭(Information Asymmetry) | `HIER_CRITERION_INFORMATION_ASYMMETRY` | `ax_bot_governance_steward` |
| 189 | [S3S-0232 성능 및 신뢰도(Performance/Reliability)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0232) | 성능 및 신뢰도(Performance/Reliability) | `HIER_CRITERION_PERFORMANCE_RELIABILITY` | `ax_bot_governance_steward` |
| 190 | [S3S-0233 네트워크 중심성(Network Centrality)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0233) | 네트워크 중심성(Network Centrality) | `HIER_CRITERION_NETWORK_CENTRALITY` | `ax_bot_governance_steward` |
| 191 | [S3S-0234 검증 능력(Verification Power)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0234) | 검증 능력(Verification Power) | `HIER_CRITERION_VERIFICATION_POWER` | `ax_bot_governance_steward` |
| 192 | [S3S-0236 구성원 확장](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0236) | 구성원 확장 | `HBRM_MEMBER_EXPANSION` | `ax_bot_governance_steward` |
| 193 | [S3S-0237 역할 확장](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0237) | 역할 확장 | `HBRM_ROLE_EXPANSION` | `ax_bot_governance_steward` |
| 194 | [S3S-0238 진화 확장](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0238) | 진화 확장 | `HBRM_EVOLUTION_EXPANSION` | `ax_bot_governance_steward` |
| 195 | [S3S-0239 구성원 정의](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0239) | 구성원 정의 | `HBRM_ROLE_MEMBER_DEFINITION` | `ax_bot_governance_steward` |
| 196 | [S3S-0240 역할 설계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0240) | 역할 설계 | `HBRM_ROLE_ROLE_DESIGN` | `ax_bot_governance_steward` |
| 197 | [S3S-0241 협력 구조 설계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0241) | 협력 구조 설계 | `HBRM_ROLE_COLLABORATION_DESIGN` | `ax_bot_governance_steward` |
| 198 | [S3S-0242 증강 관리](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0242) | 증강 관리 | `HBRM_ROLE_AUGMENTATION_MANAGEMENT` | `ax_bot_governance_steward` |
| 199 | [S3S-0243 역할균형 관리](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0243) | 역할균형 관리 | `HBRM_ROLE_ROLE_BALANCE_MANAGEMENT` | `ax_bot_governance_steward` |
| 200 | [S3S-0244 신뢰 관리](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0244) | 신뢰 관리 | `HBRM_ROLE_TRUST_MANAGEMENT` | `ax_bot_governance_steward` |
| 201 | [S3S-0245 거버넌스 연결](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0245) | 거버넌스 연결 | `HBRM_ROLE_GOVERNANCE_LINKAGE` | `ax_bot_governance_steward` |
| 202 | [S3S-0246 학습·개선 관리](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0246) | 학습·개선 관리 | `HBRM_ROLE_LEARNING_IMPROVEMENT` | `ax_bot_governance_steward` |
| 203 | [S3S-0248 방법(method)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0248) | 방법(method) | `HBRM_3M_METHOD` | `ax_bot_governance_steward` |
| 204 | [S3S-0249 의미(meaning)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0249) | 의미(meaning) | `HBRM_3M_MEANING` | `ax_bot_governance_steward` |
| 205 | [S3S-0252 인지 증강 (Cognitive A.)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0252) | 인지 증강 (Cognitive A.) | `AH_INDICATOR_COGNITIVE` | `ax_bot_governance_steward` |
| 206 | [S3S-0253 의사결정 증강 (Decision A.)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0253) | 의사결정 증강 (Decision A.) | `AH_INDICATOR_DECISION` | `ax_bot_governance_steward` |
| 207 | [S3S-0254 학습 증강 (Learning A.)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0254) | 학습 증강 (Learning A.) | `AH_INDICATOR_LEARNING` | `ax_bot_governance_steward` |
| 208 | [S3S-0255 협업 증강 (Collaboration A.)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0255) | 협업 증강 (Collaboration A.) | `AH_INDICATOR_COLLABORATION` | `ax_bot_governance_steward` |
| 209 | [S3S-0256 역할 증강 (Role A.)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0256) | 역할 증강 (Role A.) | `AH_INDICATOR_ROLE` | `ax_bot_governance_steward` |
| 210 | [S3S-0258 H0 비증강인간](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0258) | H0 비증강인간 | `HA_STAGE_H0_NON_AUGMENTED` | `ax_bot_governance_steward` |
| 211 | [S3S-0259 H1 AI 사용자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0259) | H1 AI 사용자 | `HA_STAGE_H1_AI_USER` | `ax_bot_governance_steward` |
| 212 | [S3S-0260 H2 AI 협업자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0260) | H2 AI 협업자 | `HA_STAGE_H2_AI_COLLABORATOR` | `ax_bot_governance_steward` |
| 213 | [S3S-0261 AH1 증강인간](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0261) | AH1 증강인간 | `HA_STAGE_AH1_AUGMENTED_HUMAN` | `ax_bot_governance_steward` |
| 214 | [S3S-0262 AH2 AI 오케스트레이터](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0262) | AH2 AI 오케스트레이터 | `HA_STAGE_AH2_AI_ORCHESTRATOR` | `ax_bot_governance_steward` |
| 215 | [S3S-0263 AH3 인간-AI 공생형 리더](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0263) | AH3 인간-AI 공생형 리더 | `HA_STAGE_AH3_SYMBIOTIC_LEADER` | `ax_bot_governance_steward` |
| 216 | [S3S-0265 도구 사용자 (Tool User)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0265) | 도구 사용자 (Tool User) | `AIU_STAGE_TOOL_USER` | `ax_bot_governance_steward` |
| 217 | [S3S-0266 협업 사용자 (Collaborative User)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0266) | 협업 사용자 (Collaborative User) | `AIU_STAGE_COLLABORATIVE_USER` | `ax_bot_governance_steward` |
| 218 | [S3S-0267 지휘자 (AI Orchestrator)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0267) | 지휘자 (AI Orchestrator) | `AIU_STAGE_ORCHESTRATOR` | `ax_bot_governance_steward` |
| 219 | [S3S-0268 증강자 (Augmentation User)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0268) | 증강자 (Augmentation User) | `AIU_STAGE_AUGMENTATION_USER` | `ax_bot_governance_steward` |
| 220 | [S3S-0269 사용빈도(frequency)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0269) | 사용빈도(frequency) | `AIU_COMPONENT_FREQUENCY` | `ax_bot_governance_steward` |
| 221 | [S3S-0270 활용 깊이(depth)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0270) | 활용 깊이(depth) | `AIU_COMPONENT_DEPTH` | `ax_bot_governance_steward` |
| 222 | [S3S-0271 자동화 수준(automation)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0271) | 자동화 수준(automation) | `AIU_COMPONENT_AUTOMATION` | `ax_bot_governance_steward` |
| 223 | [S3S-0272 성과개선(outcome)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0272) | 성과개선(outcome) | `AIU_COMPONENT_OUTCOME` | `ax_bot_governance_steward` |
| 224 | [S3S-0273 증강지수 (AQ, Augmentation Quotient)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0273) | 증강지수 (AQ, Augmentation Quotient) | `AUGMENTATION_QUOTIENT` | `ax_bot_governance_steward` |
| 225 | [S3S-0274 증강인간지수 (AHI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0274) | 증강인간지수 (AHI) | `AUGMENTED_HUMAN_INDEX` | `ax_bot_governance_steward` |
| 226 | [S3S-0275 증강인간 역량지수 (AHCI, Augmented Human Capability Index)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0275) | 증강인간 역량지수 (AHCI, Augmented Human Capability Index) | `AUGMENTED_HUMAN_CAPABILITY_INDEX` | `ax_bot_governance_steward` |
| 227 | [S3S-0276 증강인간과 증강봇의 협력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0276) | 증강인간과 증강봇의 협력 | `AH_AB_COLLABORATION` | `ax_bot_governance_steward` |
| 228 | [S3S-0277 팀역할균형 (TRB, Team Role Balance)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0277) | 팀역할균형 (TRB, Team Role Balance) | `TEAM_ROLE_BALANCE` | `ax_team_role_analyst` |
| 229 | [S3S-0278 팀역할 (TR, Team Role)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0278) | 팀역할 (TR, Team Role) | `TEAM_ROLE` | `ax_team_role_analyst` |
| 230 | [S3S-0279 기능역할 (functional role)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0279) | 기능역할 (functional role) | `FUNCTIONAL_ROLE` | `ax_team_role_analyst` |
| 231 | [S3S-0281 팀/자연 역할 (Team/Natural Role)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0281) | 팀/자연 역할 (Team/Natural Role) | `NATURAL_TEAM_ROLE_LEVEL` | `ax_team_role_analyst` |
| 232 | [S3S-0282 잠재/관리가능 역할 (Potential/Manageable Role)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0282) | 잠재/관리가능 역할 (Potential/Manageable Role) | `POTENTIAL_MANAGEABLE_ROLE_LEVEL` | `ax_team_role_analyst` |
| 233 | [S3S-0283 비선호 역할 (Least-preferred Role)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0283) | 비선호 역할 (Least-preferred Role) | `LEAST_PREFERRED_ROLE_LEVEL` | `ax_team_role_analyst` |
| 234 | [S3S-0284 Interplace](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0284) | Interplace | `INTERPLACE` | `ax_team_role_analyst` |
| 235 | [S3S-0286 자기진단지(SPI: self-perception inventory)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0286) | 자기진단지(SPI: self-perception inventory) | `SELF_PERCEPTION_INVENTORY_SPI` | `ax_team_role_analyst` |
| 236 | [S3S-0287 관찰자진단지(OA: observer assessment)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0287) | 관찰자진단지(OA: observer assessment) | `OBSERVER_ASSESSMENT_OA` | `ax_team_role_analyst` |
| 237 | [S3S-0288 직무요구진단지(JRE: job requirement exercise)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0288) | 직무요구진단지(JRE: job requirement exercise) | `JOB_REQUIREMENT_EXERCISE_JRE` | `ax_team_role_analyst` |
| 238 | [S3S-0289 직무관찰자진단지(JOA: job observer assessment)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0289) | 직무관찰자진단지(JOA: job observer assessment) | `JOB_OBSERVER_ASSESSMENT_JOA` | `ax_team_role_analyst` |
| 239 | [S3S-0290 집단응집성 (group cohesiveness)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0290) | 집단응집성 (group cohesiveness) | `GROUP_COHESIVENESS` | `ax_team_role_analyst` |
| 240 | [S3S-0292 인간적 유대감 측면의 팀웍](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0292) | 인간적 유대감 측면의 팀웍 | `HUMAN_BOND_TEAMWORK` | `ax_team_role_analyst` |
| 241 | [S3S-0293 업무적 활성화 측면의 팀웍](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0293) | 업무적 활성화 측면의 팀웍 | `TASK_ACTIVATION_TEAMWORK` | `ax_team_role_analyst` |
| 242 | [S3S-0294 행동유형 (behavior type) vs 성격유형 (personality type)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0294) | 행동유형 (behavior type) vs 성격유형 (personality type) | `BEHAVIOR_TYPE` | `ax_team_role_analyst` |
| 243 | [S3S-0295 RBHRM (Role-Based HRM, 역량+역할주의)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0295) | RBHRM (Role-Based HRM, 역량+역할주의) | `ROLE_BASED_HRM` | `ax_team_role_analyst` |
| 244 | [S3S-0297 창조자 (PL)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0297) | 창조자 (PL) | `BELBIN_ROLE_PLANT_PL` | `ax_team_role_analyst` |
| 245 | [S3S-0298 냉철판단자(ME)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0298) | 냉철판단자(ME) | `BELBIN_ROLE_MONITOR_EVALUATOR_ME` | `ax_team_role_analyst` |
| 246 | [S3S-0299 지휘조절자(CO)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0299) | 지휘조절자(CO) | `BELBIN_ROLE_COORDINATOR_CO` | `ax_team_role_analyst` |
| 247 | [S3S-0300 실행자(IMP)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0300) | 실행자(IMP) | `BELBIN_ROLE_IMPLEMENTER_IMP` | `ax_team_role_analyst` |
| 248 | [S3S-0301 완결자(CF)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0301) | 완결자(CF) | `BELBIN_ROLE_COMPLETER_FINISHER_CF` | `ax_team_role_analyst` |
| 249 | [S3S-0302 자원탐색가(RI)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0302) | 자원탐색가(RI) | `BELBIN_ROLE_RESOURCE_INVESTIGATOR_RI` | `ax_team_role_analyst` |
| 250 | [S3S-0303 분위기조성자(TW)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0303) | 분위기조성자(TW) | `BELBIN_ROLE_TEAMWORKER_TW` | `ax_team_role_analyst` |
| 251 | [S3S-0304 추진자(SH)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0304) | 추진자(SH) | `BELBIN_ROLE_SHAPER_SH` | `ax_team_role_analyst` |
| 252 | [S3S-0305 전문가(SP)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0305) | 전문가(SP) | `BELBIN_ROLE_SPECIALIST_SP` | `ax_team_role_analyst` |
| 253 | [S3S-0307 봇에 의한 TR의 보완](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0307) | 봇에 의한 TR의 보완 | `BOT_TR_COMPLEMENTATION` | `ax_team_role_analyst` |
| 254 | [S3S-0308 봇에 의한 TR의 증강](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0308) | 봇에 의한 TR의 증강 | `BOT_TR_AUGMENTATION` | `ax_team_role_analyst` |
| 255 | [S3S-0309 봇에 의한 TR의 추가](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0309) | 봇에 의한 TR의 추가 | `BOT_TR_ADDITION` | `ax_team_role_analyst` |
| 256 | [S3S-0311 AI Governor](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0311) | AI Governor | `AX_ROLE_AI_GOVERNOR` | `ax_team_role_analyst` |
| 257 | [S3S-0312 AI Auditor](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0312) | AI Auditor | `AX_ROLE_AI_AUDITOR` | `ax_team_role_analyst` |
| 258 | [S3S-0313 Prompt Architect](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0313) | Prompt Architect | `AX_ROLE_PROMPT_ARCHITECT` | `ax_team_role_analyst` |
| 259 | [S3S-0314 AI Workflow Orchestrator](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0314) | AI Workflow Orchestrator | `AX_ROLE_AI_WORKFLOW_ORCHESTRATOR` | `ax_team_role_analyst` |
| 260 | [S3S-0315 Human Meaning Integrator](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0315) | Human Meaning Integrator | `AX_ROLE_HUMAN_MEANING_INTEGRATOR` | `ax_team_role_analyst` |
| 261 | [S3S-0316 Trust Manager](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0316) | Trust Manager | `AX_ROLE_TRUST_MANAGER` | `ax_team_role_analyst` |
| 262 | [S3S-0317 Provenance Controller](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0317) | Provenance Controller | `AX_ROLE_PROVENANCE_CONTROLLER` | `ax_team_role_analyst` |
| 263 | [S3S-0318 동적 역할균형 (dynamic role balance)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0318) | 동적 역할균형 (dynamic role balance) | `DYNAMIC_ROLE_BALANCE` | `ax_team_role_analyst` |
| 264 | [S3S-0320 역할 진단자(Role Diagnostician)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0320) | 역할 진단자(Role Diagnostician) | `BOT_AIDED_ROLE_DIAGNOSTICIAN` | `ax_team_role_analyst` |
| 265 | [S3S-0321 협업 조정자(Collaboration Facilitator)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0321) | 협업 조정자(Collaboration Facilitator) | `BOT_AIDED_COLLABORATION_FACILITATOR` | `ax_team_role_analyst` |
| 266 | [S3S-0322 인지 증강자(Cognitive Augmenter)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0322) | 인지 증강자(Cognitive Augmenter) | `BOT_AIDED_COGNITIVE_AUGMENTER` | `ax_team_role_analyst` |
| 267 | [S3S-0324 역할의 공동 구성(Co-constitution)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0324) | 역할의 공동 구성(Co-constitution) | `COUPLED_CO_CONSTITUTION` | `ax_team_role_analyst` |
| 268 | [S3S-0325 역할 분산 최적화(Dynamic Role Allocation)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0325) | 역할 분산 최적화(Dynamic Role Allocation) | `COUPLED_DYNAMIC_ROLE_ALLOCATION` | `ax_team_role_analyst` |
| 269 | [S3S-0326 인간-봇의 보완적 적합성 극대화(Maximization of Complementary Fit)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0326) | 인간-봇의 보완적 적합성 극대화(Maximization of Complementary Fit) | `COUPLED_MAXIMIZATION_COMPLEMENTARY_FIT` | `ax_team_role_analyst` |
| 270 | [S3S-0328 Human-only TRB](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0328) | Human-only TRB | `TRB_STAGE_HUMAN_ONLY` | `ax_team_role_analyst` |
| 271 | [S3S-0331 증강 역할균형 지수 (ARBI, Augmented Role Balance Index)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0331) | 증강 역할균형 지수 (ARBI, Augmented Role Balance Index) | `ARBI` | `ax_team_role_analyst` |
| 272 | [S3S-0333 역할균형](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0333) | 역할균형 | `ARBI_AXIS_ROLE_BALANCE` | `ax_team_role_analyst` |
| 273 | [S3S-0334 보완적 적합성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0334) | 보완적 적합성 | `ARBI_AXIS_COMPLEMENTARY_FIT` | `ax_team_role_analyst` |
| 274 | [S3S-0335 AI 개입 투명성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0335) | AI 개입 투명성 | `ARBI_AXIS_AI_INTERVENTION_TRANSPARENCY` | `ax_team_role_analyst` |
| 275 | [S3S-0336 발화 주체성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0336) | 발화 주체성 | `ARBI_AXIS_UTTERANCE_AGENCY` | `ax_team_role_analyst` |
| 276 | [S3S-0337 권한·동의 경계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0337) | 권한·동의 경계 | `ARBI_AXIS_AUTHORITY_CONSENT_BOUNDARY` | `ax_team_role_analyst` |
| 277 | [S3S-0338 인간 책임성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0338) | 인간 책임성 | `ARBI_AXIS_HUMAN_ACCOUNTABILITY` | `ax_team_role_analyst` |
| 278 | [S3S-0339 의사소통 공정성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0339) | 의사소통 공정성 | `ARBI_AXIS_COMMUNICATION_FAIRNESS` | `ax_team_role_analyst` |
| 279 | [S3S-0340 기록·추적성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0340) | 기록·추적성 | `ARBI_AXIS_RECORD_TRACEABILITY` | `ax_team_role_analyst` |
| 280 | [S3S-0341 심리·신뢰 안정성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0341) | 심리·신뢰 안정성 | `ARBI_AXIS_PSYCHOLOGICAL_TRUST_STABILITY` | `ax_team_role_analyst` |
| 281 | [S3S-0342 조작 위험](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0342) | 조작 위험 | `ARBI_AXIS_MANIPULATION_RISK` | `ax_team_role_analyst` |
| 282 | [S3S-0343 HBRM (Human-Bot Role Management)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0343) | HBRM (Human-Bot Role Management) | `HUMAN_BOT_ROLE_MANAGEMENT` | `ax_team_role_analyst` |
| 283 | [S3S-0345 로컬 환경](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0345) | 로컬 환경 | `LOCAL_ENVIRONMENT` | `ax_context_chain_architect` |
| 284 | [S3S-0346 네트워크 환경](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0346) | 네트워크 환경 | `NETWORK_ENVIRONMENT` | `ax_context_chain_architect` |
| 285 | [S3S-0348 목적](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0348) | 목적 | `COMMON_CONTEXT_ELEMENT_PURPOSE` | `ax_context_chain_architect` |
| 286 | [S3S-0349 기준](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0349) | 기준 | `COMMON_CONTEXT_ELEMENT_CRITERION` | `ax_context_chain_architect` |
| 287 | [S3S-0350 역할](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0350) | 역할 | `COMMON_CONTEXT_ELEMENT_ROLE` | `ax_context_chain_architect` |
| 288 | [S3S-0351 출처](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0351) | 출처 | `COMMON_CONTEXT_ELEMENT_SOURCE` | `ax_context_chain_architect` |
| 289 | [S3S-0352 형식](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0352) | 형식 | `COMMON_CONTEXT_ELEMENT_FORMAT` | `ax_context_chain_architect` |
| 290 | [S3S-0353 피드백](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0353) | 피드백 | `COMMON_CONTEXT_ELEMENT_FEEDBACK` | `ax_context_chain_architect` |
| 291 | [S3S-0355 권한(authority)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0355) | 권한(authority) | `GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY` | `ax_context_chain_architect` |
| 292 | [S3S-0356 보안(security)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0356) | 보안(security) | `GOVERNANCE_CONTEXT_ELEMENT_SECURITY` | `ax_context_chain_architect` |
| 293 | [S3S-0357 검증(validation)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0357) | 검증(validation) | `GOVERNANCE_CONTEXT_ELEMENT_VALIDATION` | `ax_context_chain_architect` |
| 294 | [S3S-0358 승인(approval)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0358) | 승인(approval) | `GOVERNANCE_CONTEXT_ELEMENT_APPROVAL` | `ax_context_chain_architect` |
| 295 | [S3S-0359 기록(record)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0359) | 기록(record) | `GOVERNANCE_CONTEXT_ELEMENT_RECORD` | `ax_context_chain_architect` |
| 296 | [S3S-0360 책임(accountability)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0360) | 책임(accountability) | `GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY` | `ax_context_chain_architect` |
| 297 | [S3S-0361 개선(improvement)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0361) | 개선(improvement) | `GOVERNANCE_CONTEXT_ELEMENT_IMPROVEMENT` | `ax_context_chain_architect` |
| 298 | [S3S-0362 AI 거버넌스](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0362) | AI 거버넌스 | `AI_GOVERNANCE` | `ax_context_chain_architect` |
| 299 | [S3S-0364 질문](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0364) | 질문 | `KNOWLEDGE_CHAIN_STAGE_QUESTION` | `ax_context_chain_architect` |
| 300 | [S3S-0365 조직 컨텍스트 참조](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0365) | 조직 컨텍스트 참조 | `KNOWLEDGE_CHAIN_STAGE_CONTEXT_REFERENCE` | `ax_context_chain_architect` |
| 301 | [S3S-0366 거버넌스 검증](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0366) | 거버넌스 검증 | `KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION` | `ax_context_chain_architect` |
| 302 | [S3S-0367 결과 기록](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0367) | 결과 기록 | `KNOWLEDGE_CHAIN_STAGE_RESULT_RECORD` | `ax_context_chain_architect` |
| 303 | [S3S-0368 조직 지식에 재반영](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0368) | 조직 지식에 재반영 | `KNOWLEDGE_CHAIN_STAGE_REINTEGRATION` | `ax_context_chain_architect` |
| 304 | [S3S-0369 다음 AI/인간이 재사용](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0369) | 다음 AI/인간이 재사용 | `KNOWLEDGE_CHAIN_STAGE_REUSE` | `ax_context_chain_architect` |
| 305 | [S3S-0371 구조 거리 측정](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0371) | 구조 거리 측정 | `KNOWLEDGE_CHAIN_FUNCTION_STRUCTURAL_DISTANCE` | `ax_context_chain_architect` |
| 306 | [S3S-0372 전제 관계 측정](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0372) | 전제 관계 측정 | `KNOWLEDGE_CHAIN_FUNCTION_PREMISE_RELATION` | `ax_context_chain_architect` |
| 307 | [S3S-0373 추론사슬 충실도 측정](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0373) | 추론사슬 충실도 측정 | `KNOWLEDGE_CHAIN_FUNCTION_REASONING_FIDELITY` | `ax_context_chain_architect` |
| 308 | [S3S-0374 전이 가능성 측정](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0374) | 전이 가능성 측정 | `KNOWLEDGE_CHAIN_FUNCTION_TRANSFER_CAPABILITY` | `ax_context_chain_architect` |
| 309 | [S3S-0375 의미·인지 거리](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0375) | 의미·인지 거리 | `MEANING_COGNITIVE_DISTANCE` | `ax_context_chain_architect` |
| 310 | [S3S-0376 AI 기여도](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0376) | AI 기여도 | `AI_CONTRIBUTION` | `ax_context_chain_architect` |
| 311 | [S3S-0378 지식](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0378) | 지식 | `KNOWLEDGE_ACTION_CHAIN_NODE_KNOWLEDGE` | `ax_context_chain_architect` |
| 312 | [S3S-0379 스킬(skill)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0379) | 스킬(skill) | `KNOWLEDGE_ACTION_CHAIN_NODE_SKILL` | `ax_context_chain_architect` |
| 313 | [S3S-0380 runtime(SkillRuntime)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0380) | runtime(SkillRuntime) | `KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME` | `ax_context_chain_architect` |
| 314 | [S3S-0381 action(실행)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0381) | action(실행) | `KNOWLEDGE_ACTION_CHAIN_NODE_ACTION` | `ax_context_chain_architect` |
| 315 | [S3S-0382 outcome(결과)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0382) | outcome(결과) | `KNOWLEDGE_ACTION_CHAIN_NODE_OUTCOME` | `ax_context_chain_architect` |
| 316 | [S3S-0383 review(검토)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0383) | review(검토) | `KNOWLEDGE_ACTION_CHAIN_NODE_REVIEW` | `ax_context_chain_architect` |
| 317 | [S3S-0384 feedback(피드백)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0384) | feedback(피드백) | `KNOWLEDGE_ACTION_CHAIN_NODE_FEEDBACK` | `ax_context_chain_architect` |
| 318 | [S3S-0385 context(조직 기준)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0385) | context(조직 기준) | `KNOWLEDGE_ACTION_CHAIN_NODE_CONTEXT` | `ax_context_chain_architect` |
| 319 | [S3S-0388 입력](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0388) | 입력 | `SKILL_RUNTIME_SLOT_INPUT` | `ax_context_chain_architect` |
| 320 | [S3S-0389 자료](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0389) | 자료 | `SKILL_RUNTIME_SLOT_MATERIAL` | `ax_context_chain_architect` |
| 321 | [S3S-0390 도구](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0390) | 도구 | `SKILL_RUNTIME_SLOT_TOOL` | `ax_context_chain_architect` |
| 322 | [S3S-0391 금지](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0391) | 금지 | `SKILL_RUNTIME_SLOT_PROHIBITION` | `ax_context_chain_architect` |
| 323 | [S3S-0392 결과 형식](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0392) | 결과 형식 | `SKILL_RUNTIME_SLOT_RESULT_FORMAT` | `ax_context_chain_architect` |
| 324 | [S3S-0393 검토·승인자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0393) | 검토·승인자 | `SKILL_RUNTIME_SLOT_REVIEWER_APPROVER` | `ax_context_chain_architect` |
| 325 | [S3S-0394 기록 위치](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0394) | 기록 위치 | `SKILL_RUNTIME_SLOT_RECORD_LOCATION` | `ax_context_chain_architect` |
| 326 | [S3S-0395 지식행동사슬 노드 온톨로지 (identity·goal·knowledge·method·skill·task·artifact)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0395) | 지식행동사슬 노드 온톨로지 (identity·goal·knowledge·method·skill·task·artifact) | `KNOWLEDGE_ACTION_NODE_ONTOLOGY` | `ax_context_chain_architect` |
| 327 | [S3S-0398 의사소통 컨텍스트](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0398) | 의사소통 컨텍스트 | `THREE_LAYER_CONTEXT_COMMUNICATION_LAYER` | `ax_context_chain_architect` |
| 328 | [S3S-0402 AH-H 간 의사소통](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0402) | AH-H 간 의사소통 | `COMMUNICATION_TYPE_AH_TO_H` | `ax_context_chain_architect` |
| 329 | [S3S-0403 AH-AH 간 의사소통](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0403) | AH-AH 간 의사소통 | `COMMUNICATION_TYPE_AH_TO_AH` | `ax_context_chain_architect` |
| 330 | [S3S-0404 역할 공백](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0404) | 역할 공백 | `ROLE_VACANCY` | `ax_context_chain_architect` |
| 331 | [S3S-0405 기여 충돌](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0405) | 기여 충돌 | `CONTRIBUTION_CONFLICT` | `ax_context_chain_architect` |
| 332 | [S3S-0407 인간 중심 경로](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0407) | 인간 중심 경로 | `AUGMENTED_PATH_HUMAN_CENTERED` | `ax_context_chain_architect` |
| 333 | [S3S-0408 AI 중심 경로](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0408) | AI 중심 경로 | `AUGMENTED_PATH_AI_CENTERED` | `ax_context_chain_architect` |
| 334 | [S3S-0409 거버넌스 경유 경로](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0409) | 거버넌스 경유 경로 | `AUGMENTED_PATH_VIA_GOVERNANCE` | `ax_context_chain_architect` |
| 335 | [S3S-0410 AI 예측지능](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0410) | AI 예측지능 | `PREDICTIVE_INTELLIGENCE` | `ax_inclusive_transition_officer` |
| 336 | [S3S-0412 월드 모델](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0412) | 월드 모델 | `PIS_WORLD_MODEL` | `ax_inclusive_transition_officer` |
| 337 | [S3S-0414 컨텍스트 설계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0414) | 컨텍스트 설계 | `PIS_CONTEXT_DESIGN` | `ax_inclusive_transition_officer` |
| 338 | [S3S-0417 컨텍스트 설계자 (컨텍스트 설계형 AX 인재)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0417) | 컨텍스트 설계자 (컨텍스트 설계형 AX 인재) | `CONTEXT_DESIGNER` | `ax_inclusive_transition_officer` |
| 339 | [S3S-0418 AI 기반 계급화 (AI 계급사회 / AI 기반 계층화)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0418) | AI 기반 계급화 (AI 계급사회 / AI 기반 계층화) | `AI_BASED_STRATIFICATION` | `ax_inclusive_transition_officer` |
| 340 | [S3S-0420 AI 접근 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0420) | AI 접근 격차 | `GAP_AI_ACCESS` | `ax_inclusive_transition_officer` |
| 341 | [S3S-0421 AI 역량 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0421) | AI 역량 격차 | `GAP_AI_CAPABILITY` | `ax_inclusive_transition_officer` |
| 342 | [S3S-0422 AI 맥락 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0422) | AI 맥락 격차 | `GAP_AI_CONTEXT` | `ax_inclusive_transition_officer` |
| 343 | [S3S-0423 AI 판단권 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0423) | AI 판단권 격차 | `GAP_AI_JUDGMENT_RIGHT` | `ax_inclusive_transition_officer` |
| 344 | [S3S-0424 AI 감시 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0424) | AI 감시 격차 | `GAP_AI_SURVEILLANCE` | `ax_inclusive_transition_officer` |
| 345 | [S3S-0425 AI 소유 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0425) | AI 소유 격차 | `GAP_AI_OWNERSHIP` | `ax_inclusive_transition_officer` |
| 346 | [S3S-0426 AI 성과배분 격차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0426) | AI 성과배분 격차 | `GAP_AI_OUTCOME_DISTRIBUTION` | `ax_inclusive_transition_officer` |
| 347 | [S3S-0428 AI 보완형 노동자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0428) | AI 보완형 노동자 | `LABOR_AI_COMPLEMENTED_WORKER` | `ax_inclusive_transition_officer` |
| 348 | [S3S-0429 AI 관리 대상 노동자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0429) | AI 관리 대상 노동자 | `LABOR_AI_MANAGED_WORKER` | `ax_inclusive_transition_officer` |
| 349 | [S3S-0430 AI 대체·축소 위험 노동자](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0430) | AI 대체·축소 위험 노동자 | `LABOR_AI_DISPLACEMENT_RISK_WORKER` | `ax_inclusive_transition_officer` |
| 350 | [S3S-0431 컨텍스트 설계형 AX 인재](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0431) | 컨텍스트 설계형 AX 인재 | `LABOR_CONTEXT_DESIGNER_AX_TALENT` | `ax_inclusive_transition_officer` |
| 351 | [S3S-0432 알고리즘 관리](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0432) | 알고리즘 관리 | `ALGORITHMIC_MANAGEMENT` | `ax_inclusive_transition_officer` |
| 352 | [S3S-0433 포용전환 AX](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0433) | 포용전환 AX | `INCLUSIVE_TRANSFORMATION_AX` | `ax_inclusive_transition_officer` |
| 353 | [S3S-0434 효율성 중심 AX](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0434) | 효율성 중심 AX | `EFFICIENCY_CENTERED_AX` | `ax_inclusive_transition_officer` |
| 354 | [S3S-0435 맥락자본의 사회화](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0435) | 맥락자본의 사회화 | `CONTEXT_CAPITAL_SOCIALIZATION` | `ax_inclusive_transition_officer` |
| 355 | [S3S-0436 맥락자본 (Context Capital)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0436) | 맥락자본 (Context Capital) | `CONTEXT_CAPITAL` | `ax_inclusive_transition_officer` |
| 356 | [S3S-0437 맥락자본 접근권 (맥락 접근권)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0437) | 맥락자본 접근권 (맥락 접근권) | `CONTEXT_ACCESS_RIGHT` | `ax_inclusive_transition_officer` |
| 357 | [S3S-0438 맥락 정의 (Context Justice)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0438) | 맥락 정의 (Context Justice) | `CONTEXT_JUSTICE` | `ax_inclusive_transition_officer` |
| 358 | [S3S-0439 AI 역량 평등론](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0439) | AI 역량 평등론 | `AI_CAPABILITY_EQUALITY` | `ax_inclusive_transition_officer` |
| 359 | [S3S-0449 E의 확장 (AI 인프라의 지속가능성)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0449) | E의 확장 (AI 인프라의 지속가능성) | `ESG_EXT_E_AXIS` | `ax_inclusive_transition_officer` |
| 360 | [S3S-0450 S의 확장 (AI 역량 평등과 인간 존엄)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0450) | S의 확장 (AI 역량 평등과 인간 존엄) | `ESG_EXT_S_AXIS` | `ax_inclusive_transition_officer` |
| 361 | [S3S-0451 G의 확장 (AI 권력의 책임구조)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0451) | G의 확장 (AI 권력의 책임구조) | `ESG_EXT_G_AXIS` | `ax_inclusive_transition_officer` |
| 362 | [S3S-0453 이해관계자 확대론](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0453) | 이해관계자 확대론 | `ESGX_STAKEHOLDER_EXPANSION_CRITIQUE` | `ax_inclusive_transition_officer` |
| 363 | [S3S-0454 측정·검증 강화론](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0454) | 측정·검증 강화론 | `ESGX_MEASUREMENT_VERIFICATION_CRITIQUE` | `ax_inclusive_transition_officer` |
| 364 | [S3S-0455 ESG의 AI 시대 확장론](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0455) | ESG의 AI 시대 확장론 | `ESGX_AI_ERA_EXTENSION_CRITIQUE` | `ax_inclusive_transition_officer` |
| 365 | [S3S-0457 AI for ESG](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0457) | AI for ESG | `AI_FOR_ESG` | `ax_inclusive_transition_officer` |
| 366 | [S3S-0458 ESG for AI](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0458) | ESG for AI | `ESG_FOR_AI` | `ax_inclusive_transition_officer` |
| 367 | [S3S-0459 AI 포용전환 ESG (Inclusive / Just AI Transition ESG)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0459) | AI 포용전환 ESG (Inclusive / Just AI Transition ESG) | `INCLUSIVE_AI_TRANSITION_ESG` | `ax_inclusive_transition_officer` |
| 368 | [S3S-0461 확인 가능한 사실](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0461) | 확인 가능한 사실 | `LAYER_VERIFIABLE_FACT` | `ax_inclusive_transition_officer` |
| 369 | [S3S-0462 합리적 해석](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0462) | 합리적 해석 | `LAYER_REASONABLE_INTERPRETATION` | `ax_inclusive_transition_officer` |
| 370 | [S3S-0463 제안 개념](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0463) | 제안 개념 | `LAYER_PROPOSED_CONCEPT` | `ax_inclusive_transition_officer` |
| 371 | [S3S-0464 실행 모델](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0464) | 실행 모델 | `LAYER_EXECUTION_MODEL` | `ax_inclusive_transition_officer` |
| 372 | [S3S-0465 공정전환 (Just Transition)](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0465) | 공정전환 (Just Transition) | `JUST_TRANSITION` | `ax_inclusive_transition_officer` |
| 373 | [S3S-0467 AI 접근권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0467) | AI 접근권 | `RIGHT_AI_ACCESS` | `ax_inclusive_transition_officer` |
| 374 | [S3S-0468 AI 학습권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0468) | AI 학습권 | `RIGHT_AI_LEARNING` | `ax_inclusive_transition_officer` |
| 375 | [S3S-0469 AI 활용권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0469) | AI 활용권 | `RIGHT_AI_UTILIZATION` | `ax_inclusive_transition_officer` |
| 376 | [S3S-0470 AI 판단권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0470) | AI 판단권 | `RIGHT_AI_JUDGMENT` | `ax_inclusive_transition_officer` |
| 377 | [S3S-0471 AI 설명권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0471) | AI 설명권 | `RIGHT_AI_EXPLANATION` | `ax_inclusive_transition_officer` |
| 378 | [S3S-0472 AI 이의제기권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0472) | AI 이의제기권 | `RIGHT_AI_APPEAL` | `ax_inclusive_transition_officer` |
| 379 | [S3S-0473 AI 전환권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0473) | AI 전환권 | `RIGHT_AI_TRANSITION` | `ax_inclusive_transition_officer` |
| 380 | [S3S-0474 AI 성과공유권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0474) | AI 성과공유권 | `RIGHT_AI_BENEFIT_SHARING` | `ax_inclusive_transition_officer` |
| 381 | [S3S-0476 1. AI 영향평가](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0476) | 1. AI 영향평가 | `STEP_AI_IMPACT_ASSESSMENT` | `ax_inclusive_transition_officer` |
| 382 | [S3S-0477 2. AI 맥락자본 구축](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0477) | 2. AI 맥락자본 구축 | `STEP_AI_CONTEXT_CAPITAL_BUILD` | `ax_inclusive_transition_officer` |
| 383 | [S3S-0478 3. 권한 설계](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0478) | 3. 권한 설계 | `STEP_AUTHORITY_DESIGN` | `ax_inclusive_transition_officer` |
| 384 | [S3S-0479 4. 노동 전환](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0479) | 4. 노동 전환 | `STEP_LABOR_TRANSITION` | `ax_inclusive_transition_officer` |
| 385 | [S3S-0480 5. 인간 승인 기준](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0480) | 5. 인간 승인 기준 | `STEP_HUMAN_APPROVAL_CRITERIA` | `ax_inclusive_transition_officer` |
| 386 | [S3S-0481 6. 이의제기 절차](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0481) | 6. 이의제기 절차 | `STEP_APPEAL_PROCEDURE` | `ax_inclusive_transition_officer` |
| 387 | [S3S-0482 7. 감사 기록](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0482) | 7. 감사 기록 | `STEP_AUDIT_RECORD` | `ax_inclusive_transition_officer` |
| 388 | [S3S-0483 8. 성과배분](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0483) | 8. 성과배분 | `STEP_BENEFIT_DISTRIBUTION` | `ax_inclusive_transition_officer` |
| 389 | [S3S-0484 9. 개선 루프](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0484) | 9. 개선 루프 | `STEP_IMPROVEMENT_LOOP` | `ax_inclusive_transition_officer` |
| 390 | [S3S-0486 AI 접근성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0486) | AI 접근성 | `IND_AI_ACCESSIBILITY` | `ax_inclusive_transition_officer` |
| 391 | [S3S-0487 AI 교육](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0487) | AI 교육 | `IND_AI_EDUCATION` | `ax_inclusive_transition_officer` |
| 392 | [S3S-0488 AI 활용 역량](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0488) | AI 활용 역량 | `IND_AI_UTILIZATION_CAPABILITY` | `ax_inclusive_transition_officer` |
| 393 | [S3S-0489 노동 전환](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0489) | 노동 전환 | `IND_LABOR_TRANSITION` | `ax_inclusive_transition_officer` |
| 394 | [S3S-0490 인간 판단권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0490) | 인간 판단권 | `IND_HUMAN_JUDGMENT_RIGHT` | `ax_inclusive_transition_officer` |
| 395 | [S3S-0491 설명 가능성](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0491) | 설명 가능성 | `IND_EXPLAINABILITY` | `ax_inclusive_transition_officer` |
| 396 | [S3S-0492 이의제기권](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0492) | 이의제기권 | `IND_APPEAL_RIGHT` | `ax_inclusive_transition_officer` |
| 397 | [S3S-0493 감사 기록](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0493) | 감사 기록 | `IND_AUDIT_RECORD` | `ax_inclusive_transition_officer` |
| 398 | [S3S-0494 책임구조](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0494) | 책임구조 | `IND_ACCOUNTABILITY_STRUCTURE` | `ax_inclusive_transition_officer` |
| 399 | [S3S-0495 성과 공유](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0495) | 성과 공유 | `IND_BENEFIT_SHARING` | `ax_inclusive_transition_officer` |
| 400 | [S3S-0498 환경 책임](./20260719_154811_stage3_knowledge_chain_ordering_artifact.md#s3s-0498) | 환경 책임 | `IND_ENVIRONMENTAL_RESPONSIBILITY` | `ax_inclusive_transition_officer` |

## ExpectedClosureManifest

A **LIST ONLY** of the closure files that WOULD be produced, per admitted candidate:
`_identity` -> `_goal` -> `_task` -> `_knowledge` -> `_method` -> `_skill`.
**NEVER created** — 400 x 6 = **2400 files listed, 0 files written.**

| InvocationOrder | NormalizedKey | would-be closure files |
|---|---|---|
| 1 | `AI_TRANSFORMATION` | `_identity/ai_transformation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 2 | `DIGITAL_TRANSFORMATION` | `_identity/digital_transformation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 3 | `ORGANIZATIONAL_AX` | `_identity/organizational_ax/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 4 | `AX_ORGANIZATION` | `_identity/ax_organization/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 5 | `PERSONAL_AX` | `_identity/personal_ax/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 6 | `AI_GEN_1_PERCEPTIONAL` | `_identity/ai_gen_1_perceptional/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 7 | `AI_GEN_2_GENERATIVE` | `_identity/ai_gen_2_generative/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 8 | `AI_GEN_3_AGENTIC` | `_identity/ai_gen_3_agentic/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 9 | `AI_GEN_4_ORGANIZATIONAL` | `_identity/ai_gen_4_organizational/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 10 | `LLM_LAYER_1_2_DX_DOMAIN` | `_identity/llm_layer_1_2_dx_domain/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 11 | `LLM_LAYER_3_KNOWLEDGE_CHAIN` | `_identity/llm_layer_3_knowledge_chain/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 12 | `LLM_LAYER_4_FIRST_LLM_SUPPLY` | `_identity/llm_layer_4_first_llm_supply/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 13 | `LLM_LAYER_5_EXTENSION` | `_identity/llm_layer_5_extension/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 14 | `LLM_GEN_FIRST_UNIVERSAL` | `_identity/llm_gen_first_universal/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 15 | `LLM_GEN_SECOND_ENTERPRISE` | `_identity/llm_gen_second_enterprise/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 16 | `LLM_GEN_THIRD_FULL_STACK` | `_identity/llm_gen_third_full_stack/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 17 | `DOMAIN_CONTEXT` | `_identity/domain_context/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 18 | `ORG_AX_OS` | `_identity/org_ax_os/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 19 | `OS_NECESSARY_CONDITION_CLASS` | `_identity/os_necessary_condition_class/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 20 | `OS_ADDITIONAL_CONDITION_CLASS` | `_identity/os_additional_condition_class/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 21 | `OS_OPERATING_PROTOCOLS` | `_identity/os_operating_protocols/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 22 | `OS_PRIVACY_SOVEREIGNTY` | `_identity/os_privacy_sovereignty/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 23 | `OS_COMMON_GOVERNANCE_CONTEXT` | `_identity/os_common_governance_context/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 24 | `OS_ORGANIZATIONAL_DIGITAL_TWIN` | `_identity/os_organizational_digital_twin/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 25 | `AI_SOVEREIGNTY` | `_identity/ai_sovereignty/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 26 | `HUMAN_MEMBER` | `_identity/human_member/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 27 | `BOT_MEMBER` | `_identity/bot_member/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 28 | `DIGITAL_WORKER_AI_AGENT` | `_identity/digital_worker_ai_agent/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 29 | `DIGITAL_WORKER_SUBAGENT` | `_identity/digital_worker_subagent/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 30 | `DIGITAL_WORKER_BOT` | `_identity/digital_worker_bot/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 31 | `COOP_TYPE_H_PLUS_B` | `_identity/coop_type_h_plus_b/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 32 | `COOP_TYPE_H_PLUS_AH` | `_identity/coop_type_h_plus_ah/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 33 | `COOP_TYPE_AH_PLUS_B` | `_identity/coop_type_ah_plus_b/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 34 | `COOP_TYPE_AH_PLUS_AB` | `_identity/coop_type_ah_plus_ab/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 35 | `HYBRID_ORGANIZATION` | `_identity/hybrid_organization/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 36 | `COLLAB_MODE_HUMAN_IN_THE_LOOP` | `_identity/collab_mode_human_in_the_loop/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 37 | `COLLAB_MODE_AI_IN_THE_LOOP` | `_identity/collab_mode_ai_in_the_loop/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 38 | `COLLAB_MODE_HUMAN_ON_THE_LOOP` | `_identity/collab_mode_human_on_the_loop/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 39 | `COLLAB_MODE_AUTONOMOUS_AI` | `_identity/collab_mode_autonomous_ai/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 40 | `AUGMENTATION` | `_identity/augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 41 | `PREMISE_HUMAN_CENTRALITY` | `_identity/premise_human_centrality/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 42 | `SPIRIT_AUGMENTATION` | `_identity/spirit_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 43 | `SPIRIT_DIVERSITY_RESPECT` | `_identity/spirit_diversity_respect/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 44 | `SPIRIT_COMPLEMENTARY_FIT` | `_identity/spirit_complementary_fit/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 45 | `HUMAN_CENTRALITY` | `_identity/human_centrality/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 46 | `SUPPLEMENTARY_FIT` | `_identity/supplementary_fit/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 47 | `COMPFIT_COGNITIVE` | `_identity/compfit_cognitive/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 48 | `COMPFIT_EMOTIONAL` | `_identity/compfit_emotional/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 49 | `COMPFIT_BEHAVIORAL` | `_identity/compfit_behavioral/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 50 | `COMPFIT_ETHICAL` | `_identity/compfit_ethical/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 51 | `HBS_DIM_HON` | `_identity/hbs_dim_hon/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 52 | `HBS_DIM_BAEK` | `_identity/hbs_dim_baek/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 53 | `HBS_DIM_YEONG` | `_identity/hbs_dim_yeong/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 54 | `HBS_STATE_HONBI` | `_identity/hbs_state_honbi/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 55 | `HBS_STATE_BAEKSAN` | `_identity/hbs_state_baeksan/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 56 | `HBS_OUTSOURCE_HON` | `_identity/hbs_outsource_hon/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 57 | `HBS_OUTSOURCE_BAEK` | `_identity/hbs_outsource_baek/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 58 | `HBS_COMBINE_HUMANBODY_AIMIND` | `_identity/hbs_combine_humanbody_aimind/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 59 | `HBS_COMBINE_MACHINEBODY_HUMANMIND` | `_identity/hbs_combine_machinebody_humanmind/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 60 | `HBS_PREV_FINAL_RESPONSIBILITY` | `_identity/hbs_prev_final_responsibility/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 61 | `HBS_PREV_DECISION_LOGGING` | `_identity/hbs_prev_decision_logging/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 62 | `HBS_PREV_HUMAN_AS_REVIEWER` | `_identity/hbs_prev_human_as_reviewer/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 63 | `HBS_PREV_NO_HUMAN_COMPONENTIZATION` | `_identity/hbs_prev_no_human_componentization/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 64 | `HBS_PREV_GOVERNANCE_BY_DESIGN` | `_identity/hbs_prev_governance_by_design/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 65 | `LAYER_SURVIVAL` | `_identity/layer_survival/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 66 | `LAYER_CAPABILITY` | `_identity/layer_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 67 | `LAYER_RELATIONSHIP` | `_identity/layer_relationship/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 68 | `LAYER_EXISTENCE` | `_identity/layer_existence/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 69 | `IND_SURVIVAL_ANXIETY` | `_identity/ind_survival_anxiety/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 70 | `IND_COMPETENCE_INFERIORITY` | `_identity/ind_competence_inferiority/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 71 | `IND_CONTROL_LOSS` | `_identity/ind_control_loss/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 72 | `IND_SURVEILLANCE_FEAR` | `_identity/ind_surveillance_fear/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 73 | `IND_HUMANITY_DEFENSE` | `_identity/ind_humanity_defense/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 74 | `COL_LABOR_UNION` | `_identity/col_labor_union/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 75 | `COL_PROFESSIONAL_GROUP` | `_identity/col_professional_group/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 76 | `COL_SOCIOCULTURAL` | `_identity/col_sociocultural/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 77 | `COL_POLITICAL_POLICY` | `_identity/col_political_policy/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 78 | `COL_ONTOLOGICAL` | `_identity/col_ontological/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 79 | `AXSTRESS_IDENTITY` | `_identity/axstress_identity/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 80 | `AXSTRESS_TRUST` | `_identity/axstress_trust/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 81 | `AXSTRESS_CONTROL` | `_identity/axstress_control/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 82 | `AXSTRESS_RESPONSIBILITY` | `_identity/axstress_responsibility/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 83 | `HSTRESS_ROLE_AMBIGUITY` | `_identity/hstress_role_ambiguity/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 84 | `HSTRESS_REPLACEMENT_ANXIETY` | `_identity/hstress_replacement_anxiety/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 85 | `HSTRESS_COGNITIVE_OVERLOAD` | `_identity/hstress_cognitive_overload/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 86 | `HSTRESS_AI_DISTRUST_OVERTRUST` | `_identity/hstress_ai_distrust_overtrust/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 87 | `HSTRESS_SOCIAL_RELATIONAL` | `_identity/hstress_social_relational/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 88 | `BSTRESS_COMPUTATIONAL_OVERLOAD` | `_identity/bstress_computational_overload/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 89 | `BSTRESS_GOAL_CONFLICT` | `_identity/bstress_goal_conflict/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 90 | `BSTRESS_MISALIGNMENT` | `_identity/bstress_misalignment/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 91 | `BSTRESS_CONTINUOUS_UPDATE` | `_identity/bstress_continuous_update/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 92 | `BSTRESS_MULTI_AGENT_COOP` | `_identity/bstress_multi_agent_coop/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 93 | `HBCMP_ESSENCE` | `_identity/hbcmp_essence/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 94 | `HBCMP_ROOT_CAUSE` | `_identity/hbcmp_root_cause/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 95 | `HBCMP_RESULT` | `_identity/hbcmp_result/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 96 | `HBCMP_RECOVERY` | `_identity/hbcmp_recovery/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 97 | `HBCMP_RISK` | `_identity/hbcmp_risk/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 98 | `HBCMP_MEASUREMENT` | `_identity/hbcmp_measurement/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 99 | `INTERACTION_STRESS` | `_identity/interaction_stress/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 100 | `COOP_H_B` | `_identity/coop_h_b/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 101 | `COOP_H_AH` | `_identity/coop_h_ah/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 102 | `COOP_AH_B` | `_identity/coop_ah_b/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 103 | `COOP_AH_AB` | `_identity/coop_ah_ab/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 104 | `AI_LITERACY_AND_AFFINITY` | `_identity/ai_literacy_and_affinity/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 105 | `HUMAN_AI_COLLABORATION_ABILITY` | `_identity/human_ai_collaboration_ability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 106 | `CONTINUOUS_LEARNING_ABILITY` | `_identity/continuous_learning_ability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 107 | `DATA_DIGITAL_LITERACY` | `_identity/data_digital_literacy/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 108 | `CRITICAL_THINKING_COMPETENCY` | `_identity/critical_thinking_competency/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 109 | `ORG_CHANGE_ADAPTABILITY` | `_identity/org_change_adaptability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 110 | `PROBLEM_FRAMING_CAPABILITY` | `_identity/problem_framing_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 111 | `MEANING_DESIGN_CAPABILITY` | `_identity/meaning_design_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 112 | `SYSTEMS_THINKING_CAPABILITY` | `_identity/systems_thinking_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 113 | `HUMAN_AI_ORCHESTRATION_CAPABILITY` | `_identity/human_ai_orchestration_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 114 | `GOVERNANCE_AND_ETHICAL_JUDGMENT` | `_identity/governance_and_ethical_judgment/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 115 | `CONTEXT_RESPONSIBILITY` | `_identity/context_responsibility/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 116 | `JUDGMENT_RESPONSIBILITY` | `_identity/judgment_responsibility/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 117 | `EVIDENCE_RESPONSIBILITY` | `_identity/evidence_responsibility/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 118 | `ROLE_PROBLEM_DEFINER` | `_identity/role_problem_definer/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 119 | `ROLE_CONTEXT_BUILDER` | `_identity/role_context_builder/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 120 | `ROLE_AI_EXECUTION_DIRECTOR` | `_identity/role_ai_execution_director/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 121 | `ROLE_RESULT_INTERPRETER` | `_identity/role_result_interpreter/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 122 | `ROLE_VALIDATOR_OF_EIGHT` | `_identity/role_validator_of_eight/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 123 | `ROLE_ACCOUNTABILITY_JUDGE` | `_identity/role_accountability_judge/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 124 | `ROLE_EVIDENCE_KEEPER` | `_identity/role_evidence_keeper/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 125 | `ROLE_IMPROVEMENT_REFLECTOR` | `_identity/role_improvement_reflector/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 126 | `CORE_ROLE_SHAPER` | `_identity/core_role_shaper/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 127 | `CORE_ROLE_IMPLEMENTER` | `_identity/core_role_implementer/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 128 | `CORE_ROLE_VALIDATOR` | `_identity/core_role_validator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 129 | `CORE_ROLE_OPERATOR` | `_identity/core_role_operator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 130 | `CORE_ROLE_COORDINATOR` | `_identity/core_role_coordinator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 131 | `WORK_AS_PERFORMED_ACT` | `_identity/work_as_performed_act/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 132 | `CONTRIBUTION_AS_VALID_CHANGE` | `_identity/contribution_as_valid_change/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 133 | `ROLE_AS_CONTRIBUTION_POSITION` | `_identity/role_as_contribution_position/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 134 | `HUMAN_AI_ORCHESTRATION` | `_identity/human_ai_orchestration/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 135 | `HUMANITY_PROTECTION` | `_identity/humanity_protection/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 136 | `AH_PHYSICAL_AUGMENTATION` | `_identity/ah_physical_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 137 | `AH_MENTAL_AUGMENTATION` | `_identity/ah_mental_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 138 | `AH_ROLE_CONTEXT_AUGMENTATION` | `_identity/ah_role_context_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 139 | `AH_POWER_SET_PURPOSE` | `_identity/ah_power_set_purpose/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 140 | `AH_POWER_SET_CRITERIA` | `_identity/ah_power_set_criteria/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 141 | `AH_POWER_FINAL_JUDGMENT` | `_identity/ah_power_final_judgment/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 142 | `AB_VERIFIABILITY` | `_identity/ab_verifiability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 143 | `AB_BOUNDARY_COMPLIANCE` | `_identity/ab_boundary_compliance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 144 | `AB_CRITERIA_INTERNALIZATION` | `_identity/ab_criteria_internalization/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 145 | `AB_IMPROVEMENT_LOOP` | `_identity/ab_improvement_loop/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 146 | `AB_CONTEXT_AUGMENTATION` | `_identity/ab_context_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 147 | `AB_GOVERNANCE_AUGMENTATION` | `_identity/ab_governance_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 148 | `AB_LEARNING_AUGMENTATION` | `_identity/ab_learning_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 149 | `HUMAN_BOT_SOCIALITY` | `_identity/human_bot_sociality/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 150 | `BOT_BOT_SOCIALITY` | `_identity/bot_bot_sociality/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 151 | `BOT_ETHICS` | `_identity/bot_ethics/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 152 | `UNESCO_AI_ETHICS_RECOMMENDATION` | `_identity/unesco_ai_ethics_recommendation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 153 | `KOREA_HUMAN_CENTERED_AI_ETHICS` | `_identity/korea_human_centered_ai_ethics/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 154 | `CC_BROADLY_SAFE` | `_identity/cc_broadly_safe/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 155 | `CC_BROADLY_ETHICAL` | `_identity/cc_broadly_ethical/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 156 | `CC_HELPFULNESS` | `_identity/cc_helpfulness/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 157 | `CC_GUIDELINE_COMPLIANCE` | `_identity/cc_guideline_compliance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 158 | `AX_ETHICS_NECESSARY_CONDITION` | `_identity/ax_ethics_necessary_condition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 159 | `AX_ETHICS_ADDITIONAL_CONDITION` | `_identity/ax_ethics_additional_condition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 160 | `ROBOT_LAW_HUMAN_SAFETY` | `_identity/robot_law_human_safety/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 161 | `ROBOT_LAW_OBEDIENCE` | `_identity/robot_law_obedience/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 162 | `ROBOT_LAW_SELF_PRESERVATION` | `_identity/robot_law_self_preservation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 163 | `HUMAN_RESPECT_INTERNALIZATION` | `_identity/human_respect_internalization/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 164 | `HR_NON_HARM` | `_identity/hr_non_harm/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 165 | `HR_AUTONOMY` | `_identity/hr_autonomy/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 166 | `HR_FAIRNESS` | `_identity/hr_fairness/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 167 | `HR_ACCOUNTABILITY` | `_identity/hr_accountability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 168 | `HR_STAGE1_REWARD_DESIGN` | `_identity/hr_stage1_reward_design/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 169 | `HR_STAGE2_HARD_RULES` | `_identity/hr_stage2_hard_rules/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 170 | `HR_STAGE3_HUMAN_FEEDBACK_LEARNING` | `_identity/hr_stage3_human_feedback_learning/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 171 | `HR_STAGE4_VERIFICATION_LAYER` | `_identity/hr_stage4_verification_layer/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 172 | `HR_STAGE5_MULTIAGENT_HUMAN_RESPECT` | `_identity/hr_stage5_multiagent_human_respect/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 173 | `HUMAN_ILLOGICALITY` | `_identity/human_illogicality/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 174 | `HUMAN_AI_RELATED_STRESS` | `_identity/human_ai_related_stress/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 175 | `SOCIAL_COOPERATION_NORM_LEARNING` | `_identity/social_cooperation_norm_learning/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 176 | `BOT_AS_PATTERN_DETECTOR` | `_identity/bot_as_pattern_detector/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 177 | `BOT_FUNCTIONAL_SATISFACTION` | `_identity/bot_functional_satisfaction/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 178 | `BOT_DESIRE_HIERARCHY` | `_identity/bot_desire_hierarchy/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 179 | `BOT_DRIVER_GOAL` | `_identity/bot_driver_goal/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 180 | `BOT_DRIVER_REWARD_FUNCTION` | `_identity/bot_driver_reward_function/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 181 | `BOT_DRIVER_OPTIMIZATION_ALGORITHM` | `_identity/bot_driver_optimization_algorithm/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 182 | `BOT_HAPPINESS` | `_identity/bot_happiness/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 183 | `BOT_LEVEL4_VERIFIER_GOVERNOR` | `_identity/bot_level4_verifier_governor/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 184 | `BOT_LEVEL3_PLANNER_STRATEGIST` | `_identity/bot_level3_planner_strategist/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 185 | `BOT_LEVEL2_SPECIALIST_EXECUTOR` | `_identity/bot_level2_specialist_executor/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 186 | `BOT_LEVEL1_TOOL_REACTIVE_AGENT` | `_identity/bot_level1_tool_reactive_agent/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 187 | `HIER_CRITERION_DECISION_AUTHORITY` | `_identity/hier_criterion_decision_authority/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 188 | `HIER_CRITERION_INFORMATION_ASYMMETRY` | `_identity/hier_criterion_information_asymmetry/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 189 | `HIER_CRITERION_PERFORMANCE_RELIABILITY` | `_identity/hier_criterion_performance_reliability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 190 | `HIER_CRITERION_NETWORK_CENTRALITY` | `_identity/hier_criterion_network_centrality/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 191 | `HIER_CRITERION_VERIFICATION_POWER` | `_identity/hier_criterion_verification_power/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 192 | `HBRM_MEMBER_EXPANSION` | `_identity/hbrm_member_expansion/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 193 | `HBRM_ROLE_EXPANSION` | `_identity/hbrm_role_expansion/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 194 | `HBRM_EVOLUTION_EXPANSION` | `_identity/hbrm_evolution_expansion/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 195 | `HBRM_ROLE_MEMBER_DEFINITION` | `_identity/hbrm_role_member_definition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 196 | `HBRM_ROLE_ROLE_DESIGN` | `_identity/hbrm_role_role_design/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 197 | `HBRM_ROLE_COLLABORATION_DESIGN` | `_identity/hbrm_role_collaboration_design/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 198 | `HBRM_ROLE_AUGMENTATION_MANAGEMENT` | `_identity/hbrm_role_augmentation_management/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 199 | `HBRM_ROLE_ROLE_BALANCE_MANAGEMENT` | `_identity/hbrm_role_role_balance_management/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 200 | `HBRM_ROLE_TRUST_MANAGEMENT` | `_identity/hbrm_role_trust_management/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 201 | `HBRM_ROLE_GOVERNANCE_LINKAGE` | `_identity/hbrm_role_governance_linkage/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 202 | `HBRM_ROLE_LEARNING_IMPROVEMENT` | `_identity/hbrm_role_learning_improvement/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 203 | `HBRM_3M_METHOD` | `_identity/hbrm_3m_method/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 204 | `HBRM_3M_MEANING` | `_identity/hbrm_3m_meaning/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 205 | `AH_INDICATOR_COGNITIVE` | `_identity/ah_indicator_cognitive/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 206 | `AH_INDICATOR_DECISION` | `_identity/ah_indicator_decision/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 207 | `AH_INDICATOR_LEARNING` | `_identity/ah_indicator_learning/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 208 | `AH_INDICATOR_COLLABORATION` | `_identity/ah_indicator_collaboration/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 209 | `AH_INDICATOR_ROLE` | `_identity/ah_indicator_role/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 210 | `HA_STAGE_H0_NON_AUGMENTED` | `_identity/ha_stage_h0_non_augmented/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 211 | `HA_STAGE_H1_AI_USER` | `_identity/ha_stage_h1_ai_user/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 212 | `HA_STAGE_H2_AI_COLLABORATOR` | `_identity/ha_stage_h2_ai_collaborator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 213 | `HA_STAGE_AH1_AUGMENTED_HUMAN` | `_identity/ha_stage_ah1_augmented_human/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 214 | `HA_STAGE_AH2_AI_ORCHESTRATOR` | `_identity/ha_stage_ah2_ai_orchestrator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 215 | `HA_STAGE_AH3_SYMBIOTIC_LEADER` | `_identity/ha_stage_ah3_symbiotic_leader/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 216 | `AIU_STAGE_TOOL_USER` | `_identity/aiu_stage_tool_user/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 217 | `AIU_STAGE_COLLABORATIVE_USER` | `_identity/aiu_stage_collaborative_user/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 218 | `AIU_STAGE_ORCHESTRATOR` | `_identity/aiu_stage_orchestrator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 219 | `AIU_STAGE_AUGMENTATION_USER` | `_identity/aiu_stage_augmentation_user/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 220 | `AIU_COMPONENT_FREQUENCY` | `_identity/aiu_component_frequency/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 221 | `AIU_COMPONENT_DEPTH` | `_identity/aiu_component_depth/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 222 | `AIU_COMPONENT_AUTOMATION` | `_identity/aiu_component_automation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 223 | `AIU_COMPONENT_OUTCOME` | `_identity/aiu_component_outcome/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 224 | `AUGMENTATION_QUOTIENT` | `_identity/augmentation_quotient/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 225 | `AUGMENTED_HUMAN_INDEX` | `_identity/augmented_human_index/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 226 | `AUGMENTED_HUMAN_CAPABILITY_INDEX` | `_identity/augmented_human_capability_index/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 227 | `AH_AB_COLLABORATION` | `_identity/ah_ab_collaboration/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 228 | `TEAM_ROLE_BALANCE` | `_identity/team_role_balance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 229 | `TEAM_ROLE` | `_identity/team_role/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 230 | `FUNCTIONAL_ROLE` | `_identity/functional_role/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 231 | `NATURAL_TEAM_ROLE_LEVEL` | `_identity/natural_team_role_level/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 232 | `POTENTIAL_MANAGEABLE_ROLE_LEVEL` | `_identity/potential_manageable_role_level/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 233 | `LEAST_PREFERRED_ROLE_LEVEL` | `_identity/least_preferred_role_level/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 234 | `INTERPLACE` | `_identity/interplace/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 235 | `SELF_PERCEPTION_INVENTORY_SPI` | `_identity/self_perception_inventory_spi/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 236 | `OBSERVER_ASSESSMENT_OA` | `_identity/observer_assessment_oa/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 237 | `JOB_REQUIREMENT_EXERCISE_JRE` | `_identity/job_requirement_exercise_jre/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 238 | `JOB_OBSERVER_ASSESSMENT_JOA` | `_identity/job_observer_assessment_joa/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 239 | `GROUP_COHESIVENESS` | `_identity/group_cohesiveness/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 240 | `HUMAN_BOND_TEAMWORK` | `_identity/human_bond_teamwork/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 241 | `TASK_ACTIVATION_TEAMWORK` | `_identity/task_activation_teamwork/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 242 | `BEHAVIOR_TYPE` | `_identity/behavior_type/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 243 | `ROLE_BASED_HRM` | `_identity/role_based_hrm/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 244 | `BELBIN_ROLE_PLANT_PL` | `_identity/belbin_role_plant_pl/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 245 | `BELBIN_ROLE_MONITOR_EVALUATOR_ME` | `_identity/belbin_role_monitor_evaluator_me/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 246 | `BELBIN_ROLE_COORDINATOR_CO` | `_identity/belbin_role_coordinator_co/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 247 | `BELBIN_ROLE_IMPLEMENTER_IMP` | `_identity/belbin_role_implementer_imp/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 248 | `BELBIN_ROLE_COMPLETER_FINISHER_CF` | `_identity/belbin_role_completer_finisher_cf/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 249 | `BELBIN_ROLE_RESOURCE_INVESTIGATOR_RI` | `_identity/belbin_role_resource_investigator_ri/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 250 | `BELBIN_ROLE_TEAMWORKER_TW` | `_identity/belbin_role_teamworker_tw/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 251 | `BELBIN_ROLE_SHAPER_SH` | `_identity/belbin_role_shaper_sh/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 252 | `BELBIN_ROLE_SPECIALIST_SP` | `_identity/belbin_role_specialist_sp/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 253 | `BOT_TR_COMPLEMENTATION` | `_identity/bot_tr_complementation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 254 | `BOT_TR_AUGMENTATION` | `_identity/bot_tr_augmentation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 255 | `BOT_TR_ADDITION` | `_identity/bot_tr_addition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 256 | `AX_ROLE_AI_GOVERNOR` | `_identity/ax_role_ai_governor/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 257 | `AX_ROLE_AI_AUDITOR` | `_identity/ax_role_ai_auditor/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 258 | `AX_ROLE_PROMPT_ARCHITECT` | `_identity/ax_role_prompt_architect/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 259 | `AX_ROLE_AI_WORKFLOW_ORCHESTRATOR` | `_identity/ax_role_ai_workflow_orchestrator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 260 | `AX_ROLE_HUMAN_MEANING_INTEGRATOR` | `_identity/ax_role_human_meaning_integrator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 261 | `AX_ROLE_TRUST_MANAGER` | `_identity/ax_role_trust_manager/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 262 | `AX_ROLE_PROVENANCE_CONTROLLER` | `_identity/ax_role_provenance_controller/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 263 | `DYNAMIC_ROLE_BALANCE` | `_identity/dynamic_role_balance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 264 | `BOT_AIDED_ROLE_DIAGNOSTICIAN` | `_identity/bot_aided_role_diagnostician/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 265 | `BOT_AIDED_COLLABORATION_FACILITATOR` | `_identity/bot_aided_collaboration_facilitator/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 266 | `BOT_AIDED_COGNITIVE_AUGMENTER` | `_identity/bot_aided_cognitive_augmenter/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 267 | `COUPLED_CO_CONSTITUTION` | `_identity/coupled_co_constitution/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 268 | `COUPLED_DYNAMIC_ROLE_ALLOCATION` | `_identity/coupled_dynamic_role_allocation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 269 | `COUPLED_MAXIMIZATION_COMPLEMENTARY_FIT` | `_identity/coupled_maximization_complementary_fit/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 270 | `TRB_STAGE_HUMAN_ONLY` | `_identity/trb_stage_human_only/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 271 | `ARBI` | `_identity/arbi/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 272 | `ARBI_AXIS_ROLE_BALANCE` | `_identity/arbi_axis_role_balance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 273 | `ARBI_AXIS_COMPLEMENTARY_FIT` | `_identity/arbi_axis_complementary_fit/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 274 | `ARBI_AXIS_AI_INTERVENTION_TRANSPARENCY` | `_identity/arbi_axis_ai_intervention_transparency/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 275 | `ARBI_AXIS_UTTERANCE_AGENCY` | `_identity/arbi_axis_utterance_agency/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 276 | `ARBI_AXIS_AUTHORITY_CONSENT_BOUNDARY` | `_identity/arbi_axis_authority_consent_boundary/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 277 | `ARBI_AXIS_HUMAN_ACCOUNTABILITY` | `_identity/arbi_axis_human_accountability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 278 | `ARBI_AXIS_COMMUNICATION_FAIRNESS` | `_identity/arbi_axis_communication_fairness/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 279 | `ARBI_AXIS_RECORD_TRACEABILITY` | `_identity/arbi_axis_record_traceability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 280 | `ARBI_AXIS_PSYCHOLOGICAL_TRUST_STABILITY` | `_identity/arbi_axis_psychological_trust_stability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 281 | `ARBI_AXIS_MANIPULATION_RISK` | `_identity/arbi_axis_manipulation_risk/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 282 | `HUMAN_BOT_ROLE_MANAGEMENT` | `_identity/human_bot_role_management/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 283 | `LOCAL_ENVIRONMENT` | `_identity/local_environment/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 284 | `NETWORK_ENVIRONMENT` | `_identity/network_environment/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 285 | `COMMON_CONTEXT_ELEMENT_PURPOSE` | `_identity/common_context_element_purpose/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 286 | `COMMON_CONTEXT_ELEMENT_CRITERION` | `_identity/common_context_element_criterion/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 287 | `COMMON_CONTEXT_ELEMENT_ROLE` | `_identity/common_context_element_role/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 288 | `COMMON_CONTEXT_ELEMENT_SOURCE` | `_identity/common_context_element_source/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 289 | `COMMON_CONTEXT_ELEMENT_FORMAT` | `_identity/common_context_element_format/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 290 | `COMMON_CONTEXT_ELEMENT_FEEDBACK` | `_identity/common_context_element_feedback/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 291 | `GOVERNANCE_CONTEXT_ELEMENT_AUTHORITY` | `_identity/governance_context_element_authority/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 292 | `GOVERNANCE_CONTEXT_ELEMENT_SECURITY` | `_identity/governance_context_element_security/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 293 | `GOVERNANCE_CONTEXT_ELEMENT_VALIDATION` | `_identity/governance_context_element_validation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 294 | `GOVERNANCE_CONTEXT_ELEMENT_APPROVAL` | `_identity/governance_context_element_approval/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 295 | `GOVERNANCE_CONTEXT_ELEMENT_RECORD` | `_identity/governance_context_element_record/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 296 | `GOVERNANCE_CONTEXT_ELEMENT_ACCOUNTABILITY` | `_identity/governance_context_element_accountability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 297 | `GOVERNANCE_CONTEXT_ELEMENT_IMPROVEMENT` | `_identity/governance_context_element_improvement/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 298 | `AI_GOVERNANCE` | `_identity/ai_governance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 299 | `KNOWLEDGE_CHAIN_STAGE_QUESTION` | `_identity/knowledge_chain_stage_question/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 300 | `KNOWLEDGE_CHAIN_STAGE_CONTEXT_REFERENCE` | `_identity/knowledge_chain_stage_context_reference/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 301 | `KNOWLEDGE_CHAIN_STAGE_GOVERNANCE_VALIDATION` | `_identity/knowledge_chain_stage_governance_validation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 302 | `KNOWLEDGE_CHAIN_STAGE_RESULT_RECORD` | `_identity/knowledge_chain_stage_result_record/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 303 | `KNOWLEDGE_CHAIN_STAGE_REINTEGRATION` | `_identity/knowledge_chain_stage_reintegration/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 304 | `KNOWLEDGE_CHAIN_STAGE_REUSE` | `_identity/knowledge_chain_stage_reuse/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 305 | `KNOWLEDGE_CHAIN_FUNCTION_STRUCTURAL_DISTANCE` | `_identity/knowledge_chain_function_structural_distance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 306 | `KNOWLEDGE_CHAIN_FUNCTION_PREMISE_RELATION` | `_identity/knowledge_chain_function_premise_relation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 307 | `KNOWLEDGE_CHAIN_FUNCTION_REASONING_FIDELITY` | `_identity/knowledge_chain_function_reasoning_fidelity/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 308 | `KNOWLEDGE_CHAIN_FUNCTION_TRANSFER_CAPABILITY` | `_identity/knowledge_chain_function_transfer_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 309 | `MEANING_COGNITIVE_DISTANCE` | `_identity/meaning_cognitive_distance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 310 | `AI_CONTRIBUTION` | `_identity/ai_contribution/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 311 | `KNOWLEDGE_ACTION_CHAIN_NODE_KNOWLEDGE` | `_identity/knowledge_action_chain_node_knowledge/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 312 | `KNOWLEDGE_ACTION_CHAIN_NODE_SKILL` | `_identity/knowledge_action_chain_node_skill/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 313 | `KNOWLEDGE_ACTION_CHAIN_NODE_RUNTIME` | `_identity/knowledge_action_chain_node_runtime/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 314 | `KNOWLEDGE_ACTION_CHAIN_NODE_ACTION` | `_identity/knowledge_action_chain_node_action/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 315 | `KNOWLEDGE_ACTION_CHAIN_NODE_OUTCOME` | `_identity/knowledge_action_chain_node_outcome/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 316 | `KNOWLEDGE_ACTION_CHAIN_NODE_REVIEW` | `_identity/knowledge_action_chain_node_review/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 317 | `KNOWLEDGE_ACTION_CHAIN_NODE_FEEDBACK` | `_identity/knowledge_action_chain_node_feedback/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 318 | `KNOWLEDGE_ACTION_CHAIN_NODE_CONTEXT` | `_identity/knowledge_action_chain_node_context/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 319 | `SKILL_RUNTIME_SLOT_INPUT` | `_identity/skill_runtime_slot_input/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 320 | `SKILL_RUNTIME_SLOT_MATERIAL` | `_identity/skill_runtime_slot_material/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 321 | `SKILL_RUNTIME_SLOT_TOOL` | `_identity/skill_runtime_slot_tool/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 322 | `SKILL_RUNTIME_SLOT_PROHIBITION` | `_identity/skill_runtime_slot_prohibition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 323 | `SKILL_RUNTIME_SLOT_RESULT_FORMAT` | `_identity/skill_runtime_slot_result_format/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 324 | `SKILL_RUNTIME_SLOT_REVIEWER_APPROVER` | `_identity/skill_runtime_slot_reviewer_approver/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 325 | `SKILL_RUNTIME_SLOT_RECORD_LOCATION` | `_identity/skill_runtime_slot_record_location/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 326 | `KNOWLEDGE_ACTION_NODE_ONTOLOGY` | `_identity/knowledge_action_node_ontology/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 327 | `THREE_LAYER_CONTEXT_COMMUNICATION_LAYER` | `_identity/three_layer_context_communication_layer/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 328 | `COMMUNICATION_TYPE_AH_TO_H` | `_identity/communication_type_ah_to_h/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 329 | `COMMUNICATION_TYPE_AH_TO_AH` | `_identity/communication_type_ah_to_ah/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 330 | `ROLE_VACANCY` | `_identity/role_vacancy/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 331 | `CONTRIBUTION_CONFLICT` | `_identity/contribution_conflict/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 332 | `AUGMENTED_PATH_HUMAN_CENTERED` | `_identity/augmented_path_human_centered/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 333 | `AUGMENTED_PATH_AI_CENTERED` | `_identity/augmented_path_ai_centered/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 334 | `AUGMENTED_PATH_VIA_GOVERNANCE` | `_identity/augmented_path_via_governance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 335 | `PREDICTIVE_INTELLIGENCE` | `_identity/predictive_intelligence/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 336 | `PIS_WORLD_MODEL` | `_identity/pis_world_model/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 337 | `PIS_CONTEXT_DESIGN` | `_identity/pis_context_design/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 338 | `CONTEXT_DESIGNER` | `_identity/context_designer/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 339 | `AI_BASED_STRATIFICATION` | `_identity/ai_based_stratification/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 340 | `GAP_AI_ACCESS` | `_identity/gap_ai_access/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 341 | `GAP_AI_CAPABILITY` | `_identity/gap_ai_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 342 | `GAP_AI_CONTEXT` | `_identity/gap_ai_context/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 343 | `GAP_AI_JUDGMENT_RIGHT` | `_identity/gap_ai_judgment_right/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 344 | `GAP_AI_SURVEILLANCE` | `_identity/gap_ai_surveillance/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 345 | `GAP_AI_OWNERSHIP` | `_identity/gap_ai_ownership/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 346 | `GAP_AI_OUTCOME_DISTRIBUTION` | `_identity/gap_ai_outcome_distribution/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 347 | `LABOR_AI_COMPLEMENTED_WORKER` | `_identity/labor_ai_complemented_worker/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 348 | `LABOR_AI_MANAGED_WORKER` | `_identity/labor_ai_managed_worker/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 349 | `LABOR_AI_DISPLACEMENT_RISK_WORKER` | `_identity/labor_ai_displacement_risk_worker/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 350 | `LABOR_CONTEXT_DESIGNER_AX_TALENT` | `_identity/labor_context_designer_ax_talent/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 351 | `ALGORITHMIC_MANAGEMENT` | `_identity/algorithmic_management/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 352 | `INCLUSIVE_TRANSFORMATION_AX` | `_identity/inclusive_transformation_ax/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 353 | `EFFICIENCY_CENTERED_AX` | `_identity/efficiency_centered_ax/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 354 | `CONTEXT_CAPITAL_SOCIALIZATION` | `_identity/context_capital_socialization/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 355 | `CONTEXT_CAPITAL` | `_identity/context_capital/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 356 | `CONTEXT_ACCESS_RIGHT` | `_identity/context_access_right/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 357 | `CONTEXT_JUSTICE` | `_identity/context_justice/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 358 | `AI_CAPABILITY_EQUALITY` | `_identity/ai_capability_equality/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 359 | `ESG_EXT_E_AXIS` | `_identity/esg_ext_e_axis/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 360 | `ESG_EXT_S_AXIS` | `_identity/esg_ext_s_axis/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 361 | `ESG_EXT_G_AXIS` | `_identity/esg_ext_g_axis/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 362 | `ESGX_STAKEHOLDER_EXPANSION_CRITIQUE` | `_identity/esgx_stakeholder_expansion_critique/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 363 | `ESGX_MEASUREMENT_VERIFICATION_CRITIQUE` | `_identity/esgx_measurement_verification_critique/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 364 | `ESGX_AI_ERA_EXTENSION_CRITIQUE` | `_identity/esgx_ai_era_extension_critique/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 365 | `AI_FOR_ESG` | `_identity/ai_for_esg/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 366 | `ESG_FOR_AI` | `_identity/esg_for_ai/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 367 | `INCLUSIVE_AI_TRANSITION_ESG` | `_identity/inclusive_ai_transition_esg/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 368 | `LAYER_VERIFIABLE_FACT` | `_identity/layer_verifiable_fact/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 369 | `LAYER_REASONABLE_INTERPRETATION` | `_identity/layer_reasonable_interpretation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 370 | `LAYER_PROPOSED_CONCEPT` | `_identity/layer_proposed_concept/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 371 | `LAYER_EXECUTION_MODEL` | `_identity/layer_execution_model/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 372 | `JUST_TRANSITION` | `_identity/just_transition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 373 | `RIGHT_AI_ACCESS` | `_identity/right_ai_access/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 374 | `RIGHT_AI_LEARNING` | `_identity/right_ai_learning/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 375 | `RIGHT_AI_UTILIZATION` | `_identity/right_ai_utilization/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 376 | `RIGHT_AI_JUDGMENT` | `_identity/right_ai_judgment/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 377 | `RIGHT_AI_EXPLANATION` | `_identity/right_ai_explanation/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 378 | `RIGHT_AI_APPEAL` | `_identity/right_ai_appeal/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 379 | `RIGHT_AI_TRANSITION` | `_identity/right_ai_transition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 380 | `RIGHT_AI_BENEFIT_SHARING` | `_identity/right_ai_benefit_sharing/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 381 | `STEP_AI_IMPACT_ASSESSMENT` | `_identity/step_ai_impact_assessment/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 382 | `STEP_AI_CONTEXT_CAPITAL_BUILD` | `_identity/step_ai_context_capital_build/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 383 | `STEP_AUTHORITY_DESIGN` | `_identity/step_authority_design/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 384 | `STEP_LABOR_TRANSITION` | `_identity/step_labor_transition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 385 | `STEP_HUMAN_APPROVAL_CRITERIA` | `_identity/step_human_approval_criteria/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 386 | `STEP_APPEAL_PROCEDURE` | `_identity/step_appeal_procedure/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 387 | `STEP_AUDIT_RECORD` | `_identity/step_audit_record/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 388 | `STEP_BENEFIT_DISTRIBUTION` | `_identity/step_benefit_distribution/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 389 | `STEP_IMPROVEMENT_LOOP` | `_identity/step_improvement_loop/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 390 | `IND_AI_ACCESSIBILITY` | `_identity/ind_ai_accessibility/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 391 | `IND_AI_EDUCATION` | `_identity/ind_ai_education/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 392 | `IND_AI_UTILIZATION_CAPABILITY` | `_identity/ind_ai_utilization_capability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 393 | `IND_LABOR_TRANSITION` | `_identity/ind_labor_transition/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 394 | `IND_HUMAN_JUDGMENT_RIGHT` | `_identity/ind_human_judgment_right/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 395 | `IND_EXPLAINABILITY` | `_identity/ind_explainability/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 396 | `IND_APPEAL_RIGHT` | `_identity/ind_appeal_right/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 397 | `IND_AUDIT_RECORD` | `_identity/ind_audit_record/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 398 | `IND_ACCOUNTABILITY_STRUCTURE` | `_identity/ind_accountability_structure/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 399 | `IND_BENEFIT_SHARING` | `_identity/ind_benefit_sharing/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |
| 400 | `IND_ENVIRONMENTAL_RESPONSIBILITY` | `_identity/ind_environmental_responsibility/` : `_identity.md` · `_goal.md` · `_task.md` · `_knowledge.md` · `_method.md` · `_skill/SKILL.md` |

## InvocationOrder

The Stage-3 TopologicalOrder restricted to `AdmittedAtomicSkillSet`, renumbered 1..400 without
gaps (column 1 of the table above). Order is preserved from Stage 3; no re-ordering was performed here.

## Packet contents check

| field | present | note |
|---|---|---|
| AdmittedAtomicSkillSet | YES | 400 members |
| ExpectedClosureManifest | YES | 2400 would-be files, listed only |
| InvocationOrder | YES | 1..400 |
| Stage5HandoffPacketArtifact (itself) | YES | this file |
| anything else | **NO** | nothing else is passed to Stage 5 |

## ConformanceCheck (E11) — the diagnostic PASS contract

| # | PASS criterion | result |
|---|---|---|
| 1 | `U4 = C1 union ProvisionalNodeSet` admitted; ExistingIdentityReferenceSet / RegistryCollapse compare-only | PASS (|U4| = 498; 24 references compare-only) |
| 2 | All 6 process artifacts produced under runRoot, in strict sequence | PASS (6/6) |
| 3 | **NO closure file created for any candidate** | PASS (**0** created; 2400 listed) |
| 4 | All-pairs DuplicateAndContainment diagnosis is SET-LEVEL over all pairs of U4 | PASS (123,753 pairs swept) |
| 5 | AdmittedAtomicSkillSet computed via AdmitAtomicSkill with every exclusion applied | PASS (400) |
| 6 | Stage5HandoffPacket carries ONLY the three fields + itself | PASS |
| 7 | link_closure / interlock / conformance | PASS — 0 dangling; every row resolves into `./20260719_154811_stage3_knowledge_chain_ordering_artifact.md` |
| 8 | verified_record runs ONLY on conformance PASS | PASS (gate open) |

## VerifiedRunRecord

- **result**: PASS
- **runID**: `20260719_154811` · **stage**: 4-DIAG — skill surface diagnosis (SIMULATION)
- **the 6 sealed process artifacts** (all under `/Users/gesia/wwp_book_v0.2/_artifact/`):
  1. `20260719_154811_stage4diag_skill_surface_draft_artifact.md`
  2. `20260719_154811_stage4diag_agent_assignment_draft_artifact.md`
  3. `20260719_154811_stage4diag_artifact_file_manifest_artifact.md`
  4. `20260719_154811_stage4diag_duplicate_and_containment_diagnosis_artifact.md`
  5. `20260719_154811_stage4diag_concept_thinning_risk_artifact.md`
  6. `20260719_154811_stage4diag_stage5_handoff_packet_artifact.md` (this file)
- **funnel**: 185 harvested -> C0 159 -> C1 498 -> CandidateSetForStage4 498 -> **AdmittedAtomicSkillSet 400**
- **concept_to_skill**: NEVER run · **closure files created: 0**
- **HEAD segment terminal sink reached.** The Stage-5 C1/barrier/C2 tail and the 4-EXEC per-candidate loop are
  EXTERNAL WORKFLOW territory downstream of this sink — NOT invoked, NOT waited on, NOT owned.

SEALED.
