# Lovable Prompt: Team + Mentor Strategy Page

Use this prompt in Lovable together with:

- [Team_Mentor_Presentation_Source_of_Truth.md](./Team_Mentor_Presentation_Source_of_Truth.md)
- [Final_Synthesis_Pack_17April2026.md](./Final_Synthesis_Pack_17April2026.md)
- [Codex_Consensus_Mentor_Pack.md](./Codex_Consensus_Mentor_Pack.md)
- [Mentor_Data_Services_Validation_Brief.md](./Mentor_Data_Services_Validation_Brief.md)
- [Hypothesis_Glossary.md](./Hypothesis_Glossary.md)
- [HANDOFF_CONTEXT.md](../HANDOFF_CONTEXT.md)

## Prompt

```text
Create a polished one-page presentation site for an internal team + mentor strategy review.

Context:
This is for a Genesis IT School final project about Strava's expansion into a new market.
This page is not the final jury deck. It is a premium working synthesis page for tomorrow's mentor meeting.

You must use the attached source-of-truth file as the primary content guide.
Do not invent a different narrative.
Do not flatten the page into a generic startup landing page.

Language requirement:
- write the page primarily in Ukrainian
- keep company names, product names, tool names, and well-established product/marketing terms in English where that is more natural
- examples of terms that may remain in English: product-market fit, roadmap, growth, retention, monetization, unit economics, prototype, evidence quality, source of truth
- avoid awkward literal translation of professional vocabulary
- avoid comic half-English phrasing such as `Три bucket-и. Один focus.`
- prefer natural Ukrainian for structural copy, transitions, section labels, and explanations
- use English only for names and truly established terms, not as decorative slang

Design direction:
- visually inspired by a premium editorial strategy page
- similar storytelling energy to a polished Lovable insight page
- light background
- elegant gradients
- strong typography hierarchy
- fixed top navigation
- section-based scroll experience
- premium but restrained motion
- clear cards, comparison blocks, and timeline sections

Visual style:
- clean, bright, modern
- not dark mode
- not overly purple
- avoid AI-slop startup aesthetics
- use bold headings and calm supporting text
- cards should feel like a product strategy presentation, not a dashboard

Page goal:
Help a team and mentor quickly understand:
1. what the assignment is
2. what research has already been done
3. which AI tools were used
4. what idea clusters emerged
5. what the current top 3 is
6. what exactly should be validated tomorrow
7. how the team will move from now to final defense

Must include these sections:
1. Hero
2. Why this page exists
3. Assignment snapshot
4. How we researched
5. Competitor signals
6. Hypothesis universe
7. Current top 3
8. Real decision tension
9. Mentor validation plan
10. Roadmap to final delivery
11. Team workflow / source of truth
12. Closing

Important content requirements:
- explicitly mention the AI tools used:
  - ChatGPT Deep Research
  - Gemini Deep Research
  - Perplexity
  - Copilot Think Deeper
  - Codex
  - Claude Code
- clearly state that outputs were compared and deduplicated
- show three groups of hypotheses:
  - core candidates
  - interesting non-obvious candidates
  - high-risk edge cases
- directly under the hypothesis universe, add a compact `Hypothesis Glossary` block
- the glossary must include the full current hypothesis universe
- each glossary item should show:
  - the idea name in English
  - a short Ukrainian explanation of what it actually means
  - optionally one short line about the target user or use case
- this block should help the team understand the ideas quickly, not just look decorative
- highlight the current top 3:
  - Strava Work / Corporate Wellness
  - Strava Escapes / Active Travel
  - Race & Event Marketplace
- make it clear inside the Top 3 logic that `Strava Escapes` is the idea that best uses Strava's existing audience and data moat:
  - global heatmaps
  - route behavior
  - destination discovery signals
  - clubs and community activity across locations
- explicitly show the key tension:
  - Corporate Wellness = strongest business case
  - Active Travel = strongest jury story
- include the premium research tools we may use with the mentor:
  - Crunchbase
  - PitchBook
  - Dealroom
  - CB Insights
  - Ahrefs
  - Sensor Tower
  - AppTweak
  - data.ai
  - App Store / Google Play reviews
- include a timeline from April 17-20 through May 25
- include a small section that says this page is built on a source of truth and linked repo workflow

Interaction ideas:
- sticky nav with section anchors
- hero with two CTAs:
  - See shortlist
  - See validation plan
- animated reveal cards
- a comparison section for top 3 ideas
- a visual decision tension block
- an accordion or expandable card block for the full idea glossary
- a roadmap timeline
- a final action-oriented closing section

Content behavior rules:
- do not over-explain basics
- do not make up fake statistics
- do not claim that one hypothesis is final
- do not remove uncertainty; show uncertainty as a strength
- do not bury the top 3
- make the mentor validation section very practical

Copy tone:
- strategic
- crisp
- smart
- credible
- product-team style
- no marketing fluff
- Ukrainian-speaking team friendly
- natural Ukrainian, without startup-slang hybrids

Tech preferences:
- single page
- responsive
- modern React/Tailwind style output if applicable
- clean section ids for scrolling
- use reusable section/card patterns

Final note:
This page should make the team look serious, structured, and ready for a high-quality mentor discussion tomorrow.
```
