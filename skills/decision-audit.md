Analyze the decision journal at `./templates/decision-journal.md` and produce a PM Decision Profile.

Read every logged decision. For each one, extract:
- The optimization axis (what they were optimizing for)
- The influence source (who pushed for it, or was it autonomous)
- The confidence level
- The outcome quality (positive / negative / mixed / pending)
- The decision category: one of [Feature Scope, Pricing/Revenue, Team/Process, Technical Architecture, Customer Escalation, Speed vs Quality, Data vs Intuition, Build vs Buy, Say No to Leadership]

Then produce the following analysis:

## 1. Decision Pattern Summary

Create a table showing each category, how many decisions fell into it, the average confidence level, and the win rate (positive outcomes / total outcomes with known outcomes).

## 2. Your Optimization Bias

Analyze what the PM most frequently optimizes for (speed, revenue, user experience, focus, risk reduction, etc). Rank them by frequency. Then compare: which optimization axis has the BEST outcome track record vs which is used MOST? If there's a gap, that's the key insight.

## 3. Your Influence Vulnerability

Look at decisions where someone else pushed for it vs decisions made autonomously. Compare win rates. Identify specific influence sources (VP Sales, CEO, etc) and whether decisions influenced by that person tend to have better or worse outcomes. Be direct: "When [role] pushes you, your decisions have a X% success rate vs Y% when you decide independently."

## 4. Your Confidence Calibration

Compare stated confidence levels to actual outcomes. Is the PM overconfident (high confidence, bad outcomes) or underconfident (low confidence, good outcomes)? Create a simple calibration table:
- Confidence 1-2: Expected win rate ~40%, Actual win rate: X%
- Confidence 3: Expected win rate ~60%, Actual win rate: X%
- Confidence 4-5: Expected win rate ~80%, Actual win rate: X%

## 5. Your Blind Spot (THE KEY FINDING)

Based on all the above, identify the SINGLE biggest blind spot. This should be specific and actionable, not generic. Bad: "You sometimes make rushed decisions." Good: "You consistently say yes to customer escalations pushed by Sales, and those decisions have a 30% success rate vs 70% for your autonomous decisions. Your instinct is right — your Sales team's urgency is miscalibrated."

## 6. Three Actions for Next Quarter

Based on the analysis, give exactly 3 specific behavioral changes. Each should be:
- Tied to a specific pattern found in the data
- Actionable within the next 30 days
- Measurable (how will they know if they're doing it)

Format the entire output as clean markdown. Bold the single most important finding. End with: "Run this analysis again in 90 days to see if your patterns have shifted."
