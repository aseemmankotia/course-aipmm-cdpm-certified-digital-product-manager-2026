## MVP Types — Quick Reference

| MVP Type | What Happens | Customer Awareness | Tests |
|---|---|---|---|
| Concierge | Human manually delivers full service | Knows it's manual | Whether customers value the outcome enough to pay/engage |
| Wizard of Oz | Human does work behind a fake automated front-end | Believes it's automated | Whether the automated version, once built, would be adopted |
| Landing Page / Smoke Test | No product built; sign-up/waitlist/pre-order page | Sees only marketing | Pure demand — will people want this at all |
| Single-Feature MVP | One real feature shipped inside/alongside existing product | Uses a real, working feature | Whether one specific capability drives adoption/value |

**Selection rule:** Pick the CHEAPEST MVP type that can still test the riskiest assumption. If the assumption is 'will they want it' → landing page. If it's 'will they value the delivered outcome' → concierge. If it's 'will they adopt the automated experience' → Wizard of Oz. If it's 'will they use this one new capability' → single-feature.

## Mislabeled MVP Red Flags
- Built with full production infrastructure, accounts, payments before any validation
- Launched to entire target market instead of a small test group
- No predefined success metric or kill/scale threshold
- Justified as MVP solely because it has 'fewer features' than the eventual vision

**Rule:** An MVP is defined by minimum cost/time to test ONE risky assumption — not by feature count or launch scope.

## A/B Testing Fundamentals

| Term | Meaning |
|---|---|
| Control | The existing/baseline experience (A) |
| Variant | The new experience being tested (B) |
| Statistical significance | Conventionally p < 0.05 — result unlikely due to chance |
| Sample size drivers | Baseline conversion rate, minimum detectable effect, statistical power (commonly 80%) |
| Common trap | Declaring a winner from a tiny sample or a very short test window |

**Experiment design rule:** Define the success metric and pass/fail threshold BEFORE launch — never choose the metric after seeing results.

## Exam Gotchas
- Concierge = manual + disclosed. Wizard of Oz = manual + hidden (looks automated).
- A scoped-down full release ≠ MVP, even if it has fewer features.
- Cheapest valid option always wins when multiple MVP types could technically work.
- No control group = no valid A/B test, regardless of sample size.
