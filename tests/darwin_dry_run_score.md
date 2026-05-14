# Darwin Dry-Run Score

本评分按 `darwin-skill-master/SKILL.md` 的 8 维 rubric 做干跑评估。当前目录不是 git 仓库，且本轮未启动子 agent，因此 `eval_mode=dry_run`。

## Score

| 维度 | 权重 | 分数 | 加权分 | 依据 |
|------|------|------|--------|------|
| Frontmatter质量 | 8 | 8 | 64 | description 有用途、范围和触发词；仍保留非最小字段 |
| 工作流清晰度 | 15 | 9 | 135 | SKILL.md 有输入路由和依据核验步骤 |
| 边界条件覆盖 | 10 | 9 | 90 | Pronunciation、raw score、第三方资料冲突均有边界 |
| 检查点设计 | 7 | 8 | 56 | 二稿复盘和训练目标明确；长期训练确认点还可更细 |
| 指令具体性 | 15 | 9 | 135 | 输出结构、材料目录、测试验收均具体 |
| 资源整合度 | 5 | 9 | 45 | references、materials、tests 已接入 manifest |
| 整体架构 | 15 | 9 | 135 | 听说读写分科，额外资料和用户练习原稿分层 |
| 实测表现 | 25 | 8 | 200 | 有 test-prompts 和 expected behaviour；尚未做子 agent 实测 |

总分：`(64+135+90+56+135+45+135+200)/10 = 86.0`

## Remaining Bottleneck

最主要短板是“实测表现”仍为 dry run。下一步若要继续 Darwin 式优化，应让独立 agent 用 `test-prompts.json` 跑一轮，并把输出对照 `tests/expected_behaviour.md` 打分。

