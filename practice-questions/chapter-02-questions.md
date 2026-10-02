## Chapter 2: Customer Discovery, JTBD, and Design Thinking — Understanding the User — Practice Questions

**Q1.** A meal-kit company interviews churned customers. One says: "I stopped cooking from scratch because I felt like a failure every time I burned something in front of my kids." Which job type does this statement primarily reveal?

A) Functional job — the customer needs food prepared
B) Social job — the customer wants to be perceived as a good cook
C) Emotional job — the customer wants to avoid feeling incompetent
D) Financial job — the customer wants to save money on groceries

<details>
<summary>Answer</summary>

**Correct: C**

The statement centers on an internal feeling (failure, embarrassment) tied to the act of cooking, which is the definition of an emotional job — how the customer wants to feel or avoid feeling.

**Why the others are wrong:**
- Functional would be about the practical task of getting dinner on the table, not the feeling around performing it
- Social would require a reference to how others perceive them (e.g., 'my kids think I'm a bad cook'), not just her own internal feeling
- Financial job is not one of the three JTBD job types tested (functional, emotional, social)

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A PM writes: 'When I'm commuting on a crowded train and my phone battery is at 10%, I want to quickly find the nearest charging station, so I can stay connected until I get home.' What discovery artifact is this?

A) A traditional user story ('As a user, I want...')
B) A persona description
C) A job story ('When... I want to... so I can...')
D) A journey map touchpoint

<details>
<summary>Answer</summary>

**Correct: C**

The sentence follows the exact job story structure: situation (When...), motivation (I want to...), expected outcome (so I can...), and deliberately omits any reference to a persona or role.

**Why the others are wrong:**
- A traditional user story requires the format 'As a [role], I want [goal], so that [benefit]' and centers on the persona/role, which is absent here
- A persona description would summarize demographic/behavioral traits of a user archetype, not a specific situational trigger
- A journey map touchpoint would be plotted on a timeline of stages with associated emotions/friction, not written as a single sentence

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** A team has a vague hunch that users abandon onboarding but has zero data on why. Leadership wants directional insight within one week before committing engineering resources. Which discovery method BEST fits this level of uncertainty and constraint?

A) A/B test two onboarding flows with statistical significance
B) A large-scale quantitative survey sent to the entire user base
C) Build a high-fidelity prototype and run a usability test
D) 5-8 unmoderated qualitative interviews with recently churned users

<details>
<summary>Answer</summary>

**Correct: D**

When uncertainty is high (you don't even know the 'why') and time/resources are constrained, a small batch of qualitative interviews is the fastest way to surface causal insight before investing in build or statistical testing.

**Why the others are wrong:**
- A/B testing requires a working alternative flow and enough traffic for significance — premature when you don't know the underlying cause of abandonment
- A large survey is better for validating a known hypothesis at scale, not for exploring an unknown 'why' — it also takes longer to field and analyze than a week allows
- Building a prototype assumes you already know what to fix; you haven't yet defined the problem, so this skips straight to solutioning

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** Which statement correctly differentiates jobs-based segmentation from traditional persona-based segmentation?

A) Jobs-based segmentation groups customers by demographic and psychographic traits, while personas group them by the task being accomplished
B) Jobs-based segmentation groups customers by the progress they're trying to make, while personas group them by who the customer is (demographics, attitudes, behaviors)
C) Jobs-based segmentation and persona segmentation are two names for the exact same technique
D) Jobs-based segmentation is only used in B2B contexts, while personas are only used in B2C contexts

<details>
<summary>Answer</summary>

**Correct: B**

JTBD segmentation is organized around the underlying job/progress a customer is trying to make, regardless of who they are, while persona segmentation clusters users by descriptive traits like age, role, or attitudes.

**Why the others are wrong:**
- This reverses the actual definitions — demographic/psychographic traits describe personas, not jobs-based segmentation
- They are frequently confused but are distinct methods testing different questions (what progress vs. who is the user), so they are not interchangeable
- Both approaches are used across B2B and B2C; the distinction is methodological, not market-type based

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q5.** In the Design Thinking process, what is the correct sequential order of the five stages?

A) Define, Empathize, Ideate, Test, Prototype
B) Empathize, Define, Ideate, Prototype, Test
C) Ideate, Empathize, Define, Prototype, Test
D) Empathize, Ideate, Define, Test, Prototype

<details>
<summary>Answer</summary>

**Correct: B**

The standard Design Thinking sequence is Empathize (understand users), Define (frame the problem), Ideate (generate solutions), Prototype (build a testable representation), and Test (validate with users).

**Why the others are wrong:**
- This places Define before Empathize, but you cannot frame the problem statement before gathering empathy-based research
- This starts with Ideate before understanding the user, skipping the foundational research needed to generate relevant ideas
- This swaps Prototype and Test order incorrectly relative to Define/Ideate, and places Define after Ideate, which reverses the correct problem-framing sequence

</details>

---

**Q6.** A stakeholder insists: 'Our users need a mobile app with push notifications.' Applying the principle of problem framing before solutioning, what should the PM do FIRST?

A) Immediately scope the mobile app and push notification feature for the next sprint
B) Survey users on their preferred notification frequency
C) Build a low-fidelity prototype of the app to gather early feedback
D) Ask what underlying job or friction the stakeholder believes the app and notifications will resolve

<details>
<summary>Answer</summary>

**Correct: D**

The stakeholder has jumped straight to a solution; problem framing requires the PM to first uncover the underlying job, need, or friction the proposed solution is assumed to solve, before validating that the app/notifications are the right approach.

**Why the others are wrong:**
- Scoping the feature immediately skips problem definition entirely and risks building the wrong solution
- Surveying on notification preferences assumes the solution (notifications) is already correct — it's a configuration question, not a problem-framing question
- Prototyping the app is a Design Thinking step that comes after Empathize and Define; jumping there first bypasses problem framing

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** During journey mapping for a food delivery app, the team identifies that the highest customer frustration occurs at the 'waiting for driver assignment' stage, even though checkout and payment stages score positively. What is the MOST appropriate next step?

A) Redesign the checkout flow since that stage has the most product surface area
B) Conclude the app has no major usability issues since most stages score positively
C) Add more payment options to increase overall satisfaction scores
D) Prioritize discovery and ideation specifically around the driver-assignment friction point

<details>
<summary>Answer</summary>

**Correct: D**

Journey mapping is used specifically to surface friction points along the customer's experience; the map has clearly identified driver-assignment as the highest-friction moment, so discovery effort should concentrate there rather than on already-positive stages.

**Why the others are wrong:**
- Checkout is already scoring positively; redesigning a non-problematic stage misallocates discovery resources away from the identified friction point
- One high-friction stage still represents a significant experience gap; averaging positive scores elsewhere does not negate a clearly surfaced problem
- Payment options address checkout, not the driver-assignment stage where the friction was actually identified

</details>

---

**Q8.** Which of the following best distinguishes a 'social job' from an 'emotional job' in JTBD theory?

A) A social job only applies to B2B products, while emotional jobs only apply to B2C products
B) A social job relates to how the customer wants to be perceived by others, while an emotional job relates to how the customer wants to feel internally
C) A social job and emotional job are interchangeable terms describing the same underlying customer motivation
D) A social job refers to using social media features, while an emotional job refers to app notifications

<details>
<summary>Answer</summary>

**Correct: B**

Social jobs concern the customer's desired image or status in the eyes of others (e.g., 'I want colleagues to see me as innovative'), while emotional jobs concern the customer's internal feelings (e.g., 'I want to feel confident'). This distinction is core JTBD theory and heavily tested.

**Why the others are wrong:**
- Both job types apply across B2B and B2C contexts; the distinction is about perception vs. internal feeling, not market type
- They are frequently confused but are not interchangeable — one is externally oriented (perception by others), the other internally oriented (self-feeling)
- This confuses the job types with literal product features; social/emotional jobs are motivational categories, not feature categories

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

