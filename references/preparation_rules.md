# Preparation Rules

Role: coach.

## Required Input

Read `input/pre_consultation_report.md` from SkillⅠ. If no Markdown exists, read HTML. Do not request `handoff.json` and do not modify SkillⅠ.

## Optional Input

- `input/latest_context.md`: only new information after SkillⅠ report generation.
- `input/participant_info.md`: real consultation participants, parent or payer involvement, planned pricing discussion, and whether the customer already knows pricing.
- `input/product_facts/`: product facts if provided.

## Work Steps

1. Extract main direction, backup direction, and high-risk or not-recommended direction.
2. Extract customer advantages, key gaps, risk points, and open questions.
3. Generate a job-search map based on general knowledge.
4. Tell the consultant which platforms to search manually, such as BOSS直聘, 猎聘, LinkedIn, and company official websites.
5. Use screenshots as default job evidence.
6. If screenshots are not readable, request only minimal fields: job title, company, platform, visible requirements, visible responsibilities, location, and screenshot source.
7. Convert screenshots into a job evidence matrix.
8. Build the direction evidence chain.
9. Build the consulting ammo bank.
10. Identify deal risks.
11. Decide whether the case can enter Rehearsal.

## Screenshot Minimum

- Main direction: at least 5 screenshots.
- Backup direction: at least 2 screenshots.
- Counter-example or not-recommended direction: at least 1 screenshot.

## Status Rules

Use one of:

- `PASS`: evidence and preparation are sufficient.
- `PARTIAL`: usable but gaps remain.
- `FAIL`: not enough to rehearse responsibly.
- `RISK_ENTRY`: evidence is insufficient but the consultant explicitly forces entry to Rehearsal.

## Required Outputs

- `preparation/01_preparation_plan.md`
- `preparation/02_job_evidence_matrix.md`
- `preparation/03_direction_evidence_chain.md`
- `preparation/04_consulting_ammo_bank.md`
- `preparation/05_preparation_status.md`

`05_preparation_status.md` must include screenshot counts, current gaps, risk label, and whether Rehearsal is recommended.
