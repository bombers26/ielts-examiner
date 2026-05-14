# Source Map

本文件把 `ielts-examiner` 的资料来源、可信度等级和使用位置绑定起来，避免官方资料、外部资料和自造样例混用。

## 可信度等级

| 等级 | 含义 | 用法 |
|------|------|------|
| T1 | IELTS / British Council / IDP / Cambridge 官方或联合主办方来源 | 可作为评分、格式和样题依据 |
| T2 | 半官方或授权教材线索 | 可辅助解释，但不得覆盖 T1 |
| T3 | 机构讲义、高分考生经验、第三方备考资料 | 需逐条与 T1 对齐 |
| T4 | 用户自己的练习、错题、笔记 | 只作为个性化诊断材料 |
| T0 | 来源不明或营销材料 | 标注风险，不作为核心依据 |

## Core Official Files

| 文件 | 来源等级 | 用途 | 位置 |
|------|----------|------|------|
| `ielts-writing-band-descriptors.pdf` | T1 | Writing Task 1/2 band descriptor | `materials/writing/extra_materials/official/` |
| `ielts-writing-key-assessment-criteria.pdf` | T1 | Writing 四项评分标准速查 | `materials/writing/extra_materials/official/` |
| `ielts-academic-writing-sample-tasks-2023.pdf` | T1 | Academic Writing 官方样题 | `materials/writing/extra_materials/official/` |
| `ielts-general-training-writing-sample-tasks-2023.pdf` | T1 | GT Writing 官方样题 | `materials/writing/extra_materials/official/` |
| `ielts-speaking-band-descriptors.pdf` | T1 | Speaking band descriptor | `materials/speaking/extra_materials/official/` |
| `ielts-speaking-key-assessment-criteria.pdf` | T1 | Speaking 四项评分标准速查 | `materials/speaking/extra_materials/official/` |
| `ielts-listening-sample-tasks-2023.pdf` | T1 | Listening 官方样题 | `materials/listening/extra_materials/official/` |
| `ielts-academic-reading-sample-tasks-2023.pdf` | T1 | Academic Reading 官方样题 | `materials/reading/extra_materials/official/` |
| `ielts-general-reading-sample-tasks-2023.pdf` | T1 | GT Reading 官方样题 | `materials/reading/extra_materials/official/` |

## Derived Taxonomy

| 文件 | 来源等级 | 用途 | 注意 |
|------|----------|------|------|
| `scoring_tables.md` | T1-derived | Listening / Reading raw score anchor 和 overall rounding | 只做 anchor-based estimate，不扩展为固定完整表 |
| `task1_patterns.md` | T1/T2-derived | Task 1 题型策略 | 不复制真题集完整内容 |
| `task2_question_types.md` | T1/T2-derived | Task 2 问题类型与回应策略 | 以官方 Task Response 为准 |
| `error_taxonomy.md` | T1/T3-derived | 写作、口语、听力、阅读错因标签 | 用于诊断，不作为官方评分原文 |
| `vocabulary_bank.md` | T3-derived | 可控词汇升级 | 优先准确，不推荐罕见词堆砌 |

## Examples

| 文件 | 来源等级 | 用途 |
|------|----------|------|
| `task1_feedback_example.md` | T4/example | Task 1 批改输出示范 |
| `task2_feedback_example.md` | T4/example | Task 2 批改输出示范 |
| `speaking_feedback_example.md` | T4/example | 只有文字稿时的口语反馈示范 |
| `reading_error_table_example.md` | T4/example | 阅读错题归因示范 |
| `listening_error_table_example.md` | T4/example | 听力错题归因示范 |
| `institution_handout_alignment.md` | T3/example | 第三方讲义与官方标准对齐示范 |

## User Practice Drafts

`materials/*/user_practice_drafts/` 中的文件默认属于 T4，只能用于当前用户的诊断和训练规划。不要把用户练习原稿推广成通用标准。

