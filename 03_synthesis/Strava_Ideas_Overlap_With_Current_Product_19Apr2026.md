# Strava Ideas Overlap With Current Product

## Purpose

Цей документ показує, де наші expansion-ідеї вже перетинаються з тим, що Strava
**вже робить** за нашим поточним `source of truth`:

- [Strava_Product_Source_of_Truth_From_Figma_19Apr2026.md](/Users/artemkorneev/Documents/STRAVA/03_synthesis/Strava_Product_Source_of_Truth_From_Figma_19Apr2026.md)
- [Strava_Brainstorm_Scoring_Snapshot_19Apr2026.md](/Users/artemkorneev/Documents/STRAVA/03_synthesis/Strava_Brainstorm_Scoring_Snapshot_19Apr2026.md)

## Scale

- `Low overlap` = Strava має лише слабкі передумови, але не саму пропозицію цінності
- `Medium overlap` = Strava already covers частину user job, але не весь wedge
- `High overlap` = Strava уже має суттєвий surface area цієї ідеї
- `Very high overlap` = ідея виглядає радше як extension/feature, ніж новий напрям

## Executive Take

Найбільший перетин у нас не з travel або marketplace-ідеями, а з:

- clubs / organizer tooling
- recovery / guided workouts
- events
- corporate challenges
- creator/community monetization

Найменший прямий перетин із того, що виглядає ще живим:

- `Coach Marketplace`
- `Nutrition / Meal Planning`
- частково `Active Travel`, якщо фокусуватися не на маршрутах, а на trip planning + booking

## Overlap Matrix

| Idea | Overlap | Де Strava already overlaps | Що ще лишається новим |
|---|---|---|---|
| Strava Escapes / Active Travel | Medium-High | maps, routes, saved routes, sport filters, local discovery, clubs, events | multi-day trip planning, travel itineraries, partner booking, destination bundles |
| Coach Marketplace | Medium | training/recommendation surfaces, workouts, recovery hints, Runna-adjacent logic | coach discovery, matching, plan purchase, coach ops, human guidance layer |
| Local Experiences Marketplace | Medium-High | clubs, groups, events, local discovery, map/location surfaces | paid hosts, supply-side tools, booking, trust/safety, GMV layer |
| Strava Live / Race & Event Marketplace | High | browse events, event details, join flow, add to calendar, community activation | registration commerce, organizer tooling, race prep-to-result closed loop |
| Strava Courts / Social Sports | Medium | groups, clubs, events, social graph; partial sport expansion signals | opponent matching, ladder/ranking, court booking, sports-specific workflows |
| Nutrition / Meal Planning | Low | only indirect overlap via training goals/load context | meal plans, macro tracking, fueling guidance, nutrition habit engine |
| Strava Work / Corporate Wellness | High | Strava Business, sponsored challenges, clubs, leaderboards, challenge mechanics | HR admin layer, employer dashboards, B2B sales motion, org analytics |
| Strava Ready / Recovery & Longevity | Very high | workouts, recover tab, recovery-flavored content, training/recovery guidance | deeper readiness scoring, health-signal integrations, longitudinal risk model |
| Creator Pass / Creator Economy | High | clubs, challenges, community, subscription/perks, influencer-like community surfaces | paid access, creator monetization rails, content packaging economics |
| Club OS / Organizer Tools | Very high | clubs, groups, event flows, joins, community participation | stronger admin tooling, attendance, recurring coordination, ops dashboards |
| Return-to-Activity / Pre-Hab | Medium-High | recovery/training guidance already present | injury-safe progression logic, rehab specificity, medical credibility |
| Outdoor Group Safety / Beacon+ | Very high | group/community behavior plus existing Beacon-adjacent logic noted in prior synthesis | stronger safety orchestration for groups, emergency workflows |
| Gear Recommerce | Low-Medium | gear objects/profile context exist | actual marketplace, listings, payments, trust, logistics |
| Guided Audio / Adaptive Beginner Coach | High | workouts, guided training direction, beginner-friendly recommendation surfaces | audio-native coaching and onboarding-specific UX |
| University Communities | High | clubs, groups, challenges, local community | campus identity, rivalry formats, institutional go-to-market |
| Family Movement | Medium | challenges, groups, light motivation mechanics | household graph, child safety, family-specific routines |
| AI Strength Form Coach | Low | only weak adjacency via training | camera-based form analysis, strength-specific progression, CV stack |
| Adaptive / Inclusive Fitness | Low | little direct evidence on board | specialized programs, accessibility-first UX, tailored flows |
| Health-Insurance Subsidy / Proprietary Hardware | Low | partner perks only loosely adjacent | insurer economics, underwriting, hardware business |
| Fitness Dating | Low | social graph/community exists, but not dating intent | matching model, identity/safety, romantic interaction layer |
| Youth Sports Logistics | Low | clubs/groups as weak base | parent/coach/admin workflows, minors/privacy, schedules |
| Strava Paws / Dog-Friendly Activities | Low | challenges/community/maps as generic base | dog-specific identity, discovery, pet-centric experiences |
| Strava Virtual / AR Training | Low | training adjacency only | immersive engine, virtual world, AR interaction loop |

## Idea-By-Idea Notes

### 1. Strava Escapes / Active Travel

Overlap level:

- Medium-High

Why:

- Strava already owns route discovery, map exploration, local segments, clubs and events.
- Якщо сформулювати ідею як "маршрути в новому місті", це вже майже current Strava behavior.

Where the wedge still exists:

- готові trip packages
- day-by-day active itineraries
- local partner booking
- travel-specific planning layer, а не просто discovery layer

Verdict:

- Жива ідея лише якщо ми продаємо **trip orchestration**, а не "кращі маршрути".

### 2. Coach Marketplace

Overlap level:

- Medium

Why:

- Strava already touches workouts, recommendations, training, recovery.
- Але на борді не видно marketplace for coaches, transaction layer або coach workspace.

Where the wedge still exists:

- пошук і match з coach
- buy a plan / buy support
- shared data workspace coach <-> athlete
- coach-side tooling

Verdict:

- Один із найчистіших expansion wedges у списку.

### 3. Local Experiences Marketplace

Overlap level:

- Medium-High

Why:

- Strava already has clubs, local communities, events, maps and discovery.
- Якщо ідея звучить як "meet people and join local activity", overlap уже значний.

Where the wedge still exists:

- host economy
- paid experiences
- booking / capacity / trust
- localized commerce layer

Verdict:

- Сильна ідея тільки якщо тримати фокус на **marketplace + host supply**, а не на community discovery itself.

### 4. Strava Live / Race & Event Marketplace

Overlap level:

- High

Why:

- На борді прямо видно `Browse Events`, event detail, `Join`, `Add to calendar`.
- Тобто event discovery and participation уже присутні.

Where the wedge still exists:

- race registration
- organizer monetization
- full registration-to-results pipeline

Verdict:

- Виглядає ближче до commercialization of an existing surface, ніж до нового продуктового простору.

### 5. Strava Courts / Social Sports

Overlap level:

- Medium

Why:

- Social graph, groups, clubs, events у Strava already exist.
- Але sports-specific matching, booking, ladder logic на борді не видно.

Where the wedge still exists:

- partner matching
- match orchestration
- ranking ladder
- court slot booking

Verdict:

- Живе як sports-vertical wedge, але не як generic community layer.

### 6. Nutrition / Meal Planning

Overlap level:

- Low

Why:

- На борді немає nutrition, meals, macros, food logging.
- Є лише непряма база: activity load and goals.

Where the wedge still exists:

- майже вся ідея

Verdict:

- Найменший продуктовий overlap, але є стратегічний ризик віддалення від Strava DNA.

### 7. Strava Work / Corporate Wellness

Overlap level:

- High

Why:

- `Strava Business`, sponsored challenges, segmentation, challenge targeting already visible.
- Corporate/community challenge logic already exists conceptually.

Where the wedge still exists:

- HR dashboards
- B2B admin controls
- company analytics
- employer distribution model

Verdict:

- Це не "нова поведінка", а enterprise packaging of surfaces Strava already has.

### 8. Strava Ready / Recovery & Longevity

Overlap level:

- Very high

Why:

- На борді вже є `Recover`, recovery-flavored workouts, training guidance and wellness-adjacent perks/content.

Where the wedge still exists:

- readiness score
- deeper health integrations
- more credible recovery intelligence

Verdict:

- Найсильніший кандидат у категорію "feature, not expansion".

### 9. Creator Pass / Creator Economy

Overlap level:

- High

Why:

- Clubs, challenges, community and subscription/perks already make this feel like a monetization extension.

Where the wedge still exists:

- creator payouts
- paid access
- content/program packaging

Verdict:

- Більше схоже на revenue layer поверх current graph, ніж на новий ринок.

### 10. Club OS / Organizer Tools

Overlap level:

- Very high

Why:

- Clubs, groups and events are already core surfaces on the board.
- Organizer tooling would mainly deepen an existing behavior.

Where the wedge still exists:

- attendance
- recurring ops
- admin workflows

Verdict:

- Корисний product improvement, але слабкий expansion story.

### 11. Return-to-Activity / Pre-Hab

Overlap level:

- Medium-High

Why:

- Recovery/training space already exists in lightweight form.
- Але injury-safe progression and rehab specificity на борді не видно.

Where the wedge still exists:

- structured return protocols
- injury-aware progression
- prevention + guardrails

Verdict:

- Може жити як sharper recovery wedge, але все одно близько до existing recovery territory.

### 12. Outdoor Group Safety / Beacon+

Overlap level:

- Very high

Why:

- Це вже раніше визнано дублем Active Travel / Beacon-adjacent utility.
- Social outdoor coordination і так природно сідає на existing map/community layer.

Verdict:

- Скоріше add-on feature.

### 13. Gear Recommerce

Overlap level:

- Low-Medium

Why:

- Gear entities already exist, але marketplace behavior відсутній.

Where the wedge still exists:

- commerce
- listings
- resale trust/logistics

Verdict:

- Overlap невеликий, але fit і ops-complexity проблемні.

### 14. Guided Audio / Adaptive Beginner Coach

Overlap level:

- High

Why:

- Workouts/training/recommendation surfaces already exist.
- Це виглядає як packaging of existing coaching direction for beginners.

Verdict:

- Ближче до direct competitor feature set, ніж до нового ринку.

### 15. University Communities

Overlap level:

- High

Why:

- Clubs + challenges + community surfaces already cover most of the behavior.

Where the wedge still exists:

- campus identity
- school-level competition structure

Verdict:

- Новий сегмент, але не нова product logic.

### 16. Family Movement

Overlap level:

- Medium

Why:

- Challenges and group motivation already exist, але family graph/safety layer не видно.

Verdict:

- Частково новий audience packaging, не дуже новий surface.

### 17. AI Strength Form Coach

Overlap level:

- Low

Why:

- Strength form analysis by camera is not represented on the board.

Verdict:

- Product overlap низький, але strategic fit слабкий.

### 18. Adaptive / Inclusive Fitness

Overlap level:

- Low

Why:

- Немає явних inclusive or specialized training surfaces.

Verdict:

- Overlap низький, але evidence and market confidence слабкі.

### 19. Health-Insurance Subsidy / Proprietary Hardware

Overlap level:

- Low

Why:

- Partner perks are adjacent, але це не insurance/hardware operating model.

Verdict:

- Product overlap низький, але execution horizon занадто далекий.

### 20. Fitness Dating

Overlap level:

- Low

Why:

- Social graph exists, але dating intent completely changes the product contract.

Verdict:

- Не через overlap погана, а через brand risk and relevance.

### 21. Youth Sports Logistics

Overlap level:

- Low

Why:

- Existing clubs/groups are weak prerequisites, але actual youth logistics layer is absent.

Verdict:

- Overlap низький, але це інша operational category.

### 22. Strava Paws / Dog-Friendly Activities

Overlap level:

- Low

Why:

- Є generic routes/challenges/community, але ніякого dog-specific layer.

Verdict:

- Low overlap, low conviction.

### 23. Strava Virtual / AR Training

Overlap level:

- Low

Why:

- Training exists, але virtual/AR loop відсутній.

Verdict:

- Low overlap, but too far from current strengths for a short-horizon bet.

## Fast Sorting

### Ideas most threatened by overlap

- Strava Ready / Recovery & Longevity
- Club OS / Organizer Tools
- Outdoor Group Safety / Beacon+
- Strava Live / Race & Event Marketplace
- Strava Work / Corporate Wellness
- Creator Pass / Creator Economy
- Guided Audio / Adaptive Beginner Coach

### Ideas with real room left if framed correctly

- Coach Marketplace
- Nutrition / Meal Planning
- Strava Escapes / Active Travel
- Local Experiences Marketplace
- Strava Courts / Social Sports
- Gear Recommerce

## Bottom Line

Якщо наша ціль зараз не просто придумати фічу для Strava, а знайти expansion wedge,
то найнебезпечніша помилка — брати ідею, яка звучить ново на слайді, але по факту є:

- monetization layer
- organizer utility
- recovery feature
- event packaging

Найкраще виглядають ті напрямки, де Strava already має контекст і дані,
але **ще не володіє самою транзакцією, matching-логікою або новим supply-side layer**.
