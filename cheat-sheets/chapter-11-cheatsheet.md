## Ch.11 Cheat Sheet: Responsible AI, Platform Thinking & Security

### ML vs. Deterministic Logic
| Use Rules When | Use ML When |
|---|---|
| Finite, exact answer exists | Pattern is fuzzy/probabilistic |
| Must be 100% consistent & auditable | Inputs vary continuously |
| Legal/regulatory table lookup (tax, eligibility) | Too many variables to hand-code (fraud, images, NLP) |
| Low tolerance for error | Some error rate is acceptable with mitigation |

### Confidence Threshold Decision Framework
| Threshold Zone | Action |
|---|---|
| High confidence (e.g., >90-95%) | Auto-action allowed |
| Gray zone (e.g., 40-70%) | Route to human review queue w/ SLA |
| Low confidence | Do not auto-act; flag for review |
Note: Exact cutoffs are a business risk decision the PM sets with stakeholders — not a fixed exam number.

### AI Ethics / Trust & Safety Review Triggers
- Automated action on harm-related or sensitive content (self-harm, violence, hate)
- Decisions affecting legal, financial, or health outcomes
- Use of sensitive data categories: health, biometric, minors
- No human appeal/override path for an automated decision

### Data Privacy Terms
| Term | Re-identifiable? | Regulated as PII? |
|---|---|---|
| PII | Yes (direct) | Yes |
| Pseudonymized | Yes (via separate key) | Yes |
| Anonymized | No | No |
Consent: explicit opt-in required for using personal data in AI training/personalization; never pre-checked.

### API / Platform Thinking
| Concept | Rule of Thumb |
|---|---|
| Safe change | Additive only (new optional field/endpoint) |
| Breaking change | Remove/rename field, change type, add required param |
| Versioning | Breaking change → new MAJOR version + deprecation window + partner notice |
| Rate limit responses | HTTP 429 Too Many Requests |
| Rate limiting strategy | Fixed window (simple, edge-burst issue) vs. Sliding window (smoother) vs. Token bucket (allows bursts, enforces average) |

### Security & Access Control Basics
- Principle of least privilege: only roles with defined need access PII/training data
- Access should be logged and time-limited
- Separate raw PII stores from feature/analytics stores where possible

### Exam Traps
- Assuming "data involved" = ML needed (it doesn't if logic is a finite lookup)
- Treating field renames as "minor" changes not requiring a version bump
- Setting moderation threshold to catch everything (0% confidence) — causes false-positive harm
- Confusing anonymized (unregulated) with pseudonymized (still regulated)
- Waiting for legal/security to flag ethics risk instead of PM proactively triggering review
