# The Prompt That Generated This Playbook

## The Exact Prompt

```
I want absolute mastery in solving case studies for data science and any kind of analytics 
interviews. This is an extremely weak area for me. By the end of this, the target is to make 
me so confident that case studies go from my worst performance area to my superpower.

Design a structured, extremely detailed coursework that I can follow for complete mastery. 
Not just a layout or table of contents. I want the full detailed content I can actually study, 
with frameworks, worked examples, explanations, and everything I need to learn deeply. 
This will be my sole reference point. No placeholders, no "expand on this later." 
Give me the complete thing I can sit down and study right now.
```

**Model used:** Claude Opus 4.6

> **Note:** Sonnet 4.6 should give you similar quality at a fraction of the tokens. Try both and see what works for your use case. For iteration and refinement, Sonnet is usually the right call.

---

## What the Prompt Produced

The playbook covers:

- **Part I:** Foundations — the 5 evaluation axes, 7 case archetypes, the SPADE framework
- **Part II:** Metric diagnosis — decomposition engine, 4-step diagnosis protocol, segmentation checklist
- **Part III:** Simpson's Paradox, mix shifts, and data quality
- **Part IV:** Product sense — success metrics, the GAME framework, feature evaluation with PRO-CON-MEASURE
- **Part V:** A/B testing — 7-component design framework, 4 interpretation scenarios (SRM, p=0.08, conflicting metrics, etc.)
- **Part VI:** Growth strategy — AARRR framework, growth lever prioritization
- **Part VII:** Market sizing — top-down and bottom-up approaches
- **Part VIII:** Technical depth — hypothesis testing, confidence intervals, power analysis, regression, causal inference (DiD, RDD, PSM, IV), ML in case contexts
- **Part IX:** Communication and delivery — the first 60 seconds, signposting, handling follow-ups, the close
- **Part X:** 5 full worked cases end-to-end
- **Part XI:** Quick reference sheets (cheat sheets, segmentation checklist, A/B test checklist, common traps)
- **Part XII:** Product libraries — 15+ verticals with unique dynamics, edge cases, and domain-specific hypothesis libraries

---

## How to Adapt This Prompt

If you want to generate something similar for a different topic:

**Swap the domain:** Replace "case studies for data science and analytics interviews" with whatever you're targeting — SQL interviews, system design, behavioral questions, ML breadth, etc.

**Raise the stakes on completeness:** The key phrase is *"No placeholders, no 'expand on this later.'"* Without this, models tend to produce outlines instead of content. Be explicit that you want the full thing now.

**Anchor to a specific end state:** "make me so confident that X goes from my worst area to my superpower" is a useful frame — it signals you want depth, not breadth, and you want it to be usable under pressure.

**Add your context:** You can prepend personal context — role you're targeting, your current level, specific companies — and the model will calibrate the examples and emphasis accordingly. Example addition:

```
Context: I have 4 years of DS experience (recommendation systems, A/B testing, 
time series at an e-commerce company). I'm targeting senior DS roles at FAANG-level 
companies. My technical skills are strong but my product intuition and structured 
communication under pressure are weak.
```

**For follow-up generation:** Once you have the full playbook, you can run follow-up prompts like:

- *"Give me 10 more metric diagnosis cases with full worked responses, harder than the examples in the guide"*
- *"Generate a 15-question quiz on Part II (Metric Diagnosis) that tests for the specific failure modes you described"*
- *"Act as an interviewer. Give me a hard case study prompt and evaluate my response using the 5 evaluation axes"*

---

## Token Note

This playbook is long. If you hit a context limit mid-generation:

1. Ask for one Part at a time ("Generate Part I: Foundations only")
2. Chain the prompts with the previous output as context
3. Use Sonnet for parts where the content is more formulaic (cheat sheets, quick reference) — save Opus for the conceptually dense sections
