## Chapter 7: Prioritization Frameworks and Outcome-Based Roadmapping — Practice Questions

**Q1.** A product team has minimal historical usage data on a newly launched feature area and must rank 15 competing ideas across several user segments. Which prioritization framework BEST fits this constraint?

A) WSJF
B) MoSCoW
C) RICE
D) Kano model

<details>
<summary>Answer</summary>

**Correct: C**

RICE's Confidence factor is specifically designed to discount scores when data is sparse or estimates are uncertain, making it usable even with limited data.

**Why the others are wrong:**
- WSJF requires estimating Cost of Delay (business value, time criticality, risk) across initiatives, which is harder to size reliably with little data.
- MoSCoW only sorts items into binary in/out buckets; it doesn't rank or quantify uncertainty across a large backlog.
- Kano classifies the type of feature satisfaction (basic/performance/delighter), it doesn't produce a rank-ordered backlog.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A team faces a regulatory deadline with severe financial penalties if a change is delayed, and it is competing against several similarly-sized initiatives for the same sprint capacity. Which framework should be used to sequence the work?

A) RICE
B) WSJF
C) MoSCoW
D) Now-Next-Later roadmap

<details>
<summary>Answer</summary>

**Correct: B**

WSJF explicitly weighs Cost of Delay (including time criticality and risk) against job size, making it the right tool for economically sequencing urgent, high-penalty work against competing items.

**Why the others are wrong:**
- RICE has no explicit time-criticality or cost-of-delay component, so it undervalues urgency-driven work.
- MoSCoW is a scope-negotiation tool for a single release, not an economic sequencing model across competing initiatives.
- Now-Next-Later is a roadmap communication format, not a backlog-item scoring/sequencing method.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** Users never mention a capability in interviews, but when it's missing they file complaints; when it's present, satisfaction doesn't rise above baseline expectations. How should this feature be classified in the Kano model?

A) Delighter
B) Basic
C) Performance
D) Indifferent

<details>
<summary>Answer</summary>

**Correct: B**

This is the definition of a Basic (must-be) feature: absence causes dissatisfaction, but presence only meets a baseline expectation without increasing satisfaction.

**Why the others are wrong:**
- Delighters are unexpected features that boost satisfaction when present but whose absence does not cause complaints.
- Performance features show a linear relationship — more of the feature increases satisfaction proportionally, which isn't described here.
- Indifferent features have no measurable effect on satisfaction whether present or absent; here, absence clearly causes complaints.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** A team has a fixed release date and fixed capacity, and needs to quickly negotiate scope with stakeholders about what will and won't ship in this release. Which framework is the BEST fit?

A) WSJF
B) RICE
C) MoSCoW
D) Kano model

<details>
<summary>Answer</summary>

**Correct: C**

MoSCoW is designed for exactly this: negotiating binary in/out scope decisions under a fixed timebox and fixed capacity for a single release.

**Why the others are wrong:**
- WSJF sequences multiple competing initiatives by economic priority; it doesn't produce a simple in/out scope decision for one release.
- RICE ranks a large backlog by relative priority across a longer horizon, not a binary scope cut for a single fixed release.
- Kano classifies feature satisfaction type, which doesn't directly answer a scope negotiation question.

</details>

---

**Q5.** An executive asks for a roadmap that communicates strategic direction and sequencing without committing to specific delivery dates that could slip and damage trust. Which roadmap format should the product manager present?

A) Now-Next-Later roadmap
B) Date-based roadmap
C) Gantt chart
D) Release train schedule

<details>
<summary>Answer</summary>

**Correct: A**

Now-Next-Later is an outcome-based format that communicates relative sequencing and direction without locking in dates, reducing the risk of broken date commitments.

**Why the others are wrong:**
- A date-based roadmap commits to specific dates, creating false certainty that damages trust if timelines slip.
- A Gantt chart is a detailed date-based scheduling tool with the same date-commitment risk.
- A release train schedule (SAFe cadence) still ties work to fixed calendar dates/PI boundaries.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q6.** In the WSJF formula, what does 'Job Size' represent?

A) The denominator representing the effort/duration required to deliver the work
B) The numerator representing business value delivered
C) A weighting multiplier applied to Cost of Delay
D) The confidence percentage in the estimate

<details>
<summary>Answer</summary>

**Correct: A**

WSJF = Cost of Delay / Job Size. Job Size is the denominator, typically a relative sizing estimate (e.g., story points) of the effort or duration to deliver.

**Why the others are wrong:**
- Business value is one component that feeds into the Cost of Delay numerator, not Job Size itself.
- Job Size is not a weighting applied to Cost of Delay — it is a separate divisor in the formula.
- Confidence percentage is a component of the RICE formula, not WSJF.

</details>

---

**Q7.** A feature has Reach = 500 users/quarter, Impact = 2, Confidence = 80%, and Effort = 4 person-months. What is the RICE score?

A) 800
B) 250
C) 200
D) 20000

<details>
<summary>Answer</summary>

**Correct: C**

RICE = (Reach × Impact × Confidence) / Effort = (500 × 2 × 0.8) / 4 = 800 / 4 = 200.

**Why the others are wrong:**
- 800 results from forgetting to divide by Effort after multiplying Reach × Impact × Confidence.
- 250 results from omitting the Confidence factor entirely: (500 × 2) / 4.
- 20000 results from treating Confidence as a whole number (80) instead of a decimal (0.8), inflating the score 100x.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** A feature's satisfaction increases proportionally as more of it is delivered — more capacity, more speed, more storage all directly raise satisfaction, unlike a must-be feature that only prevents dissatisfaction. Which Kano category is this?

A) Performance
B) Basic
C) Delighter
D) Indifferent

<details>
<summary>Answer</summary>

**Correct: A**

Performance (one-dimensional) features have a linear relationship between the quality/quantity delivered and user satisfaction — more is better, less is worse.

**Why the others are wrong:**
- Basic features have an asymmetric relationship: missing causes dissatisfaction, but improving beyond baseline doesn't raise satisfaction further.
- Delighters provide an unexpected satisfaction boost when present, but their absence doesn't cause dissatisfaction — the opposite asymmetry.
- Indifferent features have no measurable effect on satisfaction regardless of how much is delivered.

</details>

---

