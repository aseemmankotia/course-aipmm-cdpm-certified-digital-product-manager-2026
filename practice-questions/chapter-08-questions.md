## Chapter 8: Product Analytics Foundations and the North Star Metric — Practice Questions

**Q1.** A mobile app tracks the metric 'percentage of new users who complete profile setup and send their first message within 24 hours of signup.' Which AARRR stage does this metric primarily measure?

A) Acquisition
B) Retention
C) Activation
D) Referral

<details>
<summary>Answer</summary>

**Correct: C**

This measures whether new users reach a first-value action (aha-moment) shortly after signup — the definition of Activation.

**Why the others are wrong:**
- Acquisition measures how users arrived (channel/signup count), not what they do after joining.
- Retention measures users returning over time, not first-session completion.
- Referral measures users inviting others, which is unrelated to profile setup or messaging.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A B2B project management SaaS company wants to select a North Star Metric. Which candidate BEST fits North Star Metric criteria?

A) Number of tasks completed by active teams per week
B) Total number of registered accounts
C) Monthly recurring revenue (MRR)
D) Total marketing impressions generated

<details>
<summary>Answer</summary>

**Correct: A**

Tasks completed per week by active teams reflects the core value customers receive (getting work done) and is a leading, actionable indicator teams can influence directly.

**Why the others are wrong:**
- Registered accounts is a vanity metric — it doesn't reflect ongoing usage or value delivered.
- MRR is a lagging financial outcome, not a leading indicator the product team can directly move.
- Marketing impressions is a top-of-funnel vanity metric with no link to product value.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** A team observes that Week-1 retention improved 15% after a new onboarding flow launch, but Week-4 retention remains unchanged. What is the BEST next action?

A) Declare success and roll out the onboarding flow to 100% of users immediately
B) Kill the onboarding flow since long-term retention didn't improve
C) Investigate whether the onboarding flow drives users to the true aha-moment, or just delays churn
D) Increase marketing spend to acquire more users to offset the retention issue

<details>
<summary>Answer</summary>

**Correct: C**

A short-term retention bump without a long-term change suggests the onboarding may create temporary engagement without connecting to real value; the team must correlate it against the aha-moment and Week-4+ cohort data before scaling or killing it.

**Why the others are wrong:**
- Rolling out based on a short-term win only risks scaling something that doesn't drive lasting value.
- Killing it is premature without diagnosing why the long-term impact is flat — could be measurement lag or wrong aha-moment definition.
- Acquisition spend doesn't address a retention/activation problem — it's the wrong lever entirely.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** Which of the following is an ACTIONABLE metric rather than a vanity metric?

A) Percentage of new users completing the core setup flow within 24 hours
B) Total app downloads to date
C) Total number of registered users
D) Total social media followers

<details>
<summary>Answer</summary>

**Correct: A**

This is a rate tied to a specific behavior teams can influence via onboarding changes, and it's directly comparable over time to measure the impact of experiments.

**Why the others are wrong:**
- Cumulative total downloads only grows and can't reveal engagement or test the impact of a change.
- Cumulative registered users is a vanity count that doesn't reflect active usage.
- Social followers reflect awareness/reach, not product engagement, and can't be tied to a product decision.

</details>

---

**Q5.** A growth team is running an experiment to increase Daily Active Users (DAU) by adding more push notifications. Which metric should be tracked as a GUARDRAIL metric?

A) App uninstall rate / notification opt-out rate
B) Notification click-through rate
C) Total notifications sent
D) DAU growth percentage

<details>
<summary>Answer</summary>

**Correct: A**

Uninstall/opt-out rate protects against the risk that aggressive notifications increase DAU short-term while damaging long-term retention and brand trust — the classic guardrail use case preventing local optimization.

**Why the others are wrong:**
- Click-through rate measures notification effectiveness, not a harm/risk signal.
- Total notifications sent is an activity/output metric, not a guardrail against harm.
- DAU growth is the primary metric being optimized, not the guardrail protecting against side effects.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q6.** A team wants to identify the aha-moment for a photo-sharing app. What is the correct method to find it?

A) Survey all users about which feature they like the most
B) Correlate specific early actions (e.g., photos uploaded, friends added) in the first week with Day-30 retention, then find the threshold that best predicts retention
C) Ask the CEO which feature they believe is most valuable
D) Track total feature usage across all users regardless of tenure

<details>
<summary>Answer</summary>

**Correct: B**

The aha-moment is empirically discovered by correlating specific early behaviors with long-term retention, then finding the magic threshold (e.g., '7 friends in 10 days') that best predicts a user will stick around.

**Why the others are wrong:**
- Subjective self-reported preference doesn't reliably predict actual retention behavior.
- Opinion-based selection isn't data-driven and doesn't validate against real cohort outcomes.
- Aggregate usage across all tenures doesn't isolate the early-action-to-retention correlation needed to define activation.

</details>

---

**Q7.** A cohort retention table shows the January cohort retains at 40% by Day-30, February at 45%, and March at 55%, with an onboarding improvement shipped each month. What does this trend indicate?

A) The product is losing users faster over time
B) This is a vanity metric with no actionable insight
C) The onboarding improvements are successfully increasing retention across newer cohorts
D) The data indicates a seasonal effect unrelated to the product

<details>
<summary>Answer</summary>

**Correct: C**

Improving Day-30 retention across successive cohorts after shipping onboarding changes is exactly what cohort analysis is designed to reveal — that the changes are working, isolated from calendar-time effects.

**Why the others are wrong:**
- Retention is increasing (40%→55%), not decreasing — this option is factually backwards.
- Cohort retention is a highly actionable metric that directly informs whether product changes work.
- While seasonality is theoretically possible, the consistent upward trend tied to each shipped improvement makes the product-driven explanation the best-supported reading of this scenario.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** Which statement correctly describes a key property that distinguishes a North Star Metric from a vanity metric?

A) A North Star Metric reflects the core value customers receive from the product and is a leading indicator of business success
B) A North Star Metric must always be measured in revenue or dollar terms
C) A vanity metric requires more engineering effort to calculate than a North Star Metric
D) A North Star Metric must be updated in real-time dashboards, while vanity metrics are calculated monthly

<details>
<summary>Answer</summary>

**Correct: A**

The defining property of an NSM is that it captures the value exchange between product and customer, and its movement predicts future business outcomes — not currency or calculation cadence.

**Why the others are wrong:**
- NSMs are typically NOT revenue itself, since revenue is a lagging output rather than a leading, customer-value-based signal.
- Engineering effort to calculate a metric has no bearing on whether it is vanity or North Star.
- Update frequency (real-time vs. monthly) is not the defining characteristic separating NSM from vanity metrics.

</details>

---

