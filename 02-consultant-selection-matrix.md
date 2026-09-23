# Consultant/Provider Selection Matrix

Datimpacto · MEL Community of Practice Toolkit · Tool 2

Purpose: run a selection you can explain and defend, to your team, your donor and the bidders who did not win.
When to use: set the criteria and weights before the call goes out, then score each proposal against them.
Time needed: about 30 minutes to set up, 20 to 40 minutes per proposal to score by hand. The AI-assisted triage below runs in about 5 minutes per proposal, 10 minutes to verify, and comes before the panel scores.

## Stage 1. Exclusionary Criteria (Pass/Fail)

A proposal that fails any of these is out. There is no negotiation after the deadline.

| Criterion              | Pass looks like                                                                             | Result      |
| ---------------------- | ------------------------------------------------------------------------------------------- | ----------- |
| Minimum qualifications | Team lead meets the stated years of experience and sector background                        | Pass / Fail |
| Language               | Team can work in the languages the ToR requires, including for fieldwork                    | Pass / Fail |
| Availability           | Team can start and deliver inside the dates in the ToR                                      | Pass / Fail |
| Complete submission    | Every required document is present (technical proposal, budget, CVs, references)            | Pass / Fail |
| Compliance             | Legal registration, safeguarding and data protection policies as your organization requires | Pass / Fail |

## Stage 2. Weighted Criteria (Scored)

Publish the weights in the ToR. The example below is a starting point; adjust it to your context.

| Criterion                  | Example weight | A high score (4) looks like                                                | A low score (0 to 1) looks like                                                       |
| -------------------------- | -------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Technical proposal quality | 35%            | Shows they understood the program, the users and the questions             | Generic text that could fit any engagement                                            |
| Methodology fit            | 35%            | Methods, sample and timeline match the questions and the field constraints | Methods that cannot answer the priority questions, or a timeline that does not add up |
| Cost                       | 30%            | Realistic budget within the ceiling, clearly broken down                   | Lump sums, or a price far below the others with no explanation                        |

Scoring scale: 0 = not addressed, 1 = weak, 2 = adequate, 3 = good, 4 = strong.

Converting cost to a score: a common approach is (lowest price / this bidder's price) × cost weight. Flag any bid that is much lower than the rest and ask how it covers the proposed work.

## Scoring Sheet

| Bidder | Stage 1 | Technical (×0.35) | Methodology (×0.35) | Cost (×0.30) | Total | Notes |
|--------|---------|-------------------|---------------------|--------------|-------|-------|
| A | Pass | | | | | |
| B | Pass | | | | | |
| C | Fail (no budget breakdown) | n/a | n/a | n/a | n/a | |

## Stage 3. The Human Call

- At least two people score each proposal on their own, then meet to reconcile differences.
- An AI assistant can do the first-pass triage below: missing documents, methodology and timeline mismatches. It does not score or rank.
- The final decision, including any relationship or equity dimension (local firms, team diversity, prior performance), stays with the panel. Write down the reason in two or three sentences.

---

## AI-Assisted First-Pass Triage

Purpose: check each proposal against the exclusionary and weighted criteria above and catch gaps before the panel starts scoring.
When to use: after the submission deadline, one proposal at a time, before Stage 3 scoring.

### What You Need

- The ToR, or at least its requirements, priority questions and timeline.
- The exclusionary and weighted criteria from Stage 1 and Stage 2 above.
- One proposal (technical proposal, workplan and budget).

Data note: proposals contain CVs and personal information. Check your procurement and data protection rules before using an AI tool. If in doubt, remove CVs and personal contact details and paste only the technical proposal, workplan and budget summary.

### The Prompt

```
You are supporting a selection panel with a first-pass triage of a proposal
for an external consultancy. You do not score, rank or recommend. You check
facts against the criteria and flag issues for the panel.

Exclusionary criteria (pass/fail):
[PASTE CRITERIA, e.g.
1. Team lead has at least [NUMBER OF YEARS] years of relevant experience in [SECTOR OR SETTING]
2. Team includes fluent speakers of [LANGUAGES]
3. Team is available between [DATES]
4. Submission includes technical proposal, itemized budget, CVs and 2 references]

Priority questions or requirements and timeline from the ToR:
[PASTE QUESTIONS OR REQUIREMENTS AND KEY DATES]

Task:
1. For each exclusionary criterion, state Pass, Fail or Unclear, and quote or
   reference the part of the proposal that supports your answer.
2. List any required documents or sections that are missing or incomplete.
3. Check the methodology or approach against the priority questions or
   requirements: is there a planned method and source for each one? List
   questions or requirements with no clear method.
4. Check the workplan against the ToR timeline: do the proposed dates and
   durations fit? Flag phases that look too short for the stated scope or
   number of sites or components, and explain your reasoning.
5. Check the budget: is it within the ceiling, itemized, and consistent with
   the workplan (for example, delivery days vs the costs tied to them)?
6. List up to 5 clarification questions the panel could ask this bidder.

Output format:
A. Table: Criterion | Pass / Fail / Unclear | Evidence (section or page)
B. Missing documents or sections
C. Table: Question or requirement | Proposed method and source | Gap
D. Timeline and budget flags
E. Clarification questions

Rules:
- Base every statement on the proposal text. If something is not there, say
  "Not found in proposal".
- Do not give an overall score, ranking or recommendation.

Proposal:
[PASTE PROPOSAL HERE]
```

### How to Read the Output

- Verify every Fail yourself before excluding anyone. An assistant can miss a document that was attached separately or named differently.
- Use sections C and D to guide the methodology score in Stage 2 above. They show where to look, and the panel does the scoring.

### What Stays Human

Every pass/fail decision, all scoring, and the final selection, including any relationship or equity considerations.

## References

- UNEG (2016). Norms and Standards for Evaluation (competencies, independence, ethics).
- BetterEvaluation. Manager's Guide to Evaluation. betterevaluation.org
