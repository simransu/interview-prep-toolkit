# 01 — Case Study Mastery Playbook

The foundational resource in this toolkit. A complete, self-contained guide to solving any case study you'll encounter in a Data Science or Analytics interview.

This was the starting point because case studies were the clearest weakness — and the gap between technical ability and structured communication is what kills otherwise strong candidates.

---

## What's in This Folder

| File | Description |
|------|-------------|
| `Case Study Mastery Guide.pdf` | The full 56-page playbook — all 10 parts, every framework, every worked example |
| `prompts.md` | The exact Claude prompt used to generate this, with notes on how to adapt it for other topics |

---

## What the Playbook Covers

### Part I: Foundations
- What interviewers are actually evaluating (5 axes: structure, business intuition, analytical reasoning, communication, technical depth — with weights)
- The 7 case archetypes you'll encounter and how to recognize them instantly
- The SPADE framework — a universal skeleton for any case (Situation → Problem Decomposition → Analysis Plan → Data and Decision → Edge Cases)

### Part II: Metric Diagnosis — The Most Important Skill
- Why ~40–50% of all cases are metric diagnosis
- Master metric decomposition list (revenue, DAU, conversion, engagement, retention, marketplace, SaaS, ad platform)
- The 4-step diagnosis protocol: clarify the metric → check external vs. internal → decompose mathematically → segment and isolate
- Universal segmentation checklist (10 dimensions, run through every case)
- Quantitative isolation: how to verify that a segment fully explains the aggregate drop

### Part III: Simpson's Paradox and Mix Shifts
- Why averages lie and how to catch it
- The classic worked example with full math
- How to identify mix shift triggers and call them out in an interview

### Part IV: Data Quality — The Cause Everyone Forgets
- 6-item data quality checklist (logging changes, pipeline delays, bot traffic, metric definition changes, duplicate counting, timezone/calendar issues)
- How to raise data quality without derailing your answer

### Part V: Product Sense and Metric Design
- The 3-layer metric hierarchy: North Star → Secondary → Guardrail metrics
- The GAME framework (Goal → Actions → Metrics → Evaluation)
- Full worked example: measuring success of Instagram Reels

### Part VI: Product Feature Evaluation
- The PRO-CON-MEASURE framework for "should we build X?" cases
- Full worked example: should YouTube add synchronized viewing?

### Part VII: A/B Testing — Design to Interpretation
- 7-component test design framework (hypothesis, randomization unit, population, sample size, primary metric, biases, decision criteria)
- Full worked example: Duolingo onboarding flow experiment
- 4 interpretation scenarios: significant result → should we ship? / conflicting CTR vs revenue / p=0.08 / Sample Ratio Mismatch

### Part VIII: Growth Strategy
- AARRR framework with prioritization logic
- Full worked example: grow Duolingo's DAU in Brazil 30% in 6 months
- Market sizing: top-down vs bottom-up, principles for estimation

### Part IX: Technical Depth
- Hypothesis testing: Type I/II errors, the p-value misconception, what CIs tell you that p-values don't
- Power analysis: 4 levers, CUPED and variance reduction
- Regression: coefficients, R², multicollinearity, omitted variable bias
- Causal inference toolkit: DiD, RDD, PSM, Instrumental Variables — when to use each
- ML in case contexts: precision/recall tradeoffs by business context, recommendation systems, churn prediction

### Part X: Communication and Delivery
- The 3-beat opening (restate → clarify → framework)
- Signposting: the verbal equivalent of document headers
- Handling follow-ups, pivots, and stress tests
- How to close: crisp summary → specific recommendation → monitoring plan

### Part XI: Five Full Worked Cases (End-to-End)
1. Spotify skip rate increased 20% — diagnose
2. A/B test: +5% conversion but −3% revenue per transaction — what do you do?
3. How would you grow Pinterest's male user base by 50% in 12 months?
4. Netflix: completion down, recommendation CTR up, churn flat — what's happening?
5. Design a fraud detection system for a payments platform

### Part XII: Quick Reference Sheets
- Metric decomposition cheat sheet (7 company types)
- Segmentation checklist
- A/B test design checklist
- Common traps and how to avoid them
- 16-week study schedule

### Part XIII: Product Libraries
Domain-specific hypothesis libraries and edge cases for 15+ verticals:
Fitness/Wellness · E-commerce · Marketplace · Social/Content · Subscription/SaaS · Reddit · Snap · Healthcare/Digital Health · Gaming · Fintech/Banking · Marketplace for Services · Enterprise B2B SaaS · Travel/Hospitality · Food Delivery · EdTech · Dating Apps · Streaming/Entertainment

Plus cross-cutting edge cases: denominator manipulation, instrumentation lag, cannibalization, notification suppression, OS policy changes, cohort maturation, currency/purchasing power, competitive substitution timing.

---

## Study Schedule (from the playbook)

| Weeks | Focus | Daily Practice |
|-------|-------|----------------|
| 1–2 | Parts I–III (Foundations) | 2 framework drills/day — SPADE skeleton in <3 min |
| 3–4 | Parts IV–VI (Metric Diagnosis) | 1 full diagnosis case/day, record yourself |
| 5–7 | Parts VII–X (Product Sense & A/B) | 1 metric definition OR experiment design case/day |
| 8–9 | Parts XI–XII (Growth & Strategy) | 1 growth strategy case + 1 market sizing estimation/day |
| 10–11 | Part XIII (Technical Depth) | 1 concept review/day |
| 12–14 | Parts XIV–XV (Communication & Cases) | 3–4 timed simulations/week (20 min → 15 → 12) |
| 15–16 | Company-specific targeting | 2 targeted cases/week + 2–3 mock interviews |

---

## Coming Next

Once the casebook (folder 02) is built, use it alongside this playbook: read the framework chapter, then immediately practice against 3–5 cases from the corresponding archetype section in the casebook before moving on.
