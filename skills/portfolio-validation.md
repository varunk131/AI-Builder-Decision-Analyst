| name | description |
|------|-------------|
| portfolio-validation | Analyzes the anti-portfolio to produce a Product Instinct Scorecard. Grades instincts by category, identifies recurring thinking errors, maps signal blindness, and tracks whether instincts are improving or degrading over time. Use after logging 10+ career misses in the anti-portfolio. |

---

# Portfolio Validation — Product Instinct Scorecard

This skill analyzes your record of misses, kills, and wrong calls to find where your product instinct is calibrated and where it's broken. It produces a graded scorecard with specific compensating strategies.

## PHASE 1: Data Ingestion

Read the anti-portfolio at `./templates/anti-portfolio.md`. For each logged miss, extract:

| Field | Source |
|-------|--------|
| Category | Feature Kill, Market Timing, User Need, Pricing, Technology Bet, Competitive Response, Platform/Partnership, Hiring/Team |
| Severity | How wrong was I (1-5) |
| Root cause signal | What was missed |
| Thinking error type | Classification from Phase 2 |

## PHASE 2: Analysis (6 Sections)

### Section 1: Instinct Scorecard

| Category | Misses | Avg Severity | Grade |
|----------|--------|-------------|-------|
| [Category] | [N] | [X.X] | [A-F] |

Grading scale:

| Grade | Criteria |
|-------|----------|
| A | 0-1 misses, low severity |
| B | 1-2 misses, moderate severity |
| C | 2-3 misses, mixed severity |
| D | 3+ misses or any severity-5 miss |
| F | Multiple severity-5 misses |

### Section 2: Thinking Error Patterns

Classify each miss into one or more types:

| Thinking Error | Description |
|---------------|-------------|
| **Incumbent Bias** | "Our current approach is working, why change?" |
| **Loudest Signal Bias** | Listening to existing customers over market signals |
| **Builder's Bias** | Preferring to build core product over ecosystem/platform |
| **Timing Dismissal** | "Too early" or "hype" — underestimating adoption curves |
| **Scope Minimization** | Dismissing something as "nice to have" when it's a buying signal |
| **Aggregate Blindness** | Looking at averages instead of segment-level data |
| **Revenue Anchoring** | Over-weighting immediate revenue over strategic positioning |
| **Complexity Aversion** | Avoiding the harder-but-better approach for something simpler |

Show frequency. **Bold the #1 error.**

### Section 3: Signal Blindness Map

Categorize missed signals:

| Signal Type | Description | Frequency |
|------------|-------------|-----------|
| Quantitative | Data in dashboards, metrics trending | [N] |
| Qualitative | Customer quotes, support tickets, sales call patterns | [N] |
| Market | Competitor moves, funding rounds, talent migration | [N] |
| Internal | What your team was already doing organically | [N] |

Identify which signal type is consistently missed.

### Section 4: Instinct Timeline

Are misses getting less severe over time (learning) or more severe (instincts degrading as market shifts)? Identify the trend. Be honest: "Your instinct is improving in [X] but getting worse in [Y] as the market moves."

### Section 5: The Uncomfortable Truth (THE KEY FINDING)

Synthesize into ONE paragraph starting with: "The pattern is clear:"

Connect the #1 thinking error with the #1 signal blindness to explain WHY the same type of miss keeps happening. Be direct and specific.

### Section 6: Compensating Strategy

3 structural changes — NOT "be more careful":

| Change | Description |
|--------|-------------|
| **New data source** | A specific source to check weekly that counters signal blindness |
| **Decision rule** | A rule to apply when the #1 thinking error is likely to trigger |
| **Consultation** | A person or role to consult for the lowest-scoring category |

## PHASE 3: Closing

End with: "Your product instinct isn't broken. It's miscalibrated in specific, fixable ways. Run this analysis again in 6 months with new misses to track your recalibration."

## Rules

- Use only data from the anti-portfolio — no hypotheticals
- Be uncomfortably honest about patterns
- Bold the single most important finding
- End with one question the PM should answer before proceeding
