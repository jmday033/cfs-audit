---
name: second-read
description: Review and predict the grade of a BUS 624 Comprehensive Financial Statement (CFS) draft (Step 2 common size, Step 3 ratios, Step 4 strategies draft, or final memo) against the syllabus, the published CFS 1 rubric and recurring instructor feedback patterns. Use when asked to grade, review or check a CFS deck, workbook or memo before submitting.
---

# second-read: BUS 624 CFS draft reviewer

Grades a CFS draft the way the course has been graded so far: a points scorecard against the requirements for that step, a checklist of evidence-based issues, short margin comments, and the few fixes that would move the grade most.

It is a predictor, not the real grade. Only CFS 1 has a published point rubric; the rubrics for Steps 2–4 and the memo are inferred. Say so once in the report.

Read-only: never edit the draft. When a fix sits on a teammate's slide, name the slide and let the team decide who owns it.

## Sources

- `references/syllabus-cfs.md`: the CFS assignment, what each step must contain, and the due dates
- `references/step-rubrics.md`: the published CFS 1 rubric and inferred rubrics for Step 2, Step 3, Step 4 draft and the final memo
- `references/feedback-patterns.md`: recurring patterns in instructor feedback and in the AI comments she shared, generalized for any company

## 1. Identify the draft and the step

- Locate the draft: .pptx, .xlsx, .docx, PDF, or a Google Slides/Sheets/Docs link.
- Work out the step (2 common size, 3 ratios, 4 draft, final memo) from the title or due date. If unclear, ask once.
- Work out which scenario the team chose: the uncertainty option (inflation, elections, AI, policy and so on) or the commodity option (a commodity price moving 75% either way). Judge the "what-if" against that choice.
- Extract slide text, tables and speaker notes, or workbook sheets with formulas. Note hidden slides. Render slides to images when judging visuals.

## 2. Score against the step rubric

Use the matching section of `references/step-rubrics.md`. For each line give points, Yes / Partial / No, and a one-sentence comment that cites the slide or cell. Total it and give the percentage.

## 3. Run the checklist

The order is the review order, not a ranking of the instructor's priorities. For each applicable item record:

- **Status:** Met / Partial / Not met / Not assessed / Not applicable
- **Evidence:** slide, note, cell, paragraph or source section
- **Authority:** `[syllabus]` `[rubric]` `[feedback]` `[shared-AI]` `[inferred]` (see the README)
- **Consequence:** the rubric line it affects, if any

Don't award credit for keywords alone. Don't deduct for `[inferred]` items; report them as advice. Judge each requirement at the stage it applies.

### The story

1. **One central uncertainty.** `[syllabus]` `[shared-AI]` Build the whole what-if around one uncertainty. Secondary risks can appear as constraints on the decision; flag them only when presented as co-equal themes.
2. **Uncertainty → evidence → response.** `[shared-AI]` A clear statement of the uncertainty, the financial metric that evidences it, and the proposed response. Suggested template (optional wording): "Company X's primary operational uncertainty is Y, evidenced by metric Z, which management must address through strategy A."
3. **The diagnosis supports the recommendation.** `[shared-AI]` Trace the opening financial diagnosis to the final recommendation. Separate what drove past margins from forward-looking exposure.
4. **2–3 substantive takeaways per step.** `[syllabus]` Supported by the analysis and tied to the strategy. Analysis slides need a "so what" `[shared-AI]`; supporting slides don't each need their own takeaway.
5. **Takeaways reach a decision.** `[feedback]` A takeaway that stops at "the number is low" scores Partial. Full credit needs the trade-off (e.g., buybacks vs. debt paydown), the sensitivity (e.g., how a commodity move hits the bottom line) or the adjustment (e.g., a peer's non-core revenue) spelled out.

### The numbers

6. **State the basis.** `[feedback]` Entity scope, period, units, and reported / pro forma / adjusted basis for every material comparison. After an acquisition, say which years are pro forma and which are as reported; mixed years distort growth.
7. **Verify growth across acquisitions and odd periods.** `[feedback]` Match period length and definitions (a half-year pro forma is not a full year). Recompute from filings rather than repeating a figure from feedback or an AI tool.
8. **Recompute percentages and mix shifts.** `[feedback]` Text must match tables. Keep % change, percentage-point change, share of revenue and growth rate distinct.
9. **Investigate material expense trends.** `[feedback]` A rising cost line deserves its driver before it is dismissed against the main thesis. Explain supported drivers, name unresolved ones, don't invent causes, don't give immaterial lines equal weight.
10. **Peers on matched definitions and periods.** `[feedback]` `[rubric]` Normalize peers (strip non-core revenue, investment gains, one-time items) and credit teams that do. Where disclosures differ, state the limits instead of ranking.
11. **Keep GAAP, show adjustments separately.** `[shared-AI]` Present special items, integration costs, impairments and peer non-operating items as a reconciliation with reasons, applied consistently across peers.
12. **Trace material claims to original sources.** `[syllabus]` Workbook inputs cite a specific filing; calculated cells stay formulas. A generic footer isn't enough. The syllabus asks teams to verify AI output against source documents.
13. **Verify totals, formulas, units, ratios and signs.** `[inferred]` E.g., a coverage ratio shown as a percentage. Distinguish an uncached value from a wrong formula.
14. **Consistent definitions.** `[inferred]` For ratios, disclose numerator, denominator, averaging, period, and treatment of negative values. Match any management target to its exact metric.
15. **Delivered slides vs. supporting material.** `[feedback]` Assess them separately and flag essential takeaways the audience can't see. The instructor does review the Excel, so hidden work isn't invisible.
16. **Reconcile history with the forward-risk thesis.** `[feedback]` A large exposure need not be what caused the historical margin change; say which is which.
17. **Step coverage.** `[syllabus]` Step 2: three-year horizontal and vertical analysis of both statements, two biggest competitors, industry averages, trends, significant changes, strengths and weaknesses. Step 3: 15 ratios with decision relevance, trends, competitor and industry comparisons, strengths, weaknesses, and how the company is adapting.
18. **Accounting matters relevant to the decision.** `[syllabus]` Revenue recognition and deferred revenue, taxes, leases, pensions, equity and payout, non-cash items, working capital, capex, financing. Use the chapter prompts in the syllabus file as a coverage check; separate required omissions from optional depth.

### The strategy

19. **Customer and market logic.** `[feedback]` Treat growth ideas as hypotheses needing evidence: who buys, whose business you take, how saturated the market is, and how much it will earn.
20. **Capacity isn't revenue.** `[feedback]` More premium seats, stores or capacity don't prove more revenue; locations, routes and demand matter. Assess demand, pricing, contribution, cannibalization and investment.
21. **Capital-allocation feasibility.** `[feedback]` `[shared-AI]` Cash, debt service, capex, liquidity and explicit trade-offs (e.g., buybacks while leverage is above target).
22. **What-if.** `[syllabus]` For the commodity option: +75% and −75% against a stated baseline, the translation from commodity price to expense and to operating income or EPS, strategy costs, residual exposure, labeled assumptions. For the uncertainty option: as-is vs. what-if with the investment amount and downstream impacts.
23. **Step 4 completeness.** `[syllabus]` Qualitative and quantitative support; at least two options compared; SMART objectives; investment, training and maintenance costs; timeline; financial, ethical and operational impacts with reasoned mitigations.
24. **No boilerplate or false precision.** `[shared-AI]` Reject 10-K boilerplate ("use AI", "diversify") without KPIs, dollars and dates. Trace estimates to calculations and plausible ranges.
25. **Explain needed jargon.** `[feedback]` Industry terms get a plain-language line on the slide or in the notes.

### Presentation and completion

26. **Unfinished content.** `[shared-AI]` Placeholders (empty brackets, missing figures) get deductions regardless of design. Don't confuse them with zeros, n/a marks or methodology notes.
27. **Readability.** `[shared-AI]` Bold numeric callouts, clean comparative tables, short bullets, no pasted 10-K paragraphs.
28. **Delivery, only when observed.** `[rubric]` `[feedback]` Handoffs and introductions, timing, speaking to the camera, filler words, conversational delivery. Otherwise mark Not assessed.
29. **Required deliverables.** `[syllabus]` Excel plus PPT with notes for Steps 2–3; PPT and write-up for the Step 4 draft; for the final memo, every required section, individual reflections, and the submission email.
30. **Rank and consolidate.** `[inferred]` Order findings by effect on the decision and the requirements; merge repeated symptoms of one root cause; end with the three highest-impact fixes.

## 4. Write the report

Keep it scannable.

1. **Predicted score:** total and %, one line, plus "inferred rubric" for Step 2 onward.
2. **Scorecard:** rubric lines with points, Yes/Partial/No, one-line comment.
3. **Checklist findings:** status, evidence and tag for each applicable item; `[inferred]` items listed as advice, not deductions.
4. **Margin notes:** by slide number, short and direct, questions first ("Is this pro forma?", "Who are you selling to?", "How much will it get you?"), then a short verdict. Credit what's genuinely good; never invent praise.
5. **Top 3 fixes:** each with slide and the concrete change.
