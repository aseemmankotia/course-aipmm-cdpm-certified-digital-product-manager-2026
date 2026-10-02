## Chapter 10: UX Fundamentals, Accessibility, and Design Systems for PMs — Practice Questions

**Q1.** A user clicks 'Submit Order' and the interface shows no spinner, no disabled state, and no confirmation message while the request processes for 8 seconds. Which usability heuristic is violated?

A) Visibility of system status
B) Consistency and standards
C) Aesthetic and minimalist design
D) Recognition rather than recall

<details>
<summary>Answer</summary>

**Correct: A**

Visibility of system status requires the interface to keep users informed of what is happening through timely feedback. A silent 8-second wait with no indicator directly violates this.

**Why the others are wrong:**
- Consistency and standards is about matching platform conventions, not feedback timing.
- Aesthetic and minimalist design concerns unnecessary visual clutter, not missing feedback.
- Recognition rather than recall is about minimizing memory load, unrelated to processing feedback.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A designer proposes body text in light gray (#AAAAAA) on a white background and claims it meets accessibility standards. The measured contrast ratio is approximately 2.3:1. What should the PM require?

A) Approve it since gray text looks modern
B) Require 7:1 contrast since this is a legal requirement for all products
C) Ask the designer to add a background blur instead
D) Require a redesign to reach at least 4.5:1 contrast for normal text per WCAG 2.1 AA

<details>
<summary>Answer</summary>

**Correct: D**

WCAG 2.1 Level AA requires a minimum contrast ratio of 4.5:1 for normal body text. 2.3:1 fails this threshold and must be corrected.

**Why the others are wrong:**
- Approving it ignores a clear accessibility failure that would fail an audit.
- 7:1 is the Level AAA threshold, not the standard AA requirement most products target.
- A background blur does not address the underlying luminance contrast problem.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** A product team is designing a highly novel gesture-based interaction for a data visualization tool that has no equivalent in the company's existing component library. What is the correct PM decision?

A) Force reuse of an existing chart component to save time
B) Reject the feature since custom design is never justified
C) Approve custom design work since no existing component meets the functional need
D) Ask engineering to fake the interaction with CSS only

<details>
<summary>Answer</summary>

**Correct: C**

Custom design is justified when existing components cannot satisfy a genuinely novel functional requirement — forcing reuse here would degrade usability.

**Why the others are wrong:**
- Forcing an ill-fitting component increases usability risk and technical debt.
- Custom design is sometimes necessary; blanket rejection ignores legitimate product needs.
- CSS-only tricks would not deliver the required interaction and hides the real design gap.

</details>

---

**Q4.** A government-facing web application must comply with WCAG 2.1 Level AA. What minimum contrast ratio must standard body text achieve?

A) 2:1
B) 4.5:1
C) 3:1
D) 7:1

<details>
<summary>Answer</summary>

**Correct: B**

WCAG 2.1 AA Success Criterion 1.4.3 requires a 4.5:1 contrast ratio for normal-size text.

**Why the others are wrong:**
- 2:1 is far below any WCAG conformance level.
- 3:1 is the AA threshold for large text (18pt+ or 14pt bold+), not normal text.
- 7:1 is the AAA threshold for normal text, a stricter level not required by standard AA compliance.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q5.** Which of the following is NOT one of Nielsen's 10 usability heuristics?

A) Error prevention
B) User control and freedom
C) Recognition rather than recall
D) Maximum feature density

<details>
<summary>Answer</summary>

**Correct: D**

'Maximum feature density' is not a recognized heuristic; Nielsen's heuristics actually favor minimalist, uncluttered design.

**Why the others are wrong:**
- Error prevention is one of the 10 core heuristics.
- User control and freedom is one of the 10 core heuristics, covering undo/redo and exits.
- Recognition rather than recall is one of the 10 core heuristics, reducing user memory load.

</details>

---

**Q6.** QA reports that a custom dropdown menu built entirely from styled <div> elements cannot be opened, navigated, or selected using only the Tab and Enter keys. Which accessibility requirement is being violated?

A) Color contrast requirement
B) Alt text requirement for images
C) Responsive design breakpoint requirement
D) Keyboard operability requirement (all functionality must be usable via keyboard)

<details>
<summary>Answer</summary>

**Correct: D**

WCAG requires all interactive functionality to be operable via keyboard alone (Success Criterion 2.1.1). A mouse-only custom widget fails this.

**Why the others are wrong:**
- Color contrast concerns visual perception of text/UI, not input method.
- Alt text applies to images and non-text content, not interactive widget operability.
- Responsive breakpoints concern layout across screen sizes, unrelated to keyboard access.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** A PM wants to add a date-range picker to a feature, and the company's design system already contains a standard, accessible date-range picker component that meets the functional requirements. What should the PM do?

A) Request a fully custom date-range picker to differentiate the brand
B) Skip the date picker entirely to avoid design review
C) Ask engineering to build it without consulting design at all
D) Request reuse of the existing design system component to maintain consistency and reduce cost

<details>
<summary>Answer</summary>

**Correct: D**

When an existing component meets functional and accessibility requirements, reuse is the correct default — it preserves consistency, speeds delivery, and inherits already-validated accessibility.

**Why the others are wrong:**
- Custom design here adds cost and inconsistency with no functional benefit.
- Skipping the feature ignores the product requirement rather than solving it efficiently.
- Building without design/accessibility review risks introducing usability and compliance gaps that the design system component already solves.

</details>

---

**Q8.** According to Nielsen's classic usability research, testing a design with approximately how many representative users typically uncovers about 85% of usability problems?

A) 3 users
B) 10 users
C) 5 users
D) 20 users

<details>
<summary>Answer</summary>

**Correct: C**

Nielsen's well-established finding is that testing with 5 users reveals roughly 85% of usability issues, making it a practical target for lightweight PM-led usability testing.

**Why the others are wrong:**
- 3 users is too few to reliably surface most issues per the original research.
- 10 users yields diminishing returns beyond the ~85% already found at 5.
- 20 users is far beyond the efficient threshold Nielsen's research identifies for early-stage testing.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

