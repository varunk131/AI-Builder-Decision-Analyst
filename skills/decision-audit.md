| name | description |
|------|-------------|
| decision-audit | Analyzes the decision journal to produce a PM Decision Profile. Extracts patterns across optimization bias, influence vulnerability, confidence calibration, and blind spots. Produces a data-driven report with specific behavioral changes. Use after logging 15-20+ decisions in the decision journal. |

---

# Decision Audit — Pattern and Bias Analyzer

This skill is a decision intelligence system. It reads your full decision journal, extracts patterns across multiple dimensions, and produces a PM Decision Profile that reveals how you actually decide — not how you think you decide.

## PHASE 1: Data Ingestion

Read the decision journal at `./templates/decision-journal.md`. For each logged decision, extract:

| Field | Source |
|-------|--------|
| Optimization axis | What they were optimizing for |
| Influence source | Who pushed for it, or was it autonomous |
| Confidence level | Self-reported 1-5 |
| Outcome quality | Positive / Negative / Mixed / Pending |
| Decision category | One of: Feature Scope, Pricing/Revenue, Team/Process, Technical Architecture, Customer Escalation, Speed vs Quality, Data vs Intuition, Build vs Buy, Say No to Leadership |

## PHASE 2: Analysis (6 Sections)

### Section 1: Decision Pattern Summary

Create a table:

| Category | Count | Avg Confidence | Win Rate |
|----------|-------|---------------|----------|
| [Category] | [N] | [X.X] | [X%] |

### Section 2: Optimization Bias

Rank what the PM most frequently optimizes for (speed, revenue, user experience, focus, risk reduction, etc). Compare: which optimization axis has the BEST outcome track record vs which is used MOST? If there's a gap, that's the key insight.

### Section 3: Influence Vulnerability

Compare win rates for externally-influenced decisions vs autonomous decisions. Identify specific influence sources and their impact. Be direct: "When [role] pushes you, your decisions have a X% success rate vs Y% when you decide independently."

### Section 4: Confidence Calibration

| Confidence Level | Expected Win Rate | Actual Win Rate | Calibration |
|-----------------|-------------------|-----------------|-------------|
| 1-2 (Low) | ~40% | X% | Over/Under/Calibrated |
| 3 (Medium) | ~60% | X% | Over/Under/Calibrated |
| 4-5 (High) | ~80% | X% | Over/Under/Calibrated |

### Section 5: Your Blind Spot (THE KEY FINDING)

Identify the SINGLE biggest blind spot. Must be specific and actionable.

- ❌ Bad: "You sometimes make rushed decisions."
- ✅ Good: "You consistently say yes to customer escalations pushed by Sales, and those decisions have a 30% success rate vs 70% for your autonomous decisions."

**Bold the single most important finding.**

### Section 6: Three Actions for Next Quarter

3 specific behavioral changes. Each must be:

| Requirement | Description |
|-------------|-------------|
| **Tied to data** | Connected to a specific pattern found in the analysis |
| **Actionable** | Can be started within 30 days |
| **Measurable** | Clear way to know if you're doing it |

## PHASE 3: Closing

End with: "Run this analysis again in 90 days to see if your patterns have shifted."

## Rules

- Use only data from the journal — no hypotheticals
- Be direct and specific, not generic
- Bold the single most important finding
- End with one question the PM should answer before proceeding
