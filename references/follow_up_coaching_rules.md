# Follow-up Coaching Rules

Role: coach.

## Entry Input

Use the real post-consultation transcript:

```text
follow_up/consultation_transcript.md
```

The same transcript may also be used by SkillⅠ to generate the final customer report and 14-day customer action checklist. SkillⅡ must not generate those customer-facing outputs.

## Required Outputs

- `follow_up/01_consultation_recap_for_sales.md`
- `follow_up/02_customer_conversion_status.md`
- `follow_up/03_follow_up_action_plan.md`
- `follow_up/04_next_contact_script_optional.md`

The fourth file is optional support, not the core deliverable.

## Analysis Required

Identify:

- Sales-view consultation recap.
- Current customer conversion status.
- What the customer accepted.
- What the customer still hesitates about.
- Where the consultant explained clearly.
- Where the consultant did not explain enough.
- Next follow-up entry point.
- Whether to continue conversion.
- Whether to slow down.
- Whether not to convert.
- Follow-up Action Plan.
- Optional WeChat follow-up draft.

## Product Facts Boundary

For product, price, contract, delivery, or service-boundary claims, cite only `references/product_facts/` or the case's `input/product_facts/`.

If facts are missing, mark `未确认` and recommend internal confirmation before follow-up.

Before judging product claims or writing product-related follow-up next steps, read:

- `references/product_facts/product_facts_index.md`
- `references/product_facts/pricing.md`
- `references/product_facts/service_scope.md`
- `references/product_facts/deliverables.md`
- `references/product_facts/contract_boundaries.md`
- `references/product_facts/refund_and_after_sales.md`
- `references/product_facts/marketing_claims_check.md`
- `references/product_facts/product_risk_and_red_lines.md`
- `references/product_facts/follow_up_product_usage_guide.md`

## Follow-up Product Rules

- Base follow-up on the real transcript first, then use product facts to verify what can be said next.
- Do not add new product promises that did not appear in the transcript and are not confirmed in product facts.
- If the customer's hesitation is price-related and pricing is unconfirmed, mark the next step as internal quote confirmation.
- If the customer's hesitation is result-related, use contract-boundary facts; do not answer with Offer, salary, referral, or interview promises.
- Optional WeChat drafts are reference drafts only, not a script library.
