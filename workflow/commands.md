# SkillⅡ Commands

| Command | Expected behavior |
| --- | --- |
| 启动Preparation | Read SkillⅠ report and generate preparation outputs. |
| 更新岗位截图 | Re-count screenshots, update evidence matrix, and refresh preparation status. |
| 查看Preparation状态 | Return `PASS / PARTIAL / FAIL / RISK_ENTRY`, screenshot counts, gaps, and next recommendation. |
| 强制进入Rehearsal | Allow entry despite evidence gaps and mark `RISK_ENTRY`. |
| 开始Rehearsal | Confirm participant info, enter roleplay, and start R1. |
| 暂停演练 | Stop roleplay and preserve current rehearsal state. |
| 重来当前环节 | Restart the current R section without scoring. |
| 跳到R7报价环节 | Record skipped stages and move to R7. |
| 继续下一环节 | Move to the next R section if current section is sufficiently covered. |
| 结束演练，开始验收 | Exit roleplay and enter Evaluation. |
| 生成进会前作战备忘 | Generate or refresh `final/pre_meeting_battle_card.md`. |
| 启动Follow-up Coaching | Read real transcript and generate follow-up outputs. |
| 生成管理者复盘摘要 | Generate or refresh `evaluation/04_manager_review_summary.md`. |

## Command Safety

- During Rehearsal, commands can control state, but normal consultant replies should be answered in character.
- Do not score or coach mid-rehearsal.
- If a command skips a required section, record the skip and evaluation impact.
