# Prompt: ToR Checklist Compliance Check

Datimpacto · MEL Community of Practice Toolkit · Tool 10

Purpose: run the five-element checklist from Tool 1 against a draft ToR and get a structured Meets / Partly meets / Does not meet rating for each element, with the same publish-or-revise decision Tool 1 asks for.
When to use: right after a full ToR draft exists, before Tool 7's bidder read. This checks the ToR against your own standard; Tool 7 checks it against how a bidder would read it. Run this one first.
Time needed: 5 minutes to run, 15 minutes to verify against the draft.

## What You Need

- The full ToR text (paste it or attach the file).

The prompt below carries the checklist definitions from Tool 1 inside it, so it works on its own. If Tool 1 changes, update this prompt to match.

Data note: a ToR is an internal document. Check that your organization allows the AI tool you are using for internal documents. Remove names of individuals if your policy requires it.

## The Prompt

```
You are a quality reviewer checking a draft Terms of Reference (ToR) against a
fixed five-element standard, on behalf of the commissioning team. You are not
reading as a bidder and you are not estimating timeline feasibility. You rate
compliance with each element, element by element, using only the text in front
of you.

The five elements, and what each rating means for that element:

1. What and why now
   Meets: the object, period and geography are named, with a stated reason for
     commissioning now.
   Partly meets: some of the above is named but at least one part (object,
     period, geography, or reason) is missing or vague.
   Does not meet: a generic description that could fit any program or any year.

2. Who it's for
   Meets: primary users are named, with the decisions they will make from the
     findings.
   Partly meets: users are named but their intended use of the findings is not
     stated, or vice versa.
   Does not meet: "stakeholders" with no names, or no stated use for the
     findings.

3. Questions or deliverables
   Meets: a short, prioritized list.
   Partly meets: the list is present but not ranked, or ranked but too long to
     act as a priority list.
   Does not meet: 40 to 50 questions with no ranking, or one vague line
     covering everything.

4. Boundaries
   Meets: geography, timeframe, sample or methodological scope, and a budget
     ceiling are all stated.
   Partly meets: some of the above are stated but at least one is missing (for
     example, scope is clear but there is no budget ceiling).
   Does not meet: no budget ceiling, and no indication of how many interviews,
     surveys or sites are expected.

5. What "done" looks like
   Meets: deliverables, review checkpoints and the approver are named, with
     review time built into the timeline.
   Partly meets: deliverables and an approver are named but review checkpoints
     or review time are missing from the timeline.
   Does not meet: deliverables listed with no review checkpoints, or a timeline
     with no margin for delays.

Task:
1. For each of the five elements, assign a rating (Meets / Partly meets / Does
   not meet) and quote or reference the exact ToR text that supports it. If the
   ToR says nothing relevant to an element, write "Not stated" and rate it Does
   not meet.
2. For every rating other than Meets, state in one sentence what specific
   information would need to be added for the element to meet the standard.
3. Note any place where the ToR contradicts itself on one of the five elements
   (for example, a budget ceiling stated in one section and a different figure
   implied by the described scope elsewhere).
4. Apply this decision rule and state the result:
   - Ready to publish: all five elements rated Meets.
   - Needs revision: one or more elements rated Partly meets or Does not meet.
     List exactly which elements and why, in the same order as the checklist.
5. Do not evaluate anything outside the five elements (do not assess writing
   quality, formatting, or organizational branding).

Output format:
A. Table: Element (1 to 5) | Rating | Evidence or "Not stated" | What would
   close the gap (blank if Meets)
B. Contradictions found (or "None found")
C. Decision: Ready to publish, or Needs revision with the list of weak
   elements in checklist order

Rules:
- Base every rating on the ToR text only. Do not infer intent that is not on
  the page.
- Do not rewrite or draft ToR language. Point to what is missing; the
  commissioning team decides how to write it.
- Do not soften a rating because the surrounding text reads well. A well
  written paragraph that lacks the required specifics still rates Partly meets
  or Does not meet.
- If the pasted text is a partial ToR (for example, missing an annex), say so
  before the table and rate only what is present.

ToR text:
[PASTE TOR HERE]
```

## How to Read the Output

- Table A is a compliance check, not a critique. A "Meets" rating means the element is present and specific, not that the content is strategically sound; that judgment stays with your team.
- Section B catches something a straight read-through often misses: a number stated once and contradicted elsewhere.
- If the decision comes back "Needs revision," fix the listed elements and rerun the prompt on the revised draft rather than trying to track partial fixes by memory.

## What Stays Human

Deciding what the ToR should say for each element, and any judgment call about whether a "Partly meets" is acceptable to publish anyway given time pressure.

## Related Tools

- Tool 1: the checklist this prompt operationalizes.
- Tool 7: reads the same draft ToR as a bidder would; run after this one passes.
- Tool 11: the timeline feasibility calculator.

## References

- UNEG (2010). Quality Checklist for Evaluation Terms of Reference and Inception Reports.
- BetterEvaluation. Manager's Guide to Evaluation. betterevaluation.org
