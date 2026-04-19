# Strava Product Source of Truth From Figma

## Purpose

Цей документ фіксує, що саме Strava уже собою представляє на основі Figma-борду
`01_inputs/Strava app feathers.png`.

Його задача:

- зупинити context drift у команді
- мати спільний product baseline перед пошуком expansion-ніші
- відділити те, що ми **бачимо напряму**, від того, що ми **лише припускаємо**

## Artifact

- Джерело: `01_inputs/Strava app feathers.png`
- Робоча копія для аналізу: `01_inputs/Strava app feathers.codex.png`
- Дата аналізу: `2026-04-19`
- Формат джерела: Figma board / visual inventory

## How To Read This Document

- `Observed directly` = чітко видно на борді
- `Likely / inferred` = обережний висновок із UI, назви екрана або композиції
- `Not proven by this artifact` = не можна вважати підтвердженим лише з цього файлу

## Executive Summary

За цим бордом Strava уже є не просто activity tracker.

Strava виглядає як багатошаровий продукт-екосистема, що об'єднує:

- core activity tracking і performance history
- route, segment, map та local discovery
- social/community surfaces: clubs, challenges, feed-like surfaces
- subscription monetization і perks
- light coaching / training / recovery surfaces
- branded partnerships і B2B sponsor inventory
- event discovery

Ключовий висновок для команди:

**Нішу для expansion не варто шукати в зоні "ще один basic fitness feature".**
Потрібно шукати або:

- глибшу value layer поверх уже наявної поведінки
- транзакційний / сервісний шар, якого тут ще не видно
- більш вертикальний use case, який Strava зараз покриває лише поверхнево

## What Strava Clearly Already Is

### 1. Core athlete app

Observed directly:

- нижня навігація `Home`, `Maps`, `Record`, `Groups`, `You`
- профіль користувача з activity stats
- тижнева зведена статистика: distance, time, elevation
- окремі розділи `Activities`, `Statistics`, `Routes`, `Segments`, `Best Efforts`, `Posts`, `Gear`

Що це означає:

- ядро Strava все ще тримається на особистому activity history, performance tracking та self-logging

### 2. Social fitness network

Observed directly:

- `Followers`, `Following`, `Activities`
- `Groups` tab
- `Challenges`
- `Clubs`
- екрани клубів і community joins
- social/content-like cards і feed surfaces

Що це означає:

- Strava already functions as a social graph for active people, а не лише як utility app

### 3. Discovery layer

Observed directly:

- `Maps`
- routes / saved routes
- popular segments
- sport filters for map exploration
- local events browsing
- location / POI-style cards on map

Що це означає:

- Strava already has a meaningful discovery behavior layer: де тренуватись, що проходити, що поруч відбувається

### 4. Subscription business

Observed directly:

- subscription comparison table `free` vs `subscription`
- окремий `Subscription overview`
- manage subscription screens
- subscriber benefits / perks screens
- subscription plan cards
- partner offer flows

Що це означає:

- monetization у Strava не обмежується "unlock analytics"; subscription already bundles utility, status і partner value

### 5. B2B / brand ecosystem

Observed directly:

- блок `Strava Business`
- `Sponsored Challenges`
- `Sponsored Segments`
- `Subscription Partnerships`
- challenge targeting logic
- campaign economics / reach explanation
- industries / brand verticals

Що це означає:

- Strava is already monetizing attention, motivation loops, and athlete intent for brands and partners

## Product Surface Inventory

## A. Tracking, Performance, And Personal Progress

Observed directly:

- weekly stats on home/profile
- activity history surfaces
- `Best Efforts`
- `Segments`
- `Statistics`
- progress / streak-like cues

Likely / inferred:

- Strava positions itself as an ongoing self-improvement product, not only as a logbook

Confidence:

- High

## B. Identity, Profile, And Athlete Account

Observed directly:

- profile card with name, location, subscription badge
- shareable QR code
- `Edit`
- profile completeness prompt
- counts for following / followers / activities

Likely / inferred:

- profile quality matters because social discovery and community participation are part of the product loop

Confidence:

- High

## C. Gear Management

Observed directly:

- `Your Gear`
- `Add Gear`
- gear type selector
- `Bike`, `Shoes`
- fields such as default sport, nickname, bike type, brand, model, weight, notes

Що це означає:

- Strava already supports equipment as a first-class object in the athlete workflow, especially for cycling and running contexts

Confidence:

- High

## D. Routes, Maps, Segments, And Location Discovery

Observed directly:

- map screens with route/segment overlays
- sport picker for map browsing
- `Popular segments`
- filters such as `Length`, `Elevation`, `Surface`
- route / saved route mentions
- location result card with distance/elevation/time

Likely / inferred:

- route discovery is already an important retained behavior, not a side utility
- the map is not only for recording; it is also for exploration and decision-making

Confidence:

- High

## E. Challenges, Goals, And Motivation Loops

Observed directly:

- challenge screens
- suggested goal card
- `Set Goal`
- recurring challenge examples
- club/challenge tabs inside groups area

Likely / inferred:

- Strava uses goals and challenges as engagement and retention mechanics, not just community decoration

Confidence:

- High

## F. Clubs, Groups, And Community Participation

Observed directly:

- club discovery screens
- join CTAs
- `Create Your Own Strava Club`
- nearby / popular clubs
- group tabs and group navigation

Що це означає:

- Strava already supports lightweight community formation and not just 1:1 following

Confidence:

- High

## G. Events And Real-World Participation

Observed directly:

- `Browse Events`
- filters by sport
- event list
- event detail page
- `Join`
- `Add to calendar`

Likely / inferred:

- Strava has a real-world activation layer that connects product activity with offline participation

Confidence:

- High

## H. Subscription Packaging And Pricing

Observed directly:

- free vs subscription feature comparison
- plan cards including individual / student
- `Strava + Runna` bundle mention
- subscription expiration / renewal surfaces
- `Manage Your Subscription`

Feature examples visible in subscription marketing:

- save routes for offline use
- draw your own route
- advanced insights
- create segment leaderboards
- custom goals

Likely / inferred:

- subscription packaging combines utility, progress tools, exclusivity, and partnerships

Confidence:

- High

## I. Perks, Partner Benefits, And External Offers

Observed directly:

- `Perks`
- partner landing screens
- `Visit Website`
- offers such as insurance and wellness / breathwork-like services
- subscriber perks entries including Apple Fitness+ and Recover Athletics references

Likely / inferred:

- Strava subscription extends beyond native in-app features into a partner-benefits ecosystem
- Strava is comfortable acting as a distributor of third-party value

Confidence:

- High

## J. Training, Coaching-Like Guidance, And Recovery

Observed directly:

- `Instant Workouts`
- tabs like `Maintain`, `Build`, `Explore`, `Recover`
- workout recommendation cards
- training zones
- power skills
- predicted finish times
- weekly progress references
- recovery / wellness-flavored workout cards
- video workout content examples

Likely / inferred:

- Strava already touches the training guidance space
- recovery is present at least as a lightweight workout/content surface
- this looks closer to guided recommendations and partner-enabled content than to a deep medical-grade recovery platform

Confidence:

- High on presence
- Medium on exact depth of capability

## K. Brand, Commerce, And Sponsored Inventory

Observed directly:

- `Sponsored Challenges`
- `Sponsored Segments`
- industry examples: apparel, footwear, gear and bikes, nutrition, travel & tourism, retailers
- advertising / targeting explanations
- performance/conversion framing
- branded challenge examples
- discount / promo-style brand content in community surfaces

Likely / inferred:

- Strava already has more than one commercial surface: native sponsorship products plus community-adjacent branded exposure

Confidence:

- High

## L. Strava Business As A Distinct Product Surface

Observed directly:

- dedicated `Strava Business` web pages
- positioning around reaching active people
- explanations of challenge mechanics
- targeting inputs such as gender, sport type, geography, seasonality
- sections about how challenges help brands meet goals
- cost / reach / seasonal framing

Що це означає:

- Strava should be treated not only as a consumer app but as a two-sided ecosystem with business-side monetization logic

Confidence:

- High

## What This Artifact Suggests About Strava's Product Model

На основі борду Strava already spans six product jobs:

1. `Track me`
Записати активність, зберегти history, показати прогрес.

2. `Improve me`
Підказати goals, workouts, zones, performance insights.

3. `Motivate me`
Дати challenges, streak-like structure, leaderboards, community pressure.

4. `Connect me`
Зв'язати мене з клубами, людьми, подіями, локальними спільнотами.

5. `Guide me`
Допомогти знайти routes, segments, places, events, map-based options.

6. `Monetize / partner around me`
Продати subscription, bundle perks, дати брендам доступ до athlete intent.

## Strategic Boundaries For Expansion Search

## Areas That Already Look Crowded Inside Strava

На цьому борді Strava already clearly occupies:

- activity tracking
- performance summaries
- route and segment discovery
- social clubs and challenges
- event discovery
- subscription benefits
- partner perks
- basic training / recovery / workout recommendation
- brand-sponsored motivational mechanics

Отже, якщо команда піде в одну з цих зон, треба мати:

- або значно глибший wedge
- або нову monetization logic
- або інший unit of value, ніж Strava already provides

## Areas That Do Not Look Fully Owned From This Artifact

Це **не означає, що Strava цього не має взагалі**.
Це означає лише, що цей Figma board цього чітко не доводить.

Not proven by this artifact:

- deep nutrition tracking / meal planning
- full healthcare / rehab / clinical recovery layer
- coach operations marketplace
- end-to-end travel booking
- equipment resale / transaction marketplace
- advanced team league management
- offline service booking tied to local fitness providers

Саме такі простори можуть бути цікавішими для expansion analysis, бо вони не виглядають already dominated у наданому visual inventory.

## Working Product Thesis

Якщо спиратися лише на цей борд, Strava is best understood as:

**a subscription-led social fitness platform with tracking, discovery, community, brand monetization, and lightweight training/recovery extensions.**

Це важливо, бо воно відсікає хибну постановку задачі:

- Strava is not just "an app to record runs"
- Strava is not only "a social network for runners"
- Strava is not only "a premium analytics upgrade"

Strava already behaves more like an active lifestyle platform with multiple adjacent wedges.

## Caveats

- Це джерело правди побудоване з одного Figma board, а не з повного product audit.
- Деякі екрани на борді є маркетинговими / веб-сторінками, а не тільки native mobile app screens.
- Частина capability depth неочевидна: наприклад, recovery / coaching можуть бути як повноцінною функцією, так і тонким wrapper around partner content.
- Відсутність фічі на цьому борді не є доказом, що її немає в реальному продукті.

## Recommended Use

Використовувати цей документ як baseline для:

- gap analysis
- shortlist refinement
- discussions про "що Strava already covers"
- перевірки, чи нова ідея є справді expansion, а не дублюванням наявного surface area

Не використовувати цей документ як єдине джерело для:

- точного feature-by-feature audit всього Strava
- оцінки технічної складності реалізації
- фінального твердження про відсутність певної функції в продукті
