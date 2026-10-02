## Chapter 4: Lean Startup and Riskiest Assumption Testing — Practice Questions

**Q1.** A team is building a two-sided marketplace connecting freelance electricians with homeowners. They have not yet confirmed that electricians will list their services on any platform. Which risk should they test FIRST?

A) Feasibility — whether the scheduling algorithm can be built in time
B) Viability/Desirability — whether electricians will supply listings at all, since without supply there is no marketplace
C) Desirability — whether homeowners like the app's UI colors
D) Feasibility — whether the payment gateway integrates with their chosen bank

<details>
<summary>Answer</summary>

**Correct: B**

Supply-side participation is the leap-of-faith assumption: highest uncertainty and highest impact on whether the business model works at all. No electricians = no marketplace, regardless of UI or tech.

**Why the others are wrong:**
- Scheduling algorithm feasibility is irrelevant if there's no supply to schedule — low priority compared to the core assumption.
- UI color preference is a minor desirability detail, not a business-model-breaking assumption.
- Payment gateway integration is a feasibility detail that only matters once supply and demand are validated.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A founder wants to test the assumption 'restaurants will pay $50/month for a booking widget' before building the product. Which test is the CHEAPEST valid option?

A) Run a landing page describing the widget with a 'Reserve Your Spot — $50/mo' button that collects a real credit card pre-order
B) Build a full-featured booking widget and offer a 30-day free trial
C) Survey 50 restaurant owners asking if they would find the idea 'interesting'
D) Hire developers to build an MVP with core booking features only, then launch to 5 restaurants

<details>
<summary>Answer</summary>

**Correct: A**

A landing page with a real payment commitment tests actual willingness to pay (viability) at near-zero build cost — cheaper and more valid than building anything.

**Why the others are wrong:**
- A full free trial requires building the product first, defeating the purpose of testing before building.
- Asking if something is 'interesting' produces anecdotal feedback, not validated learning — no real commitment is measured.
- Building an MVP is still more expensive than a landing page test and skips a cheaper validation step.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** After running a 4-week test of a new onboarding flow, conversion to paid stayed flat at 2% versus a 3% hypothesis threshold, and qualitative interviews showed users didn't understand the core value proposition. What should the team do?

A) Persevere — 2% is close enough to 3%, continue running the same test for another month
B) Persevere — run the exact same test again with a larger sample size only
C) Pivot — immediately shut down the product and start an entirely unrelated business
D) Pivot — the evidence indicates the value proposition itself needs to change, not just UI tweaks

<details>
<summary>Answer</summary>

**Correct: D**

The metric missed its threshold AND qualitative data points to a specific root cause (value prop misunderstanding), which is the classic pivot signal: change the core hypothesis, not just re-run the same experiment.

**Why the others are wrong:**
- 2% vs 3% missing threshold with a clear root cause is not 'close enough' — this is a pivot trigger, not persevere.
- Re-running the identical test ignores the qualitative signal explaining WHY the metric failed.
- A pivot changes a core hypothesis/strategy element (e.g., value prop, target segment) — it does not mean abandoning the business entirely.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** Which risk category does the assumption 'our engineering team can process 10,000 image uploads per second with existing infrastructure' fall into?

A) Feasibility
B) Desirability
C) Viability
D) Validated learning

<details>
<summary>Answer</summary>

**Correct: A**

This assumption concerns whether the team CAN technically build/deliver the capability — the definition of feasibility risk.

**Why the others are wrong:**
- Desirability concerns whether users want the product, not technical capacity.
- Viability concerns whether the business model makes money, not technical throughput.
- Validated learning is a learning outcome/method, not a risk category.

</details>

---

**Q5.** A team wants to test whether users actually want a same-day grocery delivery feature before building any backend logistics. Which test method BEST fits this desirability assumption?

A) A/B test two pricing tiers on the existing checkout page
B) A concierge MVP where the team manually shops and delivers groceries for a handful of real customers
C) A load test simulating 100,000 concurrent delivery requests
D) A financial model projecting delivery margins over 5 years

<details>
<summary>Answer</summary>

**Correct: B**

A concierge MVP manually delivers the real experience to a small group, generating validated learning about actual desirability and behavior without building automation.

**Why the others are wrong:**
- Pricing A/B tests validate viability/price sensitivity, not whether the feature is wanted at all.
- Load testing validates feasibility/scalability, which is irrelevant before desirability is confirmed.
- A financial model is a viability projection based on assumptions, not a real test of user behavior.

</details>

---

**Q6.** Which is the correctly ordered, well-formed hypothesis statement?

A) We believe adding one-click pay will increase checkout conversion. We will know this is true when conversion increases by 10% within 30 days, because users abandon checkout due to friction
B) Because users want faster checkout, we will know it works, we believe adding one-click pay will increase conversion
C) We will know this is true when checkout conversion increases by 10% because users want faster checkout, we believe adding one-click pay will achieve this
D) We believe users abandon checkout. We believe one-click pay helps. We will measure conversion sometime

<details>
<summary>Answer</summary>

**Correct: A**

Follows the required structure: We believe [action/outcome] → We will know [measurable signal + timeframe] → because [underlying reasoning/evidence].

**Why the others are wrong:**
- Reverses the required order — 'because' and 'we will know' come before 'we believe', which breaks the template logic.
- Jumbles all three clauses into one run-on sentence without clear separation or proper order.
- Contains two 'we believe' clauses, no measurable success criterion, and a vague timeframe — not well-formed.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** What is the correct purpose and order of the Build-Measure-Learn loop as tested on the exam?

A) Build the highest-quality product first, then measure customer satisfaction, then learn how to market it
B) Measure market size first, build a full product roadmap, then learn from investors
C) Start with what you need to LEARN, work backwards to decide what to MEASURE, then BUILD only the minimum needed to run that measurement — minimizing total loop time
D) Build, measure, and learn are three independent parallel tracks that don't need to be sequenced

<details>
<summary>Answer</summary>

**Correct: C**

Lean Startup methodology explicitly works backwards from the learning goal: decide what you need to learn, design the measurement, then build only the minimum artifact needed — the goal is minimizing total cycle time through the loop.

**Why the others are wrong:**
- Prioritizing 'highest quality' build first contradicts the MVP principle of building the minimum needed to learn.
- Measuring market size and building a full roadmap describes traditional planning, not the lean loop.
- The three stages are explicitly sequential and iterative, not independent parallel tracks.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** A product manager says: 'Three users in our interview said they loved the idea, so we've validated demand.' What is the key flaw in this claim?

A) Three users is a statistically significant sample for any hypothesis
B) This is anecdotal feedback — stated opinions without a measurable behavioral commitment — not validated learning
C) Interviews are never a legitimate research method in Lean Startup
D) The claim is correct because qualitative data always outweighs quantitative data

<details>
<summary>Answer</summary>

**Correct: B**

Validated learning requires a measurable, falsifiable metric tied to a hypothesis and ideally a behavioral commitment (e.g., payment, sign-up); verbal enthusiasm in an interview is anecdotal and unreliable.

**Why the others are wrong:**
- Three users is far too small and not designed as a statistical test — sample size alone doesn't make it significant.
- Interviews are a legitimate discovery tool, but stated preference alone doesn't equal validated learning.
- Neither qualitative nor quantitative data automatically outweighs the other — validity depends on rigor and measurable commitment, not data type.

</details>

---

