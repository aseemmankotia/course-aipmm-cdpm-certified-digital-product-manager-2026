# Chapter 6 Cheat Sheet: Agile Delivery, Backlog, and Roadmapping

## Roles & Decision Rights
| Role | Owns | Does NOT Own |
|---|---|---|
| Product Owner | Backlog prioritization, acceptance criteria, release decisions, story readiness | Process facilitation, technical implementation |
| Scrum Master | Process facilitation, removing impediments, protecting team from disruption | Backlog content, prioritization |
| Dev Team | How work gets built, sprint task breakdown, technical estimates | What gets built or in what order |

**Exam trap:** Questions often swap PO and Scrum Master responsibilities — PO = *what/why/when released*, Scrum Master = *how the process runs*.

## Scrum vs Kanban
| Factor | Scrum | Kanban |
|---|---|---|
| Cadence | Fixed sprints (commonly 2 weeks) | Continuous flow, no fixed iteration |
| Commitment | Sprint backlog locked at planning | Work pulled continuously |
| Best fit | Planned, batchable feature work | Unpredictable inflow (support, ops) |
| Key mechanism | Sprint planning, review, retro | WIP limits |

## User Story Structure
```
As a [role], I want [goal], so that [benefit].
```
**Acceptance criteria (Given/When/Then):**
```
Given [context]
When [action]
Then [expected outcome]
```

## INVEST Criteria
| Letter | Meaning |
|---|---|
| I | Independent |
| N | Negotiable |
| V | Valuable |
| E | Estimable |
| S | Small |
| T | Testable |

## Acceptance Criteria vs Definition of Done
| | Acceptance Criteria | Definition of Done |
|---|---|---|
| Scope | One specific story | Every story/increment, team-wide |
| Example | "Saved card pre-selected at checkout" | "Code reviewed, tested, deployed to staging" |

## Estimation Approaches
| Method | When to Use |
|---|---|
| T-shirt sizing (S/M/L/XL) | New team, no velocity, large unrefined backlog — fast rough pass |
| Story points (planning poker) | Team has calibration/reference story, some velocity history |
| Ideal hours | Rare in mature agile teams; avoid individual-only estimates without discussion |

**Velocity** = avg. story points completed per sprint. Never compare velocity across teams.

## Backlog Refinement
- Cadence: ongoing, budget **~5-10% of sprint capacity**
- Goal: stories reach **Definition of Ready** before sprint planning
- Skipping refinement → long chaotic planning sessions, rejected stories (common exam scenario)

## Technical Debt Visibility
- Keep tech debt items **in the visible backlog**, not a hidden engineering-only list
- PM/PO allocates recurring capacity to address it
- Exam trap: "invisible" or engineering-only debt tracking is the wrong-answer pattern
