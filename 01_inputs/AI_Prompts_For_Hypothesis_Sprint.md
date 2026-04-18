# AI Prompts For Strava Expansion Hypothesis Sprint

## How To Use This File

This document contains ready-to-paste prompts for:

1. Claude Code
2. Gemini Deep Research
3. ChatGPT Deep Research
4. Final synthesis and facilitation

Use the prompts during April 17-20, 2026 to generate, research, compare, and narrow expansion hypotheses for Strava.

## Shared Brief For All Tools

Use this context when needed:

- Product: Strava
- Task: propose expansion into an adjacent or completely new market
- Team size: 6 people
- Selection deadline: April 20, 2026
- Goal by deadline:
  - longlist of 10-15 hypotheses
  - shortlist of top 3
  - one selected hypothesis
  - one-page thesis
- Selection criteria:
  - market size
  - fit with Strava's core strengths
  - monetization potential
  - ease of prototype
  - wow-effect for jury

Core Strava strengths to use:

- social graph and community
- activity and GPS data
- engagement loops, streaks, challenges
- clubs and leaderboards
- mobile-first behavior
- credibility in sports and active lifestyle
- freemium and subscription logic

Avoid:

- weak feature extensions
- ideas with no monetization logic
- ideas that are impossible to show in 3-5 prototype screens
- vague "AI for everything" concepts

Important mentor note:

- before selecting hypotheses, review Strava's direct competitors and inspect whether they already have interesting functionality that can inspire or validate expansion opportunities

Working competitor set for this sprint:

- Garmin Connect
- Nike Run Club
- adidas Running
- ASICS Runkeeper
- MapMyRun / MapMyFitness
- komoot
- COROS

Interpretation note:

- Garmin Connect, Nike Run Club, adidas Running, ASICS Runkeeper, and MapMyRun should be treated as direct competitors
- komoot and COROS should be treated as close or partial competitors that may still reveal valuable adjacent functionality

Competitor scan questions:

- what core user job does this product solve?
- what standout features overlap with Strava?
- what standout features go beyond Strava?
- what monetization clues does it reveal?
- what expansion clues does it suggest for Strava?

---

## Prompt 1: Claude Code

Use this when you want a structured working document, synthesis, scorecard, and clear output formatting.

```text
You are acting as a product strategy analyst helping a team prepare a final project for Genesis IT School.

We are working on Strava and need to identify the best expansion hypothesis into an adjacent or completely new market.

Your task is to help us complete the first sprint by April 20, 2026. We need:

1. A longlist of 10-15 expansion hypotheses
2. A scoring matrix for those hypotheses
3. A top-3 shortlist
4. A recommended final hypothesis
5. A one-page thesis for the recommended direction

Before generating hypotheses, first run a short direct-competitor scan covering:
- Garmin Connect
- Nike Run Club
- adidas Running
- ASICS Runkeeper
- MapMyRun / MapMyFitness
- komoot
- COROS

Selection criteria:
- market size
- fit with Strava's core strengths
- monetization potential
- ease of prototype
- wow-effect for jury

Strava core strengths:
- social graph and community
- activity and GPS data
- habit loops, streaks, and challenges
- clubs, leaderboards, and identity
- mobile-first behavior
- credibility in active lifestyle
- subscription and freemium logic

Please do the following in order:

Step 1. Build a competitor scan table.
For each competitor provide:
- core user job-to-be-done
- target segment
- standout features
- features that appear stronger than Strava
- monetization clues
- expansion clues for Strava

Step 2. Generate 15 expansion hypotheses for Strava.
For each hypothesis provide:
- name of the hypothesis
- new market / audience
- core user problem
- why Strava has a right to win
- monetization logic
- prototype vision in 1 sentence

Step 3. Remove weak or redundant ideas.
Keep only the strongest 10-12.

Step 4. Build a scoring table from 1 to 5 for each idea using these criteria:
- market size
- strategic fit
- monetization potential
- ease of prototype
- wow-effect

Also calculate a weighted total score using:
- market size: 25%
- strategic fit: 25%
- monetization: 20%
- ease of prototype: 15%
- wow-effect: 15%

In one extra column, mention whether each idea is:
- inspired by a direct competitor signal
- a white space not strongly occupied by direct competitors

Step 5. Select the top 3 ideas and explain why they survived.

Step 6. Recommend one final hypothesis and write a one-page thesis with:
- hypothesis
- why this market
- why Strava
- target audience
- product concept
- monetization logic
- wow-factor
- key risks
- next research questions

Important rules:
- do not give generic startup ideas
- do not confuse a feature with a new market move
- prioritize ideas that can support a compelling jury presentation
- be opinionated and make tradeoffs explicit
- if two ideas are similar, keep the stronger one

Format the answer in clear markdown sections and tables.
```

---

## Prompt 2: Gemini Deep Research

Use this when you want broad external research, market signals, competitors, and trend-backed idea generation.

```text
I need a deep research report to help a student team choose the best expansion strategy for Strava.

Project objective:
By April 20, 2026 we must choose one expansion hypothesis for Strava into an adjacent or new market. Before that, we need a longlist of options and a shortlist of top candidates.

Please conduct research and produce a decision-oriented report, not just brainstorming.

Main goal:
Generate 10-15 strong expansion hypotheses for Strava and evaluate them using these criteria:
- market size
- fit with Strava's core strengths
- monetization potential
- ease of prototype
- wow-effect for jury

Before generating hypotheses, include a direct competitor scan covering:
- Garmin Connect
- Nike Run Club
- adidas Running
- ASICS Runkeeper
- MapMyRun / MapMyFitness
- komoot
- COROS

Strava's core strengths:
- social graph and community
- activity and GPS data
- habits, streaks, and challenges
- clubs and leaderboards
- strong mobile usage
- sports credibility
- freemium / subscription logic

Please follow this process:

1. Briefly summarize Strava's current product strengths, user behavior, and monetization model.
2. Analyze Strava's direct and close competitors. For each one, explain:
   - primary target user
   - core job-to-be-done
   - standout features
   - what appears stronger than Strava
   - monetization clues
   - what expansion clues this competitor reveals
3. Identify 8-12 adjacent or new market spaces where Strava could plausibly expand.
4. For each space, explain:
   - user problem
   - relevant trend or demand signal
   - likely target audience
   - main competitors or analogs
   - why Strava may or may not have a right to win
   - monetization route
   - whether it could be shown in a 3-5 screen prototype
5. Turn these spaces into 10-15 concrete hypotheses.
6. Score each hypothesis from 1 to 5 across:
   - market size
   - strategic fit
   - monetization potential
   - ease of prototype
   - wow-effect
7. Add a note for each hypothesis saying whether it is:
   - validated by a competitor pattern
   - a differentiated twist on a competitor pattern
   - a white-space opportunity
8. Rank the hypotheses and recommend the top 3.
9. Recommend one final direction and explain why it is stronger than the alternatives.

Output requirements:
- include a table for all hypotheses
- include sources and links for trend, market, and competitor claims
- clearly separate facts from inference
- mention where evidence is strong and where it is weak
- avoid hallucinated market-size numbers
- use credible and recent sources where possible

Final section:
Write a short "team recommendation memo" with the single best hypothesis and the key arguments for choosing it now.
```

---

## Prompt 3: ChatGPT Deep Research

Use this when you want a structured, source-backed recommendation with explicit tradeoffs and citations.

```text
Please run a deep research task to help a 6-person student team choose the best expansion strategy for Strava for a final project.

We need a concrete outcome by April 20, 2026:
- a longlist of 10-15 expansion hypotheses
- a top-3 shortlist
- one chosen hypothesis
- a one-page thesis

Research objective:
Identify the most defensible and presentation-worthy expansion opportunity for Strava into an adjacent or completely new market.

Selection criteria:
- market size
- fit with Strava's core strengths
- monetization potential
- ease of prototype
- wow-effect for jury

Strava strengths to use:
- strong active-lifestyle brand
- social graph and community
- activity and GPS data
- challenges, streaks, leaderboards
- clubs and identity layers
- mobile-first usage
- freemium and subscription experience

Before ideation, analyze these direct or close competitors:
- Garmin Connect
- Nike Run Club
- adidas Running
- ASICS Runkeeper
- MapMyRun / MapMyFitness
- komoot
- COROS

Instructions:

1. Start by summarizing Strava's current product, user segments, value proposition, and monetization.
2. Build a direct competitor scan for the listed competitors. For each competitor, include:
   - target user
   - core use case
   - standout features
   - where it appears stronger than Strava
   - monetization clues
   - expansion clues for Strava
3. Research adjacent and new categories where Strava could plausibly expand.
4. Generate 10-15 concrete hypotheses. Each hypothesis must include:
   - hypothesis name
   - target audience
   - user pain point
   - why Strava has a right to win
   - monetization logic
   - product concept in one paragraph
   - prototype potential in 3-5 screens
   - competitor signal: which competitor pattern, if any, inspired or validated the idea
5. Compare the hypotheses in a table.
6. Score them from 1 to 5 on:
   - market size
   - strategic fit
   - monetization potential
   - ease of prototype
   - wow-effect
7. Recommend the top 3 and explain the tradeoffs.
8. Recommend the single best direction and write a one-page thesis with:
   - hypothesis
   - why now
   - why Strava
   - target segment
   - product concept
   - revenue model
   - wow factor for presentation
   - key risks
   - what to validate next

Source requirements:
- prioritize credible, recent, and primary or high-quality secondary sources
- provide links
- explicitly note assumptions and weak evidence
- do not fabricate numbers

Writing requirements:
- be concise but analytical
- make tradeoffs explicit
- avoid obvious low-differentiation ideas
- optimize for a decision memo the team can actually use
```

---

## Prompt 4: Cross-Model Synthesis And Facilitation

Use this after you collect outputs from Claude Code, Gemini Deep Research, and ChatGPT Deep Research.

Paste all three outputs below this prompt.

```text
You are helping facilitate a product strategy workshop for a student team choosing one expansion hypothesis for Strava.

I will paste outputs from three AI tools:
- Claude Code
- Gemini Deep Research
- ChatGPT Deep Research

Your job is not to regenerate new ideas from scratch. Your job is to synthesize, deduplicate, compare, and prepare the team for a final decision workshop.

Please do the following:

1. Merge overlapping ideas into a single clean hypothesis list.
2. Normalize naming so similar ideas are clearly grouped.
3. Start with a short competitor synthesis:
   - what direct competitors are doing especially well
   - what seems underexploited by Strava
   - what spaces look crowded versus open
4. Remove weak ideas that are:
   - feature extensions instead of market expansions
   - low monetization
   - weak fit for Strava
   - difficult to prototype
5. Produce a final longlist of 10-15 hypotheses.
6. Build a unified scoring matrix using:
   - market size
   - fit with Strava strengths
   - monetization potential
   - ease of prototype
   - wow-effect for jury
   - include one extra field called competitor signal
7. Recommend a top 5, then narrow to a top 3.
8. For each top-3 idea, write a mini-thesis:
   - audience
   - problem
   - concept
   - why Strava can win
   - monetization
   - prototype vision
   - main risk
    - competitor context
9. Recommend one final hypothesis.
10. Write a one-page thesis for that final hypothesis.
11. Prepare a facilitation pack for a 90-minute team workshop with:
   - agenda
   - decision questions
   - conflict-resolution rules
   - final voting method

Important rules:
- separate sourced facts from inference
- make contradictions visible
- do not average weak ideas into "safe" ideas
- be decisive when one option clearly supports a stronger final project story

Format:
- section 1: competitor synthesis
- section 2: unified hypothesis list
- section 3: scoring matrix
- section 4: top 3
- section 5: final recommendation
- section 6: one-page thesis
- section 7: workshop facilitation guide
```

---

## Suggested Run Order

1. Start with Gemini Deep Research to widen the market map.
2. Run ChatGPT Deep Research to get a structured decision memo with citations.
3. Run Claude Code to structure hypotheses, clean the list, and produce a scoring framework.
4. Run the synthesis prompt on the combined outputs.
5. Facilitate the team workshop manually using the synthesized pack.

## What Good Output Should Look Like

A strong final answer should:

- contain real expansion moves, not just feature ideas
- show believable strategic fit with Strava
- make monetization explicit
- reveal tradeoffs clearly
- support a strong 10-minute final pitch
- naturally lead into market validation, prototype, and unit economics work
