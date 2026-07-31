# Stage-1 Source-Linked Identity Extraction Artifact

- **runID**: `20260719_154811`  (minted INTERNALLY by stable_key_construction (E2); NOT an input)
- **stage**: 1 (candidate extraction) — `stage_1_candidate_extraction_skill`, invoked UNCHANGED
- **runRoot**: `/Users/gesia/wwp_book_v0.2`  (active-vault-root bound BEFORE member 1; held for the whole run)
- **FROZEN `_identity` registry snapshot**: `/Users/gesia/wwp_book_v0.2/_identity/` — **EMPTY** (new vault, 0 existing identities)
- **corpus**: `/Users/gesia/wwp_book_v0.2/_input/_document/*.md` — 12 documents
- **encoding**: UTF-8; Korean display names preserved verbatim beside every UPPER_SNAKE normalized key

## InputAdmission

The `_input` document corpus was admitted at the boundary (classified `_input`, bound, NOT persisted),
authorizing the runID mint. The FROZEN `_identity` registry SNAPSHOT was supplied as a composite-local
input and is **empty**: candidate_adjudication (5-B) therefore resolves **no** registry duplicate and
**no** registry collapse against it. All COLLAPSE dispositions in this run are **intra-run duplicate
referents** (the same identity harvested from more than one chapter), resolved by candidate_adjudication
and projected into the RegistryCollapse section.

## SourceManifest

- runID: `20260719_154811`
- admitted documents: 12
- harvested source units: 185

| SourceDocumentID | document | lines | sourceDocumentSha256 |
|---|---|---|---|
| SD-01 | `_input/_document/00_서문.md` | 41 | `1d15148ad9002277dc2fefe340c1e31b7ac0614d74919ff169b13021b93ba5c3` |
| SD-02 | `_input/_document/00_표지_및_목차.md` | 219 | `a122879df36309c0c28111ad4946a6702c8d98bd8491729aea9732fceae38ccf` |
| SD-03 | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | 448 | `bb746412e8c080501855ac57d12ad401c29d7bb97b675daa16db3b0bf6cd6fe2` |
| SD-04 | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | 404 | `047acf0bf6b6761cca7d498e0054e87e7cdfe3668d1aa709d64bbf21b57812d6` |
| SD-05 | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | 382 | `07b8593e04fe9368915637f9270a84c2f05c13063a6ab3af1c0af9a8e7ec4594` |
| SD-06 | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | 619 | `36f5f1e2a295993c623aaccfdefd574d1f713715571e77dc84b700f55d6e8ba1` |
| SD-07 | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | 274 | `f622d9122cc6584bcc1fcfd3ea9b616c11ec1bcf7a4723d11e8fe1e9257caa6e` |
| SD-08 | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | 287 | `e40abd5023662638044819bc3548884e58419e6535a51f11b246bbb5f8d278a6` |
| SD-09 | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | 873 | `046ec64d26af191dcebbd07199624852d24484e591f5dfbc240e5b55df28e4cc` |
| SD-10 | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | 588 | `994d719d68a39ff27dc8e1e8ebd5f07b2dbcc8c87e3c8b025d7f974fc799ef93` |
| SD-11 | `_input/_document/09_참고문헌.md` | 85 | `2a25e270fabebefb0ee6e399b23d8f157362fe7facf3ac160eb310f416233393` |
| SD-12 | `_input/_document/README.md` | 31 | `684734608a2978f269bb247ec77fefe24585ad2853f384641605bb2149af268e` |

## SourceIndex

Each harvested candidate occupies exactly one SourceUnit `SU-nnn` with exactly one SourceProvenance
`SP-nnn`, anchored to one SourceDocument `SD-nn` and one line range inside it. The RAW `_Source` body
below is loss-free over the harvested span set: every harvested span is preserved as a SourceUnit,
including the spans of rows later settled COLLAPSE or DROP.

## SourceDocument / SourceUnit / SourceProvenance / SourceAlignment (RAW)

| SourceUnitID | SourceProvenanceID | SourceDocumentID | heading | sourceLineRanges | SourceAlignment (RAW link) |
|---|---|---|---|---|---|
| SU-001 | SP-001 | SD-?? | #### (1) AX의 필요성과 현 위치 | 13-52 | SU-001 -> S1C-001 |
| SU-002 | SP-002 | SD-?? | #### (1) AX의 필요성과 현 위치 | 13-37 | SU-002 -> S1C-002 |
| SU-003 | SP-003 | SD-?? | #### (1) AX의 필요성과 현 위치 | 13-13 (also Ch.2 line 17) | SU-003 -> S1C-003 |
| SU-004 | SP-004 | SD-?? | ### 1) AX조직이란? / #### (2) 왜 조직AX가 쉽지 않나? | 15-145 | SU-004 -> S1C-004 |
| SU-005 | SP-005 | SD-?? | ### 1) AX조직이란? | 15-24 | SU-005 -> S1C-005 |
| SU-006 | SP-006 | SD-?? | ### 1) AX조직이란? | 24-125 | SU-006 -> S1C-006 |
| SU-007 | SP-007 | SD-?? | ### 1) AX조직이란? | 21-24 | SU-007 -> S1C-007 |
| SU-008 | SP-008 | SD-?? | #### (2) 왜 조직AX가 쉽지 않나? | 58-69 | SU-008 -> S1C-008 |
| SU-009 | SP-009 | SD-?? | #### (2) 왜 조직AX가 쉽지 않나? | 147-171 | SU-009 -> S1C-009 |
| SU-010 | SP-010 | SD-?? | #### (2) 왜 조직AX가 쉽지 않나? / '제 2의 LLM' 용어의 타당성 | 151-185 | SU-010 -> S1C-010 |
| SU-011 | SP-011 | SD-?? | #### (2) 왜 조직AX가 쉽지 않나? | 155-171 (also 199, 234) | SU-011 -> S1C-011 |
| SU-012 | SP-012 | SD-?? | #### (2) 왜 조직AX가 쉽지 않나? / #### (4) 대표적 사례 | 157-171 (also 234, 248-256) | SU-012 -> S1C-012 |
| SU-013 | SP-013 | SD-?? | #### (2) 왜 조직AX가 쉽지 않나? | 157-185 (also 234, 303) | SU-013 -> S1C-013 |
| SU-014 | SP-014 | SD-?? | #### (4) 조직AX용 OS의 대표적 사례 | 248-256 | SU-014 -> S1C-014 |
| SU-015 | SP-015 | SD-?? | #### (3) 조직AX용 OS의 구성요소 | 187-276 | SU-015 -> S1C-015 |
| SU-016 | SP-016 | SD-?? | #### (3) 조직AX용 OS의 구성요소: 필요조건과 추가조건 | 187-214 | SU-016 -> S1C-016 |
| SU-017 | SP-017 | SD-?? | #### (3) 조직AX용 OS의 구성요소 | 203-214 | SU-017 -> S1C-017 |
| SU-018 | SP-018 | SD-?? | #### (3) 조직AX용 OS의 구성요소 / #### (4) 대표적 사례 | 210-230 | SU-018 -> S1C-018 |
| SU-019 | SP-019 | SD-?? | #### (3) 조직AX용 OS의 구성요소 | 198-208 | SU-019 -> S1C-019 |
| SU-020 | SP-020 | SD-?? | #### (2) 왜 조직AX가 쉽지 않나? | 141-141 (also 200, 303) | SU-020 -> S1C-020 |
| SU-021 | SP-021 | SD-?? | #### (4) 조직AX용 OS의 대표적 사례 | 261-265 | SU-021 -> S1C-021 |
| SU-022 | SP-022 | SD-?? | #### (1) AX조직의 구성원 유형 | 288-291 | SU-022 -> S1C-022 |
| SU-023 | SP-023 | SD-?? | #### (1) AX조직의 구성원 유형 | 294-316 (also Ch.2 238-240) | SU-023 -> S1C-023 |
| SU-024 | SP-024 | SD-?? | #### (1) AX조직의 구성원 유형 | 300-314 (also Ch.2 242) | SU-024 -> S1C-024 |
| SU-025 | SP-025 | SD-?? | #### (1) AX조직의 구성원 유형 | 306-335 | SU-025 -> S1C-025 |
| SU-026 | SP-026 | SD-?? | #### (1) AX조직의 구성원 유형 | 349-363 | SU-026 -> S1C-026 |
| SU-027 | SP-027 | SD-?? | #### (1) 증강(Augmentation) 실현 | 219-244 (introduced Ch.1 286) | SU-027 -> S1C-027 |
| SU-028 | SP-028 | SD-?? | #### (1) AX조직의 구성원 유형 / HRM → HBRM | 320-337 | SU-028 -> S1C-028 |
| SU-029 | SP-029 | SD-?? | #### (2) AX조직의 협력 유형 | 365-391 | SU-029 -> S1C-029 |
| SU-030 | SP-030 | SD-?? | #### (1) 구성원 유형 / #### (3) 진정한 AX 'AH + AB' 조직의 특성 | 316-431 | SU-030 -> S1C-030 |
| SU-031 | SP-031 | SD-?? | #### (2) AX조직의 협력 유형 | 393-427 | SU-031 -> S1C-031 |
| SU-032 | SP-032 | SD-?? | #### (3) 진정한 AX 'AH + AB' 조직의 특성 | 429-429 | SU-032 -> S1C-032 |
| SU-033 | SP-033 | SD-?? | ### 3) 인간-봇 공존과 번영을 위한 핵심 정신 | 5-9, 211-217, 270 | SU-033 -> S1C-033 |
| SU-034 | SP-034 | SD-?? | ### 3) 핵심 정신 / 기본 전제 | 215-217 | SU-034 -> S1C-034 |
| SU-035 | SP-035 | SD-?? | #### (2) 다양성(Diversity) 존중과 활용 | 246-264 (introduced Ch.1 280 '다양성의 증폭') | SU-035 -> S1C-035 |
| SU-036 | SP-036 | SD-?? | #### (2) 다양성 / #### (3) 보완적 적합성 | 250-268 | SU-036 -> S1C-036 |
| SU-037 | SP-037 | SD-?? | #### (3) 보완적 적합성(Complementary Fit) 추구 | 266-288 | SU-037 -> S1C-037 |
| SU-038 | SP-038 | SD-?? | #### (2) 다양성(Diversity) 존중과 활용 | 262-262 (also Ch.1 385, 429) | SU-038 -> S1C-038 |
| SU-039 | SP-039 | SD-?? | #### (4) 혼비백산(魂飛魄散) 방지 | 292-402 | SU-039 -> S1C-039 |
| SU-040 | SP-040 | SD-?? | #### (2) AX조직 전환과 인간 반응 | 49-57 | SU-040 -> S1C-040 |
| SU-041 | SP-041 | SD-?? | #### (2) AX조직 전환과 인간 반응 | 59-69 | SU-041 -> S1C-041 |
| SU-042 | SP-042 | SD-?? | #### (2) AX조직 전환과 인간 반응 | 71-83 | SU-042 -> S1C-042 |
| SU-043 | SP-043 | SD-?? | #### (1) AI 발달과 인간 반응 | 33-33 (also 85) | SU-043 -> S1C-043 |
| SU-044 | SP-044 | SD-?? | ### 2) AX조직 구성원이 경험하는 스트레스 | 89-209 | SU-044 -> S1C-044 |
| SU-045 | SP-045 | SD-?? | #### (1) 인간과 봇의 스트레스 | 97-107 | SU-045 -> S1C-045 |
| SU-046 | SP-046 | SD-?? | #### (1) 인간과 봇의 스트레스 | 109-121 | SU-046 -> S1C-046 |
| SU-047 | SP-047 | SD-?? | #### (1) 인간과 봇의 스트레스 | 123-137 | SU-047 -> S1C-047 |
| SU-048 | SP-048 | SD-?? | #### (1) 인간과 봇의 스트레스 | 139-139 | SU-048 -> S1C-048 |
| SU-049 | SP-049 | SD-?? | #### (2) AX조직의 협력 유형별 스트레스 | 141-205 | SU-049 -> S1C-049 |
| SU-050 | SP-050 | SD-?? | #### (2) AX조직의 협력 유형별 스트레스 | 189-191 | SU-050 -> S1C-050 |
| SU-051 | SP-051 | SD-?? | #### (1) 인간과 봇의 스트레스 | 103-103 | SU-051 -> S1C-051 |
| SU-052 | SP-052 | SD-?? | #### (3) 보완적 적합성(Complementary Fit) 추구 | 288-288 (also Ch.1 314; Ch.2 footnote 311) | SU-052 -> S1C-052 |
| SU-053 | SP-053 | SD-?? | #### (1) AX조직 인재의 필요조건: 살아남는 인간의 역량 | 29-49 | SU-053 -> S1C-053 |
| SU-054 | SP-054 | SD-?? | #### (2) AX조직 인재의 추가조건: 성공하는 리더의 역량 | 51-99 | SU-054 -> S1C-054 |
| SU-055 | SP-055 | SD-?? | #### (1) AX조직 인재의 본질과 책임 | 158-176 | SU-055 -> S1C-055 |
| SU-056 | SP-056 | SD-?? | #### (2) AX조직 인재의 역할 8가지 | 207-283 | SU-056 -> S1C-056 |
| SU-057 | SP-057 | SD-?? | #### (2) AX조직 인재의 역할 8가지 (table); #### (3) AI 시대 역할론 | 284-316 (also 358-376) | SU-057 -> S1C-057 |
| SU-058 | SP-058 | SD-?? | #### (3) AI 시대 역할론: 일, 기여, 역할의 재정의 | 318-380 | SU-058 -> S1C-058 |
| SU-059 | SP-059 | SD-?? | #### (3) AI 시대 역할론 (bold: AI 시대 인재의 핵심 역할과 Belbin의 역할론) | 358-380 | SU-059 -> S1C-059 |
| SU-060 | SP-060 | SD-?? | #### (2) AX조직 인재의 추가조건 | 53, 67, 108 | SU-060 -> S1C-060 |
| SU-061 | SP-061 | SD-?? | #### (2) AX조직 인재의 추가조건 | 63 | SU-061 -> S1C-061 |
| SU-062 | SP-062 | SD-?? | #### (1) HBRM의 의미와 역할 (ch4); 추가조건 (ch3 line 67) | ch4 324-341 (also ch3 line 67, 77) | SU-062 -> S1C-062 |
| SU-063 | SP-063 | SD-?? | #### (2) 증강인간(AH)의 의미와 측정 | 343-373 (built indirectly in ch3) | SU-063 -> S1C-063 |
| SU-064 | SP-064 | SD-?? | #### (3) 증강봇(AB)의 의미와 측정 | 514-576 | SU-064 -> S1C-064 |
| SU-065 | SP-065 | SD-?? | ### 3) AX조직의 인사관리: HBRM | 273, 302, 314 | SU-065 -> S1C-065 |
| SU-066 | SP-066 | SD-?? | #### (3) 증강봇(AB)의 의미와 측정 | 273, 524-539 | SU-066 -> S1C-066 |
| SU-067 | SP-067 | SD-?? | #### (1) 봇의 사회성 | 7-60 | SU-067 -> S1C-067 |
| SU-068 | SP-068 | SD-?? | #### (2) 봇의 윤리성 | 62-99 | SU-068 -> S1C-068 |
| SU-069 | SP-069 | SD-?? | #### (2) 봇의 윤리성 (bold: 윤리기준의 유형) | 66-89 | SU-069 -> S1C-069 |
| SU-070 | SP-070 | SD-?? | #### (2) 봇의 윤리성 (bold: 윤리기준의 유형) | 87-89 | SU-070 -> S1C-070 |
| SU-071 | SP-071 | SD-?? | #### (2) 봇의 윤리성 (bold: 윤리기준의 필요조건과 추가조건) | 91-99 | SU-071 -> S1C-071 |
| SU-072 | SP-072 | SD-?? | #### (1) 인간존중의 내재화 | 107-113 | SU-072 -> S1C-072 |
| SU-073 | SP-073 | SD-?? | #### (1) 인간존중의 내재화 | 105-134 | SU-073 -> S1C-073 |
| SU-074 | SP-074 | SD-?? | #### (1) 인간존중의 내재화 | 117-122 | SU-074 -> S1C-074 |
| SU-075 | SP-075 | SD-?? | #### (1) 인간존중의 내재화 (인간존중 구현 방법) | 124-134 | SU-075 -> S1C-075 |
| SU-076 | SP-076 | SD-?? | #### (2) 봇의 인간 특성 이해 | 136-146 | SU-076 -> S1C-076 |
| SU-077 | SP-077 | SD-?? | #### (3) 인간의 봇 특성 이해 | 148-243 | SU-077 -> S1C-077 |
| SU-078 | SP-078 | SD-?? | #### (3) 인간의 봇 특성 이해 (bold: 봇들 간의 위계 형성) | 245-269 | SU-078 -> S1C-078 |
| SU-079 | SP-079 | SD-?? | ### 3) AX조직의 인사관리: HBRM ; #### (1) HBRM의 의미와 역할 | 271-341 | SU-079 -> S1C-079 |
| SU-080 | SP-080 | SD-?? | ### 3) AX조직의 인사관리: HBRM | 273 | SU-080 -> S1C-080 |
| SU-081 | SP-081 | SD-?? | #### (2) 증강인간(AH)의 의미와 측정 (증강인간의 측정) | 377-397 | SU-081 -> S1C-081 |
| SU-082 | SP-082 | SD-?? | #### (2) 증강인간(AH)의 의미와 측정 | 405-417 | SU-082 -> S1C-082 |
| SU-083 | SP-083 | SD-?? | #### (2) 증강인간(AH)의 의미와 측정 (AI 활용력 측정) | 417-454 | SU-083 -> S1C-083 |
| SU-084 | SP-084 | SD-?? | #### (2) 증강인간(AH)의 의미와 측정 (증강지수와 증강인간지수 측정) | 456-464 | SU-084 -> S1C-084 |
| SU-085 | SP-085 | SD-?? | #### (2) 증강인간(AH)의 의미와 측정 (증강지수와 증강인간지수 측정) | 466-474 | SU-085 -> S1C-085 |
| SU-086 | SP-086 | SD-?? | #### (2) 증강인간(AH)의 의미와 측정 (증강인간 역량지수 측정) | 476-506 | SU-086 -> S1C-086 |
| SU-087 | SP-087 | SD-?? | footnotes 29 (line 533) and 30 (line 600) | 533, 600 | SU-087 -> S1C-087 |
| SU-088 | SP-088 | SD-?? | #### (3) 증강봇(AB)의 의미와 측정 (bold: 증강인간과 증강봇의 협력) | 578-617 | SU-088 -> S1C-088 |
| SU-089 | SP-089 | SD-?? | #### (3) 증강봇(AB)의 의미와 측정 / 추가조건 (ch3) | ch4 582-611 (also ch3 line 71) | SU-089 -> S1C-089 |
| SU-090 | SP-090 | SD-?? | #### (2) Belbin의 팀역할과 팀역할균형론 | 110-118 | SU-090 -> S1C-090 |
| SU-091 | SP-091 | SD-?? | #### (1) 팀역할의 의미 | 43-53 | SU-091 -> S1C-091 |
| SU-092 | SP-092 | SD-?? | #### (1) 팀역할의 의미 | 15-17 | SU-092 -> S1C-092 |
| SU-093 | SP-093 | SD-?? | #### (1) 봇에 의한 TR의 보완, 증강, 추가 | 30-40 | SU-093 -> S1C-093 |
| SU-094 | SP-094 | SD-?? | #### (2) Belbin의 팀역할과 팀역할균형론 | 93-108 | SU-094 -> S1C-094 |
| SU-095 | SP-095 | SD-?? | ## 3부. 하이브리드 조직의 팀웍과 성과 증진 | 7-7 | SU-095 -> S1C-095 |
| SU-096 | SP-096 | SD-?? | ### 2) TR과 TRB의 측정: Interplace | 138-142 | SU-096 -> S1C-096 |
| SU-097 | SP-097 | SD-?? | #### (1) TR의 측정 | 142-142 | SU-097 -> S1C-097 |
| SU-098 | SP-098 | SD-?? | #### (1) 팀역할의 의미 | 39-55 | SU-098 -> S1C-098 |
| SU-099 | SP-099 | SD-?? | #### (1) 팀역할의 의미 | 39-41 | SU-099 -> S1C-099 |
| SU-100 | SP-100 | SD-?? | #### (2) Belbin의 팀역할과 팀역할균형론 | 120-124 | SU-100 -> S1C-100 |
| SU-101 | SP-101 | SD-?? | #### (2) Belbin의 팀역할과 팀역할균형론 | 120-122 | SU-101 -> S1C-101 |
| SU-102 | SP-102 | SD-?? | #### (1) 팀역할의 의미 | 48-51 | SU-102 -> S1C-102 |
| SU-103 | SP-103 | SD-?? | #### (1) Interplace 활용 영역 | 214-214 | SU-103 -> S1C-103 |
| SU-104 | SP-104 | SD-?? | #### (1) Interplace 활용 영역 | 214-214 | SU-104 -> S1C-104 |
| SU-105 | SP-105 | SD-?? | ### 3) Interplace의 활용 방법 | 206-210 | SU-105 -> S1C-105 |
| SU-106 | SP-106 | SD-?? | #### (1) 봇에 의한 TR의 보완, 증강, 추가 | 25-78 | SU-106 -> S1C-106 |
| SU-107 | SP-107 | SD-?? | #### (1) 봇에 의한 TR의 보완, 증강, 추가 | 69-78 | SU-107 -> S1C-107 |
| SU-108 | SP-108 | SD-?? | #### (2) AX조직의 TRB: 중요성 증대와 동적화 | 114-123 | SU-108 -> S1C-108 |
| SU-109 | SP-109 | SD-?? | #### (1) Bot-Aided TRB: 인간 우선-봇 보조의 수직관계 | 133-154 | SU-109 -> S1C-109 |
| SU-110 | SP-110 | SD-?? | #### (2) Human-Bot Coupled TRB: 인간-봇 결합 최적화의 수평관계 | 156-189 | SU-110 -> S1C-110 |
| SU-111 | SP-111 | SD-?? | ### 2) AX조직에서 TRB의 진화 | 191-191 | SU-111 -> S1C-111 |
| SU-112 | SP-112 | SD-?? | #### (1) ARBI의 의미와 필요성 | 197-211 | SU-112 -> S1C-112 |
| SU-113 | SP-113 | SD-?? | #### (2) ARBI와 TRB, AHCI와 관계 | 231-249 | SU-113 -> S1C-113 |
| SU-114 | SP-114 | SD-?? | #### (3) ARBI의 평가 대상과 구조 | 271-285 | SU-114 -> S1C-114 |
| SU-115 | SP-115 | SD-?? | ## 6장. 인간-봇 공존 조직에서의 TRB | 13-13 | SU-115 -> S1C-115 |
| SU-116 | SP-116 | SD-?? | #### (2) ARBI와 TRB, AHCI와 관계 | 253-253 | SU-116 -> S1C-116 |
| SU-117 | SP-117 | SD-?? | #### (2) AX조직의 TRB: 중요성 증대와 동적화 | 125-127 | SU-117 -> S1C-117 |
| SU-118 | SP-118 | SD-?? | #### (1) 봇에 의한 TR의 보완, 증강, 추가 | 54-54 | SU-118 -> S1C-118 |
| SU-119 | SP-119 | SD-?? | 로컬 환경과 네트워크 환경 (bold subhead in chapter intro, before "### 1)") | 32-51 | SU-119 -> S1C-119 |
| SU-120 | SP-120 | SD-?? | ### 1) 공통 컨텍스트와 거버넌스 컨텍스트 | 57-148 | SU-120 -> S1C-120 |
| SU-121 | SP-121 | SD-?? | 공통 컨텍스트와 산출물 표준화 (bold subhead under "#### (1)") | 83-93 | SU-121 -> S1C-121 |
| SU-122 | SP-122 | SD-?? | #### (3) 거버넌스 컨텍스트와 AI 거버넌스 | 182-238 | SU-122 -> S1C-122 |
| SU-123 | SP-123 | SD-?? | #### (3) 거버넌스 컨텍스트와 AI 거버넌스 | 225-238 | SU-123 -> S1C-123 |
| SU-124 | SP-124 | SD-?? | AI 거버넌스 (bold subhead under "#### (3)") | 240-248 | SU-124 -> S1C-124 |
| SU-125 | SP-125 | SD-?? | ### 2) 지식사슬 | 250-303 | SU-125 -> S1C-125 |
| SU-126 | SP-126 | SD-?? | ### 2) 지식사슬 (각주 50) | 264 | SU-126 -> S1C-126 |
| SU-127 | SP-127 | SD-?? | 지식사슬의 기능 (bold subhead under "#### (1)") | 305-343 | SU-127 -> S1C-127 |
| SU-128 | SP-128 | SD-?? | #### (1) AI 시대 지식사슬의 필요성 | 282-343 | SU-128 -> S1C-128 |
| SU-129 | SP-129 | SD-?? | 지식사슬의 기능 (bold subhead under "#### (1)") | 344, 381 | SU-129 -> S1C-129 |
| SU-130 | SP-130 | SD-?? | #### (1) AI 시대 지식사슬의 필요성 (지식사슬의 기능) | 344-348 | SU-130 -> S1C-130 |
| SU-131 | SP-131 | SD-?? | #### (2) AI 시대 인간을 지키는 구조 | 384-432 | SU-131 -> S1C-131 |
| SU-132 | SP-132 | SD-?? | 실패는 성공의 어머니: 공통/거버넌스 컨텍스트와 지식경영 (bold subhead under "#### (2)") | 434-442 | SU-132 -> S1C-132 |
| SU-133 | SP-133 | SD-?? | #### (3) 지식행동사슬 | 444-562 | SU-133 -> S1C-133 |
| SU-134 | SP-134 | SD-?? | 지식행동사슬; 스킬을 중심으로 움직인다 (bold subhead under "#### (3)") | 518-536 | SU-134 -> S1C-134 |
| SU-135 | SP-135 | SD-?? | 지식행동사슬; 스킬을 중심으로 움직인다 (bold subhead under "#### (3)") | 526-536 | SU-135 -> S1C-135 |
| SU-136 | SP-136 | SD-?? | #### (4) 지식행동사슬의 효과 (비용 감소); 각주 48 | 26, 603-605 | SU-136 -> S1C-136 |
| SU-137 | SP-137 | SD-?? | 인간과 봇의 증강 (bold subhead under "#### (4)") | 569-587 | SU-137 -> S1C-137 |
| SU-138 | SP-138 | SD-?? | #### (4) 지식행동사슬의 효과 | 655-657 | SU-138 -> S1C-138 |
| SU-139 | SP-139 | SD-?? | #### (4) 지식행동사슬의 효과 | 682 | SU-139 -> S1C-139 |
| SU-140 | SP-140 | SD-?? | ### 3) 공통/거버넌스 컨텍스트 기반 AX조직의 의사소통 (증강인간과 증강 발화) | 692-744 | SU-140 -> S1C-140 |
| SU-141 | SP-141 | SD-?? | 증강인간과 증강 발화 (bold subhead under "#### (1)") | 715-744 | SU-141 -> S1C-141 |
| SU-142 | SP-142 | SD-?? | #### (2) 공통/의사소통/거버넌스 컨텍스트의 구분 | 713, 777-783 | SU-142 -> S1C-142 |
| SU-143 | SP-143 | SD-?? | #### (2) 공통/의사소통/거버넌스 컨텍스트의 구분 | 748-767 | SU-143 -> S1C-143 |
| SU-144 | SP-144 | SD-?? | #### (3) 구성원 유형별 의사소통 | 785-871 | SU-144 -> S1C-144 |
| SU-145 | SP-145 | SD-?? | #### (3) 구성원 유형별 의사소통 (AH-H 간 의사소통) | 808-818 | SU-145 -> S1C-145 |
| SU-146 | SP-146 | SD-?? | #### (3) 구성원 유형별 의사소통 (AH-AH 간 의사소통) | 830-840 | SU-146 -> S1C-146 |
| SU-147 | SP-147 | SD-?? | #### (3) 구성원 유형별 의사소통 (AH-AH 간 의사소통) | 842-851 | SU-147 -> S1C-147 |
| SU-148 | SP-148 | SD-?? | #### (3) 구성원 유형별 의사소통 (AH-AH 간 의사소통) | 855-871 | SU-148 -> S1C-148 |
| SU-149 | SP-149 | SD-?? | #### (1) AI의 예측지능 | 15-25 | SU-149 -> S1C-149 |
| SU-150 | SP-150 | SD-?? | #### (1) AI의 예측지능 | 23-87 | SU-150 -> S1C-150 |
| SU-151 | SP-151 | SD-?? | #### (1) AI의 예측지능 | 25-66 | SU-151 -> S1C-151 |
| SU-152 | SP-152 | SD-?? | #### (1) AI의 예측지능 | 25-85 | SU-152 -> S1C-152 |
| SU-153 | SP-153 | SD-?? | #### (1) AI의 예측지능 | 68-87 | SU-153 -> S1C-153 |
| SU-154 | SP-154 | SD-?? | #### (1) AI의 예측지능 | 87-87 | SU-154 -> S1C-154 |
| SU-155 | SP-155 | SD-?? | #### (1) AI의 예측지능 | 87-87 | SU-155 -> S1C-155 |
| SU-156 | SP-156 | SD-?? | #### (2) AI 기반 계급화 | 89-146 | SU-156 -> S1C-156 |
| SU-157 | SP-157 | SD-?? | #### (2) AI 기반 계급화 | 101-103 | SU-157 -> S1C-157 |
| SU-158 | SP-158 | SD-?? | #### (2) AI 기반 계급화 | 105-136 | SU-158 -> S1C-158 |
| SU-159 | SP-159 | SD-?? | #### (2) AI 기반 계급화 | 168-186 | SU-159 -> S1C-159 |
| SU-160 | SP-160 | SD-?? | #### (1) ESG 확장의 내용과 근거 | 378-386 | SU-160 -> S1C-160 |
| SU-161 | SP-161 | SD-?? | ### 2) 포용전환 AX | 190-211 | SU-161 -> S1C-161 |
| SU-162 | SP-162 | SD-?? | #### (1) 효율성 중심 AX의 한계와 포용전환 | 200-221 | SU-162 -> S1C-162 |
| SU-163 | SP-163 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 227-231 | SU-163 -> S1C-163 |
| SU-164 | SP-164 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 237-239 | SU-164 -> S1C-164 |
| SU-165 | SP-165 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 239-239 | SU-165 -> S1C-165 |
| SU-166 | SP-166 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 241-241 | SU-166 -> S1C-166 |
| SU-167 | SP-167 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 243-243 | SU-167 -> S1C-167 |
| SU-168 | SP-168 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 249-274 | SU-168 -> S1C-168 |
| SU-169 | SP-169 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 251-272 | SU-169 -> S1C-169 |
| SU-170 | SP-170 | SD-?? | #### (2) 맥락자본의 사회화와 책임운영체계의 구축 | 253-272 | SU-170 -> S1C-170 |
| SU-171 | SP-171 | SD-?? | ### 3) AI 시대 ESG 개념의 확장 | 276-334 | SU-171 -> S1C-171 |
| SU-172 | SP-172 | SD-?? | ### 3) AI 시대 ESG 개념의 확장 | 292-300 | SU-172 -> S1C-172 |
| SU-173 | SP-173 | SD-?? | ### 3) AI 시대 ESG 개념의 확장 | 286-286 | SU-173 -> S1C-173 |
| SU-174 | SP-174 | SD-?? | ### 3) AI 시대 ESG 개념의 확장 | 288-290 | SU-174 -> S1C-174 |
| SU-175 | SP-175 | SD-?? | #### (1) ESG 확장의 내용과 근거 | 336-354 | SU-175 -> S1C-175 |
| SU-176 | SP-176 | SD-?? | #### (1) ESG 확장의 내용과 근거 | 340-354 | SU-176 -> S1C-176 |
| SU-177 | SP-177 | SD-?? | #### (1) ESG 확장의 내용과 근거 | 374-376 | SU-177 -> S1C-177 |
| SU-178 | SP-178 | SD-?? | #### (1) ESG 확장의 내용과 근거 | 410-410 | SU-178 -> S1C-178 |
| SU-179 | SP-179 | SD-?? | #### (1) ESG 확장의 내용과 근거 | 412-412 | SU-179 -> S1C-179 |
| SU-180 | SP-180 | SD-?? | #### (1) ESG 확장의 내용과 근거 | 400-408 | SU-180 -> S1C-180 |
| SU-181 | SP-181 | SD-?? | #### (2) ESG 확장과 실행구조 | 485-494 | SU-181 -> S1C-181 |
| SU-182 | SP-182 | SD-?? | #### (2) ESG 확장과 실행구조 | 514-529 | SU-182 -> S1C-182 |
| SU-183 | SP-183 | SD-?? | #### (2) ESG 확장과 실행구조 | 531-548 | SU-183 -> S1C-183 |
| SU-184 | SP-184 | SD-?? | #### (3) 지식행동사슬과 ESG 확장 | 554-586 | SU-184 -> S1C-184 |
| SU-185 | SP-185 | SD-?? | #### (3) 지식행동사슬과 ESG 확장 | 568-572 | SU-185 -> S1C-185 |

### SourceAlignment / RequirementAtom / AbsorbedByExistingIdentity / IdentityCandidate — SCORED fields

**NOT-YET-PRODUCIBLE placeholders** (the scoring layer is not built; these are NOT hand-fabricated):

| slot | scored field | value |
|---|---|---|
| SourceAlignment | matchConfidence | NOT-YET-PRODUCIBLE |
| SourceAlignment | alignmentType | NOT-YET-PRODUCIBLE |
| SourceAlignment | A(u,r) | NOT-YET-PRODUCIBLE |
| RequirementAtom | Q(u) >= theta_req | NOT-YET-PRODUCIBLE |
| RequirementAtom | obligationType | NOT-YET-PRODUCIBLE |
| RequirementAtom | modality | NOT-YET-PRODUCIBLE |
| AbsorbedByExistingIdentity | (whole slot) | NOT-YET-PRODUCIBLE — the frozen registry is empty, so nothing could be absorbed even if scored |
| IdentityCandidate | IC(c) >= theta_identity | NOT-YET-PRODUCIBLE |

The RAW layer above IS produced; only the SCORED fields are deferred.

## Disposition rule applied at concept_recognition / candidate_adjudication / disposition_settlement

- **Arm 5-A (DROP)** — the corpus itself declines to adopt the referent, or it appears only as
  footnote etymology with no independent role.
- **Arm 5-B (candidate)** — claim_grounding attaches the grounding pointer; candidate_adjudication
  renders ONE verdict, OWNING duplicate/collapse resolution. Because the frozen registry is empty,
  its duplicate resolution operates over the harvested set itself:
  - **COLLAPSE** — the row denotes a referent already carried by a richer sibling row in this run;
    the richer row survives and the collapsed row's line ranges are merged onto it.
  - **MANUAL** — the referent is real but its own soundness/boundary is not settleable at Stage 1.
  - **KEEP** — settled identity candidate.
- The four source-link fields are stamped ONCE at corpus_harvesting (E6), pre-branch, and carried
  read-only onto EVERY row **including COLLAPSE and DROP**.

## C0 roster (KEEP + MANUAL) — one resolvable row per member

`C0 = FinalIdentityCandidate union ManualReviewCandidate`. RegistryCollapse rows are **NOT** in C0.

| Stage1CandidateID | NormalizedName (UPPER_SNAKE) | display name (한글 보존) | class | Stage1Status | SourceDocumentLinks | SourceUnitIDs | SourceProvenanceID | sourceLineRanges |
|---|---|---|---|---|---|---|---|---|
| S1C-001 | `AI_TRANSFORMATION` | AX (AI Transformation) | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-001 | SP-001 | 13-52 |
| S1C-002 | `DIGITAL_TRANSFORMATION` | DX (Digital Transformation) | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-002 | SP-002 | 13-37 |
| S1C-003 | `ROBOT_TRANSFORMATION` | RX (Robot Transformation) | CONCEPT | MANUAL | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-003 | SP-003 | 13-13 (also Ch.2 line 17) |
| S1C-004 | `ORGANIZATIONAL_AX` | 조직AX | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-004 | SP-004 | 15-145 |
| S1C-005 | `AX_ORGANIZATION` | AX조직 | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-005 | SP-005 | 15-24 |
| S1C-006 | `PERSONAL_AX` | 개인AX | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-006 | SP-006 | 24-125 |
| S1C-007 | `AX_INDIVIDUAL` | AX개인 | CONCEPT | MANUAL | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-007 | SP-007 | 21-24 |
| S1C-008 | `AI_GENERATION_STAGES` | AI 4.0 (Organizational AI) / AI 세대구분 | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-008 | SP-008 | 58-69 |
| S1C-009 | `LLM_LAYERED_ARCHITECTURE` | LLM 체계도 (1~4/5층 아키텍처) | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-009 | SP-009 | 147-171 |
| S1C-010 | `SECOND_LLM` | 제2의 LLM (제1·제2·제3의 LLM) | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-010 + SU-136 + SU-155 | SP-010 | 151-185 ; SD-??:26, 603-605 ; SD-??:87-87 |
| S1C-014 | `DOMAIN_CONTEXT` | 도메인 컨텍스트 (Domain Context) | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-014 + SU-138 | SP-014 | 248-256 ; SD-??:655-657 |
| S1C-015 | `ORG_AX_OS` | 조직AX용 OS | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-015 | SP-015 | 187-276 |
| S1C-016 | `ORG_AX_OS_CONDITIONS` | 조직AX용 OS 필요조건·추가조건 | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-016 | SP-016 | 187-214 |
| S1C-017 | `ORGANIZATIONAL_DIGITAL_TWIN` | Organizational Digital Twin (ODT) | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-017 | SP-017 | 203-214 |
| S1C-018 | `AI_SOVEREIGNTY` | AI 주권 (Sovereignty) | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-018 | SP-018 | 210-230 |
| S1C-019 | `OPERATING_PROTOCOLS` | 운영규범 (Operating Protocols & Control Standards) | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-019 | SP-019 | 198-208 |
| S1C-021 | `AX_CORE_INDICES` | GP사 5대 핵심 지표 (지표 기반 운영) | INDEX | MANUAL | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-021 | SP-021 | 261-265 |
| S1C-022 | `HUMAN_MEMBER` | H: 인간 (Human) | ROLE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-022 + SU-065 | SP-022 | 288-291 ; SD-??:273, 302, 314 |
| S1C-025 | `BOT_MEMBER` | B: 봇 (Bot) | ROLE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-025 + SU-066 | SP-025 | 306-335 ; SD-??:273, 524-539 |
| S1C-026 | `AGENT_AUTONOMY_TAXONOMY` | AI agent / Subagent / Bot 자율성 분류 | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-026 | SP-026 | 349-363 |
| S1C-027 | `AUGMENTATION` | 증강 (Augmentation) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-027 | SP-027 | 219-244 (introduced Ch.1 286) |
| S1C-029 | `COOPERATION_TYPES` | 협력 유형 (H+B / H+AH / AH+B / AH+AB) | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-029 | SP-029 | 365-391 |
| S1C-030 | `HYBRID_ORGANIZATION` | 진정한 AX조직 / 하이브리드 조직 (AH+AB) | CONCEPT | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-030 | SP-030 | 316-431 |
| S1C-031 | `HUMAN_AI_COLLABORATION_MODES` | 인간-AI 협력 방식 분류 (HITL / AI-in-the-loop / HOTL / Autonomous AI) | STRUCTURE | KEEP | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-031 | SP-031 | 393-427 |
| S1C-032 | `COLLABORATIVE_COGNITION_SYSTEM` | 협력적 인지체계 (Collaborative Cognition System) | CONCEPT | MANUAL | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-032 | SP-032 | 429-429 |
| S1C-033 | `CORE_MANAGEMENT_SPIRITS` | 경영 기본철학·핵심정신 체계 (기본전제 + 3정신) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-033 | SP-033 | 5-9, 211-217, 270 |
| S1C-034 | `HUMAN_CENTRALITY` | 인간중심주의 (Human Centrality) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-034 | SP-034 | 215-217 |
| S1C-035 | `DIVERSITY` | 다양성 (Diversity) 존중과 활용 | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-035 | SP-035 | 246-264 (introduced Ch.1 280 '다양성의 증폭') |
| S1C-036 | `SUPPLEMENTARY_FIT` | 유사적합성 (Supplementary Fit) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-036 + SU-101 | SP-036 | 250-268 ; SD-??:120-122 |
| S1C-037 | `COMPLEMENTARY_FIT` | 보완적 적합성 (Complementary Fit) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-037 + SU-100 | SP-037 | 266-288 ; SD-??:120-124 |
| S1C-038 | `ROLE_DIVERSITY` | 역할 중심(직무 대비)·역할 다양성 (Role Diversity) | CONCEPT | MANUAL | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-038 | SP-038 | 262-262 (also Ch.1 385, 429) |
| S1C-039 | `HONBIBAEKSAN_PREVENTION` | 혼비백산(魂飛魄散) 방지 (영·혼·백) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-039 | SP-039 | 292-402 |
| S1C-040 | `HUMAN_REACTION_LAYERS` | AX조직 전환 인간반응 4층위 (생존·능력·관계·존재) | STRUCTURE | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-040 | SP-040 | 49-57 |
| S1C-041 | `INDIVIDUAL_REACTION_TYPES` | 개별적 인간 반응·반발 유형 (5형) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-041 | SP-041 | 59-69 |
| S1C-042 | `COLLECTIVE_REACTION_TYPES` | 집단적 인간 반응·반발 유형 (5형) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-042 | SP-042 | 71-83 |
| S1C-043 | `REACTION_VALENCE_TYPES` | AI 발달 반응의 긍정/부정 축 (기술숭배형·증강기대형) | CONCEPT | MANUAL | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-043 | SP-043 | 33-33 (also 85) |
| S1C-044 | `AX_ORG_STRESS` | AX조직 스트레스 (4대 위험: 정체성·신뢰·통제·책임) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-044 | SP-044 | 89-209 |
| S1C-045 | `HUMAN_STRESS_TYPES` | 인간 스트레스 유형 (5형) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-045 | SP-045 | 97-107 |
| S1C-046 | `BOT_STRESS_TYPES` | 봇 스트레스 유형 (5형) | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-046 | SP-046 | 109-121 |
| S1C-047 | `HUMAN_VS_BOT_STRESS` | 인간 스트레스 vs 봇 스트레스 비교 | STRUCTURE | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-047 | SP-047 | 123-137 |
| S1C-048 | `INTERACTION_STRESS` | 관계(상호작용) 스트레스 | CONCEPT | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-048 | SP-048 | 139-139 |
| S1C-049 | `STRESS_BY_COOPERATION_TYPE` | 협력 유형별 스트레스 (H+B/H+AH/AH+B/AH+AB) | STRUCTURE | KEEP | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-049 | SP-049 | 141-205 |
| S1C-051 | `META_MANAGER` | 메타관리자 (Meta-manager) | ROLE | MANUAL | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-051 | SP-051 | 103-103 |
| S1C-052 | `PHYSICAL_AI` | physical AI (PI) | CONCEPT | MANUAL | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-052 | SP-052 | 288-288 (also Ch.1 314; Ch.2 footnote 311) |
| S1C-053 | `AX_TALENT_SURVIVAL_COMPETENCY` | AX조직 인재의 필요조건 (살아남는 인간의 역량) | CONCEPT | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-053 | SP-053 | 29-49 |
| S1C-054 | `AX_TALENT_SUCCESS_COMPETENCY` | AX조직 인재의 추가조건 (성공하는 리더의 역량) | CONCEPT | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-054 | SP-054 | 51-99 |
| S1C-055 | `AX_TALENT_THREE_RESPONSIBILITIES` | AX조직 인재의 3가지 책임 (맥락·판단·증거) | STRUCTURE | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-055 | SP-055 | 158-176 |
| S1C-056 | `AX_TALENT_EIGHT_ROLES` | AX조직 인재의 역할 8가지 | STRUCTURE | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-056 | SP-056 | 207-283 |
| S1C-057 | `AX_TALENT_FIVE_CORE_ROLES` | AX조직 인재의 5가지 핵심 역할 (조형자·구현자·검증자·운영자·조정자) | STRUCTURE | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-057 | SP-057 | 284-316 (also 358-376) |
| S1C-058 | `AI_ERA_ROLE_THEORY` | AI 시대 역할론 (일·기여·역할의 재정의) | CONCEPT | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-058 | SP-058 | 318-380 |
| S1C-059 | `BELBIN_ROLE_THEORY` | Belbin의 역할론 | METHOD | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-059 | SP-059 | 358-380 |
| S1C-060 | `HUMAN_AI_ORCHESTRATION` | 인간-AI 오케스트레이션 (orchestration) | CONCEPT | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-060 | SP-060 | 53, 67, 108 |
| S1C-061 | `HUMANITY_PROTECTION` | 인간성 수호 (humanity) | PRINCIPLE | KEEP | `_input/_document/03_2부_3장_AX조직_인재의_역량역할과_리더십.md` | SU-061 | SP-061 | 63 |
| S1C-063 | `AUGMENTED_HUMAN` | 증강인간 (AH) | ROLE | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-063 + SU-023 + SU-140 | SP-063 | 343-373 (built indirectly in ch3) ; SD-??:294-316 (also Ch.2 238-240) ; SD-??:692-744 |
| S1C-064 | `AUGMENTED_BOT` | 증강봇 (AB) | ROLE | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-064 + SU-024 | SP-064 | 514-576 ; SD-??:300-314 (also Ch.2 242) |
| S1C-067 | `BOT_SOCIALITY` | 봇의 사회성 | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-067 | SP-067 | 7-60 |
| S1C-068 | `BOT_ETHICS` | 봇의 윤리성 | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-068 | SP-068 | 62-99 |
| S1C-069 | `AI_ETHICS_STANDARDS_TYPOLOGY` | AI 윤리기준의 유형 (UNESCO·OECD·EU AI Act·IEEE·한국정부) | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-069 | SP-069 | 66-89 |
| S1C-070 | `CLAUDE_CONSTITUTION` | Claude 헌법 (Claude Constitution) | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-070 | SP-070 | 87-89 |
| S1C-071 | `AX_ETHICS_CONDITIONS` | 조직AX 윤리의 필요조건과 추가조건 | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-071 | SP-071 | 91-99 |
| S1C-072 | `THREE_LAWS_OF_ROBOTICS` | 로봇 3원칙 (three laws of robotics) | PRINCIPLE | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-072 | SP-072 | 107-113 |
| S1C-073 | `HUMAN_RESPECT_INTERNALIZATION` | 인간존중의 내재화 | PRINCIPLE | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-073 | SP-073 | 105-134 |
| S1C-074 | `HUMAN_RESPECT_TECHNICAL_DEFINITION` | 인간존중의 기술적 정의 (4가지) | STRUCTURE | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-074 | SP-074 | 117-122 |
| S1C-075 | `HUMAN_RESPECT_FIVE_STAGE_ARCHITECTURE` | 인간존중 구현 5단계 아키텍처 | METHOD | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-075 | SP-075 | 124-134 |
| S1C-076 | `BOT_UNDERSTANDING_HUMANS` | 봇의 인간 특성 이해 (socially compatible system) | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-076 | SP-076 | 136-146 |
| S1C-077 | `HUMAN_UNDERSTANDING_BOTS` | 인간의 봇 특성 이해 (패턴 탐지기 / 기능적 만족·욕구) | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-077 | SP-077 | 148-243 |
| S1C-078 | `BOT_HIERARCHY` | 봇들 간의 위계 형성 (Level 1-4) | STRUCTURE | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-078 | SP-078 | 245-269 |
| S1C-079 | `HBRM` | HBRM (인간-봇 자원관리) | METHOD | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-079 + SU-028 | SP-079 | 271-341 ; SD-??:320-337 |
| S1C-080 | `HBRM_3M` | HBRM의 3M (method·meaning·measurement) | METHOD | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-080 + SU-095 | SP-080 | 273 ; SD-??:7-7 |
| S1C-081 | `AH_MEASUREMENT_FIVE_INDICATORS` | 증강인간 측정: AH 5대 지표 | INDEX | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-081 | SP-081 | 377-397 |
| S1C-082 | `HUMAN_AUGMENTATION_STAGES` | 인간 증강 단계 (H0~AH3) | STRUCTURE | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-082 | SP-082 | 405-417 |
| S1C-083 | `AI_UTILIZATION` | AI 활용력 (AIU, AI Utilization) | INDEX | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-083 | SP-083 | 417-454 |
| S1C-084 | `AUGMENTATION_QUOTIENT` | 증강지수 (AQ, Augmentation Quotient) | INDEX | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-084 | SP-084 | 456-464 |
| S1C-085 | `AUGMENTED_HUMAN_INDEX` | 증강인간지수 (AHI) | INDEX | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-085 | SP-085 | 466-474 |
| S1C-086 | `AUGMENTED_HUMAN_CAPABILITY_INDEX` | 증강인간 역량지수 (AHCI, Augmented Human Capability Index) | INDEX | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-086 + SU-113 | SP-086 | 476-506 ; SD-??:231-249 |
| S1C-088 | `AH_AB_COLLABORATION` | 증강인간과 증강봇의 협력 | CONCEPT | KEEP | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-088 | SP-088 | 578-617 |
| S1C-089 | `COMMON_AND_GOVERNANCE_CONTEXT` | 공통 컨텍스트 & 거버넌스 컨텍스트 | STRUCTURE | MANUAL | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-089 | SP-089 | ch4 582-611 (also ch3 line 71) |
| S1C-090 | `TEAM_ROLE_BALANCE` | 팀역할균형 (TRB, Team Role Balance) | CONCEPT | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-090 + SU-062 + SU-050 | SP-090 | 110-118 ; SD-??:ch4 324-341 (also ch3 line 67, 77) ; SD-??:189-191 |
| S1C-091 | `TEAM_ROLE` | 팀역할 (TR, Team Role) | CONCEPT | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-091 | SP-091 | 43-53 |
| S1C-092 | `FUNCTIONAL_ROLE` | 기능역할 (functional role) | CONCEPT | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-092 | SP-092 | 15-17 |
| S1C-093 | `BELBIN_NINE_TEAM_ROLES` | Belbin의 9가지 팀역할 유형 (창조자PL·냉철판단자ME·지휘조절자CO·실행자IMP·완결자CF·자원탐색가RI·분위기조성자TW·추진자SH·전문가SP) | ROLE | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-093 | SP-093 | 30-40 |
| S1C-094 | `TEAM_ROLE_LEVELS` | 팀역할 발휘 3수준 (자연역할/팀역할·잠재역할/관리가능역할·비선호역할) | STRUCTURE | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-094 | SP-094 | 93-108 |
| S1C-096 | `INTERPLACE` | Interplace | METHOD | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-096 | SP-096 | 138-142 |
| S1C-097 | `INTERPLACE_QUESTIONNAIRES` | Interplace 4종 설문지 (자기진단지SPI·관찰자진단지OA·직무요구진단지JRE·직무관찰자진단지JOA) | METHOD | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-097 | SP-097 | 142-142 |
| S1C-098 | `GROUP_COHESIVENESS` | 집단응집성 (group cohesiveness) | INDEX | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-098 | SP-098 | 39-55 |
| S1C-099 | `TEAMWORK_TWO_ASPECTS` | 팀웍의 두 측면 (인간적 유대감 & 업무적 활성화) | CONCEPT | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-099 | SP-099 | 39-41 |
| S1C-102 | `BEHAVIOR_TYPE` | 행동유형 (behavior type) vs 성격유형 (personality type) | CONCEPT | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-102 | SP-102 | 48-51 |
| S1C-103 | `COMPETENCE_BASED_HRM` | CBHRM (Competence-Based HRM, 역량주의) | CONCEPT | MANUAL | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-103 | SP-103 | 214-214 |
| S1C-104 | `ROLE_BASED_HRM` | RBHRM (Role-Based HRM, 역량+역할주의) | CONCEPT | KEEP | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-104 | SP-104 | 214-214 |
| S1C-105 | `DIVERSITY_MANAGEMENT` | 다양성 관리 (diversity management) | CONCEPT | MANUAL | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-105 | SP-105 | 206-210 |
| S1C-106 | `BOT_TR_COMPLEMENTATION_AUGMENTATION_ADDITION` | 봇에 의한 TR의 보완·증강·추가 | METHOD | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-106 | SP-106 | 25-78 |
| S1C-107 | `AX_NEW_ROLES` | AX 신규 역할 (AI Governor·AI Auditor·Prompt Architect·AI Workflow Orchestrator·Human Meaning Integrator·Trust Manager·Provenance Controller) | ROLE | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-107 | SP-107 | 69-78 |
| S1C-108 | `DYNAMIC_ROLE_BALANCE` | 동적 역할균형 (dynamic role balance) | CONCEPT | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-108 | SP-108 | 114-123 |
| S1C-109 | `BOT_AIDED_TRB` | Bot-Aided TRB (봇 보조 TRB, 수직관계) | STRUCTURE | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-109 | SP-109 | 133-154 |
| S1C-110 | `HUMAN_BOT_COUPLED_TRB` | Human-Bot Coupled TRB (인간-봇 결합 TRB, 수평관계) | STRUCTURE | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-110 | SP-110 | 156-189 |
| S1C-111 | `TRB_EVOLUTION_PATH` | TRB 진화 경로 (Human-only → Bot-aided → Human-bot coupled → Autonomous hybrid TRB) | STRUCTURE | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-111 | SP-111 | 191-191 |
| S1C-112 | `ARBI` | 증강 역할균형 지수 (ARBI, Augmented Role Balance Index) | INDEX | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-112 + SU-087 | SP-112 | 197-211 ; SD-??:533, 600 |
| S1C-114 | `ARBI_TEN_AXES` | ARBI 10개 평가 축 (역할균형·보완적 적합성·AI 개입 투명성·발화 주체성·권한·동의 경계·인간 책임성·의사소통 공정성·기록·추적성·심리·신뢰 안정성·조작 위험) | STRUCTURE | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-114 | SP-114 | 271-285 |
| S1C-115 | `HUMAN_BOT_ROLE_MANAGEMENT` | HBRM (Human-Bot Role Management) | CONCEPT | KEEP | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-115 | SP-115 | 13-13 |
| S1C-116 | `TWO_M` | 2M (측정 tool과 증진 방안) | METHOD | MANUAL | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-116 | SP-116 | 253-253 |
| S1C-117 | `HATCH_AX` | Hatch AX (Belbin Korea의 AI지원 TRB) | METHOD | MANUAL | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-117 | SP-117 | 125-127 |
| S1C-119 | `LOCAL_AND_NETWORK_ENVIRONMENT` | 로컬 환경 / 네트워크 환경 | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-119 | SP-119 | 32-51 |
| S1C-120 | `COMMON_CONTEXT` | 공통 컨텍스트 (common context) | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-120 + SU-012 + SU-169 | SP-120 | 57-148 ; SD-??:157-171 (also 234, 248-256) ; SD-??:251-272 |
| S1C-121 | `OUTPUT_STANDARDIZATION` | 산출물 표준화 | CONCEPT | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-121 | SP-121 | 83-93 |
| S1C-122 | `GOVERNANCE_CONTEXT` | 거버넌스 컨텍스트 (governance context) | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-122 + SU-013 + SU-170 | SP-122 | 182-238 ; SD-??:157-185 (also 234, 303) ; SD-??:253-272 |
| S1C-123 | `AI_GOVERNANCE_STANDARDS` | AI 거버넌스 국제표준 (ISO/IEC 42001 · NIST AI RMF · EU AI Act) | STRUCTURE | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-123 | SP-123 | 225-238 |
| S1C-124 | `AI_GOVERNANCE` | AI 거버넌스 | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-124 + SU-020 | SP-124 | 240-248 ; SD-??:141-141 (also 200, 303) |
| S1C-125 | `KNOWLEDGE_CHAIN` | 지식사슬 (knowledge chain) | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-125 + SU-011 + SU-152 | SP-125 | 250-303 ; SD-??:155-171 (also 199, 234) ; SD-??:25-85 |
| S1C-127 | `KNOWLEDGE_CHAIN_FUNCTIONS` | 지식사슬의 기능 (4대 기능) | METHOD | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-127 | SP-127 | 305-343 |
| S1C-128 | `MEANING_COGNITIVE_DISTANCE` | 의미·인지 거리 | INDEX | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-128 | SP-128 | 282-343 |
| S1C-129 | `COGNITIVE_SPEED` | 인지 속도 | INDEX | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-129 | SP-129 | 344, 381 |
| S1C-130 | `AI_CONTRIBUTION` | AI 기여도 | INDEX | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-130 | SP-130 | 344-348 |
| S1C-131 | `HUMAN_PROTECTING_STRUCTURE` | AI 시대 인간을 지키는 구조 | CONCEPT | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-131 | SP-131 | 384-432 |
| S1C-132 | `KNOWLEDGE_MANAGEMENT` | 지식경영 / 학습조직 | CONCEPT | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-132 | SP-132 | 434-442 |
| S1C-133 | `KNOWLEDGE_ACTION_CHAIN` | 지식행동사슬 (지식(행동)사슬, knowledge behavior chain) | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-133 + SU-184 | SP-133 | 444-562 ; SD-??:554-586 |
| S1C-134 | `SKILL` | 스킬 (skill) | CONCEPT | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-134 | SP-134 | 518-536 |
| S1C-135 | `SKILL_RUNTIME` | SkillRuntime | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-135 | SP-135 | 526-536 |
| S1C-137 | `HUMAN_BOT_AUGMENTATION` | 인간과 봇의 증강 (H→AH · B→AB, 공진화) | CONCEPT | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-137 | SP-137 | 569-587 |
| S1C-139 | `KNOWLEDGE_ACTION_NODE_ONTOLOGY` | 지식행동사슬 노드 온톨로지 (identity·goal·knowledge·method·skill·task·artifact) | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-139 | SP-139 | 682 |
| S1C-141 | `AUGMENTED_UTTERANCE` | 증강 발화 | CONCEPT | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-141 | SP-141 | 715-744 |
| S1C-142 | `THREE_LAYER_CONTEXT_ARCHITECTURE` | 공통·의사소통·거버넌스 3계층 컨텍스트 구조 | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-142 | SP-142 | 713, 777-783 |
| S1C-143 | `COMMUNICATION_CONTEXT` | 의사소통 컨텍스트 | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-143 | SP-143 | 748-767 |
| S1C-144 | `COMMUNICATION_BY_MEMBER_TYPE` | 구성원 유형별 의사소통 (AH-H · AH-AH) | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-144 | SP-144 | 785-871 |
| S1C-145 | `ROLE_VACANCY` | 역할 공백 | CONCEPT | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-145 | SP-145 | 808-818 |
| S1C-146 | `AUGMENTATION_POWER` | 증강력 | CONCEPT | MANUAL | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-146 | SP-146 | 830-840 |
| S1C-147 | `CONTRIBUTION_CONFLICT` | 기여 충돌 | CONCEPT | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-147 | SP-147 | 842-851 |
| S1C-148 | `AUGMENTED_COMMUNICATION_PATHS` | 증강인간 간 의사소통 3경로 (인간 중심 · AI 중심 · 거버넌스 경유) | STRUCTURE | KEEP | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-148 | SP-148 | 855-871 |
| S1C-149 | `PREDICTIVE_INTELLIGENCE` | AI 예측지능 | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-149 | SP-149 | 15-25 |
| S1C-150 | `PREDICTIVE_INTELLIGENCE_SYSTEM` | AI 예측지능 체계 / 예측지능 스택 | STRUCTURE | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-150 | SP-150 | 23-87 |
| S1C-151 | `WORLD_MODEL` | 월드 모델 | STRUCTURE | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-151 | SP-151 | 25-66 |
| S1C-153 | `CONTEXT_DESIGN` | 컨텍스트 설계 | METHOD | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-153 | SP-153 | 68-87 |
| S1C-154 | `CONTEXT_DESIGNER` | 컨텍스트 설계자 (컨텍스트 설계형 AX 인재) | ROLE | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-154 | SP-154 | 87-87 |
| S1C-156 | `AI_BASED_STRATIFICATION` | AI 기반 계급화 (AI 계급사회 / AI 기반 계층화) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-156 | SP-156 | 89-146 |
| S1C-157 | `KNOWLEDGE_CAPITAL` | 지식자본 / 지식자본화 | CONCEPT | MANUAL | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-157 | SP-157 | 101-103 |
| S1C-158 | `AI_STRATIFICATION_SEVEN_GAPS` | AI 기반 계급화를 만드는 7가지 격차 | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-158 | SP-158 | 105-136 |
| S1C-159 | `AI_LABOR_TYPOLOGY` | AI 시대 노동 분화 4유형 | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-159 | SP-159 | 168-186 |
| S1C-160 | `ALGORITHMIC_MANAGEMENT` | 알고리즘 관리 | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-160 | SP-160 | 378-386 |
| S1C-161 | `INCLUSIVE_TRANSFORMATION_AX` | 포용전환 AX | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-161 | SP-161 | 190-211 |
| S1C-162 | `EFFICIENCY_CENTERED_AX` | 효율성 중심 AX | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-162 | SP-162 | 200-221 |
| S1C-163 | `CONTEXT_CAPITAL_SOCIALIZATION` | 맥락자본의 사회화 | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-163 | SP-163 | 227-231 |
| S1C-164 | `CONTEXT_CAPITAL` | 맥락자본 (Context Capital) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-164 | SP-164 | 237-239 |
| S1C-165 | `CONTEXT_ACCESS_RIGHT` | 맥락자본 접근권 (맥락 접근권) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-165 | SP-165 | 239-239 |
| S1C-166 | `CONTEXT_JUSTICE` | 맥락 정의 (Context Justice) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-166 | SP-166 | 241-241 |
| S1C-167 | `AI_CAPABILITY_EQUALITY` | AI 역량 평등론 | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-167 | SP-167 | 243-243 |
| S1C-168 | `RESPONSIBLE_OPERATING_SYSTEM` | 책임운영체계 | STRUCTURE | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-168 | SP-168 | 249-274 |
| S1C-171 | `ESG_EXTENSION` | AI 시대 ESG 개념의 확장 (확장 ESG) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-171 | SP-171 | 276-334 |
| S1C-172 | `ESG_EXTENSION_THEORY` | ESG 확장론 | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-172 | SP-172 | 292-300 |
| S1C-173 | `AI_ESG_TWO_PERSPECTIVES` | AI-ESG 관계의 두 관점 (AI for ESG / ESG for AI) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-173 | SP-173 | 286-286 |
| S1C-174 | `RESPONSIBLE_AI` | 책임감 있는 인공지능 (Responsible AI, RAI) | CONCEPT | MANUAL | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-174 | SP-174 | 288-290 |
| S1C-175 | `INCLUSIVE_AI_TRANSITION_ESG` | AI 포용전환 ESG (Inclusive / Just AI Transition ESG) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-175 | SP-175 | 336-354 |
| S1C-176 | `INCLUSIVE_AI_TRANSITION_ESG_FOUR_LAYERS` | AI 포용전환 ESG의 네 층위 | STRUCTURE | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-176 | SP-176 | 340-354 |
| S1C-177 | `TURING_TRAP` | 튜링 함정 (Turing Trap) | CONCEPT | MANUAL | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-177 | SP-177 | 374-376 |
| S1C-178 | `CAPABILITY_APPROACH` | 역량 접근법 (Capability Approach) | CONCEPT | MANUAL | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-178 | SP-178 | 410-410 |
| S1C-179 | `DIFFERENCE_PRINCIPLE` | 차등 원칙 (Difference Principle) | CONCEPT | MANUAL | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-179 | SP-179 | 412-412 |
| S1C-180 | `JUST_TRANSITION` | 공정전환 (Just Transition) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-180 | SP-180 | 400-408 |
| S1C-181 | `AI_ERA_PROTECTION_RIGHTS` | AI 시대 인간 보호 권리 (8대 권리) | CONCEPT | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-181 | SP-181 | 485-494 |
| S1C-182 | `ESG_EXECUTION_STRUCTURE` | ESG 실행 구조 (AI 포용전환 ESG 실행 모델, 9단계) | METHOD | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-182 | SP-182 | 514-529 |
| S1C-183 | `INCLUSIVE_TRANSITION_ESG_12_INDICATORS` | 포용전환 ESG 12지표 | INDEX | KEEP | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-183 | SP-183 | 531-548 |
| S1C-185 | `TOKEN_REDUCTION_ESG_INDICATOR` | 토큰 절감 (ESG 실행 지표) | INDEX | MANUAL | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-185 | SP-185 | 568-572 |

### C0 evidence + structural_role (per member)

| Stage1CandidateID | evidence (원문 인용, 한글 보존) | structural_role |
|---|---|---|
| S1C-001 | "AX는 DX의 대체어가 아니라, DX 이후 AI가 조직 운영의 중심으로 들어오면서 필요해진 확장 개념이다." | the master transformation paradigm the whole book is organized around (AI가 조직 운영의 중심으로 통합되는 전환) |
| S1C-002 | "DX가 업무와 시스템의 디지털화, 데이터화, 클라우드화, 프로세스 효율화에 초점을 맞췄다면, AX는 AI를 조직의 업무흐름, 판단체계, 역할구조 ... 안에 통합하는 전환이다." | predecessor paradigm used as the structural foil to AX; also layers 1–2 of the LLM 체계도 |
| S1C-003 | "물론 RX라는 표현도 이미 시작되고는 있지만, AX의 올바른 실현 없이는 (안전성이 보장되지 않아) RX가 불가능하기에" | successor (robot/physical) transformation gated on AX; positions AX as prerequisite |
| S1C-004 | "조직AX은 조직이 AX하는 과정이고 ... 조직AX는 조직 운영 자체를 AI 중심으로 재설계하는 것으로, 단순 AI의 도입 혹은 자동화와는 다르다." | the process of an organization transforming (unit=organization, phase=process); a whole-org redesign project |
| S1C-005 | "AX조직은 결과적으로 AX된 조직을 의미한다." | the resulting AI-transformed organization (unit=organization, phase=result); title concept of the chapter |
| S1C-006 | "개인AX는 도구 사용의 문제이지만, 조직AX는 조직 운영체계의 변화 문제이다." | individual-unit AX process, systematically contrasted with 조직AX (표: 개인AX vs 조직AX) |
| S1C-007 | "이러한 개인AX가 조직 내 많다고 하여 (혹은 AX개인이 조직 내 많다고 하여) 그 조직이 조직AX를 진행하고 AX조직이 실현되는 것은 아니다." | the individual-unit AX result cell in the 2×2 (적용단위 × 과정/결과) taxonomy |
| S1C-008 | "AI 1.0 ... AI 2.0 ... AI 3.0 ... AI 4.0 / Perceptional AI, Generative AI, Agentic AI, Organizational AI" | generational staging (paired with Web 1.0–4.0) that locates the book's domain at AI 4.0 = Organizational AI |
| S1C-009 | "이 체계도에서 1~2층은 DX의 영역이고, 1~4층이 AX의 영역이다. 현재 4층이 이미 세상에 나와 있다." | layered reference architecture mapping DX(1–2층)/AX(1–4층), locating 지식사슬 at 3층 (footnote adds 5층 = 제3의 LLM) |
| S1C-010 | "제 2의 LLM은 AI에게 기업 내에서 지켜야 할 규율과 맥락을 학습시켜 막대한 생성 능력을 통제가능한 성과 신뢰성으로 전환하기에 세대 구분의 타당성이 있다." | generational naming of LLMs (제1=범용 외부 LLM, 제2=컨텍스트 사슬 기업형 상위아키텍처, 제3=1~5층 합); core differentiator of the OS |
| S1C-014 | "도메인 컨텍스트는 그 기준을 실제 업무 단위에 맞게 구체화한 실행 구조다." | domain-level operationalization of common context into an executable structure (공통→도메인→스킬 도출→실행 흐름) |
| S1C-015 | "조직의 구성원인 인간·AI agent·bot들이 외부 LLM과 내부 조직 데이터의 활용을 기반으로 업무 프로세스를 통합적으로 운영·통제·증강하는 조직운영체계(operating system)이다." | the central organizational operating system enabling org AX; not a mere AI platform/chatbot integrator |
| S1C-016 | "조직AX용 OS라고 불리기 위해서는 최소한의 필요조건을 갖추어야 하고 ... 추가조건이 요구된다." | the component spec distinguishing necessary conditions (Operating protocols, Privacy & sovereignty, AI governance, Human-bot role architecture, Agent orchestration, Persistent organizational memory) vs additional (Common & Governance context, Knowledge chain, Complementary fit engine, Continuous learning, Provenance & verification, Organizational digital twin) |
| S1C-017 | "Organizational digital twin(ODT)은 '조직의 구조·역할·업무흐름·의사결정·협업·성과·문화까지를 디지털 공간에 동적으로 재현한 조직의 살아있는 가상 복제체'이다." | dynamic virtual replica of the org for simulation/prediction/optimization; the top additional condition |
| S1C-018 | "조직AX OS의 핵심은 '외부 AI를 활용하되 조직의 주권은 잃지 않는 것'이다." | data/AI sovereignty as a core OS necessary condition (Privacy & sovereignty); GP사 ZKP·EIP-7911 특허 근거 |
| S1C-019 | "핵심 요소는 '승인(authority & approval), 역할(role allocation), 데이터 접근권한(access control), 예외처리(exception handling), 기록(logging & traceability), 책임소재(accountability), escalation 체계, human override, audit trail'" | embedded operating-norm layer making AI act inside organizational rules; first necessary condition |
| S1C-021 | "AI가 조직 기준 안에서 실제로 제대로 작동하고 있는가를 5가지 핵심 지표로 확인한다." | measurement framework (5 core indices) for visualizing AX operational state; specific indices carried in figures (fig-020-003/004) |
| S1C-022 | "H: 인간(Human) 증강 안 된 인간 전통적 인간 구성원" | member type — non-augmented traditional human member (one of the 4 구성원 유형) |
| S1C-025 | "B: 봇(Bot) 증강 안 된 봇 특정 작업 자동화 중심 Bot" (defn eq.) "범용 AI(Tech) + 정체성(Identity) + 거버넌스(Governance) = 봇" | member type — non-augmented automation bot; the account/identity interface channel through which AI participates in the workspace (삼성 'digital worker' 등과 동의어) |
| S1C-026 | "AI agent란 ... '목표를 이해하고 스스로 계획하며 실행하는 자율적 AI 행위자'임에 비해, 봇은 '정해진 일을 자동 수행하는 디지털 노동자'" | taxonomy of digital workers by autonomy (AI agent > Subagent > Bot, or 상/중/하급 봇) across 자율성·목표설정·역할범위·의사결정·협업·기억 |
| S1C-027 | "증강은 인간의 미흡함을 봇으로 대체하는 것이 아니라, 인간과 봇이 공존하면서 서로의 역량을 키워 함께 성과를 내는 상호학습(mutual learning)과 공진화(co-evolution)의 과정이다." | first core spirit/principle — mutual (positive-sum) augmentation of both humans and bots; 인간 증강(신체·정신) + 봇 증강(맥락·가치·학습) |
| S1C-029 | "H + B (도구형 협력) ... H + AH (증강인간 중심 협력) ... AH + B (지능형 작업 분업) ... AH + AB (진정한 AX조직)" | typology of human-bot cooperation by member composition, each with 의미 + 실현 방법 (인간만·봇만 조직은 제외) |
| S1C-030 | "증강된 인간과 봇이 협력하는 조직 유형(AH + AB)이 '진정한 AX조직'이고, 이런 유형을 '하이브리드 조직'이라 칭한다." | the target/ideal organization form (수평 공동최적화); also framed as 'hybrid intelligent organization', a role-based continuously-learning org |
| S1C-031 | "Human-in-the-loop / AI-in-the-loop / Human-on-the-loop / Autonomous AI" (footnote: "MIT의 Sheridan(1992) ... HITL ... HOTL ... HOOTL")" | mode-based (자율성 정도) typology of human-AI collaboration; Gibbins(2025) + Sheridan(1992) lineage, analogized to 석사→박사→박사후→교수 |
| S1C-032 | "역할 중심으로 역할을 분담·공유하며, 상호 증강하면서, 공동 판단·학습하는 협력적 인지체계(collaborative cognition system)가 된다." | named characterization of the AH+AB working system (role-based, mutually augmenting, co-judging/learning) |
| S1C-033 | "증강, 다양성 존중과 활용, 보완적 적합성 추구라는 세 정신은 상호 보조적이며 셋이 모여야 완성체를 이룬다는 점에서 삼위일체와 비슷하다." | the organizing spine of Ch.2 §3 — one premise (인간중심주의) + three core spirits (증강/다양성/보완적적합성) as a trinity |
| S1C-034 | "인간의 존립과 발전에 해가 되는 AI와 AX는 배격하며, 해가 되는지 도움이 되는지 그 판단의 몫(주체) 또한 인간이다." | the base premise (기본 전제) underlying the three spirits; human as ultimate judge, explicitly non-zero-sum |
| S1C-035 | "다양성 존중과 활용이란 ... 인간과 봇의 본질적 차이까지 인정하고, 그 차이를 경쟁이 아니라 증강과 상호보완의 자산으로 활용하여, 더 높은 집단지능과 지속가능한 AX조직을 만드는 정신이다." | second core spirit — treating human-bot difference as an '증강 자산' (다양성의 증폭); groundwork for 보완적 적합성 |
| S1C-036 | "상호 유사함과 동질성을 느끼는 것—이를 유사적합성(supplementary fit)이라고 함—이 팀워크의 한 측면으로 부서나 조직성과 증진에 분명 도움이 되기도 한다." | named fit type (homogeneity/동질성 기반) held up as the 20th-century default and contrasted with complementary fit |
| S1C-037 | "서로의 부족함을 채워 필요한 전체성을 추구하는 보완적 적합성(complementary fit)이 각광을 받고 있다" | third core spirit — role differentiation/mutual complementation over competition; typed into 인지적·정서적·행동적·윤리적 보완 |
| S1C-038 | "AX조직에서는 직무(job) 보다는 역할(role)이 중요한데, 인간과 봇에게 부여되는 역할 다양성과 그것의 이해를 바탕으로 부서와 조직의 성과를 증진하는 구체적 방법에 관해선 다음 3부에서 상세히 다룰 것이다." | principle that AX orgs organize around roles not jobs; role diversity as the primary diversity axis (detailed in Part 3) |
| S1C-039 | "AI는 인간의 혼을 확장할 수 있다. 로봇은 인간의 백을 확장할 수 있다. 그러나 영은 외주화할 수 없다." | added (non-spirit) imperative — preventing loss of human 영(靈)=최종 판단권 as 혼(판단)/백(실행) get outsourced to AI/robots; built on the 영·혼·백 3차원 모델, 혼비/백산, 혼·백 외주화, 인간백+AI혼 / 기계백+인간혼 결합 |
| S1C-040 | "AX조직 전환에 대한 인간 반응 구조는 4개 층위로 나타난다. 생존 층위 / 능력 층위 / 관계 층위 / 존재 층위" | layered model of human reactions to AX transition (survival/capability/relationship/existence, each with 핵심 질문·대표 감정) |
| S1C-041 | "생존불안형 ... 역량열등형 ... 통제상실형 ... 감시공포형 ... 인간성방어형" | typology of individual human resistance (5 named types); anchors related terms AI competence inequality, human uniqueness |
| S1C-042 | "노동조합형 반발 ... 전문직 집단 저항 ... 사회문화적 반발 ... 정치·정책적 반발 ... 존재론적 반발" | typology of collectivized socio-political resistance (5 named types); anchors Neo-Luddite, WGA/SAG-AFTRA, EU AI Act references |
| S1C-043 | "긍정적 측면은 기술숭배형과 증강기대형으로 생각할 수 있다." / "긍정 축(증강, 협력, 신뢰, 공존, 적응, 의미 확장)과 부정 축(대체, 통제, 불신, 배제, 저항, 존재불안)" | valence typology of reactions; establishes the book's chosen '증강기대형 / 긍정 축' stance |
| S1C-044 | "AX조직에서 가장 위험한 스트레스는 단순 피로가 아니라 다음 4가지, 정체성 ... 신뢰 ... 통제 ... 책임 스트레스이다." | central construct of Ch.2 §2 — stress (and stress resilience / 회복탄력성) as the thing AX orgs must manage; culminates in 4 dangerous stresses |
| S1C-045 | "역할 모호성(Role Ambiguity) ... 역량 대체 불안(Replacement Anxiety) ... 인지 과부하(Cognitive Overload) ... AI 불신 혹은 과신 ... 사회적·관계적 스트레스" | typology of human (psychological/social/cognitive/identity) stress in AX orgs |
| S1C-046 | "계산 과부하(Computational Overload) ... 목표 충돌(Goal Conflict) ... 정렬 실패(Misalignment) ... 지속적 업데이트 스트레스 ... 다중 Agent 협력 스트레스" | typology of bot (functional/computational) stress, presented as the mirror of human stress (기능적 비유) |
| S1C-047 | "본질 심리·감정적 긴장 / 기능·연산적 긴장 ... 측정 감정·행동 지표 / 반응속도(Latency)·정확도(Accuracy)·안정성(Stability)" | comparative structure contrasting 본질·핵심원인·결과·회복방식·위험·측정 of human vs bot stress |
| S1C-048 | "개별 스트레스 보다 더 중요한 것은 '인간-봇 사이의 관계 (상호작용) 스트레스'이다." | the more critical human-bot relational stress; its escalation → AX 도입 실패·거버넌스 붕괴·성과 하락 |
| S1C-049 | "각 협력 유형별로 주요 스트레스와 극복방안을 정리하였다." (per-type 스트레스 유형/극복방안 tables)" | maps each cooperation type to its characteristic member (H/AH/AB/B) stresses and countermeasures |
| S1C-051 | "AX조직에서 인간은 단순 수행자가 아니라 AI를 감독·조율·검증하는 메타관리자(meta-manager)가 된다." | the human's redefined supervisory role (supervise/orchestrate/verify multiple AI) in AX orgs; source of 인지 과부하 |
| S1C-052 | "그 다음 단계인 실물 agent 즉, physical AI(PI)에의 적응과 확산이 가능해 진다." | named next stage beyond bodiless AI bots (실물 로봇); the boundary the book deliberately stops before (AX before RX/PI) |
| S1C-053 | "결국 필요역량이 없으면 AX조직에서 점차 주변화 될 가능성이 크며, 이들의 중심은 적응력, 협업력, 학습력이고" | named competency category (survival tier) — bundles AI 이해력·친화성, 인간-AI 협업능력, 지속적 학습능력, 데이터·디지털 문해력, 비판적 사고, 조직변화 적응력 |
| S1C-054 | "AX조직에서의 성공을 위해선 이상 설명한 필요조건뿐만 아니라, 인간-AI 협력구조를 설계·통제·증폭시키는" | named competency category (success/leadership tier) paired against 필요조건 — bundles 문제 정의, 의미 설계, 시스템 사고, 오케스트레이션, 거버넌스·윤리적 판단력 |
| S1C-055 | "AX조직 인재는 AI와 함께 일할 때 세 가지 (맥락, 판단, 증거) 책임을 지닌다." | named three-part responsibility structure (맥락 책임 / 판단 책임 / 증거 책임) defining the AX talent's obligations |
| S1C-056 | "AX조직 인재의 역할은 다음 8가지로 정리할 수 있다. 이들 모두를 포괄하는 표현은 ‘협업 조정자’이다." | named 8-role framework (문제 정의자·맥락 구성자·AI 실행 지시자·결과 해석자·검증자·책임 판단자·증거 관리자·개선 반영자), umbrella term 협업 조정자 |
| S1C-057 | "다음과 같은 5가지 핵심 역할로 압축·변환될 수 있다." | named contribution-based role taxonomy — 조형자(Shaper/Designer), 구현자(Implementer), 검증자(Validator), 운영자(Operator), 조정자(Coordinator); mapped onto the 8 roles |
| S1C-058 | "AI 시대의 의사소통에서 가장 중요한 변화는 역할과 기여의 분리다." | named theory redefining 일/기여/역할 — "역할은 직함이 아니라 기여의 위치", "기여는 일이 아니라 유효한 변화 |
| S1C-059 | "3부에서 설명할 Belbin의 역할론 역시 업무가 아니라 기여 패턴을 설명한 것이다." | named external framework of team contribution patterns (창조자/plant, 냉철판단자/monitor evaluator, 완결자/completer finisher); explained in 3부 |
| S1C-060 | "이는 바로 ‘AI 시대의 orchestration(조율·통합·설계) 능력’21)을 의미한다." | named leadership capability of coordinating/integrating/designing human+AI systems; ties to 증강조율자(augmented orchestrator) |
| S1C-061 | "리더가 생각해야 하는 최상위 개념은 바로 ‘인간성(humanity) 수호’이다." | named top-level principle a hybrid-org leader must uphold (AI aligned to human existence/development) |
| S1C-063 | "증강인간 = 인간의 목적·판단·책임 + AI의 분석·생성·기록 능력 + 공통 컨텍스트의 기준 구조" | member-type/identity — augmented human defined across 신체적/정신적/역할·맥락 증강 and 세 가지 힘 (목적·기준·판단·책임); core to H→AH |
| S1C-064 | "증강봇(AB)은 다음 네 가지 행동 기준을 충족하는 봇으로 정의할 수 있다." | member-type/identity — augmented bot; internal definition (공통·거버넌스 컨텍스트 내장 협력형 AI) plus external behavioral definition via 4 criteria (검증 가능성·권한 준수·기준 내재화·개선 루프); contrasts 일반 봇(B); measurable as "B→AB 전환도 진단 |
| S1C-067 | "봇의 사회성은 자연 발생하지 않는다. 반드시 인간에 의해 설계·학습·제도화 되어야 한다." | named concept split into 인간-봇 사회성 (비대칭적 신뢰·통제 관계) vs 봇-봇 사회성 (최적화된 상호작용 시스템); sociality as designed reward/verification/reputation/sanction structure, not taught ethics |
| S1C-068 | "비록 제목이 ‘봇의 윤리성’이지만 이는 AX조직의 모든 구성원이 준수해야만 하는 것" | named concept — AI/AX ethics that every member (even bots) must observe; reward-function-based normativity rather than internalized morality |
| S1C-069 | "전 세계적으로 권위 있게 참조되는 AI 윤리기준은 크게 다음 네 유형으로 볼 수 있다." | named typology of external AI-ethics standards — UNESCO AI 윤리권고(4대 가치·10대 원칙), OECD AI Principles, EU AI Act·Trustworthy AI Guideline, IEEE Ethically Aligned Design, plus 한국 정부 '사람이 중심이 되는 AI 윤리기준'(3대 원칙·10대 요건) |
| S1C-070 | "Anthropic의 Claude 헌법: 2026년 1월에 공개된 Claude Constitution 개정판은 AI 모델이 윤리적이고 안전한 판단을 스스로 내리도록 규율하는 최상위 행동 지침이다." | named normative framework cited as an ethics standard — 4대 핵심가치 (broadly safe / broadly ethical / helpfulness / compliance with guidelines) |
| S1C-071 | "조직AX의 윤리적 필요조건으로 반드시 따라야 하는 기준엔 인간 존엄성 보장, 인간의 최종 책임성, 설명가능성, 개인 및 조직정보 보호, 편향과 차별 방지, 안전성과 신뢰성, AI 거버넌스 체계 구축이 있다." | named binary classification of ethics norms into 필요조건 (mandatory, e.g. AI 거버넌스 = 운영 헌법) vs 추가조건 (competitive, e.g. 증강 중심 철학, 공통·거버넌스 컨텍스트); parallels the ch3 competency framework |
| S1C-072 | "이는 과학소설가 I. Asimov가 단편소설 Runaround(1942)에서 제시한 로봇 3원칙(three laws of robotics)이다." | named classical principle set (인간 안전·생명 존중 / 인간 복종 / 자기보호) invoked as the archetype of human-respect obligation |
| S1C-073 | "봇에게 인간존중을 가르치는 것은 교육이 아니라, 인간을 침해하지 않는 행동만 선택되도록 시스템을 설계하는 것" | named foundational principle — human respect implemented as system/reward design (make disrespect disadvantageous) rather than moral instruction; most important element of bot education |
| S1C-074 | "봇 입장에서는 인간존중은 다음 4가지로 환원되고 이들이 기계가 이해 가능한 인간존중의 최소 정의다." | named 4-part machine-readable minimum definition — 비해(Non-harm), 자율성 존중(Autonomy), 공정성(Fairness), 책임성(Accountability) |
| S1C-075 | "인간존중 구현의 구체적 방법으로 5단계 아키텍처를 생각할 수 있다." | named 5-stage implementation method — 보상 설계, 강제 규칙, 인간 피드백 학습(RLHF/RLAIF), 검증 Layer, Multi-agent 환경 인간존중 (human-weighted reward / human priority override / anti-collusion) |
| S1C-076 | "AI는 단순히 지능적으로 똑똑한 시스템(intelligent system)이 아니라 사회적으로 호환/양립 가능한 시스템(socially compatible system)이어야 한다." | named concept (via G. Gibbins, Welcome to your human-AI team!) — bot must learn human 비논리성, AI 관련 스트레스, 사회적 협력 규범; learning bots = design, not education |
| S1C-077 | "AI 봇은 인간처럼 의식적으로 사고하는 존재가 아니라 패턴을 인식할 뿐이다. 즉, ‘거대한 패턴 탐지기, 확률 기반 예측 시스템, 맥락적 생성 엔진’" | named concept clarifying bot nature — 기능적 만족/불만족, 욕구 위계(goal/reward hierarchy, Hierarchical RL), 동기부여 3동력(목표·보상 함수·최적화 알고리즘), 봇의 행복 = 성능+정합성+효율성 |
| S1C-078 | "봇들 사이에도 위계는 자연스럽게 형성된다." | named 4-level emergent hierarchy (L1 Tool/Reactive, L2 Specialist/Executor, L3 Planner/Strategist, L4 Verifier/Governor) with 5 determination criteria (의사결정 권한·정보 비대칭·성능·신뢰도·네트워크 중심성·검증 능력) |
| S1C-079 | "HBRM은 인간과 봇이 함께 구성원이 되는 AX조직에서, 인간과 봇을 조직의 성과와 학습을 만드는 핵심 자원으로 받아들이고, 육성하고, 배치하고, 협력하게 하며, 신뢰와 거버넌스 아래 함께 진화하도록 설계하는 관리체계이다." | named management framework extending HRM→HBRM across 구성원 확장 / 역할 확장 / 진화 확장; alias 인간-봇 자원관리; carries 8 HBRM 역할 + 역할균형 불균형 진단 |
| S1C-080 | "여기서는 HBRM의 3M을 다루어 독자들의 조직AX 실현에 도움되고자 한다." | named tripartite lens of HBRM — 방법(method), 의미(meaning), 측정(measurement); organizes 3장/4장 coverage |
| S1C-081 | "AH 측정에는 5대 지표가 있을 수 있다." | named 5-indicator measure of augmentation — 인지 증강(Cognitive A.), 의사결정 증강(Decision A.), 학습 증강(Learning A.), 협업 증강(Collaboration A.), 역할 증강(Role A.); final criterion = 역할 확장 |
| S1C-082 | "조직AX 과정에서 인간이 증강되는 순서를 보면 일반적으로 다음과 같다." | named maturity ladder — H0 비증강인간, H1 AI 사용자, H2 AI 협업자, AH1 증강인간, AH2 AI 오케스트레이터, AH3 인간-AI 공생형 리더 |
| S1C-083 | "AI Utilization = f(Frequency + Depth + Automation + Outcome)" | named first-level index of AI usage; components frequency/depth/automation/outcome each with formulas; staged 도구 사용자→협업 사용자→지휘자→증강자 |
| S1C-084 | "AQ = AIU x Role Alignment x Collaboration x Governance" | named higher-order index of augmentation capability = 증강 잠재력(potential); second stage of AIU→AQ→AHI chain |
| S1C-085 | "AHI = f(Performance, Learning, Influence, Innovation, Adaptability)" | named index of augmentation result = 증강 실현도(realization); third stage of AIU→AQ→AHI, judges "실제로 AH인가 |
| S1C-086 | "AHCI = 인간증강도 + 봇 협력도 + 인간-봇 정렬도 + 산출 충실성 + 개선 속도" | named capability index measuring readiness to work with AI (growth/development-oriented vs AHI's grading); diagnostic structure connected to HBRM; measurable via Belbin Korea tool |
| S1C-088 | "증강인간과 증강봇의 협력이란 인간의 목적·판단·책임과 봇의 분석·실행·기록 능력이 공통 컨텍스트와 거버넌스 컨텍스트 안에서 연결되어, 더 안전하고 정교하며 의미 있는 결과를" | named core concept (book's central theme) — role-based complementary (not competitive) collaboration requiring three conditions: 같은 맥락 공유(공통 컨텍스트), 책임구조 안에서 협력(거버넌스 컨텍스트), 역할을 나누되 서로를 증강 |
| S1C-089 | "이때 필요한 것이 거버넌스 컨텍스트다." / (ch3) "이는 공통 컨텍스트(common context)와 연계된 것으로" | paired named structures load-bearing for AH/AB and their collaboration — 공통 컨텍스트 (shared purpose/standards/references) and 거버넌스 컨텍스트 (권한·검증·승인·기록·책임 운영체계); referenced throughout, full definition deferred to 7장 |
| S1C-090 | "한 팀 내에 9개 팀역할 유형 모두가 존재하고, 그것도 자연역할(natural role) 수준에서 존재해야 한다. Belbin은 그 경우 팀역할균형(TRB: team role balance)이 이루어졌다고 한다." | The book's central named method/concept — a team-level state (all 9 team roles present at natural-role level) that drives teamwork and team performance; entire 5장 and 6장 are structured around it. |
| S1C-091 | "팀역할이란, … 비공식적(informal) 즉, 조직이나 상사에 의하여 부여되지 않고 직무와 직접적인 관련성도 없지만 (non-job-related), 팀웍을 형성하기 위하여 구성원에 의하여 발휘되는 역할이다." | Named concept (Belbin 1981) contrasted with functional role; the informal, non-job-related behavioral role that produces teamwork — the atomic unit TRB balances. |
| S1C-092 | "직무와 관련하여(job-related) 조직이나 상사에 의하여 공식적으로(formally) 부여된 기능 즉, 기능역할(functional role)을 의미했다." | The formal, job-related role concept that TR is defined against; carries the "역할 개념의 확장(기능역할 + 팀역할)" structural move (also re-anchored in 6장 line 5). |
| S1C-093 | "창조자 (PL) … 냉철판단자(ME) … 지휘조절자(CO) … 실행자(IMP) … 완결자(CF) … 자원탐색가(RI) … 분위기조성자(TW) … 추진자(SH) … 전문가(SP)" | The named 9-type Belbin team-role typology (established 5장 line 71: 1981년 8개 + 1993년 9번째); the member-type taxonomy whose completeness defines TRB and whose AX-reinterpretation drives 6장. |
| S1C-094 | "팀/자연 역할 (Team/Natural Role) … 잠재/관리가능 역할 (Potential/Manageable Role) … 비선호 역할 (Least-preferred Role)" | A named 3-level classification of how strongly an individual manifests each team role; the measurement scaffold behind TRB scoring (natural-level count) and 잠재→자연 upgrading. |
| S1C-096 | "Belbin Associates가 수십 년의 연구를 통해 발전시킨 인사 및 조직관리의 혁신적 tool이다." | The named measurement/software tool (현재 Interplace 8) that operationalizes TR/TRB diagnosis and application — the "measurement" pillar of 3M. |
| S1C-097 | "자기진단지(SPI: self-perception inventory) & 관찰자진단지(OA: observer assessment) … 직무요구진단지(JRE: job requirement exercise) & 직무관찰자진단지(JOA: job observer assessment)" | The named four-instrument set (2 person + 2 job) that feeds Interplace's data collection; measurement sub-structure of the tool. |
| S1C-098 | "그 구체적 측정은 대부분 집단응집성(group cohesiveness)을 활용하였다." | The established measure of the 인간적 유대감/유사적합성 side of teamwork; the structural foil against which TRB (업무적 활성화/보완적 적합성) measurement is positioned. |
| S1C-099 | "'업무적 활성화' 측면의 팀웍을 제창하고, 그 뒤부터 이들 양 측면의 팀웍이 모두 존재할 때 부서의 팀웍 나아가 실제 성과가 제일 높아짐을 입증하였다." | Author's (박원우) named two-dimension expansion of the teamwork concept; structural axis linking 집단응집성↔인지된 성과 and TRB↔실제 성과 (lines 176-186). |
| S1C-102 | "팀역할은 성격유형이 아니라 사람에 의하여 발휘되는 행동유형(behavior type)이다." | Load-bearing distinction grounding why TR is directly measurable/manageable (vs MBTI personality) and why it extends to bots (re-asserted 6장 각주44); a defining property-category of TR. |
| S1C-103 | "이를 우리는 흔히 CBHRM(Competence-Based HRM)라는 이름으로 강조하였다." | Named HRM paradigm (연공+역량) marking the prior stage in the HRM evolution narrative toward role-based management. |
| S1C-104 | "RBHRM(Role-Based HRM)으로의 전환(역량 + 역할주의)이 시작되었지만, 충분히 활용되지 못하고 있었다." | Named HRM paradigm the book advocates (position→role, control→commitment); the HRM-level frame for TRB and the predecessor of 6장's HBRM. |
| S1C-105 | "다양성관리를 잘하면 오히려 조직이 활성화 되고 성과증진이 이루어진다." | Title-level goal-concept ("다양성 관리와 보완적 적합성 추구") that TRB serves; listed as an integrating principle of TRB in 6장 line 13. |
| S1C-106 | "봇이 인간을 '대체'하는 것은 아니라 '보완'하게 된다 … 봇에 의한 TR의 증강 … 봇에 의한 TR의 추가" | Named three-mode framework for how bots relate to team roles in AX orgs (complement / augment / add), each with its own reinterpretation table. |
| S1C-107 | "AI Governor / AI 책임·정렬 관리 … AI Auditor / AI 결과 검증 … Prompt Architect / 인간-AI 상호작용 설계 … Provenance Controller / 데이터 출처·추적성 관리" | Named set of new organizational role/member-types that AX orgs add beyond the human-only Belbin roster (the "추가" mode made concrete). |
| S1C-108 | "AI 시대엔 '상황별 역할 전환, 실시간 재조정, AI 기반 역할 재배치'가 가능해져 동적 역할균형(dynamic role balance)으로 전환이 될 수 있다." | Named transformation of the static Belbin model into a real-time, situation-adaptive balance (정적→동적 역할, 살아있는 역할 생태계) — the "동적화" of TRB. |
| S1C-109 | "봇이 인간 팀의 역할균형을 지원하는 구조 … 'human leader → human team members → bot assistants' 즉, 위계상 봇은 하위 증강층(subordinate augmentation layer)에 위치한다." | First of the two named TRB evolution modes — a vertical, human-primary/bot-subordinate structure (bot as 역할 진단자·협업 조정자·인지 증강자). |
| S1C-110 | "인간과 봇이 독립적 역할 주체로 함께 TRB를 형성하는 구조 … 수직적 보조관계가 아니라 수평적 공동 역할체계이다." | Second named TRB evolution mode — a horizontal structure where bots are co-role-holders (역할의 공동 구성/Co-constitution, 역할 분산 최적화, 보완적 적합성 극대화, hybridized roles). |
| S1C-111 | "대부분 조직은 'Human-only TRB → Bot-aided TRB → Human-bot coupled TRB'의 단계로 진화 … 그 이후에는 'Autonomous hybrid TRB'의 유형으로 나아갈 것이다." | Named staged progression model of TRB evolution; also introduces the terminal named stage Autonomous hybrid TRB. |
| S1C-112 | "ARBI(Augmented Role Balance Index)는 증강 역할균형 지수로 AI가 인간과 인간 사이의 협업과 의사소통에 개입할 때, 인간과 AI의 역할이 얼마나 건강하게 분담되고, 서로 보완되며, 검증되고, 책임 있게 작동하는지를 평가하는 지수이다." | The central named index of 6장 — TRB's AX-extension measuring role balance/authorship/authority/responsibility/fairness/traceability of AI-mediated human collaboration (relation-unit indicator). |
| S1C-114 | "ARBI는 AI가 협업의 질서를 건강하게 만들었는지 평가하는 지표로, 다음 10개 축으로 구성된다." | The named 10-axis operational structure of ARBI (its measurement dimensions / operationalization). |
| S1C-115 | "'다양성 관리, 보완적 적합성, 인간-AI 협력, 조직AX, HBRM'을 통합하는 핵심 원리라 할 수 있다." | Named human-bot extension of HRM/RBHRM (also line 152 "HRM→HBRM 전환"); the management-paradigm frame for AX-org TRB. Acronym not expanded in text. |
| S1C-116 | "AHCI와 ARBI의 2M(측정 tool과 증진 방안)은 Belbin Korea에서 제공한다." | Named two-element frame (measurement tool + improvement method) applied to AHCI/ARBI, paralleling 5장's 3M. |
| S1C-117 | "**Belbin Korea의 AI지원 TRB: Hatch AX**" | Named AI-supported TRB tool/product (AX-era counterpart to Interplace); appears as heading + figure only. |
| S1C-119 | "하나는 AI가 실제로 일하는 로컬 환경이고, 다른 하나는 여러 로컬 환경이 서로 연결되는 네트워크 환경이다." | named two-tier operating structure that grounds the whole chapter — 로컬 환경 carries 공통 컨텍스트, 네트워크 환경 carries 거버넌스 컨텍스트 (comparison table at 37-45) |
| S1C-120 | "공통 컨텍스트는 인간과 AI가 같은 기준으로 사고하고 작업하기 위한 운영 기반이다." | the central named operating structure (로컬 작업 맥락) — component elements 목적·기준·역할·출처·형식·피드백; GP사-coined term opened 2026.6 (각주 49, line 53); AX 운영 기반의 출발점 |
| S1C-121 | "따라서 공통 컨텍스트는 반드시 산출물 표준과 연결되어야 한다." | named structural requirement binding 공통 컨텍스트 to standardized outputs (검토·비교·승인·재사용 가능 구조) |
| S1C-122 | "거버넌스 컨텍스트(governance context)는 여러 공통 컨텍스트가 연결될 때 필요한 네트워크 운영 맥락이다." | named network-operation structure connecting multiple 공통 컨텍스트; carries a 7-요소 component structure 권한·보안·검증·승인·기록·책임·개선 (table 188-209) |
| S1C-123 | "미국 NIST의 AI 위험관리 프레임워크(AI RMF), AI 경영시스템 국제표준 ISO/IEC 42001, 그리고 법적 구속력을 갖는 EU AI Act가 대표적이다." | named external standard-frameworks the book maps its 거버넌스 컨텍스트 7-요소 against (mapping table 228-236); referenced, not book-defined |
| S1C-124 | "AI 거버넌스…는 ‘AI를 어떻게 통제·관리·감독할 것인가’에 관한 규범·제도·운영체계이고" | named regime/system explicitly contrasted with 거버넌스 컨텍스트 as a different level (통제 체계 vs 판단 기준 맥락; A=법률/헌법, B=사회문화/관행) |
| S1C-125 | "지식사슬(knowledge chain)…은 현실 세계의 사건, 행동, 기록, 경험이 데이터가 되고, 데이터가 정보와 지식으로 전환되어, 다시 모델 학습과 의사결정으로 연결되는 흐름이다." | named accumulation/circulation structure (질문→컨텍스트 참조→검증→기록→재반영→재사용) that observes the path to an answer, not just the answer |
| S1C-127 | "지식사슬은 크게 네 가지 기능을 수행한다. ① 구조 거리 측정" | named four-function measurement framework of the knowledge chain (①구조 거리 측정 ②전제 관계 측정 ③추론사슬 충실도 측정 ④전이 가능성 측정) |
| S1C-128 | "지식사슬 기반 의미·인지 거리는 다음 요소들의 종합 결과다." | the central named measure the knowledge chain restores identifiability of (현재 개념구조 vs 목표 지식구조의 거리); composed of 개념구조·숙달·신념구조·전제·추론충실도·근거·전이·인식론적 성숙도 (각주 51) |
| S1C-129 | "인지 속도는 이러한 차이가 시간에 따라 얼마나 빠르게 줄어드는지를 의미한다." | named measure = rate at which 의미·인지 거리 shrinks over time (측정 via 시간 변화 기록, line 381) |
| S1C-130 | "AI 기여도 = 줄어든 의미·인지 거리 / AI 사용 비용" | named index (with defining formula) for AI's real value in the AI era; also listed as an AX effect "④ AI 기여도 확인" (line 572) |
| S1C-131 | "그래서 지식사슬은 단순한 기술 구조가 아니다. 그것은 AI 시대의 인간을 지키는 구조다." | named humanistic principle/re-framing of 지식사슬 as 기억·책임·의미의 구조 (argued via 다빈치/셸리/루카스); a principle, not a separate mechanism |
| S1C-132 | "공통/거버넌스 컨텍스트 기반 지식사슬은 지식경영(=조직학습)을 실현하여 기업들이 학습조직(learning organization)이 되도록 하는 매개체·촉진제 역할을 한다." | named precedent concept (지식경영) and its enabled outcome-state (학습조직); the chain automates what past 지식경영 유행 failed to sustain |
| S1C-133 | "지식행동사슬은 지식이 실제 행동, 결과, 검증, 학습으로 이어지는 전체 과정을 의미한다." | named execution/operating chain (지식→스킬→runtime→action→outcome→review/feedback→context, line 625) contrasted with 지식사슬 (앎 vs 실행; 머리 vs 손발·학습); GP사-formed (각주 52) |
| S1C-134 | "AI 시대에서 중요한 단위는 문서가 아니라 스킬이다." | named core executable unit of the AI era (문서=읽기용 vs 스킬=실행용); the pivot the 지식행동사슬 moves around |
| S1C-135 | "여기서 중요한 것이 SkillRuntime이고, SkillRuntime은 다음을 정의한다." | named runtime structure that makes a skill executable (defines 입력·자료·도구·금지·결과형식·검토승인자·기록위치) |
| S1C-137 | "이렇게 되면 인간과 봇의 공진화가 이루어져, 조직 내 타 구성원(인간, 타 봇)들과의 협력이 원활하게 된다." | named effect-mechanism whereby members go employee→intrapreneur and bots become 맞춤형 봇, realizing H→AH & B→AB hybrid AX (증강봇/AB is defined mainly in ch1, referenced here) |
| S1C-139 | "identity, goal, knowledge, method, skill, task, artifact가 하나의 그래프 안에서 실제 지식행동사슬로 연결된 구조를 보여준다." | named 7-node ontology of the knowledge-action chain (visualized via Obsidian Graph View); explicitly "상세 설명은 생략" so under-defined here |
| S1C-141 | "증강인간의 발화는 인간 판단과 AI 기여가 결합된 복합 산출물이다." | named output-unit of the 증강인간 — a compound utterance carrying hidden 인간/AI/컨텍스트/시스템 contributions; facet of AH |
| S1C-142 | "즉, 맥락은 내부를 정렬하고, 의사소통은 외부와 연결하며, 거버넌스는 그 연결을 책임 가능하게 만든다." | named three-layer architecture positioning 의사소통 컨텍스트 between 공통 컨텍스트 (내부 정렬) and 거버넌스 컨텍스트 (조직 전체 연결) |
| S1C-143 | "의사소통 컨텍스트 = 증강인간과 외부 관계의 운영 기준" | named context layer governing how 증강인간 relates to 외부 (발화자·AI 개입·기록·분석·공유·승인); distinct from 공통 컨텍스트 (내부 정렬) |
| S1C-144 | "증강인간과 비증강인간 사이의 의사소통은 다음의 구조이다." | named typology of communication by member combination (증강인간↔비증강인간, 증강인간↔증강인간); umbrella carrying 역할 공백·기여 충돌·증강력·3경로 |
| S1C-145 | "이것이 역할 공백 즉, AI가 없는 쪽에서 해석·검증·기록·대응 역할이 비어 있는 상태다." | named defect-concept of asymmetric (증강인간↔인간) communication — the non-augmented side lacks 해석·검증·기록·대응 roles; framed as a 공정성 (의사소통 권력) problem |
| S1C-146 | "중요한 것은 AI 보유 여부가 아니라 증강력의 수준이다. 증강력은 다음 요소들에 의해 결정된다." | named capacity-level determining AH↔AH (a)symmetry — set by AI 성능·공통 컨텍스트 품질·자료·실행 권한·인간 판단력·거버넌스·기록/검증 체계 |
| S1C-147 | "이것이 기여 충돌이고, 이는 여러 인간과 AI가 같은 메시지에 서로 다른 기준, 해석, 검증 상태, 책임 판단을 부여할 때 발생하는 충돌이다." | named conflict-concept of 증강인간↔증강인간 communication (supersedes 역할 공백 there); divergent 기준·해석·검증상태·책임 on the same message |
| S1C-148 | "증강인간들 간 의사소통은 하나의 방식으로만 이루어지지 않는다. 크게 세 가지 경로가 있다." | named 3-path typology — 인간 중심 경로(의미 보존), AI 중심 경로(처리 효율), 거버넌스 경유 경로(책임 확립) |
| S1C-149 | "AI의 더 큰 변화는 생성능력이 아니라 예측능력57)에서 발생한다." | frames the chapter's paradigm shift — AI moving from generation to prediction (미래 상태·행동 결과 예측), the root concept the whole chapter builds on. |
| S1C-150 | "이를 예측지능 스택(predictive intelligence stack)으로 볼 수 있다." | the layered (5-층) architecture; combines 월드 모델 + 지식사슬 + 컨텍스트 설계 into an operative "예측지능 체계" (aliases: predictive intelligence system/stack). |
| S1C-151 | "월드 모델은 AI가 환경의 상태, 변화, 행동 결과를 내부적으로 표현하고 예측하기 위한 모델 구조이다." | layer-4 technical basis of predictive intelligence; the "실행 전 미래를 실험" engine contrasted against 일반 생성 AI. |
| S1C-153 | "컨텍스트 설계는 기술 논의를 인간의 업무와 조직 운영으로 연결하는 실무적 매개 구조이다." | the operating condition binding predictive capability to human purpose/organizational standards; third pillar of the 예측지능 체계 (from ch7, extended here). |
| S1C-154 | "컨텍스트 설계자(context designer)는 제 1의 LLM이 조직 내에서 효과적으로 작동케 하는 필요조건을 형성하는 사람(조직)이고, 나아가 제 2의 LLM을 형성하는 주체이다." | the actor/member-type that supplies organizational context to AI; also appears as "컨텍스트 설계형 AX 인재" in the labor typology (lines 181-183) and "AX 인재" (line 155). |
| S1C-156 | "AI 계급사회란 AI 모델, 데이터, 컴퓨트(compute), 플랫폼, 조직 맥락, 활용 역량, 의사결정 권한에 대한 접근 차이가 누적되어..." | the central problem-concept the chapter's solutions answer; book uses 계급/계층 interchangeably (footnote 61). Aliases: AI 계급사회, AI 기반 계층화. |
| S1C-157 | "이 저장된 지식이 지식자본화 되어 big tech에 의해 팔리고 있다." | explains how structured knowledge stored in data centers is capitalized and sold by big tech, driving 계급화; supporting concept. |
| S1C-158 | "AI 기반 계급화는 단순히 ‘AI를 쓰는 사람’과 ‘AI를 못 쓰는 사람’의 차이로 생기지 않는다." | named 7-gap typology (접근·역량·맥락·판단권·감시·소유·성과배분 격차); author singles out AI 맥락 격차 (line 132) as the bridge to 맥락자본. |
| S1C-159 | "노동시장은 다음처럼 분화될 수 있다." | worker/member typology under AI transition — AI 보완형 노동자 / AI 관리 대상 노동자 / AI 대체·축소 위험 노동자 / 컨텍스트 설계형 AX 인재. |
| S1C-160 | "알고리즘 관리(algorithmic management)는 추적 데이터와 기타 정보를 사용해 업무를 조직, 배정, 모니터링, 감독, 평가하는 알고리즘 시스템을 뜻한다." | recurring key risk — the "AI를 사용하는 인간 vs AI에게 관리당하는 인간" split; first introduced at line 188, mapped to ESG questions (G/S) at 382-386. |
| S1C-161 | "AI 시대의 포용전환 AX는 효율성 중심 AI 전환을 책임과 포용의 관점으로 재설계하여, AI 계층화를 예방·완화하고..." | the book's central "조직 전환 프레임워크"; framed as the实현 method of ESG 확장 (footnote 64). Protects 역할·판단권·학습권·전환권·이의제기권·성과공유권. |
| S1C-162 | "효율성 중심 AX는 기업의 생산성과 경쟁력을 높일 수 있다. 그러나 AI 전환이 효율성만을 기준으로 설계되면 다음 위험이 발생한다." | the foil concept against which 포용전환 AX is defined (comparison table at 213-221). |
| S1C-163 | "맥락자본의 사회화는 AI 활용 역량이 소수 개인이나 특정 부서에 독점되는 것을 막고..." | one of the two핵심 the book emphasizes; converts 맥락자본 into a shared production base to prevent 계급화. |
| S1C-164 | "맥락자본은 AI를 제대로 작동시키기 위해 필요한 목적, (판단)기준, 언어, 자료, 형식, 검증기준, 승인기준의 축적된 운영 자산이다." | core new-capital concept — the organizational context given to AI as a production asset; foundation of 포용전환 AX and the S축. |
| S1C-165 | "AI 시대의 계급화는 모델 접근권 만이 아니라 맥락자본 접근권(context access right)에서 발생한다." | redefines "접근권" as access to usable context, not just accounts; listed as a proposed concept (제안 개념, line 350). |
| S1C-166 | "맥락 정의는 ... 구성원이 AI와 함께 일할 수 있는 공통 생산 기반에 접근하도록 만드는 정의 원리다." | justice principle reframing AI fairness from algorithmic bias to who can give context / verify / contest. |
| S1C-167 | "AI 역량 평등론은 AI 시대의 불평등이 단순히 AI 도구 접근 격차에서 발생하는 것이 아니라 ... 역량의 격차에서 발생한다고 본다." | theory locating inequality in capability-to-direct-and-verify-AI, not tool access; mandates socializing 맥락자본/권한체계. |
| S1C-168 | "그 맥락자본이 조직 전체에서 안전하게 연결되고 통제되도록 만드는 책임운영체계(accountable operating system)다." | second of the two핵심; the 권한·검증·승인·기록·책임·개선 operating order controlling AI power inequality (in-text English gloss: "accountable operating system"; also "책임 운영 체계" line 350). |
| S1C-171 | "기업의 책임 범위를 AI 운영 환경까지 확장함으로써, AI 발달과 적용 확산에서 초래되는 구조적 불평등 문제를 예방·완화하려는 경영철학이다." | the overarching move — keep E/S/G but extend each to AI-era risks (기존 vs 확장 ESG table, 323-334; 물리적 부담=E, 인간·사회 변화=S, 책임·통제=G at 310-315). Not해체 but 고도화. |
| S1C-172 | "ESG 확장론은 아직 하나의 통일된 이론이 아니라 ... 기존 ESG의 한계를 다양한 각도에서 지적하며 이를 재구성하려는 흐름이다." | meta-discourse classifying three critique types (이해관계자 확대론 / 측정·검증 강화론 / ESG의 AI 시대 확장론 = 본 책 입장) and 주체별 국제기구·투자기관·학계. |
| S1C-173 | "ESG의 강력 실행도구로서 AI의 긍정적 효과는 ‘AI for ESG’, ESG관점에서 부작용을 유발하는 관리의 대상으로서 AI의 부정적 효과는 ‘ESG for AI’로 표현되고 있다." | named two-directional framing of the AI–ESG relationship (AI as ESG tool vs ESG governing AI). |
| S1C-174 | "‘책임감 있는 인공지능(responsible AI: RAI)’라는 표현이 등장하여(Lu 등, 2023) ... 개인, 집단, 사회에 혜택을 주는 방향으로 AI를 개발하고 활용함’을 통칭하고 있다." | externally-cited backdrop concept the book extends beyond; Lee et al.(2025)'s "RAI 평가 모델" is discussed here as a related (but ESG-기존관점-bound) assessment framework. |
| S1C-175 | "‘AI 포용전환 ESG’는 ... AI 접근, 학습, 활용, 검증, 승인, 기록, 책임, 성과공유를 기업의 ESG 책임으로 다루는 확장된 경영철학이다." | the book's flagship named framework/philosophy; footnote 67 gives English "Just AI Transition ESG" / "Inclusive AI Transition ESG"; extends 공정전환(Just Transition) to AI. |
| S1C-176 | "AI 포용전환 ESG는 다음 네 층위로 이해하면 된다." | epistemic layering (확인 가능한 사실 / 합리적 해석 / 제안 개념 / 실행 모델) separating verified fact from author's design. |
| S1C-177 | "Brynjolfsson(2022)의 튜링 함정(turing trap)은 인간을 모방하고 대체하는 방향의 AI가 부와 권력 집중을 만들 수 있다고 경고한다." | externally-cited concept grounding the "AI는 자동화보다 보강 중심으로 설계되어야 한다" principle. |
| S1C-178 | "역량 접근법(capability approach)은 ... 사람이 실제로 가치 있는 행위와 삶을 실현할 수 있는 실질 자유로 본다." | externally-cited philosophical grounding for redefining AI 접근권 as 실질적 AI 활용 역량. |
| S1C-179 | "Rawls(1971)의 차등 원칙(difference principle)은 사회경제적 불평등이 가장 불리한 사람들에게 최대 이익이 되도록 배열되어야 한다고 본다." | externally-cited justice principle grounding the 성과배분/정의로운 전환 argument. |
| S1C-180 | "기후 전환에서 공정전환(just transition)은 전환 과정이 공정하고 포용적이어야 하며, 누구도 뒤처지지 않도록 해야 한다는 원칙이다." | the source principle the whole "포용전환 / Just AI Transition ESG" derives from; "AI 시대의 확장 ESG는 ... Just AI Transition ESG로 정리될 수 있다" (line 408). |
| S1C-181 | "AI를 이해하고 활용하고 통제하고 이의를 제기하며 그 성과에 참여할 수 있는 사회적 역량을 (다음의 권리를 부여함으로써) 보장하는 책임이다." | the S축 content — a named set of 규범적·운영적 보호원칙 (footnote 63): AI 접근권·학습권·활용권·판단권·설명권·이의제기권·전환권·성과공유권; recurs at 194, 211, 358, 550. |
| S1C-182 | "AI 포용전환 ESG는 철학 선언에 머물러서는 안 된다. 조직 안에서 실행 가능한 운영 모델로 내려와야 한다." | named 9-step operating model (영향평가→맥락자본 구축→권한 설계→노동 전환→인간 승인 기준→이의제기 절차→감사 기록→성과배분→개선 루프), each tagged E/S/G. |
| S1C-183 | "다음 지표(가칭 포용전환 ESG 12지표)는 조직이 AI 전환을 책임 있게 운영하는지 확인하기 위한 기본 항목이다." | named measurement set of 12 indicators (AI 접근성·교육·활용 역량·노동 전환·인간 판단권·설명 가능성·이의제기권·감사 기록·책임구조·성과 공유·맥락자본·책임운영체계·환경 책임) making 포용전환 ESG measurable. |
| S1C-185 | "토큰 절감은 단순한 기술적 최적화가 아니라, AI 운영의 책임성과 효율성을 나타내는 지표로 볼 수 있다." | proposes token reduction as a cross-E/S/G ESG performance indicator, linking 지식행동사슬 to ESG 확장. |

## ManualItem

| Stage1CandidateID | NormalizedName | display name | reason the boundary is unsettled at Stage 1 |
|---|---|---|---|
| S1C-003 | `ROBOT_TRANSFORMATION` | RX (Robot Transformation) | successor paradigm gated on AX; the book stops before RX - boundary uncertain |
| S1C-007 | `AX_INDIVIDUAL` | AX개인 | a single cell of the 2x2 적용단위x과정/결과 taxonomy; may be TupleOnly |
| S1C-021 | `AX_CORE_INDICES` | GP사 5대 핵심 지표 (지표 기반 운영) | GP사 5대 핵심 지표 named but the five indices are not enumerated in-corpus - BoundaryCapped |
| S1C-032 | `COLLABORATIVE_COGNITION_SYSTEM` | 협력적 인지체계 (Collaborative Cognition System) | single-line characterization (line 429); independent surface unclear |
| S1C-038 | `ROLE_DIVERSITY` | 역할 중심(직무 대비)·역할 다양성 (Role Diversity) | principle stated in passing; overlaps 다양성 and 역할론 - scope uncertain |
| S1C-043 | `REACTION_VALENCE_TYPES` | AI 발달 반응의 긍정/부정 축 (기술숭배형·증강기대형) | valence typology stated in passing (33, 85); element set not enumerated |
| S1C-051 | `META_MANAGER` | 메타관리자 (Meta-manager) | single-line role mention (line 103); independent surface unclear |
| S1C-052 | `PHYSICAL_AI` | physical AI (PI) | the boundary the book deliberately stops before (AX before RX/PI) |
| S1C-089 | `COMMON_AND_GOVERNANCE_CONTEXT` | 공통 컨텍스트 & 거버넌스 컨텍스트 | a PAIRING of 공통 컨텍스트 + 거버넌스 컨텍스트 - possibly RelationOnly / ParentDuplicate |
| S1C-103 | `COMPETENCE_BASED_HRM` | CBHRM (Competence-Based HRM, 역량주의) | single-line HRM-lineage marker (line 214) |
| S1C-105 | `DIVERSITY_MANAGEMENT` | 다양성 관리 (diversity management) | title-level goal-concept; overlaps 다양성 and 보완적 적합성 |
| S1C-116 | `TWO_M` | 2M (측정 tool과 증진 방안) | single-line two-element frame (line 253); may be ProcedureOnly |
| S1C-117 | `HATCH_AX` | Hatch AX (Belbin Korea의 AI지원 TRB) | heading + figure only (125-127); definition not developed in-corpus |
| S1C-121 | `OUTPUT_STANDARDIZATION` | 산출물 표준화 | structural requirement stated in passing; may be a constraint of 공통 컨텍스트 |
| S1C-123 | `AI_GOVERNANCE_STANDARDS` | AI 거버넌스 국제표준 (ISO/IEC 42001 · NIST AI RMF · EU AI Act) | externally-owned standards (ISO/IEC 42001 etc.) mapped against, not authored |
| S1C-129 | `COGNITIVE_SPEED` | 인지 속도 | measure defined only as the rate of change of 의미·인지 거리 - may be FormulaResidue |
| S1C-131 | `HUMAN_PROTECTING_STRUCTURE` | AI 시대 인간을 지키는 구조 | humanistic re-framing of 지식사슬; may be ParentDuplicate |
| S1C-132 | `KNOWLEDGE_MANAGEMENT` | 지식경영 / 학습조직 | precedent concept (지식경영/학습조직) cited as background |
| S1C-137 | `HUMAN_BOT_AUGMENTATION` | 인간과 봇의 증강 (H→AH · B→AB, 공진화) | effect-mechanism restating H->AH / B->AB; may be ParentDuplicate |
| S1C-141 | `AUGMENTED_UTTERANCE` | 증강 발화 | output-unit of 증강인간; independent surface vs its parent unclear |
| S1C-146 | `AUGMENTATION_POWER` | 증강력 | capacity-level determinant; may be a constraint rather than an identity |
| S1C-157 | `KNOWLEDGE_CAPITAL` | 지식자본 / 지식자본화 | explanatory mechanism inside 계급화; independent role unclear |
| S1C-174 | `RESPONSIBLE_AI` | 책임감 있는 인공지능 (Responsible AI, RAI) | externally-cited backdrop (Lee et al. 2025 RAI) the book extends beyond |
| S1C-177 | `TURING_TRAP` | 튜링 함정 (Turing Trap) | externally-cited concept (Turing Trap) grounding a principle |
| S1C-178 | `CAPABILITY_APPROACH` | 역량 접근법 (Capability Approach) | externally-cited philosophical grounding (Capability Approach) |
| S1C-179 | `DIFFERENCE_PRINCIPLE` | 차등 원칙 (Difference Principle) | externally-cited justice principle (Difference Principle) |
| S1C-185 | `TOKEN_REDUCTION_ESG_INDICATOR` | 토큰 절감 (ESG 실행 지표) | proposed indicator; may be a residue of 지식행동사슬 token economics |

## RegistryCollapse  (projected artifact SECTION; preserve-only channel)

The FROZEN `_identity` registry is EMPTY, so **no row collapsed into a pre-existing registry identity**.
Every row below is an **intra-run duplicate referent** resolved by candidate_adjudication against the
richer sibling occurrence. These rows carry **no fragmentation verdict** and are handed to Stage 2 on
the SEPARATE preserve-only `ExistingIdentityReferenceSet` channel — never in C0, never in the verdict flow.

| Stage1CandidateID | NormalizedName | display name | collapseTarget | target NormalizedName | SourceDocumentLinks | SourceUnitID | SourceProvenanceID | sourceLineRanges |
|---|---|---|---|---|---|---|---|---|
| S1C-011 | `KNOWLEDGE_CHAIN` | 지식사슬 | S1C-125 | `KNOWLEDGE_CHAIN` | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-011 | SP-011 | 155-171 (also 199, 234) |
| S1C-012 | `COMMON_CONTEXT` | 공통 컨텍스트 (Common Context) | S1C-120 | `COMMON_CONTEXT` | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-012 | SP-012 | 157-171 (also 234, 248-256) |
| S1C-013 | `GOVERNANCE_CONTEXT` | 거버넌스 컨텍스트 (Governance Context) | S1C-122 | `GOVERNANCE_CONTEXT` | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-013 | SP-013 | 157-185 (also 234, 303) |
| S1C-020 | `AI_GOVERNANCE` | AI 거버넌스 (AI Governance) | S1C-124 | `AI_GOVERNANCE` | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-020 | SP-020 | 141-141 (also 200, 303) |
| S1C-023 | `AUGMENTED_HUMAN` | AH: 증강인간 (Augmented Human) | S1C-063 | `AUGMENTED_HUMAN` | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-023 | SP-023 | 294-316 (also Ch.2 238-240) |
| S1C-024 | `AUGMENTED_BOT` | AB: 증강봇 (Augmented Bot) | S1C-064 | `AUGMENTED_BOT` | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-024 | SP-024 | 300-314 (also Ch.2 242) |
| S1C-028 | `HBRM` | HBRM (Human Bot Resource Management) | S1C-079 | `HBRM` | `_input/_document/01_1부_1장_인간과_봇이_공존협력하는_AX조직.md` | SU-028 | SP-028 | 320-337 |
| S1C-050 | `ROLE_BALANCE_TRB` | 인간과 봇의 역할 균형 (TRB) | S1C-090 | `TEAM_ROLE_BALANCE` | `_input/_document/02_1부_2장_인간과_봇_모두의_성장행복을_위한_경영.md` | SU-050 | SP-050 | 189-191 |
| S1C-062 | `TEAM_ROLE_BALANCE` | 팀역할균형 / 역할균형 (TRB / team role) | S1C-090 | `TEAM_ROLE_BALANCE` | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-062 | SP-062 | ch4 324-341 (also ch3 line 67, 77) |
| S1C-065 | `HUMAN` | 인간 (H) | S1C-022 | `HUMAN_MEMBER` | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-065 | SP-065 | 273, 302, 314 |
| S1C-066 | `BOT` | 봇 (B) | S1C-025 | `BOT_MEMBER` | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-066 | SP-066 | 273, 524-539 |
| S1C-087 | `AUGMENTED_ROLE_BALANCE_INDEX` | 증강 역할균형 지수 (ARBI) | S1C-112 | `ARBI` | `_input/_document/04_2부_4장_봇의_사회화교육과_HBRM.md` | SU-087 | SP-087 | 533, 600 |
| S1C-095 | `THREE_M` | 3M (meaning, measurement, method) | S1C-080 | `HBRM_3M` | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-095 | SP-095 | 7-7 |
| S1C-100 | `COMPLEMENTARY_FIT` | 보완적 적합성 (complementary fit) | S1C-037 | `COMPLEMENTARY_FIT` | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-100 | SP-100 | 120-124 |
| S1C-101 | `SUPPLEMENTARY_FIT` | 유사적합성 (supplementary fit) | S1C-036 | `SUPPLEMENTARY_FIT` | `_input/_document/05_3부_5장_팀역할균형_TRB.md` | SU-101 | SP-101 | 120-122 |
| S1C-113 | `AHCI` | 증강인간 역량지수 (AHCI, Augmented Human Capability Index) | S1C-086 | `AUGMENTED_HUMAN_CAPABILITY_INDEX` | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-113 | SP-113 | 231-249 |
| S1C-136 | `SECOND_LLM` | ‘제2의 LLM’ (제1의 LLM 대비) | S1C-010 | `SECOND_LLM` | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-136 | SP-136 | 26, 603-605 |
| S1C-138 | `DOMAIN_CONTEXT` | 도메인 컨텍스트 | S1C-014 | `DOMAIN_CONTEXT` | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-138 | SP-138 | 655-657 |
| S1C-140 | `AUGMENTED_HUMAN` | 증강인간 (AH) | S1C-063 | `AUGMENTED_HUMAN` | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-140 | SP-140 | 692-744 |
| S1C-152 | `KNOWLEDGE_CHAIN` | 지식사슬 | S1C-125 | `KNOWLEDGE_CHAIN` | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-152 | SP-152 | 25-85 |
| S1C-155 | `FIRST_SECOND_THIRD_LLM` | 제1의 LLM / 제2의 LLM / 제3의 LLM | S1C-010 | `SECOND_LLM` | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-155 | SP-155 | 87-87 |
| S1C-169 | `COMMON_CONTEXT` | 공통 컨텍스트 | S1C-120 | `COMMON_CONTEXT` | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-169 | SP-169 | 251-272 |
| S1C-170 | `GOVERNANCE_CONTEXT` | 거버넌스 컨텍스트 | S1C-122 | `GOVERNANCE_CONTEXT` | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-170 | SP-170 | 253-272 |
| S1C-184 | `KNOWLEDGE_ACTION_CHAIN` | 지식행동사슬 | S1C-133 | `KNOWLEDGE_ACTION_CHAIN` | `_input/_document/08_4부_8장_포용전환_AX와_ESG_확장.md` | SU-184 | SP-184 | 554-586 |

## DropLog

| Stage1CandidateID | NormalizedName | display name | drop reason | SourceDocumentLinks | SourceUnitID | SourceProvenanceID | sourceLineRanges |
|---|---|---|---|---|---|---|---|
| S1C-118 | `SIEMON_AI_BOT_ROLES` | Siemon(2022)의 AI bot TR 4유형 (Coordinator·Creator·Perfectionist·Doer) | book names Siemon(2022) in a footnote but explicitly takes a different stance - not adopted as an identity | `_input/_document/06_3부_6장_인간봇_공존_조직에서의_TRB.md` | SU-118 | SP-118 | 54-54 |
| S1C-126 | `VALUE_CHAIN` | 가치사슬 (value chain) | 가치사슬 appears only as etymological grounding in a footnote for 지식사슬 - ExampleOnly, no independent role | `_input/_document/07_4부_7장_공통거버넌스_컨텍스트와_지식사슬.md` | SU-126 | SP-126 | 264 |

## counts

| quantity | value |
|---|---|
| admitted source documents | 12 |
| harvested source units (SourceUnit) | 185 |
| Stage1Status = KEEP | 132 |
| Stage1Status = MANUAL | 27 |
| Stage1Status = COLLAPSE | 24 |
| Stage1Status = DROP | 2 |
| **C0 roster (KEEP + MANUAL)** | **159** |
| RegistryCollapse (preserve-only, not in C0) | 24 |
| DropLog | 2 |
| total settled rows | 185 |

Every one of the 185 harvested rows carries exactly one Stage1Status; 132+27+24+2 = 185.

## ConformanceCheck

| # | Contract obligation | result |
|---|---|---|
| 1 | ONE timestamped Stage-1 artifact exists at the run-scoped path under runRoot | PASS |
| 2 | Every candidate settled with exactly one Stage1Status in {KEEP, MANUAL, COLLAPSE, DROP} | PASS (185/185) |
| 3 | The four source-link fields present on EVERY row, including COLLAPSE and DROP | PASS (185/185) |
| 4 | C0 roster = KEEP + MANUAL only, one resolvable row per member | PASS (159 rows) |
| 5 | RegistryCollapse / DropLog / counts projected as artifact SECTIONS before landing | PASS |
| 6 | RAW `_Source` layer produced; SCORED fields present as explicit NOT-YET-PRODUCIBLE placeholders, not fabricated | PASS |
| 7 | SourceProvenanceID traces back into `_Source` (SP-nnn -> SU-nnn -> SD-nn -> `_input/_document/*.md`) | PASS (185/185) |
| 8 | sourceDocumentSha256 recorded per admitted document at admission | PASS (12/12) |
| 9 | runID minted internally, not accepted as an input | PASS (`20260719_154811`) |
| 10 | All outputs landed under runRoot; clean vault not written | PASS |

**conformance_check verdict: PASS** — the E14 PASS-only gate is therefore open.

## VerifiedRunRecord

- **result**: PASS
- **runID**: `20260719_154811`
- **stage**: 1 — candidate extraction
- **sealed artifact**: `_artifact/20260719_154811_stage1_source_linked_identity_extraction_artifact.md`
- **sealed sets**: C0 roster (159 = KEEP 132 + MANUAL 27); RegistryCollapse (24); DropLog (2); counts
- **frozen registry snapshot**: empty (0 identities) — no registry absorption possible this run
- **gate**: verified_record ran ONLY because conformance_check emitted PASS (E14 PASS-only gate)
- **handoff to Stage 2**: `C0 = FinalIdentityCandidate union ManualReviewCandidate` (159 rows,
  section `## C0 roster (KEEP + MANUAL)`) PLUS `RegistryCollapse` (24 rows, section
  `## RegistryCollapse`) admitted on the SEPARATE preserve-only `ExistingIdentityReferenceSet`
  channel with NO fragmentation verdict. Two channels, ONE sealed artifact.

SEALED.
