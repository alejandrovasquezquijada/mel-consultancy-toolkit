# Prompt: Read a ToR as a Bidder Would

Datimpacto · MEL Community of Practice Toolkit · Tool 7

Purpose: get a first-pass review of your ToR from the point of view of a consultant/provider deciding whether and how to bid.
When to use: before publishing, after you have run the checklist in Tool 1.
Time needed: 5 minutes to run, 20 minutes to review the output.

## What You Need

- The full ToR text (paste it or attach the file).
- The planned publication date and contract start date, if they are not in the ToR.

Data note: a ToR is an internal document. Check that your organization allows the AI tool you are using for internal documents. Remove names of individuals if your policy requires it.

## The Prompt

```
You are an experienced external provider reviewing a Terms of Reference (ToR)
before deciding whether to bid. Read it the way a careful bidder would: looking
for what is missing, unclear or unrealistic.

Context:
- Organization commissioning the work: [ORGANIZATION TYPE, e.g. international NGO]
- Type of engagement: [e.g. final performance evaluation, MEL system design, standalone data-collection exercise]
- Expected contract start date: [DATE]

Review the ToR against these checks:
1. Object and timing: is it clear what is being delivered (program, period,
   sites, partners) and why now?
2. Users and use: are the intended users named, and is it clear what decisions
   they will make with the findings or product?
3. Priority questions or requirements: how many are there? Are they
   prioritized? Flag ones that are vague, overlapping, or not answerable
   within the stated scope.
4. Budget: is there a budget ceiling or indicative budget?
5. Methodological or technical scope: are sample sizes, number of interviews
   or focus groups, sites, sectors or system components quantified?
6. Review checkpoints: are interim deliverables and review points defined, with
   who reviews and how long review takes?
7. Definition of done: are deliverables, quality criteria and the approver named?
8. Timeline arithmetic: list every phase and site-level or build activity the
   ToR requires (inception, tool or system design, training, data collection
   or build, validation or testing, analysis, reporting, review rounds).
   Estimate the minimum realistic duration for each, state your assumptions,
   and compare the total with the window the ToR allows.
9. Contradictions: anything the ToR says in one place and contradicts elsewhere.

Output format:
A. A table with columns: Check | Finding | Severity (High / Medium / Low) |
   Suggested fix. One row per check.
B. The timeline arithmetic as a table: Phase or activity | Your estimate |
   Assumption. End with total estimated duration vs the time available.
C. Up to 10 clarification questions a bidder would send during the Q&A period.

Rules:
- Quote or reference the ToR section for every finding.
- If the ToR does not mention something, say "Not stated" rather than guessing.
- Do not rewrite the whole ToR. Point to specific fixes.

ToR text:
[PASTE TOR HERE]
```

## How to Read the Output

- Start with High severity rows. In many cases they are about budget, scope numbers and timeline, the three things bidders price around.
- Check the timeline assumptions. The assistant estimates; you know your context (permits, seasons, holidays). Adjust and rerun Tool 11 if needed.
- The clarification questions are a preview of what bidders will ask. Answering them in the ToR saves a round of Q&A.

## What Stays Human

Deciding what to change in the ToR, and what trade-offs to make between scope, time and budget.
