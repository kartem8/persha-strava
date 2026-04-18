# Claude Code Open Validation Brief

## Goal

Use all collected research outputs to produce a broad but structured validation pack for lecturer review.

This brief is intentionally more open than the cleaned synthesis brief.

Do **not** prematurely discard non-obvious ideas unless they are clearly:

- not true market expansions
- impossible to defend
- wildly outside Strava's brand and assets
- dependent on unrealistic infrastructure for a student project

The goal here is:

1. preserve the strongest obvious candidates
2. keep a small set of non-obvious candidates alive
3. ask Claude to validate and rank them
4. prepare a version the team can show a lecturer tomorrow without losing creative upside

## Source Files To Use

- [17-20_April_Hypothesis_Sprint_Playbook.md](/Users/artemkorneev/Documents/STRAVA/17-20_April_Hypothesis_Sprint_Playbook.md)
- [Codex_Strava_Expansion_Decision_Pack.md](/Users/artemkorneev/Documents/STRAVA/Codex_Strava_Expansion_Decision_Pack.md)
- [Perplexity_Strava_Expansion_Hypothesis_Sprint_Output.md](/Users/artemkorneev/Documents/STRAVA/Perplexity_Strava_Expansion_Hypothesis_Sprint_Output.md)
- [ChatGPT_DeepResearch_Strava_Expansion_Output.md](/Users/artemkorneev/Documents/STRAVA/ChatGPT_DeepResearch_Strava_Expansion_Output.md)
- [Copilot_ThinkDeeper_Strava_Expansion_Output.md](/Users/artemkorneev/Documents/STRAVA/Copilot_ThinkDeeper_Strava_Expansion_Output.md)
- [Gemini_DeepResearch_Strava_Expansion_Output.md](/Users/artemkorneev/Documents/STRAVA/Gemini_DeepResearch_Strava_Expansion_Output.md)
- [Strava_Expansion_Strategy_Research_Report_from_DOCX.md](/Users/artemkorneev/Documents/STRAVA/Strava_Expansion_Strategy_Research_Report_from_DOCX.md)
- [Claude_Code_Clean_Synthesis_Brief.md](/Users/artemkorneev/Documents/STRAVA/Claude_Code_Clean_Synthesis_Brief.md)

## How To Treat The Idea Set

Instead of hard-pruning, organize ideas into three buckets:

### Bucket A: Core Candidates

These have the strongest cross-model support and the clearest strategic case.

- Corporate Wellness / Strava for Work
- Active Travel / Adventure / Active Experiences
- Race & Event Marketplace
- Coaching / Coach Marketplace
- Creator Economy
- Recovery / Longevity

### Bucket B: Interesting Non-Obvious Candidates

These are less consensus-driven but may still be worth showing the lecturer because they are distinctive or strategically surprising.

- Local Experiences Marketplace
- Club OS / organizer tools
- Social sports / court booking / Padel-Tennis layer
- Guided audio / adaptive beginner coaching
- University communities
- Family movement
- Outdoor group navigation / stronger safety layer
- Return-to-activity / recovery onboarding

### Bucket C: High-Risk Edge Cases

Do not discard automatically, but validate very critically.

- Fitness dating
- Youth sports logistics
- Recommerce / gear marketplace
- Nutrition module
- AR / virtual training engine
- Proprietary hardware ideas

These can still be mentioned to the lecturer as "explored but likely weak" if needed.

## Validation Questions For Claude

Claude should test every meaningful hypothesis against these questions:

1. Is this a true market expansion or just a feature extension?
2. Does Strava have a believable right to win?
3. Can the team defend it in front of the Genesis jury?
4. Can it be shown in a strong 3-5 screen prototype?
5. Is the monetization story clear enough for unit economics work later?
6. Is it differentiated enough from direct competitors?
7. Is it interesting enough to surface to a lecturer even if it is not the final winner?

## Important Instruction

Claude should not optimize only for obviousness.

Claude should explicitly identify:

- the safest candidate
- the best business case
- the best jury story
- the most interesting non-obvious candidate worth lecturer feedback

## Evidence Quality Guidance

Downweight weak sources, but do not throw away an idea only because one model supported it with weak citations.

Instead:

- preserve the idea if the strategic logic is still strong
- mark evidence quality separately as high / medium / low
- distinguish between "interesting but under-evidenced" and "weak idea"

## Desired Output From Claude

1. Clean competitor synthesis
2. Unified hypothesis universe
3. Ranked list of hypotheses by:
   - business strength
   - jury appeal
   - distinctiveness
   - evidence quality
4. Top 3 final candidates
5. 2-3 non-obvious alternatives worth showing the lecturer
6. One recommended direction
7. One-page thesis
8. Lecturer discussion notes:
   - what to ask
   - where the team is uncertain
   - which tradeoffs need mentor input

## Suggested Prompt For Claude Code

```text
You are helping a student team synthesize several AI research outputs about Strava's expansion into a new market for a Genesis IT School final project.

Do not start from scratch.
Use the attached research outputs and briefs.

Important:
Do not aggressively discard non-obvious ideas too early.
The team wants a version they can show a lecturer tomorrow, so they want both:
- a strong shortlist
- a few interesting non-obvious alternatives that may be worth validating

Please do the following:

1. Read all attached outputs and merge overlapping ideas.
2. Build a clean competitor synthesis.
3. Create a unified hypothesis universe.
4. Classify ideas into:
   - Core candidates
   - Interesting non-obvious candidates
   - High-risk edge cases
5. For each meaningful idea, score:
   - market size
   - strategic fit
   - monetization potential
   - ease of prototype
   - wow-effect for jury
   - evidence quality
6. Recommend:
   - the safest candidate
   - the strongest business case
   - the strongest jury story
   - the most interesting non-obvious candidate
7. Narrow to a top 3 final shortlist.
8. Recommend one final direction.
9. Write a one-page thesis.
10. Add a short section called "What to ask the lecturer tomorrow" with the biggest unresolved tradeoffs.

Important rules:
- remove only clearly bad ideas
- do not collapse everything into a vague hybrid
- preserve interesting alternatives when they are strategically plausible
- distinguish between low evidence and low quality
- make disagreements between models visible

Output structure:
1. Competitor synthesis
2. Unified hypothesis universe
3. Scoring matrix
4. Top 3
5. Non-obvious candidates worth discussing
6. Final recommendation
7. One-page thesis
8. Lecturer questions
```
