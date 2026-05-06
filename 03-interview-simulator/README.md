# 03 — Interview Simulator

A React-based conversational case interview simulator. Give it a prompt, work through a case, get real-time structured feedback — like a mock interview you can run anytime, alone, at 11pm before a morning loop.

**Status: Planned**

---

## The Problem This Solves

Reading frameworks is not the same as using them under pressure. The gap between knowing SPADE and executing it fluently in a real interview is a practice problem, not a knowledge problem.

Mock interviews with humans are the gold standard — but they require scheduling, availability, and often money. This simulator is the on-demand alternative: close enough to the real thing to build the muscle, available whenever you need reps.

---

## Planned Features

**Core flow:**
- Select a case archetype (or pick "random" to simulate not knowing)
- Receive a case prompt (pulled from the casebook or generated fresh)
- Work through the case conversationally — the simulator responds to your questions and pushes back like a real interviewer
- Get a structured debrief at the end: scores on each of the 5 evaluation axes with specific callouts

**Interview modes:**
- `Guided` — the simulator provides structure prompts if you get stuck (good for early practice)
- `Standard` — the simulator only responds to what you say (mirrors a real interview)
- `Hard mode` — the simulator deliberately introduces ambiguity, conflicting data, and follow-up pressure

**Follow-up logic:**
- After your initial response, the simulator asks at least 2 follow-up questions:
  - One depth probe ("how would you actually run that analysis?")
  - One stress test ("what if the data showed the opposite?")

**Timer:**
- Target: 12-minute cases
- Visual indicator when you hit 8 min (time to land) and 12 min (close)

---

## Tech Stack

- **Frontend:** React + TypeScript
- **AI layer:** Claude API (Anthropic) — claude-sonnet-4-6 for conversational simulation, claude-opus-4-7 for debrief scoring
- **State management:** Zustand
- **Deployment:** Vercel
- **Prompt caching:** Enabled via the Anthropic API for cost efficiency on repeated context

---

## Why React (Not a CLI)

A browser-based simulator makes it easier to:
- See your response alongside the prompt (split screen)
- Track time with a visible countdown
- Export the debrief as a PDF for review later
- Eventually add audio input for voice-based practice

---

## Development Timeline

This is the most technically complex piece of the toolkit. It will be built after the casebook is at ~20 cases — the simulator needs a solid prompt library to draw from.

Estimated start: after `02-case-interview-casebook` reaches v1.

---

## Want to Build This?

If you find this repo and want to contribute to the simulator, open an issue. The architecture is straightforward and the Claude API integration is well-documented in the prompts.md file in folder 01.
