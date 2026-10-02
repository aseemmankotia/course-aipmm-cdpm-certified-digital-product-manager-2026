## Chapter 1: Digital Product Management Foundations — Practice Questions

**Q1.** A digital product team ships a redesigned checkout flow and reports success by pointing to '14 user stories delivered on schedule, zero critical bugs.' Leadership asks whether the redesign actually improved the business. Which reframing BEST demonstrates outcome orientation?

A) Report velocity trends across the last three sprints to show delivery predictability
B) Report the number of story points completed versus story points planned
C) Report the change in checkout completion rate and revenue per session before and after launch
D) Report that the team followed the Definition of Done for every story

<details>
<summary>Answer</summary>

**Correct: C**

Outcome orientation measures the change in customer or business behavior (completion rate, revenue) that the output was intended to cause, not the act of shipping itself.

**Why the others are wrong:**
- Velocity is an output/throughput metric describing delivery pace, not the impact of what was delivered.
- Story points completed vs planned measures execution against a plan (output), not whether the plan achieved a result.
- Following the Definition of Done confirms process compliance, not business impact — a common confusion between quality gates and outcomes.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A company is migrating an internal reporting tool from a one-time-launch mindset to a product mindset. The tool was built by a project team that disbanded after go-live, and no one currently owns post-launch improvements. Which operating model change addresses this gap?

A) Extend the project timeline by one additional sprint before disbanding the team
B) Establish a persistent, cross-functional product team accountable for the tool across its life cycle
C) Assign a single support engineer to handle tickets as they arise
D) Create a new project charter each time a change request is approved

<details>
<summary>Answer</summary>

**Correct: B**

The project-to-product shift replaces temporary, disbanding project teams with a persistent team that owns the product's outcomes continuously through discovery, delivery, and growth.

**Why the others are wrong:**
- Extending the timeline still ends in disbandment — it delays the core problem rather than solving it.
- A single support engineer only covers reactive maintenance, not proactive discovery or growth ownership.
- Re-chartering a project per change request re-creates the project model repeatedly instead of adopting a product model.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** Which statement correctly distinguishes continuous delivery from a one-time launch model for a digital product?

A) Continuous delivery means deploying code automatically, while one-time launch means deploying manually
B) Continuous delivery applies only to mobile apps, while one-time launch applies only to web apps
C) Continuous delivery requires a larger initial budget than a one-time launch
D) Continuous delivery treats launch as the start of an ongoing improvement loop, while one-time launch treats it as the end of the initiative

<details>
<summary>Answer</summary>

**Correct: D**

The defining distinction is life cycle framing: continuous delivery views launch as day one of an ongoing loop of learning and iteration; one-time launch treats go-live as project completion.

**Why the others are wrong:**
- Automated vs manual deployment describes a CI/CD engineering practice, not the product life cycle philosophy tested here.
- The distinction is not tied to platform type; both models can apply to any digital channel.
- Budget size is not the defining characteristic — both models can have varying budgets depending on scope.

</details>

---

**Q4.** A team is deciding between a 'platform product' framing and a 'data product' framing for a new internal capability that exposes customer transaction history to multiple downstream teams via an API, with the primary value being the curated, trustworthy dataset itself. Which framing is most appropriate?

A) Platform product, because it exposes an API
B) Data product, because the core value delivered is the dataset's quality, accessibility, and trustworthiness
C) Platform product, because multiple teams consume it
D) Neither framing applies since it is an internal capability, not customer-facing

<details>
<summary>Answer</summary>

**Correct: B**

Data products are defined by the dataset itself being the primary deliverable of value (curated, discoverable, trustworthy data), regardless of the interface used to deliver it.

**Why the others are wrong:**
- Having an API is a delivery mechanism, not the defining trait; platform products are defined by enabling other products/teams to build on shared capabilities, not merely by having an API.
- Multiple consumers alone doesn't determine the category — data products are also commonly consumed by many teams.
- Internal-facing products are still products; audience (internal vs external) does not exclude product framing.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q5.** In the standard vision-to-strategy cascade, which sequence correctly orders the levels from most abstract to most concrete?

A) Roadmap → Strategy → Vision → Backlog
B) Backlog → Roadmap → Vision → Strategy
C) Strategy → Backlog → Vision → Roadmap
D) Vision → Strategy → Roadmap → Backlog

<details>
<summary>Answer</summary>

**Correct: D**

The cascade flows from the long-term aspirational Vision, through the Strategy (target market, needs, goals), into a time-bound Roadmap, down to the tactical Backlog of executable items.

**Why the others are wrong:**
- This reverses the order, placing the most tactical artifact (Roadmap) before the guiding Vision.
- This inverts the entire cascade, starting from the most tactical item and ending at Strategy without ever reaching a proper endpoint order.
- This scrambles the sequence, placing Backlog before Vision and breaking the abstract-to-concrete flow.

</details>

---

**Q6.** A digital PM spends most of their time this quarter running customer interviews, testing prototypes, and validating problem hypotheses before any build work begins. Which phase of the digital PM role does this represent?

A) Growth
B) Discovery
C) Delivery
D) Sunset

<details>
<summary>Answer</summary>

**Correct: B**

Discovery is the phase focused on validating problems and solutions with users before committing engineering effort to delivery.

**Why the others are wrong:**
- Growth focuses on scaling adoption and optimizing an already-launched product, not on validating unbuilt hypotheses.
- Delivery is the phase of building and shipping the validated solution, which occurs after discovery.
- Sunset involves winding down or retiring a product, which is unrelated to pre-build validation activity.

</details>

---

**Q7.** A legacy product has flat usage, aging architecture, and rising support costs, with no planned new features. According to digital product life cycle stages, which stage is this product in, and what operating stance typically fits?

A) Growth stage; scale the team and increase feature investment
B) Discovery stage; run new customer interviews to find a fresh vision
C) Maturity/Decline (sunset) stage; shift to a minimal maintenance team and plan retirement or migration
D) Launch stage; assemble a new project team to relaunch the product

<details>
<summary>Answer</summary>

**Correct: C**

Flat usage, rising support costs, and no roadmap of new investment are hallmark signals of maturity moving into decline/sunset, where the appropriate stance is minimal-maintenance staffing and retirement planning.

**Why the others are wrong:**
- Growth stage is characterized by rising adoption and active feature investment, which contradicts the flat-usage, no-investment signals given.
- Discovery applies to new or pivoting products seeking product-market fit, not an aging product with an established, declining user base.
- Reverting to a project-team relaunch ignores life cycle signals indicating the product should be wound down, not reinvested in.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** A company is launching a brand-new internal tool with a fixed scope, fixed deadline, and a team that will be reassigned to other initiatives immediately after go-live. Which operating model does this describe?

A) Persistent product team
B) Platform team
C) Project team
D) Growth team

<details>
<summary>Answer</summary>

**Correct: C**

A team staffed for a fixed scope and timeline, disbanding at completion, is the defining characteristic of a project team operating model.

**Why the others are wrong:**
- A persistent product team stays intact and accountable beyond launch, which contradicts the described reassignment after go-live.
- A platform team is a functional description of what is built (shared capabilities), not an operating model defined by team permanence.
- A growth team specifically focuses on post-launch optimization and scaling, not fixed-scope, disbanding delivery efforts.

</details>

---

