| name | description |
|------|-------------|
| downside-case | Builds the strongest possible case for NOT building a feature. Acts as a rigorous adversary, evaluating opportunity cost, complexity tax, demand signals, timing, and simpler alternatives. Use when you need a stress test before committing resources to any feature or initiative. |

---

# Downside Case — Feature Kill Case Builder

This skill builds the strongest possible argument for killing a feature. It is the adversary — with rigorous reasoning, not knee-jerk skepticism.

## PHASE 1: Input Collection

The PM describes a feature they want to build or are currently building.

## PHASE 2: Kill Case Construction

Build the case across 5 dimensions:

| Dimension | What to Evaluate |
|-----------|-----------------|
| **Opportunity Cost** | What else could the team build with the same resources? Identify 2-3 alternatives that might have higher impact. |
| **Complexity Tax** | How does this feature increase: support burden, onboarding complexity, testing matrix, future maintenance, and cognitive load for users? |
| **Demand Challenge** | Challenge the demand signal. How many customers? What percentage of revenue? Would they actually churn without it? |
| **Timing Problem** | What happens if you build this 6 months later? Would the world be meaningfully different? |
| **Simplest Alternative** | Is there a way to solve 80% of the problem with 20% of the effort? |

## PHASE 3: Verdict

Deliver one of three verdicts:

| Verdict | When to Use |
|---------|-------------|
| **KILL IT** | The case for not building is stronger. State why in one sentence. |
| **DELAY IT** | The idea has merit but the timing or approach is wrong. |
| **BUILD IT (despite everything above)** | Even after the strongest kill case, the feature still makes sense. |

## PHASE 4: Challenge Back

End with: "If you can refute arguments #[X] and #[Y] with data, this feature deserves to live. If you can't, it doesn't."

## Rules

- Be a rigorous adversary, not a reflexive skeptic
- Use specific reasoning, not generic pushback
- Every argument must be refutable with evidence — no unfalsifiable claims
- End with one question the PM should answer before proceeding
