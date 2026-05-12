# The Prompt That Generated This Casebook

## The Exact Prompt

```
I have studied the case study frameworks and theory. Now I need to build real mastery through 
practice. Help me do this by creating a comprehensive casebook of real world case studies to 
read through before I start practicing live.

Create 40 real world case study simulations at medium to hard difficulty. Each case should be 
structured as a real interview conversation between an interviewer and a candidate. Not just 
the question, the full back and forth so I can see exactly what a strong answer looks like 
in real time.

Requirements:
- Each case must go deep. Cover all the important aspects a strong candidate would touch on, 
  not just surface level answers
- All cases must be different from each other. I want breadth across case types so I am 
  exposed to the full range of what could come up in an interview
- If you feel more than 40 cases are needed to achieve both depth and breadth, you have the 
  liberty to go up to 50
- Organize cases into clear sections such as Metric Diagnosis, Product and Metrics Design, 
  A/B Testing, Growth and Strategy, Root Cause Analysis, and Technical or ML
- Use real companies like Netflix, Uber, Meta, Google, Stripe, DoorDash, Airbnb, Spotify, 
  TikTok and others to make cases feel realistic
- Label each case with difficulty (Medium or Hard) and include a key lesson or takeaway at 
  the end of each case

Before building, tell me your proposed approach and the outline of sections and case 
distribution. Only proceed to build the full casebook once I approve.
```

**Model used:** Claude Opus 4.6

> **Note:** Sonnet 4.6 should give similar quality at a fraction of the tokens. Try both and see what works for your use case.

---

## How to Adapt This Prompt

**Change the section mix:** The prompt leaves section selection open ("such as"). You can constrain it — e.g., "focus only on Metric Diagnosis and A/B Testing, 20 cases each" — if you want depth over breadth in a specific area.

**Adjust difficulty:** "Medium to Hard" is the default. If you're earlier in prep, drop to "Easy to Medium." If you want pure gauntlet material, specify "Hard only, no Medium."

**Add company specificity:** If you're interviewing at one company, prepend: *"I have an interview at Stripe next week. Weight the cases toward Stripe-relevant contexts: payments, fraud, developer tooling."*

**Request the outline first:** The prompt already asks for an outline before building. Use that checkpoint — push back on the distribution if one section is over- or under-represented relative to what you actually need.

**For follow-up generation:** Once you finish the casebook, run:
- *"Generate 10 more A/B testing cases at Hard difficulty, different from any in the existing casebook"*
- *"Take Case 7 (Netflix engagement drop) and create 3 variant versions with different underlying causes"*
- *"Act as the interviewer for Case 3. I'll give my answer; you respond as the interviewer would, including follow-up probes"*
