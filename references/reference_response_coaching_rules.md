# Reference Response Coaching Rules

## 1. Positioning

Reference Response Coaching is an Evaluation-stage output.

It provides case-specific reference responses and rewrite suggestions for consultant review after rehearsal ends. It is not a fixed script library and does not require consultants to memorize or repeat the sample wording.

Evaluation still scores the consultant by consulting-action completion, evidence use, boundary expression, product-fact accuracy, risk control, and customer progression effect.

Chinese name: 参考回答与话术改写建议.

Evaluation must treat `evaluation/05_reference_response_coaching.md` as a fixed output, but the content remains case-specific. It must not be converted into a fixed script library.

## 2. Entry Boundary

Generate reference responses only after entering Evaluation.

During Rehearsal, SkillⅡ must still only play customer, parent, or payer. It must not:

- Comment on the consultant's answer.
- Score the consultant.
- Reveal standard answers.
- Provide reference responses.
- Coach the consultant mid-session.

## 3. When to Generate Reference Responses

Generate a reference response only for questions where at least one condition applies:

1. The consultant answer is evaluated as `PARTIAL`.
2. The consultant answer is evaluated as `FAIL`.
3. The consultant used high-risk wording.
4. The consultant did not respond to the customer's real concern.
5. The consultant answer was too vague or generic.
6. The consultant did not explain the service boundary clearly.
7. The consultant did not connect service value to the customer's case-specific bottleneck.
8. The consultant did not complete a reasonable close or next-step confirmation.

If a consultant answer is already strong, do not force a rewrite. Mark it as:

> 本题回答可作为优秀表达候选。

## 4. Reference Response Boundaries

Reference responses must follow these boundaries:

1. Do not add customer facts.
2. Do not add product facts.
3. Do not add service commitments.
4. Do not promise Offer.
5. Do not promise salary.
6. Do not promise referral.
7. Do not imply guaranteed interview.
8. Do not turn marketing language into contract commitments.
9. Do not package course projects as real business outcomes.
10. Do not package team outcomes as individual outcomes.
11. For price, payment, refund, service scope, deliverables, service period, and contract boundaries, use only `references/product_facts/` or case-level confirmed product facts.
12. If product facts do not provide a confirmed basis, write `以正式合同/服务文件为准` or `该项需进一步确认`.
13. Improve clarity and persuasion, but never cross service boundaries.

## 5. Output File

Evaluation must generate:

```text
evaluation/05_reference_response_coaching.md
```

Use:

```text
templates/evaluation/05_reference_response_coaching_template.md
```

## 6. Required Content

The file should include:

- Overall note explaining that the file is for review and training only.
- A list of questions that need improvement.
- Per-question diagnosis.
- Case-specific reference answer.
- Why the rewritten answer is better.
- Alternative expressions.
- Forbidden expressions.
- Evidence sources.
- Strong answer candidates that can be retained.
- Next targeted re-practice suggestions.

## 7. Evidence Requirements

Each generated reference answer must cite the basis from:

- SkillⅠ pre-consultation report.
- Rehearsal log.
- Product facts.
- Confirmed case inputs such as `latest_context.md` or `participant_info.md`.

Do not use unsupported assumptions.
