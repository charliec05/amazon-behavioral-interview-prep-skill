# Amazon Behavioral Interview Prep Skill

A Claude Code skill that acts as your personal Amazon behavioral interview coach. It helps you craft realistic, well-structured STAR/STARL stories anchored to Amazon's 16 Leadership Principles — and quizzes you in mock interview mode.

## Features

### Mode 1 — Prepare
1. **Resume intake** — paste your resume and the coach identifies your role level, domain, and strongest story candidates
2. **LP + question selection** — choose from all 16 Leadership Principles, with questions grouped by category so you know which ones can share the same story
3. **Experience matching** — the coach suggests 2–3 of your best-fit experiences and flags reuse opportunities across LPs
4. **Guided story skeleton** — walks you through the STAR/STARL skeleton conversationally, asking a few questions at a time
5. **Draft generation** — produces a polished 3–5 minute spoken answer, calibrated to your seniority level with realistic scope and quantified impact
6. **Collaborative refinement** — iterates with you until the story feels right
7. **Cheat sheet** — compact bullet-point memory aid with the LP tie-in and a note on which other questions this story covers

### Mode 2 — Practice
- Mock interview: the coach asks behavioral questions one at a time as an Amazon interviewer
- After each answer, scores you on Structure, Ownership, Impact, LP Alignment, and Packaging Quality (1–5 each)
- Gives one concrete strength and one actionable improvement per answer
- Ends with an overall summary: strongest LPs, gaps, and story reuse opportunities

## What Makes This Different

- **"Packaging" concept**: stories are real experiences reframed with LP-aligned logic — not fabricated. One real project can cover 5+ different LP questions.
- **Question categories**: questions within each LP are grouped by sub-type (e.g., Customer Obsession has "customer interaction", "difficult interaction/push back", "above & beyond") — each with its own story flow template
- **Story flows**: step-by-step narrative skeletons (A → B → C chains) for each question type, derived from field-tested interview experience
- **Story checkpoints**: what the interviewer is actually listening for — so you know what to emphasize
- **Story reuse map**: shows which core stories cover multiple LPs, cutting prep time significantly

## Installation

```bash
claude plugin install amazon-interview-prep@github:charliec05/amazon-behavioral-interview-prep-skill
```

## Usage

Start a new Claude Code session and say anything like:

- "I want to prep for my Amazon behavioral interview"
- "Help me write a STAR story for Ownership"
- "Let's do a mock Amazon interview"
- "I have an Amazon loop next week, can you help me prepare?"

The skill triggers automatically from context — no slash command needed.

## Coverage

The reference file covers 11 LPs in depth with full question banks, story flows, and checkpoints:

| LP | Question Categories |
|---|---|
| Customer Obsession | Customer interaction, Difficult interaction/pushback, Above & beyond |
| Are Right, A Lot | Mistake/failure, Interpersonal conflict, Judgment from incomplete data |
| Ownership | Above & beyond, Pushback & conflicting, Transition, Helping peers |
| Bias for Action | Calculated risk, Incomplete information, Take action & move fast |
| Think Big | Achievements |
| Invent & Simplify | Innovation & improvements, Simplify |
| Learn and Be Curious | Learn new things |
| Dive Deep | With data, Big/complex system analysis |
| Insist on the Highest Standards | Miss expectations/goals, Improve an already good system |
| Earn Trust | Mistake/failure, Interpersonal interaction, Earn trust questions |
| Deliver Results | Deliver results, Negative/failure |

Also includes: Why [Company] motivation questions, LP frequency by role, and a story reuse map.

## License

MIT
