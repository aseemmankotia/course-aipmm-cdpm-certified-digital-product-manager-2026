# Chapter 8 Cheat Sheet: Product Analytics & North Star Metric

## AARRR Funnel (order matters on the exam)
| Stage | Question It Answers | Example Metric |
|---|---|---|
| Acquisition | How do users find us? | Signups by channel |
| Activation | Do users reach first value (aha-moment)? | % completing setup in 24h |
| Retention | Do users come back? | Day-30 retention rate |
| Referral | Do users bring others? | Viral coefficient (K-factor) |
| Revenue | Do users pay? | MRR, LTV, conversion-to-paid |

**Exam trap:** A metric described as "% of new users doing X within Y hours of signup" = Activation, NOT Acquisition.

## Vanity vs. Actionable Metrics
| Vanity (avoid as primary KPI) | Actionable (prefer) |
|---|---|
| Total downloads | Activation rate (% reaching aha-moment) |
| Total registered users | Weekly active users doing core action |
| Page views | Task completion rate |
| Social followers | Referral-driven signups (K-factor) |

**Rule of thumb:** If a metric only ever goes up (cumulative total) and can't be tested against a change, it's vanity.

## North Star Metric (NSM) Selection Checklist
1. Reflects real customer value delivered (not company output)
2. Leading indicator of revenue/business success — NOT revenue itself
3. Actionable — teams can move it through product decisions
4. Measurable frequently enough to detect experiment impact

**Classic examples:** Facebook — "7 friends in 10 days" (activation → predicts retention); Airbnb — nights booked; Spotify — time spent listening.

**Exam trap:** MRR/Revenue is almost never the correct NSM answer — it's a lagging output, not a leading/actionable signal.

## Guardrail Metrics
Purpose: prevent local optimization (winning one metric while silently harming another).
| Primary Metric Being Optimized | Guardrail to Pair With It |
|---|---|
| DAU (via more notifications) | Uninstall/opt-out rate |
| Engagement (via infinite scroll/autoplay) | Session quality / complaint rate |
| Conversion rate (via aggressive upsells) | Refund rate / support tickets |

## Cohort Analysis Basics
- Groups users by signup period (e.g., month) and tracks retention over time for each group.
- Rising Day-30 retention across successive cohorts after a shipped change = evidence the change works.
- Flat/declining retention across cohorts despite feature launches = changes aren't moving the needle.
- A flattening (plateauing) retention curve = product-market fit signal; a curve trending to 0% = no PMF.

## Interpreting Metric Movement (Decision Logic)
- Short-term metric up, long-term flat → investigate causal link to aha-moment before scaling or killing.
- Funnel-stage metrics flat but NSM declining → check guardrail metrics (quality, latency, satisfaction).
- Acquisition up, Activation flat → onboarding problem, not a marketing/spend problem.
