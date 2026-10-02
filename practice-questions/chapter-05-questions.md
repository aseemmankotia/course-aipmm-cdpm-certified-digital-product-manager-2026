## Chapter 5: MVP Types and Experiment Design — Practice Questions

**Q1.** A startup wants to test whether users will pay for 'AI-curated' grocery lists before building any machine learning. Founders manually pick each list behind the scenes while users are told the curation is automated. Which MVP type is this?

A) Concierge MVP
B) Landing page smoke test
C) Single-feature MVP
D) Wizard of Oz MVP

<details>
<summary>Answer</summary>

**Correct: D**

In a Wizard of Oz MVP, the user believes they are interacting with an automated system while a human performs the work behind the curtain — this tests whether the automated outcome is valuable before investing in real automation.

**Why the others are wrong:**
- Concierge MVP is wrong because in concierge, the manual, high-touch service is delivered openly — the user knows a human is doing the work.
- Landing page smoke test is wrong because that validates demand signal (e.g., sign-ups) before any product exists, not a working-but-faked experience.
- Single-feature MVP is wrong because it implies one real, functioning feature was built, not a disguised manual process.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A founder personally schedules and delivers meal-prep boxes by hand for the first 10 customers, openly telling them it's a manual pilot service run by the founder. Which MVP type is this?

A) Wizard of Oz MVP
B) Concierge MVP
C) Landing page smoke test
D) Single-feature MVP

<details>
<summary>Answer</summary>

**Correct: B**

Concierge MVP delivers the value proposition manually and transparently — the customer knows a human, not software, is doing the work — used to learn what customers actually value before automating.

**Why the others are wrong:**
- Wizard of Oz is wrong because that requires the user to believe the process is automated; here the manual nature is disclosed.
- Landing page smoke test is wrong because no real service delivery happens in a smoke test — only a demand signal is captured.
- Single-feature MVP is wrong because this describes a full manual service experience, not one stripped-down product feature.

</details>

---

**Q3.** A team spent four months building a stripped-down version of their planned product, complete with production infrastructure, user accounts, and payment processing, then released it to their entire target market. The PM calls this an MVP. What is the BEST characterization of this release?

A) It is a valid MVP because it has fewer features than the full product vision
B) It is not an MVP — it is a scoped-down full release built to confirm a plan, not a cheap test of a risky assumption
C) It is a valid MVP because it was launched to real users
D) It is not an MVP because it lacks a landing page

<details>
<summary>Answer</summary>

**Correct: B**

A true MVP is defined by testing the riskiest assumption at minimum cost/time, not by having fewer features. Building full production infrastructure, accounts, and payments before learning anything is a scoped-down full release mislabeled as an MVP.

**Why the others are wrong:**
- Having fewer features is not the defining trait of an MVP — a feature-reduced product can still be a full release if it wasn't built to cheaply test a specific assumption.
- Launching to real users doesn't make something an MVP — mislabeled full releases are also launched to real users.
- Landing pages are one possible MVP form, not a requirement for something to qualify as an MVP.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** A founder wants to gauge demand for a new subscription box before building or manually fulfilling anything. Which is the cheapest valid MVP for this assumption?

A) Landing page / smoke test MVP
B) Single-feature MVP
C) Concierge MVP
D) Wizard of Oz MVP

<details>
<summary>Answer</summary>

**Correct: A**

A landing page or smoke test captures a demand signal (sign-ups, pre-orders, click-through) with no product or fulfillment built at all — the cheapest way to validate 'will people want this' before any delivery mechanism exists.

**Why the others are wrong:**
- Single-feature MVP requires building at least one working feature, which is more expensive than a landing page.
- Concierge MVP requires manually fulfilling the service for real customers, incurring delivery cost that isn't needed to test pure demand.
- Wizard of Oz MVP requires simulating a working backend for real transactions, more costly than simply measuring interest.

</details>

---

**Q5.** A team already has a working core product and wants to test whether users adopt one new proposed feature, rather than validating the whole product concept. Which approach fits best?

A) Landing page MVP
B) Single-feature MVP
C) Concierge MVP
D) Wizard of Oz MVP

<details>
<summary>Answer</summary>

**Correct: B**

Single-feature MVP builds and ships only the one feature being tested within an existing product, isolating the assumption without rebuilding or faking the whole experience.

**Why the others are wrong:**
- Landing page MVP is for testing demand before any product exists, not for adding a feature to an existing live product.
- Concierge MVP is for manually delivering an entire early-stage service, not for testing one incremental feature in an existing app.
- Wizard of Oz MVP fakes automation for something not yet built; it doesn't fit adding one real feature to an established product.

</details>

---

**Q6.** A team ran an A/B test comparing two onboarding flows (control A vs variant B) for two days with 40 total visitors, then declared B the winner. What is the main flaw in this experiment?

A) They should have used a Wizard of Oz MVP instead of an A/B test
B) The sample size and test duration were too small to reach statistical significance
C) They needed a landing page MVP instead of an A/B test
D) A/B tests require at least three variants to be valid

<details>
<summary>Answer</summary>

**Correct: B**

With only 40 visitors over two days, the sample is almost certainly too small to distinguish a real effect from random noise, making any 'winner' declaration statistically unreliable.

**Why the others are wrong:**
- MVP type selection is unrelated — this is a flaw in experiment execution, not a wrong choice of validation method.
- A landing page MVP tests demand, not which of two existing flows performs better — that's precisely what A/B testing is for.
- A/B testing is defined by comparing a control against one or more variants; two variants (A vs B) is a completely valid and standard setup.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** Which statement correctly describes standard A/B testing practice around statistical significance?

A) A p-value above 0.05 indicates strong statistical significance
B) Statistical significance guarantees the effect is practically important for the business
C) Significance can be determined without a control group
D) A p-value below 0.05 conventionally indicates the observed result is unlikely to be due to chance alone

<details>
<summary>Answer</summary>

**Correct: D**

The conventional threshold of p < 0.05 is widely used to indicate that an observed difference between control and variant is unlikely to have occurred by random chance, under the standard hypothesis-testing framework.

**Why the others are wrong:**
- A higher p-value indicates weaker, not stronger, evidence against the null hypothesis — this reverses the correct interpretation.
- Statistical significance only indicates the effect is unlikely due to chance; it says nothing about whether the effect size is large enough to matter practically.
- A control group is required to have a baseline to compare the variant against; without it there is nothing to test significance against.

</details>

---

**Q8.** Which best describes correct experiment design practice for the success metric of an MVP test?

A) Define the success metric and its threshold before launch, then measure actual results against it
B) Define the success metric after reviewing results, so it can be interpreted fairly
C) Success metrics are unnecessary for concierge MVPs since founders observe customers directly
D) Success metrics only matter for A/B tests, not for other MVP types

<details>
<summary>Answer</summary>

**Correct: A**

Defining the success metric and pass/fail threshold before launch prevents post-hoc rationalization (moving the goalposts) and ensures the test genuinely validates or invalidates the assumption.

**Why the others are wrong:**
- Choosing the metric after seeing results invites confirmation bias and lets teams cherry-pick a metric that makes the outcome look favorable.
- Every MVP type, including concierge, needs a predefined metric (e.g., repeat usage rate, willingness to pay) — direct observation alone is not a substitute for a clear pass/fail bar.
- Every experiment, regardless of MVP type, needs a predefined success metric to determine whether the underlying assumption was validated.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

