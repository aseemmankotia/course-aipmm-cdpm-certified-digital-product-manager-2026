## Chapter 9 Cheat Sheet: Growth, Pricing, PLG

### Funnel Diagnosis Rule
1. Compute conversion % between EVERY consecutive stage (stage_n / stage_n-1).
2. The stage with the **lowest %** = biggest leak = highest-leverage experiment target.
3. Never prioritize by raw user count lost — always by conversion rate.
4. Don't fix top-of-funnel volume while a mid-funnel leak exists — it wastes acquisition spend.

### PLG vs. Sales-Led Motion
| Dimension | PLG | Sales-Led |
|---|---|---|
| Who drives adoption | End user (bottom-up) | Sales rep / buyer (top-down) |
| Access before purchase | Self-serve trial/freemium | Demo gated by rep |
| Typical ACV | Lower, high volume | Higher, lower volume |
| CAC | Generally lower | Generally higher (SDR/AE cost) |
| Expansion driver | In-product usage triggers | Account manager / renewal calls |

### Pricing Model Selection
| Model | Definition | Best Fit |
|---|---|---|
| Flat-rate | One price, all customers | Simple products, undifferentiated usage |
| Usage-based | Price scales with consumption | APIs, infra, dev tools |
| Tiered | Fixed bands, feature-gated | Multiple segments (solo/team/enterprise) |
| Freemium | Free tier + paid tiers | PLG products needing wide top-of-funnel + self-serve upgrade path |

### In-Product Upgrade Prompts (PLG)
- Trigger at the **moment of friction tied to value** (usage limit hit, gated feature attempted).
- Exam trap: prompting at signup, before any value experienced = wrong answer.

### Growth Experiment Design Checklist
1. **Hypothesis** tied to one funnel stage.
2. **Primary success metric** = conversion rate of that specific stage (not company-wide lagging metrics like total revenue or NPS).
3. **Sample size / duration** defined before launch.
4. **One variable changed** per test where possible.

### Interpreting Metric Movement — Correct Next Action Patterns
| Observation | Correct Action |
|---|---|
| Engagement up, conversion flat despite repeated same-lever tests | Move to next funnel stage or investigate pricing/packaging |
| Free-tier limits widened, conversion drops, signups rise | Reintroduce meaningful cap or gate high-value feature |
| One stage has much lower % conversion than others | Prioritize experiments there first |
| Broad lagging metric (revenue/NPS) used to judge a stage-specific test | Wrong — use a stage-specific leading metric instead |

### Common Exam Traps
- Choosing 'add more top-of-funnel acquisition' when the real problem is a mid-funnel conversion leak.
- Assuming sales-led always has lower CAC than PLG (usually the opposite).
- Treating rising signups/engagement as success while conversion (revenue driver) is declining.
- Repeating the same experiment type after diminishing returns instead of shifting focus to the next stage or lever.
