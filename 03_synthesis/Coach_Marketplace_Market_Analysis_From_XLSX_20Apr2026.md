# Coach Marketplace Market Analysis From XLSX

## Purpose

Цей документ — структурована markdown-версія файлу
[coach_marketplace_analysis.xlsx](/Users/artemkorneev/Downloads/coach_marketplace_analysis.xlsx),
який зібрала команда для оцінки ринку `Coach Marketplace`.

Його задача:

- зберегти findings у repo в читабельному форматі
- мати stable source of truth для подальших overlap-аналізів
- відокремити командний research від усних інтерпретацій

## Source

- Excel file: [coach_marketplace_analysis.xlsx](/Users/artemkorneev/Downloads/coach_marketplace_analysis.xlsx)
- Date captured: `2026-04-20`

## Executive Summary

Згідно з цим research-паком, `Coach Marketplace` виглядає як **сильний expansion direction**
для Strava, але вже не як "build generic coaching app from scratch".

Головна логіка така:

- ринок already validated реальними revenue signals
- Strava already has distribution moat через existing athlete audience
- Runna already de-risks plan / coaching side
- найбільший whitespace лишається в:
  - human coach marketplace
  - coach dashboards
  - plan store
  - coach monetization rails
  - coach-athlete interaction layer

Найважливіший нюанс:

**Runna і Recover Athletics already належать Strava, тому вони зменшують whitespace для generic coaching / injury / guidance products.**

Отже, якщо йти в цей напрям, найкраща framing:

**not another training app, but a marketplace + coach infrastructure layer on top of Strava-owned training context.**

## 1. Competitor Overview

### Summary table

| App | Market Focus | Relation to Strava | Monetization | Coach Marketplace? | AI Coaching? |
|---|---|---|---|---|---|
| Runna | Running coaching | Strava-owned (Apr 2025) | Subscription + Strava bundle | No | Yes |
| TrainingPeaks | Endurance / Triathlon | Independent | Athlete + coach subscription + plan marketplace | Yes | Partial |
| CoachUp | Coach marketplace (all sports) | Independent | Commission marketplace + coach subscription | Yes | No |
| Humango | Triathlon / Endurance | Independent | Freemium subscription + Coach Mode | Yes (coach mode) | Yes |
| GoWOD | Mobility & Recovery | Independent | Freemium subscription | No | No |
| LADDER | Strength training | Independent | Subscription tiers | No | Yes |
| Recover Athletics | Injury prevention / Prehab | Strava-owned (May 2022) | Bundled with Strava Premium / standalone | No | Yes |

### Key competitor takeaways

#### Runna

- Focus: running coaching
- Strong app quality signal: `4.9/5`, `26,000+` reviews
- Pricing: `$19.99/mo`, `$119.99/yr`
- Free tier: yes, including week 1 of plans and beginner plans
- Estimated scale: `2M MAU`
- Monetization: direct subscription + Strava bundle at `$149.99/yr`
- Strategic relevance:
  - already Strava-owned
  - already covers AI-adaptive plan layer
  - reduces whitespace for generic coaching app

#### TrainingPeaks

- Focus: endurance / triathlon coach-athlete ecosystem
- Strongest benchmark for serious coaching infrastructure
- Pricing includes both athlete and coach editions
- Plan marketplace signal:
  - `70K+ plans sold per month`
  - marketplace commission around `33%`
- Key insight:
  - strongest proof that coach/plan marketplace behavior already exists and monetizes

#### CoachUp

- Focus: pure coach marketplace, all sports
- Revenue signal:
  - estimated `~$115.8M` annual revenue
- Monetization:
  - `40%` first session commission
  - then `6%` after 5 sessions
  - coach subscription `$10–30/mo`
- Key insight:
  - strongest proof for 1:1 coach marketplace economics

#### Humango

- Focus: triathlon / endurance with AI-first angle
- Pricing:
  - `$16.99` to `$28.99/mo`
- Has `Coach Mode` at `$20/mo per athlete`
- Key insight:
  - validates hybrid AI + coach logic
  - relevant especially for multi-sport and performance-focused audience

#### GoWOD

- Focus: mobility and recovery
- Pricing: `$9.99/mo`, `$90/yr`
- Key insight:
  - validates specialized support verticals adjacent to coaching

#### LADDER

- Focus: strength training with coach-led teams
- Strong rating/review signal: `4.95/5`, `130,000+` reviews
- Revenue signal:
  - `> $2M/month`
- Key insight:
  - validates that expert-guided subscription products can scale strongly
  - but this is not a marketplace

#### Recover Athletics

- Focus: injury prevention and prehab
- Already Strava-owned
- Bundled with Strava Premium
- Key insight:
  - lowers whitespace for prehab / injury-support ideas

## 2. Feature Gaps Versus Strava

The Excel sheet explicitly asks:

**What do competitors offer that Strava does not?**

### Highest-priority gaps for a Coach Marketplace MVP

These are marked in the source as the most important missing pieces:

| Feature | Gap for Strava | Priority |
|---|---|---|
| Human Coach Marketplace (browse & book coaches) | High gap | High |
| Training Plan Store | High gap | High |
| Coach Revenue Share / Commission Model | High gap | High |
| Per-Athlete Coach Subscription | High gap | High |
| Commission on Marketplace Transactions | High gap | High |
| Elite / 1-on-1 Coaching Upsell Tier | High gap | High |

### Medium-priority gaps

| Feature | Gap for Strava | Priority |
|---|---|---|
| Coach Dashboard (manage multiple athletes) | High gap | Medium |
| Coach Verification / Vetting System | High gap | Medium |
| Coach–Athlete Messaging In-App | High gap | Medium |
| AI-Adaptive Training Plans | Partial gap | Medium |
| Mobility & Stretching Programs | High gap | Medium |
| Strength Training Programs | High gap | Medium |
| Multi-sport Training Plans | High gap | Medium |

### Low or already-partially-covered gaps

| Feature | Gap for Strava | Priority |
|---|---|---|
| Structured Workout Sync to Devices | Partial | Low |
| Training Load / TSS / Form analytics | Partial | Low |
| Nutrition Guidance | Partial via Runna | Low |
| Injury Prevention / Prehab | Low gap via Recover Athletics | N/A |

### Main implication

The source file points to one strong conclusion:

**Strava’s biggest whitespace is not generic coaching content, but the marketplace and coach-infrastructure layer.**

In other words:

- the content / training / support side is increasingly covered through `Runna` and `Recover Athletics`
- the true missing system is:
  - coach discovery
  - booking / payment
  - coach monetization
  - multi-athlete management
  - trust / vetting

## 3. Marketing & Ads Analysis

The Excel research also captures how competitors grow.

### Main acquisition patterns by competitor

| App | Main acquisition pattern |
|---|---|
| Runna | Strava integration, organic, word of mouth, App Store SEO |
| TrainingPeaks | SEO, coach partner network, B2B ecosystem, endurance event sponsorship |
| CoachUp | SEO, PR, coach supply-side recruitment, paid Meta acquisition |
| Humango | Triathlon community, forums, affiliate / coach partners |
| GoWOD | CrossFit community, affiliate gyms, Instagram organic |
| LADDER | Influencer / creator marketing, paid social, YouTube, podcast sponsorships |
| Recover Athletics | Mostly distributed through Strava itself |

### Main messaging themes captured in the source

#### Runna

- personalization
- expert coaching at scale
- injury prevention built in
- race achievement

#### TrainingPeaks

- scientific training
- coach-athlete collaboration
- data precision

#### CoachUp

- access
- affordability
- vetted coaches
- all sports

#### Humango

- AI precision
- multi-sport integration
- race readiness

#### GoWOD

- recovery speed
- sport specificity
- exercise depth

#### LADDER

- expert coaching
- audio immersion
- progressive strength
- accountability

#### Recover Athletics

- prevention over treatment
- science-backed
- time efficient

### Important meta-note from the sheet

The source explicitly notes that:

- most coaching apps run **limited paid Meta Ads**
- many rely heavily on:
  - ASO
  - community
  - coach ecosystems
  - partnerships
  - event distribution

This matters because:

**Coach marketplace is not purely a paid-acquisition category. Distribution and trust loops matter more than just performance media.**

## 4. Final Verdict From The XLSX

### Weighted score

The sheet gives the idea:

**`4.35 / 5.00` → `STRONG RECOMMENDATION`**

### Why the sheet says "Yes"

The file’s final argument is:

1. `Distribution moat`
Strava already has massive athlete distribution, so athlete-side CAC can be much lower than for standalone competitors.

2. `Willingness to pay is proven`
TrainingPeaks and CoachUp show that athletes and coaches already pay in this category.

3. `Natural fit with existing behavior`
Strava users already track and compare performance; coaching is a logical next layer.

4. `Competitive gap`
Competitors don’t combine large social distribution with coaching as naturally as Strava can.

5. `Monetization upside`
The sheet identifies three revenue streams:
- plan sales commission
- coach subscriptions
- athlete premium upgrades

## 5. Risks And Mitigations

### Risk 1: entrenched competitors

Sheet takeaway:

- TrainingPeaks and CoachUp are already established

Suggested mitigation:

- differentiate around simpler, more social-first coaching UX
- do not try to out-TrainingPeaks TrainingPeaks

### Risk 2: coach quality control

Sheet takeaway:

- trust is a major marketplace risk

Suggested mitigation:

- start with tiered coach verification
- begin invite-only before opening marketplace broadly

### Risk 3: Runna confusion / cannibalization

Sheet takeaway:

- Runna already gives AI coaching, which could blur the value prop

Suggested mitigation:

- position Runna as beginner-intermediate AI coaching
- position marketplace as advanced human coaching

### Risk 4: build complexity

Sheet takeaway:

- marketplace infra is not trivial

Suggested mitigation:

- phase the build
- possibly partner or white-label earlier capability before building full stack

## 6. Recommended MVP Path From The Source

The source does **not** recommend launching full 1:1 human coaching immediately.

### Phase 1

Launch:

- `Training Plan Store only`

Why:

- lower complexity
- already validated by TrainingPeaks
- can use Runna for run-specific plans
- external coaches can contribute plans for other sports

Suggested monetization:

- `25–30%` commission on plan sales

### Phase 2

Add:

- coach messaging
- athlete dashboard
- coach subscriptions

### Phase 3

Add:

- full marketplace
- verified coach profiles
- athlete-coach matching
- 1:1 coaching

## 7. What This Means For Our Current Strava Work

This team XLSX changes the conversation in an important way.

### What it strengthens

- `Coach Marketplace` is still one of the strongest strategic directions
- the market is real, not theoretical
- monetization logic is clearer than many other ideas

### What it narrows

Because of `Runna` and `Recover Athletics`, the whitespace is now narrower than a generic pitch like:

- "Strava should do coaching"
- "Strava should do running plans"
- "Strava should do injury prevention"

Those layers are already partially occupied.

### Best current framing

The strongest updated framing is:

**Strava should consider not another coaching app, but a coach commerce and infrastructure layer on top of its existing athlete graph plus Runna-owned training context.**

## 8. Bottom Line

The Excel analysis strongly supports `Coach Marketplace`, but it also makes the scope more precise.

Best interpretation:

- `YES` to marketplace and coach monetization rails
- `NO` to framing it as just another training-plan app

The most credible wedge now is:

- plan store
- coach discovery
- booking / payments
- coach dashboard
- coach monetization

not:

- generic coaching content
- basic AI plans
- generic beginner running support
