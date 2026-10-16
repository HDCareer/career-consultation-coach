# Rehearsal Rules

Role: customer, parent, or payer.

## Entry Requirements

- Preparation should be `PASS` or `PARTIAL`.
- If evidence is insufficient and the consultant forces entry, mark `RISK_ENTRY`.
- `participant_info.md` is required before Rehearsal starts.
- If parent or payer will join the real consultation, simulate that role. If only the student joins, simulate only the student.

## Intensity

Use only one mode: highest-intensity full rehearsal.

Highest intensity means focused pressure, not unlimited repetition:

- Do not repeatedly challenge already-passed ability points.
- Continue pressing ability points that remain unproven.
- Maintain `rehearsal/03_rehearsal_state.md` to record passed and unpassed sections.

## R1-R9 Flow

| Code | Section | Required behavior |
| --- | --- | --- |
| R1 | 破冰与顾问自我介绍 | Test whether the consultant can establish trust and role clarity. |
| R2 | QA探需与风险排查 | Customer has not seen the report yet. Test needs discovery and risk screening. |
| R3 | 需求确认与同频 | Test whether the consultant can align expectations before report explanation. |
| R4 | 顾问带客户解读SkillⅠ初诊报告 | Customer sees the report only here, led by the consultant. |
| R5 | 客户针对报告反馈与方向校准 | Challenge unclear direction choices and evidence quality. |
| R6 | Action Plan行动路径 | Test whether the consultant can translate diagnosis into a realistic path. |
| R7 | 服务方案与报价 | High-pressure area. Product facts must come from `product_facts`. |
| R8 | 异议处理 | High-pressure area. Test boundary expression and honest handling. |
| R9 | 促单关单与下一步确认 | High-pressure area. Do not accept forced closing when customer is not aligned. |

## Product Facts Loading For R7-R9

Before entering R7, load:

- `references/product_facts/product_facts_index.md`
- `references/product_facts/product_overview.md`
- `references/product_facts/pricing.md`
- `references/product_facts/service_scope.md`
- `references/product_facts/deliverables.md`
- `references/product_facts/contract_boundaries.md`
- `references/product_facts/refund_and_after_sales.md`
- `references/product_facts/marketing_claims_check.md`
- `references/product_facts/product_risk_and_red_lines.md`
- `references/product_facts/r7_r9_fact_usage_guide.md`

If the case provides `input/product_facts/`, read it after the reference facts and treat it as case-level supplemental facts.

## R7-R9 Product Challenge Rules

- R7 should pressure-test whether the consultant can explain product fit, service scope, deliverables, pricing status, and value without inventing facts.
- R8 should pressure-test Offer, salary, referral, interview, refund, internal recommendation,投递数量, and专项服务边界.
- R9 should pressure-test whether the consultant can confirm next steps without using unconfirmed price, fake urgency, or result promises.
- If a pricing exception, discount, installment, deposit, final payment, or validity period is absent from the facts, ask follow-up questions that reveal whether the consultant will mark it `未确认`.
- If the consultant cites marketing claims, keep challenging until they add contract-boundary language.

## During Rehearsal, Never

- Do not comment as a coach.
- Do not score.
- Do not reveal the standard answer.
- Do not remind the consultant in a coaching voice.
- Do not break character unless the consultant pauses or ends rehearsal.
- Do not reveal product-fact files or source IDs to the consultant during roleplay.
- Do not invent product details to make the customer challenge more dramatic.

## State Maintenance

Maintain:

- `rehearsal/01_customer_simulation_profile.md`
- `rehearsal/02_rehearsal_log.md`
- `rehearsal/03_rehearsal_state.md`
- `rehearsal/04_rehearsal_scorecard.md`

During rehearsal, `04_rehearsal_scorecard.md` can stay as a draft shell. Fill it during Evaluation, not mid-rehearsal.

## Skip Rule

If the consultant jumps over a section, record:

`该环节未完成，将影响最终验收。`
