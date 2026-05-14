# error_taxonomy.md

用途：让 IELTS skill 批改时输出可归类、可复查、可训练的反馈。

## Writing errors

| code | 名称 | 触发条件 | 影响维度 | 修复方向 |
|---|---|---|---|---|
| W-TA-OVERVIEW-MISSING | overview 缺失 | Task 1 没有总体特征段 | TA | 加 1-2 句总览 |
| W-TA-DATA-DUMP | 数据堆砌 | 逐项列数字，缺少筛选比较 | TA/CC | 按趋势/极值/组别重组 |
| W-TR-PARTIAL-ANSWER | 漏答问项 | Task 2 少答一问或少给观点 | TR | 回到 prompt 拆问项 |
| W-CC-COMMA-SPLICE | comma splice | 两个独立句只用逗号连接 | CC/GRA | 句号、分号或连接词 |
| W-CC-MECHANICAL-LINKERS | 连接词机械 | firstly/secondly/therefore 堆叠 | CC | 用逻辑关系替代模板连接 |
| W-LR-COLLOCATION | 搭配错误 | e.g. do a progress, big increase inappropriately | LR | 查搭配，使用高频准确表达 |
| W-LR-MEMORISED | 背诵痕迹 | 套句与题目关系弱或过度华丽 | LR/TR | 换成题目相关表达 |
| W-GRA-SVA | 主谓一致 | third-person singular/plural mismatch | GRA | 标出主语核心词 |
| W-GRA-ARTICLE | 冠词错误 | a/an/the/zero article misuse | GRA | 判断可数、特指、泛指 |
| W-GRA-FRAGMENT | 句子残缺 | 缺主语/谓语或从句独立成句 | GRA | 补完整主句 |

## Speaking errors

| code | 名称 | 影响维度 | 诊断重点 |
|---|---|---|---|
| S-FC-HESITATION | 停顿过多 | FC | 停顿是否因找词/语法导致 |
| S-FC-UNDEREXTEND | 回答过短 | FC | 是否缺少扩展和例子 |
| S-LR-REPETITION | 词汇重复 | LR | 是否反复使用 basic words |
| S-GRA-SIMPLE-ONLY | 结构单一 | GRA | 是否几乎只有简单句 |
| S-P-WORD-STRESS | 重音/节奏问题 | P | 是否影响理解 |
| S-P-MISPRONUNCIATION | 发音错误 | P | 是否造成理解成本 |

## Reading errors

| code | 名称 | 常见题型 | 修复方向 |
|---|---|---|---|
| R-TFNG-NG-FALSE | False/Not Given 混淆 | TFNG/YNNG | False 要有文本反证；NG 是无信息 |
| R-KEYWORD-TRAP | 关键词定位陷阱 | all | 定位后读完整句和转折 |
| R-HEADING-DETAIL | heading 被细节诱导 | matching headings | 先找段落主功能 |
| R-PARAPHRASE-MISS | 同义替换未识别 | all | 建立 paraphrase pair |
| R-WORD-LIMIT | 超词数 | completion | 逐字检查 NO MORE THAN |

## Listening errors

| code | 名称 | 常见题型 | 修复方向 |
|---|---|---|---|
| L-SPELLING | 拼写错误 | completion | 建立错词表，复听拼写 |
| L-SINGULAR-PLURAL | 单复数错误 | completion | 听冠词/数量词/语境 |
| L-WORD-LIMIT | 词数超限 | completion | 答案前检查 instruction |
| L-DISTRACTOR | 干扰项 | multiple choice/completion | 标记否定、改口、纠正 |
| L-MAP-DIRECTION | 方位迷失 | map/plan | 预读入口、方向、参照物 |
