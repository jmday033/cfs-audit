# second-read

A second reader for BUS 624 CFS drafts (UH Shidler DLEMBA, Fall 2026). Give it your deck, workbook or memo and it returns a predicted score, a checklist of what's missing, margin-style comments, and the three fixes most likely to move your grade.

It is a **predictor, not the grade**. Use it to catch gaps before you submit, not to argue with a score.

## How to use it

**ChatGPT, Claude or Copilot (no setup):** upload `SKILL.md` and the three files in `references/` together with your draft, then ask: *"Grade this draft following the second-read instructions."*

**Claude skill:** copy this folder into your skills directory (or upload it as a skill in Claude). It triggers when you ask Claude to review or grade a CFS draft.

Tell it which step the draft is for (Step 2 common size, Step 3 ratios, Step 4 draft, or the final memo) if the file name doesn't make it obvious.

## How we derived it

Built in November 2026 by a DLEMBA student, then generalized for the class. Every rule in it is tagged with where it came from, so you can see what's a real requirement and what's a guess:

| Tag | Source | How much to trust it |
|---|---|---|
| `[syllabus]` | The CFS section of the Fall 2026 BUS 624 syllabus (paraphrased in `references/syllabus-cfs.md`) | Published requirement |
| `[rubric]` | The published CFS 1 point rubric | Published, CFS 1 only |
| `[feedback]` | Recurring patterns in instructor feedback on CFS 1 and CFS 2, generalized so no team, company or student is identifiable | Her stated priorities, but drawn from one team's drafts |
| `[shared-AI]` | The sanitized, composite AI-generated comments the instructor shared alongside the CFS 1 rubric | Signals what she values; not her own grading |
| `[inferred]` | Our own inference, e.g. the point rubrics for Steps 2–4 and the memo | A guess, built to the CFS 1 rubric's shape |

The process:

1. **Syllabus first.** Each step's required content was turned into checklist items and rubric lines.
2. **The one published rubric.** CFS 1's point rubric set the format: content lines worth 5 points, an extra weighted "strategic uncertainty" line, plus live presentation.
3. **Feedback patterns.** One team's CFS 1 scores and CFS 2 margin notes were read for what cost points. Only patterns that would apply to any company were kept: every "Partial" was a takeaway that never reached a decision, the basis of the numbers (reported vs. pro forma vs. adjusted) had to be stated, and peers had to be normalized. The team's scores, notes and company details are **not** in this repo.
4. **Red team.** The checklist was run through a separate AI review (ChatGPT) to find gaps and overreach, then rechecked against the original sources. Anything not traceable to a source was re-tagged `[inferred]` or dropped.
5. **Inferred rubrics.** Steps 2–4 and the final memo have no published point rubric, so those in `references/step-rubrics.md` are built from the syllabus plus the feedback patterns. Replace them as soon as real ones are published.

## Limits

- The rubrics for Steps 2–4 and the memo are inferred, not published.
- The feedback patterns come from one team's drafts. Your instructor feedback may stress other things; add it (see below).
- AI graders can sound confident and still be wrong. Check every number it flags against your own workbook.
- Not affiliated with or endorsed by the instructor or the University of Hawaiʻi. Follow the syllabus AI policy: verify against source documents and make the analysis your own.

## Contributing

Classmates are welcome to improve it:

- **New feedback?** Add the pattern (not your team's grades or private comments) to `references/feedback-patterns.md` with a tag, and add a checklist item to `SKILL.md` if it recurs.
- **A real rubric gets published?** Replace the matching inferred section in `references/step-rubrics.md` and change its tag to `[rubric]`.
- Open a pull request, or fork it and make it your own.

Please keep it free of grades, names, and anything a teammate shared privately.
