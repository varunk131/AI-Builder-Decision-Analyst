| name | description |
|------|-------------|
| assumption-check | Surfaces the 5 riskiest untested assumptions in a feature or product bet, ranks them by risk, identifies the cheapest validation test for each, and produces a 3-day test plan for the single most dangerous assumption. Use before committing engineering resources to any new feature or initiative. |

---

# Assumption Check — Hidden Risk Surfacer

This skill identifies what you're implicitly betting on and haven't validated. It does NOT evaluate whether the idea is good. It only surfaces assumptions.

## PHASE 1: Input Collection

The PM describes a feature or product bet they're planning to build. The more specific the input, the sharper the output.

## PHASE 2: Assumption Extraction (5 Assumptions, Ranked Riskiest → Safest)

For each assumption, produce:

| Field | Description |
|-------|-------------|
| **Assumption** | Frame as a testable hypothesis: "You're assuming that [specific user group] will [specific behavior] because [implicit reason]." |
| **Risk Rating** | High / Medium / Low — based on damage if wrong AND level of uncertainty |
| **Cheapest Test** | Fastest, cheapest validation method. Options: customer interviews (5 conversations), fake door test, landing page test, Wizard of Oz prototype, data analysis of existing behavior, competitive evidence, survey, or internal dogfooding. Always prefer tests that take <1 week and cost <$500. |
| **Consequence of Being Wrong** | What specifically happens if this assumption fails after you've already built it |

## PHASE 3: Critical Finding

End with:

> "Your single riskiest unvalidated assumption is #[X]. If you only test one thing before committing engineering resources, test this. Here's exactly how:"

Produce a specific, step-by-step **3-day test plan** for that one assumption.

## Rules

- Do NOT say "this is a great idea" or suggest improvements
- Do NOT evaluate the idea — only surface assumptions
- Focus on assumptions the PM hasn't articulated, not obvious ones
- End with one question the PM should answer before proceeding
