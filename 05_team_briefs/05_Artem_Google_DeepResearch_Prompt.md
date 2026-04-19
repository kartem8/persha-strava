# Prompt for Google Deep Research — Artem

Use the attached context files to research a specific Strava expansion hypothesis.

## Role

Act as a senior strategy researcher helping evaluate whether `Strava` should expand into `Local Experiences / Bookable Experiences & Tours`.

This is not a general brainstorm.  
Your job is to produce a decision-useful competitor teardown and market validation.

## Task

Analyze these 3 competitors:

1. `GetYourGuide`
2. `Viator`
3. `Eventbrite`

The goal is to understand whether `bookable experiences` is a credible expansion direction for `Strava`.

## Context you must follow

- We already know from paid mobile analytics that:
  - `GetYourGuide` has `17.52M downloads`
  - `Eventbrite` has `9.28M downloads`
  - `Viator` has `3.61M downloads`
  - the broader `Events / Travel Discovery` cluster has `46.7M downloads`
- Do **not** treat `zero in-app revenue` as proof of weak market.
- You must explicitly look for:
  - `GMV`
  - `take-rate`
  - `service fees`
  - `ticketing fees`
  - `supplier commissions`
  - `host onboarding logic`
- You must also evaluate whether `Eventbrite` belongs more with `Local Experiences` or with `Race & Event Marketplace`.

## What to research for each competitor

For each of the 3 companies, provide:

### 1. Product offering
- core value proposition
- who the primary user is
- the main user flow from discovery to booking
- top features / trust mechanisms that drive conversion

### 2. Monetization and business model
- who pays
- how money flows
- take-rate / service fee / ticket fee / commission structure
- whether there is supplier-side pricing
- any available public signals on revenue, GMV, bookings volume, funding, scale

### 3. Audience and geography
- tourist vs local persona
- key geographies
- repeat vs one-off usage pattern
- what kind of supply they aggregate

### 4. Strategic relevance to Strava
- what Strava could realistically learn from this competitor
- what Strava does not have today that this competitor has
- whether this is:
  - a feature inspiration
  - a true expansion path
  - or too far from Strava’s current DNA

## Required cross-competitor analysis

After the 3 teardown sections, provide:

### A. Comparison table

Include columns for:
- company
- audience
- business model
- who pays
- fee / take-rate logic
- travel vs local
- overlap with Strava
- relevance to `Strava Escapes`

### B. Overlap analysis

Answer:

1. Are `GetYourGuide`, `Viator`, and `Eventbrite` part of one coherent category or two different categories?
2. Is `Eventbrite` closer to:
   - `bookable experiences`
   - or `Race & Event Marketplace`
3. Does this direction overlap heavily with `Meetup / ClassPass / Fever`, or is it a distinct booking layer?

### C. Final verdict for Strava

Give a clear verdict:

- `feature`
- `expansion`
- `new market`

Then answer:

1. Why would `Strava` win here, if at all?
2. What exact entry wedge would make the most sense?
3. What is the biggest reason to reject this direction?

## Output format

Write the answer in clear business English.

Structure it exactly like this:

1. `Executive Summary`
2. `Competitor 1 — GetYourGuide`
3. `Competitor 2 — Viator`
4. `Competitor 3 — Eventbrite`
5. `Comparison Table`
6. `Overlap Analysis`
7. `Final Verdict for Strava`
8. `Open Questions / Missing Evidence`

## Important quality bar

- Prefer official sources and public filings whenever possible.
- If you infer something, label it clearly as an inference.
- Be concrete.
- Avoid generic strategy language.
- Focus on decision-useful evidence, not broad travel market theory.
