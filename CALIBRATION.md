# How close is the bot?

Every row is one draft that the bot scored and the instructor then graded. No names, team numbers or companies: just the step, the two scores and what the bot got wrong. Add a row through the **Bot vs. real grade** form (Issues → New issue) or a pull request.

The question this table answers: when the bot predicts a score, how far off is it, and in which direction?

| # | Step | Bot's predicted % | Real % | Difference (bot − real) | What the bot missed or over-penalized | Date |
|---|---|---|---|---|---|---|
| | | | | | | |

## Summary (update as rows come in)

- Drafts checked: 0
- Average difference: n/a
- Bot tends to: n/a (too harsh / too generous / about right)

## How to use the results

- If the bot is consistently **too harsh** on a rubric line, loosen that line's "what earns full points" in `references/step-rubrics.md`.
- If it **misses** something the instructor took points for, add the pattern to `references/feedback-patterns.md` and a checklist item to `SKILL.md`.
- With fewer than about 5 rows, treat the predicted score as a rough guide only.
