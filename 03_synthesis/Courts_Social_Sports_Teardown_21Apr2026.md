# Courts Social Sports Teardown

## Purpose

Цей документ зберігає teardown по напряму `Courts / Social Sports` у markdown-форматі для подальшого overlap та expansion аналізу.

Його задача:

- зафіксувати конкурентний landscape у court sports
- зрозуміти, за що саме тут платять користувачі й організатори
- оцінити, чи це natural expansion для Strava, чи вже окремий product layer

## Source

- Original file: `Courts _ Social Sports.docx`
- Date captured: `2026-04-21`

## Executive Summary

Цей напрямок виглядає перспективним не тому, що `теніс` чи `падел` можна просто додати як ще один activity type, а тому, що тут працює інша логіка продукту:

- центральний об'єкт не маршрут, а `корт + партнер + слот часу`
- paid value приходить із `booking`, `matchmaking`, `club SaaS`, `AI analytics` і `event organization`
- social graph тут глибший, ніж у Strava today: треба не лише follow/kudos, а знайти гравців на конкретний час і зібрати матч

Головний висновок для Strava:

- це не feature extension у межах current endurance UX
- це potential expansion vertical
- але тільки якщо будувати окремий court-sports layer, а не просто додати нові activity labels

## Category Takeaways

### What users actually pay for

Across the category, paid value найчастіше зосереджене навколо таких шарів:

- court booking
- split payments
- open match / matchmaking
- tournament or session organization
- club management SaaS
- AI video analysis and coaching
- structured session formats like round robin or ladders

### Core user jobs in this category

- знайти корт поруч і забронювати його
- знайти партнера або повний склад на матч
- розподілити оплату між гравцями
- організувати групову гру або міні-турнір
- отримати об'єктивний аналіз матчу чи техніки

### Main implication for Strava

Court sports змінюють основний product object:

- у Strava це переважно `activity log + route + performance`
- тут це `session orchestration + player graph + court availability`

Тому це виглядає як нова vertical product logic, а не як легке розширення current Strava flow.

## Competitor Breakdown

## 1. Playtomic

### Product offering

Source описує Playtomic як інфраструктурний marketplace для padel / court sports:

- користувач шукає вільний корт за гео, часом і видом спорту
- бронює та оплачує через додаток
- може розділити платіж із партнерами
- може приєднатися до open match або турніру

### What people pay for

Top paid value layers:

- court booking and split payment
- open match / matchmaking
- club management SaaS for operators

### Hero use-case

Гравець хоче зіграти сьогодні ввечері, але не має повного складу. Він знаходить корт і open match у nearby club, платить лише свою частку і підключається до гри без ручної координації.

### Monetization

У source модель описана як:

- marketplace for booking and matchmaking
- club SaaS via Playtomic Manager

Основні revenue layers:

- GMV from bookings
- service fee on open matches
- club-side SaaS + transaction layer

### Audience and geo

Main personas:

- urban player who plays padel several times per week
- club owner who wants automation and better court utilization

Scale indicators listed in the source:

- 6,000+ clubs
- 1.5M active players per month
- presence in 63 countries
- 23,000+ courts

### Differentiator

Головний differentiator у source:

- Playtomic behaves more like `Stripe for padel clubs`
- це не просто discovery app, а transaction and operations layer for clubs

### Main takeaway for Strava

Playtomic показує, що найбільша цінність у court sports часто лежить не в контенті чи tracking, а в:

- bookings
- payments
- club operations
- real-time player coordination

Це дуже далекий UX від current Strava.

## 2. SwingVision

### Product offering

Source описує SwingVision як AI analytics and coaching product:

- користувач ставить iPhone або iPad біля корту
- записує гру
- отримує shot tracking, clips, stats, line calls і personalized feedback

### What people pay for

Top paid value layers:

- AI line calling
- auto stats and highlights
- AI coaching feedback

### Hero use-case

Аматорський тенісист хоче зрозуміти, чому програє certain rallies, але не має тренера або дорогої аналітичної системи. SwingVision дає професійний video-analysis layer через звичайний смартфон.

### Monetization

У source модель описана як:

- primarily B2C subscription
- early B2B around clubs, universities and officiating

Key pricing logic:

- free tier with recording limits
- paid plans around annual or monthly subscription
- family-like plan on higher tier

### Audience and geo

Main personas:

- amateur or semi-pro tennis player
- university teams
- fast-growing pickleball audience

Core geography:

- mainly USA

### Differentiator

У source головний differentiator такий:

- professional-grade AI analytics via a single mobile camera
- strong Apple-native execution
- patent-protected 3D tracking technology

### Main takeaway for Strava

SwingVision показує окремий possible wedge:

- coaching and analytics for court sports
- but without booking or community orchestration

Для Strava це не social layer, а окремий AI coaching layer, який радше підходить для acquisition, partnership або dedicated premium vertical.

## 3. Pickleheads

### Product offering

Source описує Pickleheads як community-first platform:

- користувач шукає courts and games
- бачить sessions by skill level
- приєднується до open play або створює власний event
- organizer керує waitlist, reminders, payments і results

### What people pay for

Top paid value layers:

- payments for organizers
- skill-based matchmaking
- ads and partner monetization

### Hero use-case

Local organizer хоче масштабувати weekly social mixer з кількох друзів до десятків або сотень гравців без ручної координації.

### Monetization

У source модель описана як:

- community-first freemium
- organizer tools
- payment processing
- emerging subscription logic
- coaching affiliate / partnership revenue

### Audience and geo

Main personas:

- recreational player
- community organizer
- beginner looking for where to play

Core geography:

- mostly USA and partly Canada

### Differentiator

Головний differentiator у source:

- official court and game finder positioning
- community-driven directory with strong network effects
- organizer tooling instead of club-first marketplace logic

### Main takeaway for Strava

Pickleheads показує, що court sports може будуватися не лише як booking marketplace, а і як:

- community graph
- game finder
- organizer platform

Це ближче до Strava DNA, але все одно потребує нових product mechanics beyond clubs and feed.

## Cross-Competitor Patterns

Across all three competitors видно кілька стабільних patterns:

### 1. Session orchestration is the core product

У court sports value створюється навколо `who`, `where`, `when` і `how to organize`, а не навколо дистанції чи маршруту.

### 2. Payments are embedded in the product

Booking fees, split payments, event payments і club monetization already є core part of the category.

### 3. Social graph is deeper than Strava’s current one

Court sports потребують:

- partner matching
- skill matching
- round robin logic
- organizer coordination

Це значно глибше, ніж `follow + kudos + comments`.

### 4. Analytics exists as a separate premium wedge

SwingVision показує, що AI analytics може бути самостійним бізнесом навіть без booking/community layer.

### 5. Category winners choose a clear wedge

- Playtomic wins on infrastructure and club operations
- SwingVision wins on AI coaching
- Pickleheads wins on community and organizer tooling

Ніхто не виграє лише через generic social-fitness messaging.

## Key Insights For Strava

### 1. There is no real Strava overlap at the product-surface level

Source прямо підкреслює:

- Strava built around endurance activities
- current logic revolves around distance, time, HR and routes
- court sports need a different interaction model

Тобто це не crowded overlap territory, а радше greenfield inside Strava.

### 2. Social graph is transferable, but insufficient

Те, що Strava already має:

- clubs
- friends
- comments
- challenges

може бути стартовим asset, але цього недостатньо без:

- matchmaking
- booking
- rotation formats
- organizer flows

### 3. Community-first entry makes more sense than marketplace-first entry

Source дуже чітко підводить до висновку:

- marketplace для кортів операційно важкий
- community and matchmaking — ближче до того, що Strava already вміє

Тому найреалістичніший entry wedge виглядає як:

- court sports vertical
- player matching
- social coordination

а вже потім booking or analytics.

### 4. This direction is expansion, not feature work

Court sports не виглядає як:

- new activity tag
- extra challenge template
- small community add-on

Це окремий product layer зі своєю monetization logic.

### 5. Acquisition could be more realistic than building from zero

Source окремо підсвічує:

- SwingVision as AI layer
- Playtomic as booking infrastructure
- Pickleheads as community-first graph

Тобто для Strava acquisition or partnership може бути реалістичнішим, ніж greenfield build of everything at once.

## Final Verdict

Вердикт із цього research можна сформулювати так:

- `Courts / Social Sports` є справжнім expansion opportunity
- overlap зі Strava core today низький
- але fit не автоматичний, бо category потребує нового UX і нових business mechanics

Найкращий спосіб дивитися на цей напрям:

- не як `додати tennis/padel/pickleball у список активностей`
- а як `створити новий social-sports layer поверх Strava network`

Найсильніший initial wedge:

- community
- matchmaking
- session coordination

Найризикованіша частина для першого етапу:

- club integrations
- court booking marketplace
- operational complexity

### Short table-ready conclusion

Перспективний expansion із низьким overlap зі Strava core, але тільки як окрема vertical для matchmaking / session coordination, а не як ще один тип активності в поточному продукті.
