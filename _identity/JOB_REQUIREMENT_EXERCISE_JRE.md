---
identity: JOB_REQUIREMENT_EXERCISE_JRE
displayName: "Job Requirement Exercise (JRE: job requirement exercise)"
class: METHOD
runID: 20260719_164605
walkOrder: 206
stage3SequenceID: S3S-0258
stage2CandidateID: S2C-0382
stage1CandidateID: S1C-097
derivedFrom:
  - "[S1C-097 Stage-1 source-linked extraction](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-roster-keep--manual--one-resolvable-row-per-member)"
  - "[S2C-0382 Stage-2 identity fragmentation](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary)"
  - "[S3S-0258 Stage-3 knowledge-chain ordering](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0258)"
fragmentedFrom: "[S2C-0084 INTERPLACE_QUESTIONNAIRES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)"
collapsedFrom: none
sequencePreviousIdentity: "[OBSERVER_ASSESSMENT_OA](./OBSERVER_ASSESSMENT_OA.md)"
sequenceNextIdentity: "[JOB_OBSERVER_ASSESSMENT_JOA](./JOB_OBSERVER_ASSESSMENT_JOA.md)"
sourceDocument: "_input/_document/05_3부_5장_팀역할균형_TRB.md"
sourceLines: "142-142"
---

# JOB_REQUIREMENT_EXERCISE_JRE — Job Requirement Exercise (JRE: job requirement exercise)

## Concept Definition
One of the two questionnaires that assess a job among the 4 questionnaires Interplace uses — a questionnaire that diagnoses the requirements that the job demands.

## Decision Criteria
It is distinguished by whether the assessment target is not a person but a job, and responses are given based on the requirements the job demands (job-requirements items).

## Output
Job-requirements data. It is processed as job-assessment material for what TRs the job should be composed of (lines 236-238), and is coupled with an individual's TR characteristics to be used in person-job fit judgment (line 154).

## Evidence (original quotation)
> "The two questionnaires that assess a job — the job requirement exercise (JRE: job requirement exercise)"

Source: `_input/_document/05_3부_5장_팀역할균형_TRB.md` lines 142-142

## Provenance
- Stage-1: [S1C-097](../_artifact/20260719_164605_stage1_source_linked_identity_extraction_artifact.md#c0-evidence--structural_role-per-member) — The named four-instrument set (2 person + 2 job) that feeds Interplace's data collection; measurement sub-structure of the tool.
- Stage-2: [S2C-0382](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#settled-records--the-9-codex-required-fields--1-auxiliary) — fragmentationAction SPLIT
- Stage-3: [S3S-0258](../_artifact/20260719_164605_stage3_knowledge_chain_ordering_artifact.md#s3s-0258) — SequenceOrder 258
- fragmentedFrom: [S2C-0084 INTERPLACE_QUESTIONNAIRES](../_artifact/20260719_164605_stage2_identity_fragmentation_artifact.md#splitset--parent---promoted-fragments-with-the-source-read-evidence-per-element)

## Sequence
- previous: [OBSERVER_ASSESSMENT_OA](./OBSERVER_ASSESSMENT_OA.md)
- next: [JOB_OBSERVER_ASSESSMENT_JOA](./JOB_OBSERVER_ASSESSMENT_JOA.md)

## Derivation
[goal](../_goal/job_requirement_exercise_jre_goal.md) · [task](../_task/job_requirement_exercise_jre_task.md) ·
[knowledge](../_knowledge/job_requirement_exercise_jre_knowledge.md) · [method](../_method/job_requirement_exercise_jre_method.md) ·
[skill](../_skill/JOB_REQUIREMENT_EXERCISE_JRE/SKILL.md)
