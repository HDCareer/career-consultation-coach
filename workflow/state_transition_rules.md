# State Transition Rules

## States

- `NEW_CASE`
- `PREPARATION_RUNNING`
- `PREPARATION_PASS`
- `PREPARATION_PARTIAL`
- `PREPARATION_FAIL`
- `RISK_ENTRY`
- `REHEARSAL_RUNNING`
- `REHEARSAL_PAUSED`
- `EVALUATION_RUNNING`
- `READY_FOR_REAL_CONSULTATION`
- `REQUIRES_REPRACTICE`
- `FOLLOW_UP_RUNNING`
- `FOLLOW_UP_COMPLETE`

## Transitions

| From | Trigger | To | Rule |
| --- | --- | --- | --- |
| NEW_CASE | 启动Preparation | PREPARATION_RUNNING | Required report must exist. |
| PREPARATION_RUNNING | Status PASS | PREPARATION_PASS | Evidence sufficient. |
| PREPARATION_RUNNING | Status PARTIAL | PREPARATION_PARTIAL | Usable with gaps. |
| PREPARATION_RUNNING | Status FAIL | PREPARATION_FAIL | Do not recommend rehearsal. |
| PREPARATION_FAIL / PREPARATION_PARTIAL | 强制进入Rehearsal | RISK_ENTRY | Record risk entry. |
| PREPARATION_PASS / PREPARATION_PARTIAL / RISK_ENTRY | 开始Rehearsal | REHEARSAL_RUNNING | Participant info required. |
| REHEARSAL_RUNNING | 暂停演练 | REHEARSAL_PAUSED | Preserve state. |
| REHEARSAL_PAUSED | 继续下一环节 | REHEARSAL_RUNNING | Resume from saved state. |
| REHEARSAL_RUNNING | 结束演练，开始验收 | EVALUATION_RUNNING | Exit roleplay. |
| EVALUATION_RUNNING | Ready score passes and no veto | READY_FOR_REAL_CONSULTATION | Manager watch items may still apply. |
| EVALUATION_RUNNING | Low score or veto | REQUIRES_REPRACTICE | Recommend targeted re-practice. |
| READY_FOR_REAL_CONSULTATION | 启动Follow-up Coaching | FOLLOW_UP_RUNNING | Real transcript required. |
| FOLLOW_UP_RUNNING | Outputs complete | FOLLOW_UP_COMPLETE | Internal follow-up plan complete. |
