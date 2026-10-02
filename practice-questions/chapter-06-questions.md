## Chapter 6: Agile Delivery Fundamentals for Digital Products — Practice Questions

**Q1.** A digital product team receives a constant stream of unpredictable customer support tickets alongside planned feature work, and stakeholders need to see items released as soon as they're ready rather than waiting for a fixed cadence. Which delivery approach BEST fits this team?

A) Scrum with 2-week sprints and a hard sprint commitment
B) Kanban with WIP limits and continuous flow
C) Scrum with 4-week sprints to absorb variability
D) Waterfall with quarterly release gates

<details>
<summary>Answer</summary>

**Correct: B**

Kanban is designed for continuous, unpredictable inflow of work with WIP limits controlling throughput, and it releases items as soon as they clear the workflow — no fixed iteration boundary needed.

**Why the others are wrong:**
- A fixed sprint commitment assumes predictable, plannable batches of work, which conflicts with unpredictable ticket inflow.
- Longer sprints don't solve the core mismatch — the team still can't commit to a fixed batch when inflow is unpredictable.
- Waterfall's quarterly gates are the opposite of the release-as-ready need described.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** During sprint planning, the development team says a user story is too vague to estimate. The Product Owner insists the sprint commitment can't change and pushes the team to estimate anyway. Whose responsibility was it to prevent this situation?

A) The Scrum Master, by facilitating the sprint planning meeting
B) The Product Owner, by ensuring the story was refined and met the Definition of Ready before planning
C) The development team, by refusing to attend sprint planning
D) The stakeholders, by writing clearer requirements

<details>
<summary>Answer</summary>

**Correct: B**

The Product Owner owns the backlog and is accountable for ensuring items are refined, clear, and estimable (Definition of Ready) before they enter sprint planning.

**Why the others are wrong:**
- The Scrum Master facilitates process and removes impediments but doesn't own backlog content quality.
- Refusing to attend doesn't address the root cause — poor refinement — and isn't a standard team responsibility.
- Stakeholders provide input but the PO is accountable for translating that into ready, estimable stories.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** A newly formed team has no historical velocity data and needs a fast way to size a 40-item backlog before the first sprint. Which estimation approach is MOST appropriate for this situation?

A) Story points calibrated against a known reference story from a previous team
B) Ideal hours estimated individually by each developer with no discussion
C) T-shirt sizing (S/M/L/XL) followed by a planning poker refinement pass
D) Skipping estimation and committing to all 40 items in sprint 1

<details>
<summary>Answer</summary>

**Correct: C**

T-shirt sizing is fast for rough relative sizing of a large, unrefined backlog with no baseline, and following it with planning poker refines the estimate as the team calibrates together.

**Why the others are wrong:**
- Story points calibrated against another team's reference story are unreliable since velocity/complexity perception isn't transferable across teams.
- Individual estimates without discussion lose the calibration benefit that group estimation (e.g., planning poker) provides and produce inconsistent results.
- Committing without any estimation ignores capacity planning entirely and risks an unachievable sprint commitment.

</details>

---

**Q4.** Which activity is the Scrum Master responsible for, that is explicitly NOT a Product Owner responsibility?

A) Removing impediments blocking the development team's progress
B) Prioritizing the product backlog based on business value
C) Writing acceptance criteria for user stories
D) Deciding whether a feature should be released to customers

<details>
<summary>Answer</summary>

**Correct: A**

Removing impediments and facilitating the team's process is the Scrum Master's core accountability; the PO focuses on backlog content and value decisions.

**Why the others are wrong:**
- Prioritization is a Product Owner decision right, not the Scrum Master's.
- Acceptance criteria are typically owned/authored (or approved) by the Product Owner in collaboration with the team.
- Release decisions are a Product Owner (or product management) call, not the Scrum Master's.

</details>

---

**Q5.** A backlog item reads: 'As a returning customer, I want to save my payment method, so that I can check out faster next time.' The team adds: 'Given a saved card on file, when the user reaches checkout, then the saved card is pre-selected and the user can complete purchase in one click.' What does the second part represent?

A) The Definition of Done for the entire sprint
B) A separate epic that should be split out
C) Acceptance criteria written in Given/When/Then format
D) A non-functional requirement unrelated to the story

<details>
<summary>Answer</summary>

**Correct: C**

Given/When/Then is a standard acceptance criteria format that defines the specific, testable condition under which the story is considered correctly implemented.

**Why the others are wrong:**
- Definition of Done applies to every story/increment team-wide (e.g., code reviewed, tested, deployed) — it's not story-specific like this condition.
- This is a testable condition for the existing story, not a new epic.
- This is a functional condition directly tied to the story's behavior, not a non-functional requirement like performance or security.

</details>

---

**Q6.** Which of the following backlog items BEST satisfies the 'Independent' and 'Small' criteria of INVEST?

A) As a user, I want a redesigned account settings page including profile, security, notifications, and billing sections, so that everything is in one place.
B) As a user, I want the entire onboarding flow rebuilt to support three new user types, so that acquisition improves.
C) As a user, I want to update my email address in account settings, so that I receive notifications at my current address.
D) As a developer, I want to refactor the authentication service, so that the code is cleaner.

<details>
<summary>Answer</summary>

**Correct: C**

This story is scoped to a single, deliverable capability (updating an email address) that can be built and tested independently within a sprint — satisfying Small and Independent.

**Why the others are wrong:**
- Bundling four distinct sections violates Small and creates dependencies between sub-features, violating Independent.
- Rebuilding an entire flow for three user types is epic-sized, not a sprint-sized independent story.
- This is written from a developer/technical angle with no user value framing, and it's broad ('refactor the service') rather than a small, valuable increment.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** A team has been skipping backlog refinement for three sprints because 'there's no time.' As a result, sprint planning meetings are running 3 hours instead of 1, and half the stories get rejected as unclear. What is the MOST likely root cause?

A) The team's story point scale is miscalibrated
B) Refinement (typically 5-10% of sprint capacity) was skipped, so stories arrived at planning without clarity or estimates
C) The Definition of Done is too strict
D) The Scrum Master scheduled sprint planning at the wrong time of day

<details>
<summary>Answer</summary>

**Correct: B**

Backlog refinement is typically budgeted at roughly 5-10% of a sprint's capacity to keep upcoming stories clear, sized, and ready; skipping it directly causes long, chaotic planning sessions and rejected stories.

**Why the others are wrong:**
- A miscalibrated point scale would cause estimate disputes, not wholesale story rejection for being unclear.
- An overly strict DoD affects what counts as 'done,' not whether stories are understood at planning time.
- Meeting scheduling time doesn't explain rejected, unclear stories — that's a content/preparation problem, not a timing problem.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** What is the primary distinction between 'acceptance criteria' and 'Definition of Done' in agile delivery?

A) Acceptance criteria are story-specific conditions for a single item; Definition of Done is a team-wide standard applied to every increment
B) Acceptance criteria apply to the whole team's process; Definition of Done applies only to one story
C) They are interchangeable terms for the same artifact
D) Acceptance criteria are written by developers; Definition of Done is written by stakeholders

<details>
<summary>Answer</summary>

**Correct: A**

Acceptance criteria define when a specific story meets its intended behavior; Definition of Done is a consistent, team-wide checklist (e.g., tested, reviewed, documented) applied to every completed item regardless of story content.

**Why the others are wrong:**
- This reverses the actual scope of each artifact.
- They serve different purposes and are commonly confused, but are not interchangeable — this is the exact trap the exam tests.
- Authorship isn't the distinguishing factor; both are typically shaped collaboratively, often with PO involvement on acceptance criteria.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

