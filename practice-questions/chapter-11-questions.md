## Chapter 11: Responsible AI, Platform Thinking, and Security for Digital Products — Practice Questions

**Q1.** A team is building a feature that calculates the correct sales tax for an e-commerce order based on ZIP code and product category, using a published, finite table of official tax rates. Which approach should the PM recommend?

A) Train a machine learning model on historical order data to predict the tax rate
B) Use a generative AI model to estimate the likely tax rate
C) Use an ML model with mandatory human review of every calculation
D) Use deterministic rule-based logic that references the official tax rate table

<details>
<summary>Answer</summary>

**Correct: D**

The logic is finite, exact, and auditable — a lookup/rule engine guarantees correctness and compliance, which ML cannot.

**Why the others are wrong:**
- ML introduces unnecessary non-determinism and error risk for a task with one exact correct answer
- Generative AI is inappropriate for exact numeric/regulatory calculations
- Adds cost and latency without benefit since ML isn't needed at all

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A product team plans to launch an AI feature that automatically flags user photos suspected of containing self-harm imagery and removes them without human review. What should the PM require before launch?

A) An A/B test to measure engagement impact of the removal feature
B) A press release announcing the new safety feature
C) An A/B test comparing removal speed against a competitor's feature
D) A mandatory trust & safety review with a human-in-the-loop escalation path for flagged content

<details>
<summary>Answer</summary>

**Correct: D**

High-harm, sensitive content with fully automated irreversible action is a classic trust & safety review trigger requiring a human escalation path.

**Why the others are wrong:**
- Engagement metrics are irrelevant to a safety-critical risk decision
- Marketing communication is not a launch-blocking safety control
- Speed benchmarking does not address the harm/appeal risk

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** An external partner integrates with your company's public API. Engineering wants to rename a required field in the API response and remove the old field immediately. What is the PM's best course of action?

A) Approve the change since it improves internal code clarity
B) Silently make the change since partners should adapt automatically
C) Require a new major API version, keep the old field available during a deprecation window, and notify partners in advance
D) Ask engineering to rename the field but keep the version number the same

<details>
<summary>Answer</summary>

**Correct: C**

Renaming/removing a required field is a breaking change and requires a major version bump, deprecation window, and advance partner communication to preserve backward compatibility.

**Why the others are wrong:**
- Internal code clarity doesn't justify breaking an external contract
- Silent breaking changes destroy partner trust and violate integration norms
- Keeping the same version number while breaking the contract misleads consumers about compatibility

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** A payments team wants to detect fraudulent transactions involving complex, evolving patterns across thousands of variables (device, location, velocity, amount). Which approach is most appropriate?

A) A deterministic if/else rule engine listing all known fraud patterns
B) A single fixed threshold on transaction amount
C) No automated detection; manual review of all transactions
D) A machine learning model trained on labeled historical fraud data, with human review for edge cases

<details>
<summary>Answer</summary>

**Correct: D**

The pattern space is too large and evolving to hand-code exhaustively, making ML with human review of edge cases the right fit.

**Why the others are wrong:**
- Fraud patterns evolve faster than a hand-maintained rule list can keep up with
- A single amount threshold ignores most fraud signals and produces high error rates
- Manual review of all transactions doesn't scale to transaction volume

</details>

---

**Q5.** A PM is defining the confidence threshold strategy for an AI-based content moderation model that outputs a probability score for policy-violating content. Which strategy best balances user experience and safety risk?

A) Auto-remove all content flagged above 0% confidence
B) Auto-remove content only when confidence exceeds a high threshold (e.g., 95%); route lower-confidence flags to human review
C) Never auto-remove; require human review of every single post regardless of confidence
D) Set no threshold and let the model decide independently in production

<details>
<summary>Answer</summary>

**Correct: B**

A high auto-action threshold minimizes false positives on legitimate users while routing uncertain cases to humans, balancing safety and experience.

**Why the others are wrong:**
- An extremely low threshold causes massive false positives, harming legitimate users
- Reviewing every post manually doesn't scale and defeats the purpose of automation at high confidence
- No threshold means the PM abdicates a critical risk decision to the model

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q6.** A team building a fraud-scoring model must decide what happens when the model's confidence score falls into a 'gray zone' (e.g., 40%-70%). What is the best configuration for a PM to specify?

A) Auto-approve all gray-zone transactions to reduce friction
B) Auto-decline all gray-zone transactions to minimize fraud loss
C) Randomly assign gray-zone transactions to approve or decline
D) Route gray-zone transactions to a human review queue with a defined SLA

<details>
<summary>Answer</summary>

**Correct: D**

Uncertain-confidence cases should be escalated to human review with a service-level agreement, rather than resolved by an arbitrary automated rule.

**Why the others are wrong:**
- Auto-approving ignores real fraud risk in an uncertain zone
- Auto-declining creates unacceptable false-positive friction for legitimate customers
- Random handling is not defensible, consistent, or auditable

</details>

---

**Q7.** An API is experiencing bursty traffic from a partner integration, with occasional short spikes but a stable average request rate. Which rate-limiting configuration should the PM specify to accommodate this pattern without blocking legitimate spikes?

A) Token bucket algorithm allowing burst capacity above the sustained average rate
B) Fixed window counter reset every 60 seconds with a hard cap
C) Block all requests above the average rate immediately
D) No rate limiting at all

<details>
<summary>Answer</summary>

**Correct: A**

A token bucket permits short bursts while still enforcing a long-term average rate, matching the described traffic pattern.

**Why the others are wrong:**
- Fixed windows cause edge-of-window burst rejection and don't accommodate expected spikes well
- Hard-blocking at the average rate rejects legitimate burst traffic
- No rate limiting leaves the API vulnerable to abuse and overload

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** Which statement correctly distinguishes pseudonymized data from anonymized data under privacy regulations such as GDPR?

A) Pseudonymized data cannot be re-identified under any circumstances, while anonymized data can be
B) There is no legal distinction between the two terms
C) Pseudonymized data can be re-linked to an individual via a separate key and is still regulated as personal data, while anonymized data cannot be re-linked and falls outside PII regulation
D) Anonymized data always requires more security controls than pseudonymized data

<details>
<summary>Answer</summary>

**Correct: C**

Pseudonymized data retains a re-identification key and remains regulated personal data; true anonymization removes re-linkage entirely and is out of scope.

**Why the others are wrong:**
- The definitions are reversed
- The two terms carry materially different legal treatment
- Anonymized data typically requires fewer controls since it is out of PII scope, not more

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

