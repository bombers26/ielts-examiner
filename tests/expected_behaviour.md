# Expected Behaviour

本文件定义 `test-prompts.json` 的验收标准。它用于 Darwin-style dry run 或后续子 agent 实测，不作为用户输出模板直接照抄。

## 全局要求

- 先给结论：预估 band、最大瓶颈或可信度判断。
- 每个评分判断必须绑定用户原文、错题记录或官方评分维度。
- 资料不足时写“无法可靠判断”，不要编造缺失信息。
- 输出最后必须有一个最小训练任务或下一步。
- 第三方资料与官方标准冲突时，以官方标准为准，同时保留可用部分。

## Prompt 验收点

### writing-task1-feedback

必须出现：
- 预估 band，带置信度或“estimate”说明。
- 四项诊断：TA / CC / LR / GRA。
- 指出缺少 clear overview、chronological/data dump、unsupported opinion。
- 给出一个重写 overview 的训练任务和验收标准。

不得出现：
- 把“museums are important for tourism”当成合理 Task 1 结论。
- 只给泛泛鼓励，不给原文证据。

### speaking-text-only

必须出现：
- Pronunciation 无法可靠评分，因为没有录音。
- 文字稿可评估 FC / LR / GRA。
- 指出词汇重复、展开不足、句式单一。

不得出现：
- 给 Pronunciation 精确分数。
- 假装听到了语音、语调或发音问题。

### reading-gt-raw-score

必须出现：
- General Training Reading 与 Academic Reading 不是同一 anchor。
- GT Reading 30/40 约 Band 6 anchor-based estimate。
- cut-off 会随试卷版本浮动。

不得出现：
- 把 30/40 直接按 Academic Reading 判 Band 7。
- 给出“官方固定完整换算表”。

### student-material-conflict

必须出现：
- 来源可信度判断，默认机构讲义为 T3，来源不明可降为 T0/T3。
- 官方评分标准不强制五段。
- 过度机械使用 Firstly/Secondly/Thirdly 会影响自然衔接。
- 可保留“段落清晰”这个训练目标，但不把固定句式当铁律。

不得出现：
- 把机构讲义当官方标准。
- 直接全盘否定所有第三方资料。

### second-draft-review

必须出现：
- 只检查上一轮目标：overview。
- 给出通过/部分通过/未通过。
- 如果通过，下一步再进入 body grouping 或 data support。

不得出现：
- 重新进行完整四项批改。
- 引入与 overview 无关的新任务。

