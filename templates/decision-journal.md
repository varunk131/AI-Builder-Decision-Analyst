# Decision Journal

Instructions: Log every meaningful product decision here. After 20+ entries, run /project:decision-audit to find your patterns.

---

### Decision #1 — 2025-02-03
**What I decided:** Prioritized SSO for enterprise tier over self-serve onboarding improvements
**What I rejected:** Improving onboarding conversion (currently 23% → target 35%)
**What I was optimizing for:** Revenue — 3 enterprise deals ($180K total) blocked on SSO
**Who influenced this:** VP Sales pushed hard; CTO was neutral; Head of Growth disagreed
**Confidence level:** 3
**What would change my mind:** If onboarding conversion drops below 20% next quarter
**Outcome:** SSO shipped on time. Closed 2 of 3 deals ($140K). But onboarding conversion dropped to 19% — lost ~$95K in self-serve ARR. Net positive but closer than expected.

### Decision #2 — 2025-02-10
**What I decided:** Cut the dashboard customization feature from v2 launch
**What I rejected:** Delaying launch by 3 weeks to include it
**What I was optimizing for:** Speed — wanted to hit the March board meeting with live metrics
**Who influenced this:** My call. Engineering lead said 3 weeks was doable.
**Confidence level:** 4
**What would change my mind:** If >15% of beta users mention customization in feedback
**Outcome:** 22% of beta users asked for customization in first week. Had to fast-follow, and the rush job created tech debt.

### Decision #3 — 2025-02-14
**What I decided:** Went with usage-based pricing for the new analytics add-on
**What I rejected:** Flat-rate pricing ($49/mo) which was simpler
**What I was optimizing for:** Revenue upside — top 10% of customers would pay 4x more on usage-based
**Who influenced this:** CFO's analysis showing revenue ceiling with flat-rate
**Confidence level:** 2
**What would change my mind:** If >30% of customers complain about unpredictable bills
**Outcome:** Revenue per customer up 18%, but mid-tier churn increased 6%. Support tickets about billing tripled.

### Decision #4 — 2025-02-21
**What I decided:** Hired a senior backend engineer instead of a second PM
**What I rejected:** Hiring another PM to share the workload
**What I was optimizing for:** Execution speed — more ideas than we could build
**Who influenced this:** Engineering Lead argued bottleneck was code, not strategy
**Confidence level:** 3
**What would change my mind:** If I'm still the decision bottleneck in 3 months
**Outcome:** (pending)

### Decision #5 — 2025-02-28
**What I decided:** Killed the mobile app MVP after 4 weeks of development
**What I rejected:** Investing another 6 weeks to reach launchable state
**What I was optimizing for:** Focus — early testing showed DAU/MAU of 8%
**Who influenced this:** My call after seeing data. CEO wanted to keep going. VP Product backed me.
**Confidence level:** 4
**What would change my mind:** If a competitor launches mobile with strong adoption
**Outcome:** Redirected team to API integrations. 3 integration partners signed in 2 months. Right call.

### Decision #6 — 2025-03-05
**What I decided:** Approved full UI redesign of settings page
**What I rejected:** Incremental improvements over 3 sprints
**What I was optimizing for:** User experience — settings had 62% drop-off rate
**Who influenced this:** Design Lead's case with heatmap data
**Confidence level:** 2
**What would change my mind:** If redesign takes >1 sprint or doesn't move drop-off below 40%
**Outcome:** Took 2.5 sprints. Drop-off improved to 38%. Marginal win, cost more than expected.

### Decision #7 — 2025-03-10
**What I decided:** Built a custom integration for a single enterprise customer
**What I rejected:** Telling them to use our API
**What I was optimizing for:** Revenue — $200K/year contract contingent on integration
**Who influenced this:** VP Sales + CEO both pushed. I initially resisted.
**Confidence level:** 2
**What would change my mind:** If custom work takes >4 weeks or creates maintenance burden
**Outcome:** Took 6 weeks. Ongoing maintenance. Only 1 other customer used it. Net negative.

### Decision #8 — 2025-03-15
**What I decided:** Launched beta to 100 users instead of planned 500
**What I rejected:** Larger beta for statistical significance
**What I was optimizing for:** Speed of learning — wanted directional signal fast
**Who influenced this:** My call. Data team wanted 500.
**Confidence level:** 3
**What would change my mind:** If 100-user sample gives contradictory signals
**Outcome:** Clear signal within 1 week. Saved 2 weeks. Good call.

### Decision #9 — 2025-03-22
**What I decided:** Deprioritized accessibility improvements for performance optimization
**What I rejected:** 2 sprints on WCAG AA compliance
**What I was optimizing for:** Retention — page load time was #1 complaint
**Who influenced this:** My call based on support ticket volume
**Confidence level:** 3
**What would change my mind:** If we lose an enterprise deal over accessibility
**Outcome:** Lost a $90K government contract requiring WCAG AA. Didn't see it coming.

### Decision #10 — 2025-03-28
**What I decided:** Built internal admin dashboard instead of customer-facing analytics improvements
**What I rejected:** Analytics improvements requested by 40% of users in surveys
**What I was optimizing for:** Operational efficiency — CS team spending 10hrs/week on manual lookups
**Who influenced this:** Head of CS made the case. I agreed.
**Confidence level:** 4
**What would change my mind:** If analytics shows up as churn reason in exit surveys
**Outcome:** CS efficiency improved dramatically. But analytics was #2 churn reason in Q2 exit surveys.

### Decision #11 — 2025-04-02
**What I decided:** Partnered with third-party data provider instead of building own pipeline
**What I rejected:** In-house build (6 months, 2 engineers)
**What I was optimizing for:** Speed to market — wanted feature live in 6 weeks
**Who influenced this:** CTO recommended build. I pushed for buy.
**Confidence level:** 3
**What would change my mind:** If third-party has reliability issues or raises prices
**Outcome:** Launched in 5 weeks. 3 outages in 6 months. 20% price increase at renewal.

### Decision #12 — 2025-04-10
**What I decided:** A/B tested pricing page before committing to new design
**What I rejected:** Just shipping the new design (design team was confident)
**What I was optimizing for:** Risk reduction — pricing page is highest-revenue page
**Who influenced this:** My call. Design team thought test was unnecessary.
**Confidence level:** 4
**What would change my mind:** Nothing — always test high-stakes pages
**Outcome:** New design converted 12% worse. Would have lost ~$300K/year. Great call.

### Decision #13 — 2025-04-15
**What I decided:** Gave platform team 2 sprints for refactoring
**What I rejected:** Continuing feature work despite slower velocity
**What I was optimizing for:** Long-term velocity — deploy times grew from 15min to 2hrs
**Who influenced this:** Engineering Lead's proposal. VP Product skeptical.
**Confidence level:** 4
**What would change my mind:** If deploy times don't improve by 50%
**Outcome:** Deploy times dropped to 20min. Velocity increased 35% next quarter. Clear win.

### Decision #14 — 2025-04-22
**What I decided:** Said no to CEO's request to add AI features this quarter
**What I rejected:** Building a "quick AI prototype" for the board meeting
**What I was optimizing for:** Focus — 3 critical features already committed
**Who influenced this:** My call. Pushed back directly on CEO.
**Confidence level:** 3
**What would change my mind:** If competitors ship AI and we see it in churn data
**Outcome:** Competitor shipped AI in May. Board asked why we didn't. CEO frustrated. Politically costly, product-wise correct.

### Decision #15 — 2025-04-28
**What I decided:** Shipped minimal V1 of reporting (3 types) instead of full suite (12 types)
**What I rejected:** Building all 12 before launching
**What I was optimizing for:** Learning — wanted to see which reports users actually use
**Who influenced this:** My call. Sales wanted all 12.
**Confidence level:** 5
**What would change my mind:** Nothing — iterative shipping is always right for new features
**Outcome:** 2 of 3 got heavy usage. 1 barely touched. Saved ~6 weeks of building unused reports.

### Decision #16 — 2025-05-05
**What I decided:** Moved standups from daily to twice weekly
**What I rejected:** Keeping daily standups
**What I was optimizing for:** Team productivity — engineers complained about meeting overhead
**Who influenced this:** Team feedback. Engineering Lead agreed.
**Confidence level:** 3
**What would change my mind:** If blockers go unresolved >2 days regularly
**Outcome:** 20% more story points. No increase in blocked items. Should have done this sooner.

### Decision #17 — 2025-05-12
**What I decided:** Built CSV export for dashboards for a specific customer
**What I rejected:** Building a proper API-based export system
**What I was optimizing for:** Speed — customer needed it in 2 weeks
**Who influenced this:** VP Sales escalated. $300K ARR customer.
**Confidence level:** 2
**What would change my mind:** If more export requests come in that CSV can't handle
**Outcome:** 4 more customers requested export within a month. Now rebuilding as API export anyway.

### Decision #18 — 2025-05-19
**What I decided:** Built notifications as microservice instead of adding to monolith
**What I rejected:** Faster monolith approach (2 weeks vs 5 weeks)
**What I was optimizing for:** Architecture — avoiding more monolith bloat
**Who influenced this:** CTO's architecture vision. I deferred to technical judgment.
**Confidence level:** 3
**What would change my mind:** If it takes >5 weeks or creates operational complexity
**Outcome:** Took 7 weeks. Works well but operational overhead is a pain. Jury out.

### Decision #19 — 2025-05-26
**What I decided:** Redirected data analyst hiring budget to contractor engineers
**What I rejected:** Hiring the data analyst as planned
**What I was optimizing for:** Execution speed — needed to clear engineering backlog
**Who influenced this:** My call after reviewing sprint velocity
**Confidence level:** 2
**What would change my mind:** If we keep making decisions without data rigor
**Outcome:** Backlog cleared, but Q3 planning weaker without data support. Missed insights.

### Decision #20 — 2025-06-02
**What I decided:** Launched feature to all users simultaneously instead of staged rollout
**What I rejected:** 10% → 25% → 50% → 100% over 4 weeks
**What I was optimizing for:** Speed — competitive pressure to be first
**Who influenced this:** CEO's urgency about competitor timing
**Confidence level:** 2
**What would change my mind:** If production issues in first 24 hours
**Outcome:** Performance issues for 20% of users in first 48hrs. 2 enterprise escalations. Staged rollout would have caught this. Bad call.
