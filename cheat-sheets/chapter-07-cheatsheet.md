# Ch.7 Cheat Sheet: Prioritization & Roadmapping

## RICE
`RICE = (Reach × Impact × Confidence) / Effort`
- Reach: # users/customers affected per time period
- Impact: scale, commonly 3=massive, 2=high, 1=medium, 0.5=low, 0.25=minimal
- Confidence: decimal 0–1 (NOT whole %, this is the #1 calc trap)
- Effort: person-time (denominator — higher effort lowers score)
- Best for: large backlog, limited/uncertain data — Confidence absorbs uncertainty

## WSJF (SAFe)
`WSJF = Cost of Delay / Job Size`
- Cost of Delay = User-Business Value + Time Criticality + Risk Reduction/Opportunity Enablement Value
- Job Size = relative effort/duration estimate
- Higher WSJF = higher priority (do first)
- Best for: high cost-of-delay urgency, sequencing competing initiatives economically

## MoSCoW
| Category | Meaning |
|---|---|
| Must | Non-negotiable, release fails without it |
| Should | Important, not release-blocking |
| Could | Nice-to-have, first cut if constrained |
| Won't | Explicitly out of scope this cycle |

Best for: fixed date + fixed capacity, single-release scope negotiation.

## Kano Model
| Category | Behavior |
|---|---|
| Basic (must-be) | Absent → dissatisfaction; present → no boost above baseline |
| Performance | Linear: more delivered = more satisfaction |
| Delighter | Absent → no complaint; present → satisfaction boost (unexpected) |

Exam trap: delighters migrate to performance/basic over time as expectations rise.

## Framework Selection Rule of Thumb
| Constraint described | Framework |
|---|---|
| Limited/uncertain data, many ideas | RICE |
| High cost-of-delay/urgency, competing initiatives | WSJF |
| Fixed date + capacity, need scope cut | MoSCoW |
| Need to classify feature type by satisfaction | Kano |

## Roadmap Formats
| Format | Commitment | Risk |
|---|---|---|
| Date-based roadmap / Gantt | Specific dates | False certainty, trust damage on slip |
| Now-Next-Later | Outcomes, relative sequencing | Communicates direction without date lock-in |

Now = active, high confidence. Next = upcoming, medium confidence. Later = exploratory, low confidence, no dates.

## Value Stream Mapping (VSM) Basics
- Maps each step from idea → delivered value
- Measures Lead Time (total elapsed) vs Cycle Time (active work time) per stage
- Goal: find bottlenecks / wait time / non-value-add steps
- NOT a prioritization tool — it's a flow-efficiency diagnostic

## Common Exam Traps
1. Confusing RICE's Confidence (decimal) with a percentage in calculations.
2. Choosing RICE when the scenario clearly states urgency/cost-of-delay is the driver (should be WSJF).
3. Choosing WSJF when data is sparse and the scenario has no urgency signal (should be RICE).
4. Classifying a delighter as a basic feature (or vice versa) by ignoring the asymmetry of dissatisfaction vs satisfaction.
5. Recommending a date-based roadmap when the scenario stresses avoiding overcommitment to dates.
