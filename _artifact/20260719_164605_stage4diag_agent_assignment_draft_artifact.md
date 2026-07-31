# Stage-4 DIAG · AgentAssignmentDraftArtifact

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

Per candidate: does an executing `agent_role` exist that can perform `skill_action`, holds authority over
`artifact_file`, and can read `skill_reads` / write `skill_writes`? Candidates with none go to
**UnassignedAgentSet -> DeferredManualReviewSet**.

## Agent roster (simulated)

| agent_role | responsibility | candidates held |
|---|---|---|
| `ax_bot_governance_steward` | 봇 사회화·윤리 내재화와 HBRM 측정 지표를 소유한다 | 110 |
| `ax_context_chain_architect` | 공통·거버넌스 컨텍스트와 지식(행동)사슬 실행 구조를 소유한다 | 66 |
| `ax_inclusive_transition_officer` | 예측지능·포용전환 AX와 확장 ESG 실행·지표를 소유한다 | 89 |
| `ax_management_philosopher` | 경영 기본철학·핵심정신과 인간/봇 반응·스트레스 판정을 소유한다 | 76 |
| `ax_paradigm_architect` | AX 패러다임·조직 OS 정의를 소유하고 층위 구조를 판정한다 | 48 |
| `ax_talent_role_designer` | AX조직 인재의 역량·역할·기여 위치 설계를 소유한다 | 42 |
| `ax_team_role_analyst` | 팀역할(TR)·팀역할균형(TRB) 진단과 측정 도구를 소유한다 | 67 |

## Per-candidate assignment

> **축 순수성 (upstream, non-gating)**: Stage 2 re-partitioned 9 containers under its declared 축 순수성 rule,
> so U4 arrives at 468, not the superseded run's 498. 31 elements that sat on a 부차 축 were returned to their
> parent as 판정기준/속성 and therefore never reach Stage 4 as skill candidates; 5 were re-parented onto the new
> axis-separation parent `HONBIBAEKSAN_PREVENTION_MEASURES` (S3S-0064). 4-DIAG does not re-open that
> decision — it diagnoses the SET it is handed.


| Stage3SequenceID | candidate | agent_role | can perform skill_action | authority over artifact_file | can read reads | can write writes | assigned |
|---|---|---|---|---|---|---|---|
| [S3S-0001 AX (AI Transformation)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0001) | AX (AI Transformation) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0002 DX (Digital Transformation)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0002) | DX (Digital Transformation) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0003 조직AX](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0003) | 조직AX | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0004 AX조직](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0004) | AX조직 | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0005 개인AX](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0005) | 개인AX | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0006 AI 4.0 (Organizational AI) / AI 세대구분](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0006) | AI 4.0 (Organizational AI) / AI 세대구분 | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0007 AI 1.0 (Perceptional AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0007) | AI 1.0 (Perceptional AI) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0008 AI 2.0 (Generative AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0008) | AI 2.0 (Generative AI) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0009 AI 3.0 (Agentic AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0009) | AI 3.0 (Agentic AI) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0010 AI 4.0 (Organizational AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0010) | AI 4.0 (Organizational AI) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0011 LLM 체계도 (1~4/5층 아키텍처)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0011) | LLM 체계도 (1~4/5층 아키텍처) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0012 1~2층 (DX의 영역)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0012) | 1~2층 (DX의 영역) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0013 3층 (공통 & 거버넌스 컨텍스트 기반 지식사슬)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0013) | 3층 (공통 & 거버넌스 컨텍스트 기반 지식사슬) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0014 4층 (이미 세상에 나와 있는 LLM = '제 1의 LLM')](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0014) | 4층 (이미 세상에 나와 있는 LLM = '제 1의 LLM') | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0015 5층 (8장에서 추가되는 층)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0015) | 5층 (8장에서 추가되는 층) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0016 제2의 LLM (제1·제2·제3의 LLM)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0016) | 제2의 LLM (제1·제2·제3의 LLM) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0017 제 1의 LLM](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0017) | 제 1의 LLM | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0018 제 2의 LLM](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0018) | 제 2의 LLM | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0019 제 3의 LLM](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0019) | 제 3의 LLM | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0020 도메인 컨텍스트 (Domain Context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0020) | 도메인 컨텍스트 (Domain Context) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0021 조직AX용 OS](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0021) | 조직AX용 OS | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0022 조직AX용 OS 필요조건·추가조건](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0022) | 조직AX용 OS 필요조건·추가조건 | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0023 운영규범 (Operating protocols & control standards)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0023) | 운영규범 (Operating protocols & control standards) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0024 정보 보안 (Privacy & sovereignty)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0024) | 정보 보안 (Privacy & sovereignty) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0025 공통 컨텍스트와 거버넌스 컨텍스트 (Common & Governance context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0025) | 공통 컨텍스트와 거버넌스 컨텍스트 (Common & Governance context) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0026 Organizational digital twin(ODT)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0026) | Organizational digital twin(ODT) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0027 Organizational Digital Twin (ODT)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0027) | Organizational Digital Twin (ODT) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0028 AI 주권 (Sovereignty)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0028) | AI 주권 (Sovereignty) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0029 운영규범 (Operating Protocols & Control Standards)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0029) | 운영규범 (Operating Protocols & Control Standards) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0030 H: 인간 (Human)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0030) | H: 인간 (Human) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0031 B: 봇 (Bot)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0031) | B: 봇 (Bot) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0032 AI agent / Subagent / Bot 자율성 분류](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0032) | AI agent / Subagent / Bot 자율성 분류 | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0033 AI agent](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0033) | AI agent | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0034 Subagent](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0034) | Subagent | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0035 Bot (봇)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0035) | Bot (봇) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0036 협력 유형 (H+B / H+AH / AH+B / AH+AB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0036) | 협력 유형 (H+B / H+AH / AH+B / AH+AB) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0037 H + B (도구형 협력)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0037) | H + B (도구형 협력) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0038 H + AH (증강인간 중심 협력)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0038) | H + AH (증강인간 중심 협력) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0039 AH + B (지능형 작업 분업)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0039) | AH + B (지능형 작업 분업) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0040 AH + AB (진정한 AX조직)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0040) | AH + AB (진정한 AX조직) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0041 진정한 AX조직 / 하이브리드 조직 (AH+AB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0041) | 진정한 AX조직 / 하이브리드 조직 (AH+AB) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0042 인간-AI 협력 방식 분류 (HITL / AI-in-the-loop / HOTL / Autonomous AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0042) | 인간-AI 협력 방식 분류 (HITL / AI-in-the-loop / HOTL / Autonomous AI) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0043 Human-in-the-loop (인간 승인 중심)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0043) | Human-in-the-loop (인간 승인 중심) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0044 AI-in-the-loop (인간 중심 + AI 보조)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0044) | AI-in-the-loop (인간 중심 + AI 보조) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0045 Human-on-the-loop (AI 자율 + 인간 감독)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0045) | Human-on-the-loop (AI 자율 + 인간 감독) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0046 Autonomous AI (AI 자율 수행)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0046) | Autonomous AI (AI 자율 수행) | `ax_paradigm_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0047 증강 (Augmentation)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0047) | 증강 (Augmentation) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0048 경영 기본철학·핵심정신 체계 (기본전제 + 3정신)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0048) | 경영 기본철학·핵심정신 체계 (기본전제 + 3정신) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0049 증강(Augmentation) 실현](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0049) | 증강(Augmentation) 실현 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0050 다양성(Diversity) 존중과 활용](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0050) | 다양성(Diversity) 존중과 활용 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0051 보완적 적합성(Complementary Fit) 추구](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0051) | 보완적 적합성(Complementary Fit) 추구 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0052 인간중심주의 (Human Centrality)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0052) | 인간중심주의 (Human Centrality) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0053 다양성 (Diversity) 존중과 활용](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0053) | 다양성 (Diversity) 존중과 활용 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0054 유사적합성 (Supplementary Fit)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0054) | 유사적합성 (Supplementary Fit) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0055 보완적 적합성 (Complementary Fit)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0055) | 보완적 적합성 (Complementary Fit) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0056 인지적(cognitive) 보완](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0056) | 인지적(cognitive) 보완 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0057 정서적(emotional) 보완](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0057) | 정서적(emotional) 보완 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0058 행동적(behavioral) 보완](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0058) | 행동적(behavioral) 보완 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0059 윤리적(ethical) 보완](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0059) | 윤리적(ethical) 보완 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0060 혼비백산(魂飛魄散) 방지 (영·혼·백)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0060) | 혼비백산(魂飛魄散) 방지 (영·혼·백) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0061 혼(魂)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0061) | 혼(魂) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0062 백(魄)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0062) | 백(魄) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0063 영(靈)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0063) | 영(靈) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0064 혼비백산 방지 방안](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0064) | 혼비백산 방지 방안 | `honbibaeksan_governance_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0065 최종 책임은 인간과 조직에 남아야 한다](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0065) | 최종 책임은 인간과 조직에 남아야 한다 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0066 AI의 판단 과정은 기록되어야 한다](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0066) | AI의 판단 과정은 기록되어야 한다 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0067 인간은 AI 결과의 소비자가 아니라 검토자가 되어야 한다](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0067) | 인간은 AI 결과의 소비자가 아니라 검토자가 되어야 한다 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0068 자동화는 인간을 부품화해서는 안 된다](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0068) | 자동화는 인간을 부품화해서는 안 된다 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0069 기술 도입에는 거버넌스가 함께 설계되어야 한다](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0069) | 기술 도입에는 거버넌스가 함께 설계되어야 한다 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0070 AX조직 전환 인간반응 4층위 (생존·능력·관계·존재)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0070) | AX조직 전환 인간반응 4층위 (생존·능력·관계·존재) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0071 생존 층위](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0071) | 생존 층위 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0072 능력 층위](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0072) | 능력 층위 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0073 관계 층위](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0073) | 관계 층위 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0074 존재 층위](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0074) | 존재 층위 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0075 개별적 인간 반응·반발 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0075) | 개별적 인간 반응·반발 유형 (5형) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0076 생존불안형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0076) | 생존불안형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0077 역량열등형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0077) | 역량열등형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0078 통제상실형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0078) | 통제상실형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0079 감시공포형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0079) | 감시공포형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0080 인간성방어형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0080) | 인간성방어형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0081 집단적 인간 반응·반발 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0081) | 집단적 인간 반응·반발 유형 (5형) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0082 노동조합형 반발](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0082) | 노동조합형 반발 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0083 전문직 집단 저항](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0083) | 전문직 집단 저항 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0084 사회문화적 반발](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0084) | 사회문화적 반발 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0085 정치·정책적 반발](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0085) | 정치·정책적 반발 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0086 존재론적 반발](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0086) | 존재론적 반발 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0087 AX조직 스트레스 (4대 위험: 정체성·신뢰·통제·책임)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0087) | AX조직 스트레스 (4대 위험: 정체성·신뢰·통제·책임) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0088 정체성(identity) 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0088) | 정체성(identity) 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0089 신뢰(trust) 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0089) | 신뢰(trust) 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0090 통제(control) 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0090) | 통제(control) 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0091 책임(responsibility) 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0091) | 책임(responsibility) 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0092 인간 스트레스 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0092) | 인간 스트레스 유형 (5형) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0093 역할 모호성(Role Ambiguity)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0093) | 역할 모호성(Role Ambiguity) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0094 역량 대체 불안(Replacement Anxiety)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0094) | 역량 대체 불안(Replacement Anxiety) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0095 인지 과부하(Cognitive Overload)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0095) | 인지 과부하(Cognitive Overload) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0096 AI 불신 혹은 과신에서 오는 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0096) | AI 불신 혹은 과신에서 오는 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0097 사회적·관계적 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0097) | 사회적·관계적 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0098 봇 스트레스 유형 (5형)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0098) | 봇 스트레스 유형 (5형) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0099 계산 과부하(Computational Overload)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0099) | 계산 과부하(Computational Overload) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0100 목표 충돌(Goal Conflict)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0100) | 목표 충돌(Goal Conflict) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0101 정렬 실패(Misalignment)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0101) | 정렬 실패(Misalignment) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0102 지속적 업데이트 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0102) | 지속적 업데이트 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0103 다중 Agent 협력 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0103) | 다중 Agent 협력 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0104 인간 스트레스 vs 봇 스트레스 비교](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0104) | 인간 스트레스 vs 봇 스트레스 비교 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0105 본질](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0105) | 본질 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0106 핵심 원인](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0106) | 핵심 원인 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0107 결과](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0107) | 결과 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0108 회복 방식](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0108) | 회복 방식 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0109 위험](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0109) | 위험 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0110 측정](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0110) | 측정 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0111 관계(상호작용) 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0111) | 관계(상호작용) 스트레스 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0112 협력 유형별 스트레스 (H+B/H+AH/AH+B/AH+AB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0112) | 협력 유형별 스트레스 (H+B/H+AH/AH+B/AH+AB) | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0113 H + B 유형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0113) | H + B 유형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0114 H + AH 유형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0114) | H + AH 유형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0115 AH + B 유형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0115) | AH + B 유형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0116 AH + AB 유형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0116) | AH + AB 유형 | `ax_management_philosopher` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0117 AX조직 인재의 필요조건 (살아남는 인간의 역량)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0117) | AX조직 인재의 필요조건 (살아남는 인간의 역량) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0118 AI 이해력과 친화성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0118) | AI 이해력과 친화성 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0119 인간-AI 협업능력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0119) | 인간-AI 협업능력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0120 지속적 학습능력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0120) | 지속적 학습능력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0121 데이터·디지털 문해력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0121) | 데이터·디지털 문해력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0122 비판적 사고](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0122) | 비판적 사고 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0123 조직변화 적응력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0123) | 조직변화 적응력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0124 AX조직 인재의 추가조건 (성공하는 리더의 역량)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0124) | AX조직 인재의 추가조건 (성공하는 리더의 역량) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0125 문제 정의 능력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0125) | 문제 정의 능력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0126 의미(meaning) 설계 능력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0126) | 의미(meaning) 설계 능력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0127 시스템 사고](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0127) | 시스템 사고 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0128 인간-AI 오케스트레이션 능력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0128) | 인간-AI 오케스트레이션 능력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0129 거버넌스 & 윤리적 판단력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0129) | 거버넌스 & 윤리적 판단력 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0130 AX조직 인재의 3가지 책임 (맥락·판단·증거)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0130) | AX조직 인재의 3가지 책임 (맥락·판단·증거) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0131 맥락 책임](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0131) | 맥락 책임 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0132 판단 책임](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0132) | 판단 책임 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0133 증거 책임](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0133) | 증거 책임 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0134 AX조직 인재의 역할 8가지](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0134) | AX조직 인재의 역할 8가지 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0135 문제 정의자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0135) | 문제 정의자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0136 맥락 구성자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0136) | 맥락 구성자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0137 AI 실행 지시자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0137) | AI 실행 지시자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0138 결과 해석자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0138) | 결과 해석자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0139 검증자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0139) | 검증자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0140 책임 판단자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0140) | 책임 판단자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0141 증거 관리자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0141) | 증거 관리자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0142 개선 반영자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0142) | 개선 반영자 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0143 AX조직 인재의 5가지 핵심 역할 (조형자·구현자·검증자·운영자·조정자)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0143) | AX조직 인재의 5가지 핵심 역할 (조형자·구현자·검증자·운영자·조정자) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0144 조형자 (Shaper/Designer)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0144) | 조형자 (Shaper/Designer) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0145 구현자 (Implementer)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0145) | 구현자 (Implementer) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0146 검증자 (Validator)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0146) | 검증자 (Validator) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0147 운영자 (Operator)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0147) | 운영자 (Operator) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0148 조정자 (Coordinator)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0148) | 조정자 (Coordinator) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0149 AI 시대 역할론 (일·기여·역할의 재정의)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0149) | AI 시대 역할론 (일·기여·역할의 재정의) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0150 일](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0150) | 일 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0151 기여](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0151) | 기여 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0152 역할](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0152) | 역할 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0153 Belbin의 역할론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0153) | Belbin의 역할론 | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0154 창조자(plant)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0154) | 창조자(plant) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0155 냉철판단자(monitor evaluator)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0155) | 냉철판단자(monitor evaluator) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0156 완결자(completer finisher)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0156) | 완결자(completer finisher) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0157 인간-AI 오케스트레이션 (orchestration)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0157) | 인간-AI 오케스트레이션 (orchestration) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0158 인간성 수호 (humanity)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0158) | 인간성 수호 (humanity) | `ax_talent_role_designer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0159 증강인간 (AH)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0159) | 증강인간 (AH) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0160 신체적 증강](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0160) | 신체적 증강 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0161 정신적 증강](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0161) | 정신적 증강 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0162 역할·맥락 증강](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0162) | 역할·맥락 증강 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0163 증강봇 (AB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0163) | 증강봇 (AB) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0164 맥락 증강](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0164) | 맥락 증강 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0165 거버넌스 증강](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0165) | 거버넌스 증강 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0166 학습 증강](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0166) | 학습 증강 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0167 봇의 사회성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0167) | 봇의 사회성 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0168 인간-봇 사회성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0168) | 인간-봇 사회성 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0169 봇-봇 사회성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0169) | 봇-봇 사회성 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0170 봇의 윤리성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0170) | 봇의 윤리성 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0171 AI 윤리기준의 유형 (UNESCO·OECD·EU AI Act·IEEE·한국정부)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0171) | AI 윤리기준의 유형 (UNESCO·OECD·EU AI Act·IEEE·한국정부) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0172 UNESCO의 AI 윤리권고 (Recommendation on the Ethics of AI, 2021)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0172) | UNESCO의 AI 윤리권고 (Recommendation on the Ethics of AI, 2021) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0173 한국 정부 (사람이 중심이 되는 AI 윤리기준)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0173) | 한국 정부 (사람이 중심이 되는 AI 윤리기준) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0174 Claude 헌법 (Claude Constitution)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0174) | Claude 헌법 (Claude Constitution) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0175 포괄적 안전성 (broadly safe)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0175) | 포괄적 안전성 (broadly safe) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0176 포괄적 윤리성 (broadly ethical)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0176) | 포괄적 윤리성 (broadly ethical) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0177 유용성 (helpfulness)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0177) | 유용성 (helpfulness) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0178 가이드라인 준수 (compliance with guidelines)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0178) | 가이드라인 준수 (compliance with guidelines) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0179 조직AX 윤리의 필요조건과 추가조건](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0179) | 조직AX 윤리의 필요조건과 추가조건 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0180 조직AX의 윤리적 필요조건](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0180) | 조직AX의 윤리적 필요조건 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0181 조직AX의 추가조건](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0181) | 조직AX의 추가조건 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0182 로봇 3원칙 (three laws of robotics)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0182) | 로봇 3원칙 (three laws of robotics) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0183 ① 인간의 안전과 생명 존중(보호)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0183) | ① 인간의 안전과 생명 존중(보호) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0184 ② 인간에 대한 복종(존엄성 및 시열 인정)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0184) | ② 인간에 대한 복종(존엄성 및 시열 인정) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0185 ③ 로봇 스스로 자기보호(존재의 유지)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0185) | ③ 로봇 스스로 자기보호(존재의 유지) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0186 인간존중의 내재화](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0186) | 인간존중의 내재화 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0187 인간존중의 기술적 정의 (4가지)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0187) | 인간존중의 기술적 정의 (4가지) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0188 비해(Non-harm)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0188) | 비해(Non-harm) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0189 자율성 존중(Autonomy)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0189) | 자율성 존중(Autonomy) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0190 공정성(Fairness)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0190) | 공정성(Fairness) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0191 책임성(Accountability)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0191) | 책임성(Accountability) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0192 인간존중 구현 5단계 아키텍처](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0192) | 인간존중 구현 5단계 아키텍처 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0193 1단계(보상 설계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0193) | 1단계(보상 설계) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0194 2단계(강제 규칙)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0194) | 2단계(강제 규칙) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0195 3단계(인간 피드백 학습)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0195) | 3단계(인간 피드백 학습) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0196 4단계(검증 Layer)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0196) | 4단계(검증 Layer) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0197 5단계(Multi-agent 환경의 인간존중)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0197) | 5단계(Multi-agent 환경의 인간존중) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0198 봇의 인간 특성 이해 (socially compatible system)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0198) | 봇의 인간 특성 이해 (socially compatible system) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0199 인간의 비논리성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0199) | 인간의 비논리성 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0200 AI 관련 인간의 스트레스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0200) | AI 관련 인간의 스트레스 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0201 사회적 협력 규범 학습](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0201) | 사회적 협력 규범 학습 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0202 인간의 봇 특성 이해 (패턴 탐지기 / 기능적 만족·욕구)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0202) | 인간의 봇 특성 이해 (패턴 탐지기 / 기능적 만족·욕구) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0203 거대한 패턴 탐지기로서의 봇](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0203) | 거대한 패턴 탐지기로서의 봇 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0204 기능적 만족/불만족](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0204) | 기능적 만족/불만족 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0205 봇의 욕구 위계(hierarchy) 형성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0205) | 봇의 욕구 위계(hierarchy) 형성 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0206 봇의 행복](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0206) | 봇의 행복 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0207 봇들 간의 위계 형성 (Level 1-4)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0207) | 봇들 간의 위계 형성 (Level 1-4) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0208 Level 4 Verifier/Governor](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0208) | Level 4 Verifier/Governor | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0209 Level 3 Planner/Strategist](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0209) | Level 3 Planner/Strategist | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0210 Level 2 Specialist/Executor](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0210) | Level 2 Specialist/Executor | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0211 Level 1 Tool/Reactive Agent](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0211) | Level 1 Tool/Reactive Agent | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0212 HBRM (인간-봇 자원관리)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0212) | HBRM (인간-봇 자원관리) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0213 구성원 정의](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0213) | 구성원 정의 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0214 역할 설계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0214) | 역할 설계 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0215 협력 구조 설계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0215) | 협력 구조 설계 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0216 증강 관리](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0216) | 증강 관리 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0217 역할균형 관리](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0217) | 역할균형 관리 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0218 신뢰 관리](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0218) | 신뢰 관리 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0219 거버넌스 연결](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0219) | 거버넌스 연결 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0220 학습·개선 관리](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0220) | 학습·개선 관리 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0221 HBRM의 3M (method·meaning·measurement)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0221) | HBRM의 3M (method·meaning·measurement) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0222 방법(method)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0222) | 방법(method) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0223 의미(meaning)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0223) | 의미(meaning) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0224 측정(measurement)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0224) | 측정(measurement) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0225 증강인간 측정: AH 5대 지표](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0225) | 증강인간 측정: AH 5대 지표 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0226 인지 증강 (Cognitive A.)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0226) | 인지 증강 (Cognitive A.) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0227 의사결정 증강 (Decision A.)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0227) | 의사결정 증강 (Decision A.) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0228 학습 증강 (Learning A.)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0228) | 학습 증강 (Learning A.) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0229 협업 증강 (Collaboration A.)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0229) | 협업 증강 (Collaboration A.) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0230 역할 증강 (Role A.)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0230) | 역할 증강 (Role A.) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0231 인간 증강 단계 (H0~AH3)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0231) | 인간 증강 단계 (H0~AH3) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0232 H0 비증강인간](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0232) | H0 비증강인간 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0233 H1 AI 사용자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0233) | H1 AI 사용자 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0234 H2 AI 협업자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0234) | H2 AI 협업자 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0235 AH1 증강인간](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0235) | AH1 증강인간 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0236 AH2 AI 오케스트레이터](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0236) | AH2 AI 오케스트레이터 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0237 AH3 인간-AI 공생형 리더](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0237) | AH3 인간-AI 공생형 리더 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0238 AI 활용력 (AIU, AI Utilization)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0238) | AI 활용력 (AIU, AI Utilization) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0239 도구 사용자 (Tool User)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0239) | 도구 사용자 (Tool User) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0240 협업 사용자 (Collaborative User)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0240) | 협업 사용자 (Collaborative User) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0241 지휘자 (AI Orchestrator)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0241) | 지휘자 (AI Orchestrator) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0242 증강자 (Augmentation User)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0242) | 증강자 (Augmentation User) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0243 증강지수 (AQ, Augmentation Quotient)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0243) | 증강지수 (AQ, Augmentation Quotient) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0244 증강인간지수 (AHI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0244) | 증강인간지수 (AHI) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0245 증강인간 역량지수 (AHCI, Augmented Human Capability Index)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0245) | 증강인간 역량지수 (AHCI, Augmented Human Capability Index) | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0246 증강인간과 증강봇의 협력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0246) | 증강인간과 증강봇의 협력 | `ax_bot_governance_steward` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0247 팀역할균형 (TRB, Team Role Balance)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0247) | 팀역할균형 (TRB, Team Role Balance) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0248 팀역할 (TR, Team Role)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0248) | 팀역할 (TR, Team Role) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0249 기능역할 (functional role)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0249) | 기능역할 (functional role) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0250 팀역할 발휘 3수준 (자연역할/팀역할·잠재역할/관리가능역할·비선호역할)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0250) | 팀역할 발휘 3수준 (자연역할/팀역할·잠재역할/관리가능역할·비선호역할) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0251 팀/자연 역할 (Team/Natural Role)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0251) | 팀/자연 역할 (Team/Natural Role) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0252 잠재/관리가능 역할 (Potential/Manageable Role)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0252) | 잠재/관리가능 역할 (Potential/Manageable Role) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0253 비선호 역할 (Least-preferred Role)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0253) | 비선호 역할 (Least-preferred Role) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0254 Interplace](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0254) | Interplace | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0255 Interplace 4종 설문지 (자기진단지SPI·관찰자진단지OA·직무요구진단지JRE·직무관찰자진단지JOA)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0255) | Interplace 4종 설문지 (자기진단지SPI·관찰자진단지OA·직무요구진단지JRE·직무관찰자진단지JOA) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0256 자기진단지(SPI: self-perception inventory)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0256) | 자기진단지(SPI: self-perception inventory) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0257 관찰자진단지(OA: observer assessment)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0257) | 관찰자진단지(OA: observer assessment) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0258 직무요구진단지(JRE: job requirement exercise)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0258) | 직무요구진단지(JRE: job requirement exercise) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0259 직무관찰자진단지(JOA: job observer assessment)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0259) | 직무관찰자진단지(JOA: job observer assessment) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0260 집단응집성 (group cohesiveness)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0260) | 집단응집성 (group cohesiveness) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0261 팀웍의 두 측면 (인간적 유대감 & 업무적 활성화)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0261) | 팀웍의 두 측면 (인간적 유대감 & 업무적 활성화) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0262 인간적 유대감 측면의 팀웍](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0262) | 인간적 유대감 측면의 팀웍 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0263 업무적 활성화 측면의 팀웍](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0263) | 업무적 활성화 측면의 팀웍 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0264 행동유형 (behavior type) vs 성격유형 (personality type)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0264) | 행동유형 (behavior type) vs 성격유형 (personality type) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0265 RBHRM (Role-Based HRM, 역량+역할주의)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0265) | RBHRM (Role-Based HRM, 역량+역할주의) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0266 Belbin의 9가지 팀역할 유형 (창조자PL·냉철판단자ME·지휘조절자CO·실행자IMP·완결자CF·자원탐색가RI·분위기조성자TW·추진자SH·전문가SP)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0266) | Belbin의 9가지 팀역할 유형 (창조자PL·냉철판단자ME·지휘조절자CO·실행자IMP·완결자CF·자원탐색가RI·분위기조성자TW·추진자SH·전문가SP) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0267 창조자 (PL)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0267) | 창조자 (PL) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0268 냉철판단자(ME)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0268) | 냉철판단자(ME) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0269 지휘조절자(CO)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0269) | 지휘조절자(CO) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0270 실행자(IMP)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0270) | 실행자(IMP) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0271 완결자(CF)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0271) | 완결자(CF) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0272 자원탐색가(RI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0272) | 자원탐색가(RI) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0273 분위기조성자(TW)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0273) | 분위기조성자(TW) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0274 추진자(SH)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0274) | 추진자(SH) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0275 전문가(SP)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0275) | 전문가(SP) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0276 봇에 의한 TR의 보완·증강·추가](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0276) | 봇에 의한 TR의 보완·증강·추가 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0277 봇에 의한 TR의 보완](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0277) | 봇에 의한 TR의 보완 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0278 봇에 의한 TR의 증강](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0278) | 봇에 의한 TR의 증강 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0279 봇에 의한 TR의 추가](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0279) | 봇에 의한 TR의 추가 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0280 AX 신규 역할 (AI Governor·AI Auditor·Prompt Architect·AI Workflow Orchestrator·Human Meaning Integrator·Trust Manager·Provenance Controller)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0280) | AX 신규 역할 (AI Governor·AI Auditor·Prompt Architect·AI Workflow Orchestrator·Human Meaning Integrator·Trust Manager·Provenance Controller) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0281 AI Governor](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0281) | AI Governor | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0282 AI Auditor](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0282) | AI Auditor | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0283 Prompt Architect](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0283) | Prompt Architect | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0284 AI Workflow Orchestrator](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0284) | AI Workflow Orchestrator | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0285 Human Meaning Integrator](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0285) | Human Meaning Integrator | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0286 Trust Manager](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0286) | Trust Manager | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0287 Provenance Controller](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0287) | Provenance Controller | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0288 동적 역할균형 (dynamic role balance)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0288) | 동적 역할균형 (dynamic role balance) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0289 Bot-Aided TRB (봇 보조 TRB, 수직관계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0289) | Bot-Aided TRB (봇 보조 TRB, 수직관계) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0290 역할 진단자(Role Diagnostician)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0290) | 역할 진단자(Role Diagnostician) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0291 협업 조정자(Collaboration Facilitator)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0291) | 협업 조정자(Collaboration Facilitator) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0292 인지 증강자(Cognitive Augmenter)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0292) | 인지 증강자(Cognitive Augmenter) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0293 Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0293) | Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0294 역할의 공동 구성(Co-constitution)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0294) | 역할의 공동 구성(Co-constitution) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0295 역할 분산 최적화(Dynamic Role Allocation)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0295) | 역할 분산 최적화(Dynamic Role Allocation) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0296 인간-봇의 보완적 적합성 극대화(Maximization of Complementary Fit)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0296) | 인간-봇의 보완적 적합성 극대화(Maximization of Complementary Fit) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0297 TRB 진화 경로 (Human-only → Bot-aided → Human-bot coupled → Autonomous hybrid TRB)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0297) | TRB 진화 경로 (Human-only → Bot-aided → Human-bot coupled → Autonomous hybrid TRB) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0298 Human-only TRB](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0298) | Human-only TRB | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0299 Bot-aided TRB](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0299) | Bot-aided TRB | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0300 Human-bot coupled TRB](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0300) | Human-bot coupled TRB | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0301 증강 역할균형 지수 (ARBI, Augmented Role Balance Index)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0301) | 증강 역할균형 지수 (ARBI, Augmented Role Balance Index) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0302 ARBI 10개 평가 축 (역할균형·보완적 적합성·AI 개입 투명성·발화 주체성·권한·동의 경계·인간 책임성·의사소통 공정성·기록·추적성·심리·신뢰 안정성·조작 위험)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0302) | ARBI 10개 평가 축 (역할균형·보완적 적합성·AI 개입 투명성·발화 주체성·권한·동의 경계·인간 책임성·의사소통 공정성·기록·추적성·심리·신뢰 안정성·조작 위험) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0303 역할균형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0303) | 역할균형 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0304 보완적 적합성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0304) | 보완적 적합성 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0305 AI 개입 투명성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0305) | AI 개입 투명성 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0306 발화 주체성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0306) | 발화 주체성 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0307 권한·동의 경계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0307) | 권한·동의 경계 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0308 인간 책임성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0308) | 인간 책임성 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0309 의사소통 공정성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0309) | 의사소통 공정성 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0310 기록·추적성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0310) | 기록·추적성 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0311 심리·신뢰 안정성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0311) | 심리·신뢰 안정성 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0312 조작 위험](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0312) | 조작 위험 | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0313 HBRM (Human-Bot Role Management)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0313) | HBRM (Human-Bot Role Management) | `ax_team_role_analyst` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0314 로컬 환경 / 네트워크 환경](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0314) | 로컬 환경 / 네트워크 환경 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0315 로컬 환경](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0315) | 로컬 환경 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0316 네트워크 환경](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0316) | 네트워크 환경 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0317 공통 컨텍스트 (common context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0317) | 공통 컨텍스트 (common context) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0318 목적](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0318) | 목적 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0319 기준](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0319) | 기준 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0320 역할](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0320) | 역할 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0321 출처](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0321) | 출처 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0322 형식](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0322) | 형식 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0323 피드백](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0323) | 피드백 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0324 거버넌스 컨텍스트 (governance context)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0324) | 거버넌스 컨텍스트 (governance context) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0325 권한(authority)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0325) | 권한(authority) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0326 보안(security)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0326) | 보안(security) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0327 검증(validation)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0327) | 검증(validation) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0328 승인(approval)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0328) | 승인(approval) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0329 기록(record)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0329) | 기록(record) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0330 책임(accountability)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0330) | 책임(accountability) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0331 개선(improvement)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0331) | 개선(improvement) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0332 AI 거버넌스](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0332) | AI 거버넌스 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0333 지식사슬 (knowledge chain)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0333) | 지식사슬 (knowledge chain) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0334 질문](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0334) | 질문 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0335 조직 컨텍스트 참조](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0335) | 조직 컨텍스트 참조 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0336 거버넌스 검증](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0336) | 거버넌스 검증 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0337 결과 기록](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0337) | 결과 기록 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0338 조직 지식에 재반영](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0338) | 조직 지식에 재반영 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0339 다음 AI/인간이 재사용](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0339) | 다음 AI/인간이 재사용 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0340 지식사슬의 기능 (4대 기능)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0340) | 지식사슬의 기능 (4대 기능) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0341 구조 거리 측정](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0341) | 구조 거리 측정 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0342 전제 관계 측정](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0342) | 전제 관계 측정 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0343 추론사슬 충실도 측정](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0343) | 추론사슬 충실도 측정 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0344 전이 가능성 측정](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0344) | 전이 가능성 측정 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0345 의미·인지 거리](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0345) | 의미·인지 거리 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0346 AI 기여도](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0346) | AI 기여도 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0347 지식행동사슬 (지식(행동)사슬, knowledge behavior chain)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0347) | 지식행동사슬 (지식(행동)사슬, knowledge behavior chain) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0348 지식](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0348) | 지식 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0349 스킬(skill)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0349) | 스킬(skill) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0350 runtime(SkillRuntime)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0350) | runtime(SkillRuntime) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0351 action(실행)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0351) | action(실행) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0352 outcome(결과)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0352) | outcome(결과) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0353 review(검토)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0353) | review(검토) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0354 feedback(피드백)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0354) | feedback(피드백) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0355 context(조직 기준)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0355) | context(조직 기준) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0356 스킬 (skill)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0356) | 스킬 (skill) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0357 SkillRuntime](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0357) | SkillRuntime | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0358 입력](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0358) | 입력 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0359 자료](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0359) | 자료 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0360 도구](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0360) | 도구 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0361 금지](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0361) | 금지 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0362 결과 형식](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0362) | 결과 형식 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0363 검토·승인자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0363) | 검토·승인자 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0364 기록 위치](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0364) | 기록 위치 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0365 지식행동사슬 노드 온톨로지 (identity·goal·knowledge·method·skill·task·artifact)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0365) | 지식행동사슬 노드 온톨로지 (identity·goal·knowledge·method·skill·task·artifact) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0366 공통·의사소통·거버넌스 3계층 컨텍스트 구조](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0366) | 공통·의사소통·거버넌스 3계층 컨텍스트 구조 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0367 공통 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0367) | 공통 컨텍스트 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0368 의사소통 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0368) | 의사소통 컨텍스트 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0369 거버넌스 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0369) | 거버넌스 컨텍스트 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0370 의사소통 컨텍스트](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0370) | 의사소통 컨텍스트 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0371 구성원 유형별 의사소통 (AH-H · AH-AH)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0371) | 구성원 유형별 의사소통 (AH-H · AH-AH) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0372 AH-H 간 의사소통](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0372) | AH-H 간 의사소통 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0373 AH-AH 간 의사소통](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0373) | AH-AH 간 의사소통 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0374 역할 공백](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0374) | 역할 공백 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0375 기여 충돌](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0375) | 기여 충돌 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0376 증강인간 간 의사소통 3경로 (인간 중심 · AI 중심 · 거버넌스 경유)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0376) | 증강인간 간 의사소통 3경로 (인간 중심 · AI 중심 · 거버넌스 경유) | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0377 인간 중심 경로](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0377) | 인간 중심 경로 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0378 AI 중심 경로](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0378) | AI 중심 경로 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0379 거버넌스 경유 경로](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0379) | 거버넌스 경유 경로 | `ax_context_chain_architect` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0380 AI 예측지능](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0380) | AI 예측지능 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0381 AI 예측지능 체계 / 예측지능 스택](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0381) | AI 예측지능 체계 / 예측지능 스택 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0382 월드 모델](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0382) | 월드 모델 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0383 지식사슬](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0383) | 지식사슬 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0384 컨텍스트 설계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0384) | 컨텍스트 설계 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0385 월드 모델](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0385) | 월드 모델 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0386 컨텍스트 설계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0386) | 컨텍스트 설계 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0387 컨텍스트 설계자 (컨텍스트 설계형 AX 인재)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0387) | 컨텍스트 설계자 (컨텍스트 설계형 AX 인재) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0388 AI 기반 계급화 (AI 계급사회 / AI 기반 계층화)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0388) | AI 기반 계급화 (AI 계급사회 / AI 기반 계층화) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0389 AI 기반 계급화를 만드는 7가지 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0389) | AI 기반 계급화를 만드는 7가지 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0390 AI 접근 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0390) | AI 접근 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0391 AI 역량 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0391) | AI 역량 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0392 AI 맥락 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0392) | AI 맥락 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0393 AI 판단권 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0393) | AI 판단권 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0394 AI 감시 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0394) | AI 감시 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0395 AI 소유 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0395) | AI 소유 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0396 AI 성과배분 격차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0396) | AI 성과배분 격차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0397 AI 시대 노동 분화 4유형](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0397) | AI 시대 노동 분화 4유형 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0398 AI 보완형 노동자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0398) | AI 보완형 노동자 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0399 AI 관리 대상 노동자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0399) | AI 관리 대상 노동자 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0400 AI 대체·축소 위험 노동자](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0400) | AI 대체·축소 위험 노동자 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0401 컨텍스트 설계형 AX 인재](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0401) | 컨텍스트 설계형 AX 인재 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0402 알고리즘 관리](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0402) | 알고리즘 관리 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0403 포용전환 AX](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0403) | 포용전환 AX | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0404 효율성 중심 AX](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0404) | 효율성 중심 AX | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0405 맥락자본의 사회화](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0405) | 맥락자본의 사회화 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0406 맥락자본 (Context Capital)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0406) | 맥락자본 (Context Capital) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0407 맥락자본 접근권 (맥락 접근권)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0407) | 맥락자본 접근권 (맥락 접근권) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0408 맥락 정의 (Context Justice)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0408) | 맥락 정의 (Context Justice) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0409 AI 역량 평등론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0409) | AI 역량 평등론 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0410 책임운영체계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0410) | 책임운영체계 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0411 권한](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0411) | 권한 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0412 보안](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0412) | 보안 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0413 검증](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0413) | 검증 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0414 승인](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0414) | 승인 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0415 기록](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0415) | 기록 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0416 책임](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0416) | 책임 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0417 개선](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0417) | 개선 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0418 AI 시대 ESG 개념의 확장 (확장 ESG)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0418) | AI 시대 ESG 개념의 확장 (확장 ESG) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0419 E의 확장 (AI 인프라의 지속가능성)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0419) | E의 확장 (AI 인프라의 지속가능성) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0420 S의 확장 (AI 역량 평등과 인간 존엄)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0420) | S의 확장 (AI 역량 평등과 인간 존엄) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0421 G의 확장 (AI 권력의 책임구조)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0421) | G의 확장 (AI 권력의 책임구조) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0422 ESG 확장론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0422) | ESG 확장론 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0423 이해관계자 확대론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0423) | 이해관계자 확대론 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0424 측정·검증 강화론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0424) | 측정·검증 강화론 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0425 ESG의 AI 시대 확장론](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0425) | ESG의 AI 시대 확장론 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0426 AI-ESG 관계의 두 관점 (AI for ESG / ESG for AI)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0426) | AI-ESG 관계의 두 관점 (AI for ESG / ESG for AI) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0427 AI for ESG](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0427) | AI for ESG | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0428 ESG for AI](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0428) | ESG for AI | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0429 AI 포용전환 ESG (Inclusive / Just AI Transition ESG)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0429) | AI 포용전환 ESG (Inclusive / Just AI Transition ESG) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0430 AI 포용전환 ESG의 네 층위](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0430) | AI 포용전환 ESG의 네 층위 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0431 확인 가능한 사실](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0431) | 확인 가능한 사실 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0432 합리적 해석](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0432) | 합리적 해석 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0433 제안 개념](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0433) | 제안 개념 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0434 실행 모델](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0434) | 실행 모델 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0435 공정전환 (Just Transition)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0435) | 공정전환 (Just Transition) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0436 AI 시대 인간 보호 권리 (8대 권리)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0436) | AI 시대 인간 보호 권리 (8대 권리) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0437 AI 접근권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0437) | AI 접근권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0438 AI 학습권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0438) | AI 학습권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0439 AI 활용권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0439) | AI 활용권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0440 AI 판단권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0440) | AI 판단권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0441 AI 설명권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0441) | AI 설명권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0442 AI 이의제기권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0442) | AI 이의제기권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0443 AI 전환권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0443) | AI 전환권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0444 AI 성과공유권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0444) | AI 성과공유권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0445 ESG 실행 구조 (AI 포용전환 ESG 실행 모델, 9단계)](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0445) | ESG 실행 구조 (AI 포용전환 ESG 실행 모델, 9단계) | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0446 1. AI 영향평가](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0446) | 1. AI 영향평가 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0447 2. AI 맥락자본 구축](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0447) | 2. AI 맥락자본 구축 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0448 3. 권한 설계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0448) | 3. 권한 설계 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0449 4. 노동 전환](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0449) | 4. 노동 전환 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0450 5. 인간 승인 기준](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0450) | 5. 인간 승인 기준 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0451 6. 이의제기 절차](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0451) | 6. 이의제기 절차 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0452 7. 감사 기록](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0452) | 7. 감사 기록 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0453 8. 성과배분](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0453) | 8. 성과배분 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0454 9. 개선 루프](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0454) | 9. 개선 루프 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0455 포용전환 ESG 12지표](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0455) | 포용전환 ESG 12지표 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0456 AI 접근성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0456) | AI 접근성 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0457 AI 교육](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0457) | AI 교육 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0458 AI 활용 역량](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0458) | AI 활용 역량 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0459 노동 전환](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0459) | 노동 전환 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0460 인간 판단권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0460) | 인간 판단권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0461 설명 가능성](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0461) | 설명 가능성 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0462 이의제기권](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0462) | 이의제기권 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0463 감사 기록](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0463) | 감사 기록 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0464 책임구조](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0464) | 책임구조 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0465 성과 공유](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0465) | 성과 공유 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0466 맥락자본](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0466) | 맥락자본 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0467 책임운영체계](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0467) | 책임운영체계 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |
| [S3S-0468 환경 책임](./20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0468) | 환경 책임 | `ax_inclusive_transition_officer` | YES | YES | YES | YES | **ASSIGNED** |

## UnassignedAgentSet

**EMPTY (0)** — every one of the 468 candidates falls inside exactly one of the 7
chapter-scoped agent roles, each of which holds authority over the `_identity/<key>/` subtree its candidates
would write.

## DeferredManualReviewSet (from agent assignment)

**EMPTY (0)** — no candidate was deferred for want of an executing agent.
