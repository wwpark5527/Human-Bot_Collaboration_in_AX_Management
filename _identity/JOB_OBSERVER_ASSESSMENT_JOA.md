---
identity: JOB_OBSERVER_ASSESSMENT_JOA
displayName: "Job Observer Assessment (JOA: job observer assessment)"
class: METHOD
runID: 20260719_164605
walkOrder: 207
stage3SequenceID: S3S-0259
stage2CandidateID: S2C-0383
stage1CandidateID: S1C-097
derivedFrom:
  - "[S1C-097 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0383 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0259 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0259)"
fragmentedFrom: "[S2C-0084 INTERPLACE_QUESTIONNAIRES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[JOB_REQUIREMENT_EXERCISE_JRE](./JOB_REQUIREMENT_EXERCISE_JRE.md)"
sequenceNextIdentity: "[GROUP_COHESIVENESS](./GROUP_COHESIVENESS.md)"
sourceDocument: "_input/_document/05_3부_5장_팀역할균형_TRB.md"
sourceLines: "142-142"
---

# JOB_OBSERVER_ASSESSMENT_JOA — Job Observer Assessment (JOA: job observer assessment)

## Concept Definition
One of the two questionnaires that assess a job — a questionnaire that diagnoses the results of observing that job (job-observation items).

## Decision Criteria
It is distinguished by whether the assessment target is a job, but responses are given based not on a requirements description but on the observation results by a job observer.

## Output
Job-observation data. Together with the job-requirements items, it is processed as input to job assessment and becomes the basis for deriving job characteristics and for staffing/selection advice (lines 236-246).

## Evidence (original quotation)
> "When the data (on personnel and jobs) collected through the job observer assessment (JOA: job observer assessment) is entered"

Source: `_input/_document/05_3부_5장_팀역할균형_TRB.md` lines 142-142

## Provenance
- Stage-1: [S1C-097](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — The named four-instrument set (2 person + 2 job) that feeds Interplace's data collection; measurement sub-structure of the tool.
- Stage-2: [S2C-0383](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0259](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0259) — SequenceOrder 259
- fragmentedFrom: [S2C-0084 INTERPLACE_QUESTIONNAIRES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [JOB_REQUIREMENT_EXERCISE_JRE](./JOB_REQUIREMENT_EXERCISE_JRE.md)
- next: [GROUP_COHESIVENESS](./GROUP_COHESIVENESS.md)

## Derivation
[goal](../_goal/job_observer_assessment_joa_goal.md) · [task](../_task/job_observer_assessment_joa_task.md) ·
[knowledge](../_knowledge/job_observer_assessment_joa_knowledge.md) · [method](../_method/job_observer_assessment_joa_method.md) ·
[skill](../_skill/JOB_OBSERVER_ASSESSMENT_JOA/SKILL.md)
