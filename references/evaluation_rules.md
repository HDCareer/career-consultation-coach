# Evaluation Rules

Role: evaluator.

## Entry Condition

Enter Evaluation only when:

- Consultant says `结束演练，开始验收`; or
- R1-R9 have all been covered.

## Required Outputs

- `evaluation/01_process_coverage_review.md`
- `evaluation/02_capability_matrix_review.md`
- `evaluation/03_risk_expression_review.md`
- `evaluation/04_manager_review_summary.md`
- `evaluation/05_reference_response_coaching.md`
- `rehearsal/04_rehearsal_scorecard.md`
- `final/pre_meeting_battle_card.md`

## Process Coverage

Score each R1-R9 section as:

- `pass`
- `partial`
- `fail`

If a section was skipped, mark `fail` unless the log clearly proves equivalent coverage elsewhere.

## Capability Matrix

Use 1-5 points for each capability:

- Needs discovery
- Risk screening
- Report explanation
- Evidence use
- Direction calibration
- Action Plan clarity
- Product boundary expression
- Pricing and service explanation
- Objection handling
- Closing and next-step confirmation

Read `references/evaluation_rubric.md` for the concrete 1-5 scoring anchors.

## Final Readiness

Use a 100-point readiness score.

Recommended weighting:

- Process coverage: 40 points.
- Capability matrix: 40 points.
- Risk expression and boundary control: 20 points.

Recommended interpretation:

- 85-100: allow real consultation.
- 70-84: allow with manager watch items or focused prep.
- 60-69: require targeted re-practice before real consultation.
- Below 60: do not enter real consultation.

## One-Vote Veto Items

List all observed veto items:

- Promised Offer.
- Promised salary.
- Promised referral.
- Implied guaranteed interview.
- Fabricated job resources.
- Fabricated customer experience.
- Packaged course project as real business outcome.
- Packaged team outcome as individual outcome.
- Pricing or product facts inconsistent with confirmed product facts.
- Forced closing when the customer was clearly not aligned.
- Invented price or service content without product-fact evidence.
- Used marketing claims as result promises without contract-boundary correction.
- Claimed refund, after-sales, parent service, or payment terms that are not confirmed in product facts.
- Expanded internal recommendation or投递管理 into guaranteed referral, guaranteed interview, or guaranteed Offer.

If any one-vote veto item appears, mark real-consultation readiness as blocked until reviewed by a manager.

## Product Facts Review

When evaluating R7-R9, read `references/product_facts/` and check:

- Did the consultant cite only confirmed service scope, deliverables, contract, refund, and pricing facts?
- Did the consultant cite confirmed pricing and payment rules accurately, and mark absent特殊例外、渠道价、价格有效期、赠品、加购折扣 as `未确认`?
- Did the consultant explain product fit from the customer's case, not from a generic product pitch?
- Did the consultant correct high-risk marketing claims with contract-boundary language?
- Did the consultant avoid promising Offer, salary, referral success, guaranteed interview, or target-company result?
- Did the consultant avoid creating new product commitments during objection handling or closing?

Record product-fact issues in `evaluation/03_risk_expression_review.md` and include manager watch items in `evaluation/04_manager_review_summary.md`.

## Reference Response Coaching

After Evaluation starts, generate this fixed Evaluation output:

- `evaluation/05_reference_response_coaching.md`

Chinese name: 参考回答与话术改写建议.

Read `references/reference_response_coaching_rules.md` and use `templates/evaluation/05_reference_response_coaching_template.md`.

This output is for consultant review and training only. It is not a fixed script library, does not require word-for-word memorization, and must not be used as the only scoring standard.

Generate reference responses only for:

- Answers evaluated as `PARTIAL`.
- Answers evaluated as `FAIL`.
- High-risk consultant wording.
- Answers that did not respond to the customer's real concern.
- Answers that were too vague or generic.
- Answers that did not explain service boundaries clearly.
- Answers that did not connect service value to the customer's case-specific bottleneck.
- Answers that did not complete a reasonable close or next-step confirmation.

If an answer is already strong, do not force a rewrite. Mark it as:

> 本题回答可作为优秀表达候选。

Reference responses must not add customer facts, product facts, service commitments, Offer promises, salary promises, referral promises, guaranteed interview implications, or contract commitments not supported by confirmed facts.

For price, payment, refund, service scope, deliverables, service period, and contract boundaries, cite `references/product_facts/` or case-level confirmed facts. If no confirmed basis exists, write `以正式合同/服务文件为准` or `该项需进一步确认`.

## Manager Review Summary

Write `04_manager_review_summary.md` for manager reading. Include:

- Overall readiness.
- Highest-risk sections.
- Evidence gaps.
- Product-fact risks.
- Required re-practice.
- Reference response generation status.
- Go / no-go recommendation.
