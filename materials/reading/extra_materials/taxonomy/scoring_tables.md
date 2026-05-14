# scoring_tables.md

依据：IELTS scoring in detail 页面，2026-05-14 核验。

## Overall band rounding

总体分 = Listening / Reading / Writing / Speaking 四项平均值，四舍五入到最接近的整分或半分。

- 平均分尾数 `.25`：进到下一半分，例如 `6.25 -> 6.5`。
- 平均分尾数 `.75`：进到下一整分，例如 `6.75 -> 7.0`。
- 例：`6.5, 6.5, 5.0, 7.0` 平均 `6.25`，overall `6.5`。

## Listening raw score anchors

官方说明：40 题，每题 1 分；不同版本所需分数会轻微变化。以下是官方给出的 average number of marks anchors。

| Band | Raw score out of 40 |
|---:|---:|
| 5 | 16 |
| 6 | 23 |
| 7 | 30 |
| 8 | 35 |

## Academic Reading raw score anchors

| Band | Raw score out of 40 |
|---:|---:|
| 5 | 15 |
| 6 | 23 |
| 7 | 30 |
| 8 | 35 |

## General Training Reading raw score anchors

| Band | Raw score out of 40 |
|---:|---:|
| 4 | 15 |
| 5 | 23 |
| 6 | 30 |
| 7 | 35 |

## Skill implementation note

不要把这些 anchor 扩展成“精确完整换算表”，除非另有官方表格。skill 输出 raw-score 判断时应写：`official anchor-based estimate; exact cutoffs vary by test version`。
