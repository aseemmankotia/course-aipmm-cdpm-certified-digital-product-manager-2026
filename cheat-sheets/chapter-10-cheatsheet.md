## Chapter 10 Cheat Sheet — UX, Accessibility, Design Systems

### WCAG 2.1 Contrast Requirements
| Level | Normal Text | Large Text (18pt+/14pt bold+) |
|---|---|---|
| AA (standard target) | 4.5:1 | 3:1 |
| AAA (strict) | 7:1 | 4.5:1 |

**Exam note:** Most products only need to meet AA. AAA is the exception, often for specialized/government use cases.

### Core Accessibility Checks a PM Must Recognize
| Requirement | WCAG SC | What Fails It |
|---|---|---|
| Contrast | 1.4.3 | Light gray text on white, low-contrast buttons |
| Keyboard nav | 2.1.1 | Mouse-only custom dropdowns/modals, no Tab/Enter support |
| Alt text | 1.1.1 | Images/icons with no text alternative for screen readers |

**Common mistake:** Assuming visual polish = accessibility. A beautiful UI can still fail contrast or keyboard checks.

### Nielsen's 10 Usability Heuristics (heavily tested subset)
| Heuristic | Violation Example |
|---|---|
| Visibility of system status | No feedback during long processing (e.g., silent 8s wait) |
| Error prevention | No confirmation before destructive action (delete account) |
| Consistency and standards | Custom icon meanings that contradict platform norms |
| User control and freedom | No way to cancel/undo an action in progress |
| Recognition rather than recall | Forcing users to remember codes instead of showing labels |

**Exam trap:** Questions describe a broken interface and ask *which heuristic* is violated — match the symptom to the exact heuristic, not a similar-sounding one.

### Design System: Reuse vs Custom Decision Rule
| Situation | PM Decision |
|---|---|
| Existing component meets functional + accessibility needs | **Reuse** — default choice, preserves consistency & speed |
| Existing component structurally cannot support the required interaction | **Custom** — justified exception |
| Team wants custom purely for branding/preference | **Reuse** — brand preference alone is not sufficient justification |

**Common mistake:** Approving custom design purely for aesthetic differentiation when a compliant, functional component already exists — this is a classic wrong-answer trap on the exam.

### Usability Testing Basics
- **5 users** ≈ 85% of usability issues found (Nielsen). Use for fast, PM-led validation rounds.
- PM role: define test scenarios, recruit representative users, observe/synthesize findings.
- PM does NOT own: exact interaction/animation specs, visual design details — partner with design/eng instead.

### Quick Decision Framework for Design Constraint Questions
1. Is there an accessibility violation (contrast, keyboard, screen reader)? → Flag and require fix to meet WCAG AA.
2. Is a usability heuristic violated? → Name the specific heuristic, not a general 'bad UX' answer.
3. Does an existing design system component satisfy the need? → Reuse unless a genuine functional gap exists.
4. Is this an interaction-design detail? → PM partners, does not dictate.
