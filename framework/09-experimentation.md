# Experimentation: Test Cards and Learning Cards

This is the engine of the entire framework. You take your riskiest assumption, design the cheapest possible test, run it, and capture what you learned. Then repeat.

## The Build-Measure-Learn Loop

```
HYPOTHESIS → BUILD (minimal) → MEASURE (data) → LEARN (insight) → NEW HYPOTHESIS
```

The faster you cycle through this loop, the faster you learn. Ten small experiments beat one big launch every time.

## The Test Card

Before running any experiment, fill out a test card. It forces clarity on what you're testing and how you'll know if it worked.

### Step 1: Hypothesis
**"We believe that..."**
State the specific assumption you're testing. Not "people will like our product" but "solo consultants making $100-300K will pay $49/month for automated follow-up because they're losing at least 2 deals/month due to slow response time."

### Step 2: Test
**"To verify that, we will..."**
Describe the specific experiment. Keep it minimal — what's the cheapest, fastest way to test this? Examples:
- Interview 10 target customers about their follow-up process
- Create a landing page with pricing and measure sign-up intent
- Offer a manual "concierge" version to 5 people
- Run a smoke test ad to gauge demand

### Step 3: Metric
**"And measure..."**
What specific, quantifiable data will you collect? Examples:
- 7 out of 10 interviewees confirm they lose deals due to slow follow-up
- 5% of landing page visitors click "Start Free Trial"
- 3 out of 5 concierge users convert to paying after the trial

### Step 4: Criteria
**"We are right if..."**
Define your success threshold *before* running the experiment. This prevents moving the goalposts after the fact. Be honest about what would actually convince you.

## The Learning Card

After running the experiment, fill out a learning card. This captures what actually happened and what you'll do about it.

### Step 1: Hypothesis
**"We believed that..."**
Restate what you were testing.

### Step 2: Observation
**"We observed..."**
What actually happened? Report the data honestly, including surprises and contradictions.

### Step 3: Learnings and Insights
**"From that we learned that..."**
What does the data mean? This is the most valuable part. Don't just report numbers — interpret them. What did you learn about your customer, your problem, or your solution?

### Step 4: Decisions and Actions
**"Therefore we will..."**
Based on what you learned, what will you do next? Options:
- **Persevere:** The assumption was validated. Move to the next riskiest assumption.
- **Pivot:** The assumption was invalidated. Change your hypothesis and test again.
- **Zoom in:** The results were ambiguous. Design a more focused test.

## Types of Experiments

From cheapest/fastest to most expensive/slowest:

| Type | Effort | What You Learn |
|------|--------|---------------|
| **Customer interviews** | Very low | Whether the problem exists and matters |
| **Landing page / smoke test** | Low | Whether people are interested enough to take action |
| **Concierge / manual delivery** | Medium | Whether your solution actually solves the problem |
| **Wizard of Oz** | Medium | Whether the UX/flow works (fake the backend) |
| **MVP / beta** | High | Whether people will use and pay for a real product |
| **Pilot / paid beta** | High | Whether the business model works |

Always start with the cheapest test that can invalidate the assumption. Don't build an MVP to test whether the problem exists — interviews are enough for that.

## Common Mistakes

1. **Testing multiple assumptions at once.** You won't know which one was right/wrong. One assumption per test.
2. **Not defining success criteria upfront.** You'll rationalize any result as "good enough."
3. **Building too much before testing.** The MVP should be embarrassingly minimal.
4. **Only talking to friends/family.** They'll tell you what you want to hear.
5. **Ignoring negative results.** If the data says you're wrong, you're wrong. That's valuable.
6. **Not capturing learnings.** Running experiments without documenting what you learned is like doing research without taking notes.

## Experiment Cadence

Aim for at least one experiment per week. If an experiment takes more than 2 weeks, break it into smaller tests. Speed of learning is your only real competitive advantage right now.

**Next step:** After each experiment, use `/learning` to capture what you learned.
