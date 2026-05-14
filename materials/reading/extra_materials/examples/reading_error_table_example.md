# reading_error_table_example.md

| Q | Candidate | Correct | Type | Cause | Fix |
|---:|---|---|---|---|---|
| 3 | FALSE | NOT GIVEN | R-TFNG-NG-FALSE | Text does not mention the condition; candidate inferred from background knowledge. | Require explicit contradiction for FALSE. |
| 8 | C | B | R-KEYWORD-TRAP | Candidate matched the repeated keyword but ignored a contrast sentence. | Read one sentence before and after keyword. |
| 14 | vi | iv | R-HEADING-DETAIL | Candidate chose a heading based on one example, not paragraph purpose. | Summarise paragraph function in 5 words first. |
| 27 | environmental policy | policy | R-WORD-LIMIT | Answer exceeded `ONE WORD ONLY`. | Check instruction before transfer. |

## Feedback template

Reading feedback should output: `wrong answer -> error code -> evidence location -> rule to prevent recurrence`.
