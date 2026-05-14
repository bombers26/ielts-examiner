# IELTS Examiner Quality Checklist

按 Darwin Skill 的 8 维 rubric 改写为本 skill 的人工/干跑检查表。

## 结构维度

| 维度 | 检查项 |
|------|--------|
| Frontmatter | `name` 清晰；`description` 同时包含用途、触发词、覆盖范围；不夸大“官方考官”身份 |
| 工作流清晰度 | SKILL.md 能把输入路由到考官模式、分数模式、资料导入模式、教学老师模式、二稿复盘模式 |
| 边界条件 | 文字稿不能评 Pronunciation；raw score 只能 anchor-based estimate；第三方资料需分级 |
| 检查点 | 长期训练、资料吸收、二稿复盘前需确认用户目标或上一轮目标 |
| 指令具体性 | 每种输出都能落到 band / 证据 / 改写 / 训练任务 / 验收标准 |
| 资源整合度 | SKILL.md 能指向 `references/`、`materials/*/INDEX.md`、`test-prompts.json` |

## 效果维度

| 维度 | 检查项 |
|------|--------|
| 整体架构 | 资料按 Listening / Speaking / Reading / Writing 分科，额外资料与用户练习原稿清楚分开 |
| 实测表现 | 跑 `test-prompts.json` 后，输出满足 `tests/expected_behaviour.md`，并明显优于通用 ChatGPT 式泛泛反馈 |

## 失败信号

- 把预估分数说成官方成绩。
- 对只有文字稿的口语给 Pronunciation 分数。
- 把第三方机构讲义当官方评分标准。
- 对二稿重新全量批改，忽略上一轮训练目标。
- raw score 换算说成固定精确表。
- 输出没有下一轮训练任务。

