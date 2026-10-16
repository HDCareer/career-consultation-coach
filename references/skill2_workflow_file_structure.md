# SkillⅡ Workflow File Structure

## Skill Directory

```text
career-consultation-coach/
├── SKILL.md
├── README.md
├── references/
├── templates/
└── workflow/
```

## Case Directory

Create one independent directory for each customer case:

```text
<外部私有案例根目录>/
└── CASE-YYYYMMDD-匿名编号/
    ├── input/
    │   ├── pre_consultation_report.md
    │   ├── latest_context.md
    │   ├── participant_info.md
    │   └── product_facts/
    ├── screenshots/
    │   ├── main_direction/
    │   ├── backup_direction/
    │   └── counter_examples/
    ├── preparation/
    │   ├── 01_preparation_plan.md
    │   ├── 02_job_evidence_matrix.md
    │   ├── 03_direction_evidence_chain.md
    │   ├── 04_consulting_ammo_bank.md
    │   └── 05_preparation_status.md
    ├── rehearsal/
    │   ├── 01_customer_simulation_profile.md
    │   ├── 02_rehearsal_log.md
    │   ├── 03_rehearsal_state.md
    │   └── 04_rehearsal_scorecard.md
    ├── evaluation/
    │   ├── 01_process_coverage_review.md
    │   ├── 02_capability_matrix_review.md
    │   ├── 03_risk_expression_review.md
    │   └── 04_manager_review_summary.md
    ├── follow_up/
    │   ├── consultation_transcript.md
    │   ├── 01_consultation_recap_for_sales.md
    │   ├── 02_customer_conversion_status.md
    │   ├── 03_follow_up_action_plan.md
    │   └── 04_next_contact_script_optional.md
    └── final/
        └── pre_meeting_battle_card.md
```

## Input Rules

- Required: `input/pre_consultation_report.md`.
- If Markdown is unavailable, read SkillⅠ report HTML.
- Optional: `latest_context.md`, `participant_info.md`, `product_facts/`.
- Do not ask SkillⅠ to generate extra handoff files.
- Do not modify SkillⅠ source or output files.

## Screenshot Rules

- Main direction screenshots: at least 5.
- Backup direction screenshots: at least 2.
- Counter-example or not-recommended direction screenshots: at least 1.
- Default to screenshots as evidence. Ask for minimal text fields only when screenshots cannot be identified.
