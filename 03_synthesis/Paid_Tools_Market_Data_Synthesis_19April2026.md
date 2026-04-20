# Paid Tools Market Data Synthesis

Дата: `19 April 2026`  
Джерело: CSV-файли з `01_inputs/market_data`  
Контекст: market validation для проєкту про `Strava` expansion strategy

---

## 1. Навіщо цей файл

Це зведення аналітики, яку лектор зібрав із платних тулів, щоб:

- не втратити цифри
- не втратити важливі коментарі до цих цифр
- зрозуміти, які adjacent/new-market ідеї для `Strava` реально підкріплені traction даними

---

## 2. Що саме було в даних

У папці [market_data](../01_inputs/market_data) є `40` CSV-файлів по:

- `Unified Downloads`
- `Unified Revenue`

для трьох вікон:

- `April 2023 - April 2024`
- `April 2024 - April 2025`
- `April 2025 - April 2026`

Покриття:

- всі країни / регіони
- App Store + Google Play
- по багатьох продуктах, згрупованих навколо гіпотез для `Strava`

---

## 3. Важливі коментарі, які треба зберегти

### Коментар 1

У самих CSV **немає окремої текстової колонки з comments**.  
Тому тут я зберігаю важливі **інтерпретаційні нотатки поруч із цифрами**, щоб не загубити логіку читання даних.

### Коментар 2

У файлах є **дублікати однакових рядків між різними CSV**.  
Під час зведення я дедуплікував записи по:

- app
- date
- country
- platform
- device
- downloads
- revenue
- RPD

Інакше підсумки були б завищені.

### Коментар 3

`Revenue = 0` у цих CSV **не означає, що продукт не заробляє взагалі**.  
Це часто означає:

- монетизація йде не через mobile in-app revenue
- оплата відбувається на web
- продукт B2B / enterprise
- гроші заробляються через hardware, marketplace, booking, services або subscriptions поза app store

Це особливо важливо для:

- `WHOOP`
- `Oura`
- `ClassPass`
- `Eventbrite`
- `GetYourGuide`
- `Viator`
- частини sports/community apps

### Коментар 4

Цей датасет **набагато краще валідовує consumer adjacencies**, ніж `B2B corporate wellness`.

Тобто він сильніше допомагає оцінити:

- outdoor / active travel
- coaching / training
- social sports / courts
- recovery / longevity
- event / travel discovery

і слабше допомагає довести:

- enterprise wellness
- HR dashboards
- B2B benefits administration

### Коментар 5

Тому цей пакет даних варто читати не як "остаточну істину по всіх ринках", а як:

- сильну валідацію `consumer market pull`
- перевірку того, де вже є масштабний mobile demand
- перевірку того, де користувачі реально платять у related categories

---

## 4. Executive Summary

Найсильніше ці дані підтверджують такі напрями для `Strava`:

1. **Active Travel / Outdoor Discovery / Escapes**
2. **Coaching / Training / Performance Guidance**
3. **Social Sports / Courts**

Слабше, але цікаво:

4. **Recovery / Longevity**
5. **Community / Group coordination**

Найгірше цим пакетом даних доводиться:

6. **Corporate Wellness / B2B Work**

---

## 5. Кластери і що показують цифри

| Кластер | 2023-2024 Downloads | 2024-2025 Downloads | 2025-2026 Downloads | 2025-2026 Revenue | Що це означає |
|---|---:|---:|---:|---:|---|
| `Outdoor / Active Travel` | 54.6M | 66.6M | 91.7M | $326.6M | великий і зростаючий ринок; outdoor planning і discovery реально монетизуються |
| `Social Sports / Courts` | 2.6M | 3.6M | 4.4M | $2.9M | менший ринок, але дуже швидке зростання; сильний сигнал для non-obvious bet |
| `Coaching / Training` | 2.6M | 4.4M | 7.5M | $68.7M | одна з найсильніших consumer ніш за growth + monetization |
| `Recovery / Longevity` | 1.8M | 3.4M | 6.2M | $0.7M | попит є, але app-store monetization слабко відображає реальний бізнес |
| `Events / Travel Discovery` | 40.0M | 46.9M | 46.7M | $14.1M | дуже великий user demand на discovery, travel і event behavior |
| `Community / Team Ops` | 16.3M | 16.3M | 16.5M | $4.7M | стабільний, але не вибуховий ринок; це радше utility layer, ніж sexy expansion story |

### Швидкі YoY сигнали

- `Outdoor / Active Travel`: downloads `+22.1%`, потім `+37.7%`
- `Social Sports / Courts`: downloads `+39.8%`, потім `+22.0%`
- `Coaching / Training`: downloads `+68.5%`, потім `+71.4%`
- `Recovery / Longevity`: downloads `+90.1%`, потім `+82.8%`, але revenue в app store падає
- `Community / Team Ops`: майже flat по downloads

---

## 6. Key App Readout

### Outdoor / Active Travel

| App | 2025-2026 Downloads | 2025-2026 Revenue | Signal |
|---|---:|---:|---|
| `Strava` | 59.95M | $189.57M | already massive platform with global demand and strong monetization |
| `AllTrails` | 15.70M | $76.03M | outdoor discovery / trail utility is very real and strongly monetized |
| `komoot` | 8.10M | $35.29M | paid route-planning layer is proven |
| `Wikiloc` | 4.54M | $9.74M | user-generated trail library also has paid demand |
| `Outdooractive` | 1.14M | $3.94M | smaller niche, but professional outdoor planning clearly exists |

#### Key comments to keep

- `AllTrails` and `komoot` are not tiny niche apps. They are real, scaled consumer products.
- `AllTrails` is stronger in `discovery + trust + safe trail usage`.
- `komoot` is stronger in `planning + route utility + premium planning value`.
- `Wikiloc` and `Outdooractive` show there is room for multiple subpositions inside outdoor, not just one winner.

#### Geo pattern

- `Strava`: strongest downloads in `ID`, `BR`, `US`, `PH`, `IN`; strongest revenue in `US`, `GB`, `FR`, `DE`, `AU`
- `AllTrails`: strongest in `US`, then `GB`, `FR`, `ZA`, `CA`
- `komoot`: strongest in `DE`, `FR`, `IT`, `NL`, `GB`
- `Wikiloc`: strongest in `ES`, `IT`, `BR`, `MX`, `CO`
- `Outdooractive`: strongest in `DE`, then `IT`, `GB`, `FR`, `CH`

#### Interpretation for Strava

This is one of the strongest external validations for **Strava Escapes / Active Travel**:

- market exists
- users download these products at scale
- users pay for outdoor utility
- demand is geographically diverse, not only US-only

---

## 7. Coaching / Training

| App | 2025-2026 Downloads | 2025-2026 Revenue | Signal |
|---|---:|---:|---|
| `Runna` | 6.61M | $56.05M | breakout winner; strongest proof that guided training is hot |
| `TrainingPeaks` | 0.36M | $6.96M | smaller but highly monetized pro-grade training niche |
| `GOWOD` | 0.31M | $4.44M | mobility / performance add-on monetizes surprisingly well |
| `CoachNow` | 0.15M | $0.48M | coach workflow exists but is smaller |
| `Recover Athletics` | 0.02M | $0.12M | recovery add-on exists, but not breakout |

#### Key comments to keep

- `Runna` is the clearest single proof in this dataset that **coaching / training guidance is accelerating**.
- `TrainingPeaks` shows that smaller specialized products can monetize very deeply.
- This is a much stronger numeric signal than a vague "AI coach" argument without market evidence.

#### Interpretation for Strava

This strongly validates:

- `Coach Marketplace`
- `Guided Training`
- `AI Coach / Performance Plans`

If the team wants a direction with very strong **consumer willingness to pay**, this cluster is one of the best supported.

---

## 8. Social Sports / Courts

| App | 2025-2026 Downloads | 2025-2026 Revenue | Signal |
|---|---:|---:|---|
| `Playtomic` | 3.43M | $2.80M | strongest category proof for padel / courts |
| `CourtReserve` | 0.47M | $0 | bookings/ops utility clearly used |
| `MATCHi` | 0.26M | $0 | niche but persistent |
| `Pickleheads` | 0.20M | $0.04M | pickleball layer is emerging |
| `PlayYourCourt` | 0.005M | $0.08M | tiny downloads, but still monetized |

#### Key comments to keep

- `Social sports / courts` is much smaller than outdoor or coaching, but it is **one of the fastest-growing clusters** in the pack.
- `Playtomic` is the strongest proof that court booking + player ecosystem can work.
- The low app-store revenue here likely understates the business, because marketplace, booking and off-app flows may dominate.

#### Interpretation for Strava

This validates `Strava Courts / Padel-Tennis Layer` as:

- not the safest main bet
- but a very legitimate **timely non-obvious candidate**
- especially good if the team wants a differentiated jury story

---

## 9. Recovery / Longevity

| App | 2025-2026 Downloads | 2025-2026 Revenue | Signal |
|---|---:|---:|---|
| `Oura` | 3.40M | $0 | huge demand, but monetization happens outside app stores |
| `WHOOP` | 2.70M | $0 | strong demand, same caveat |
| `Eight Sleep` | 0.025M | $0.64M | premium sleep/recovery willingness to pay exists |
| `HRV4Training` | 0.020M | $0.11M | niche but real |
| `Biostrap` | 8 | $278 | tiny / fading |

#### Key comments to keep

- This cluster shows **consumer interest is real**, because downloads are growing quickly.
- But it also shows the category is **hardware-led and ecosystem-led**, not simple app-led monetization.
- So a pure `Strava readiness score` needs careful framing: it may become an add-on feature, not a category-defining standalone wedge.

#### Interpretation for Strava

This cluster supports:

- `Recovery / Longevity`

but mostly as:

- retention / premium feature
- secondary layer

not as the cleanest main expansion market.

---

## 10. Events / Travel Discovery

| App | 2025-2026 Downloads | 2025-2026 Revenue | Signal |
|---|---:|---:|---|
| `GetYourGuide` | 17.52M | $0 | very strong travel planning demand |
| `Fever` | 11.40M | $0 | event discovery behavior is huge |
| `Eventbrite` | 9.28M | $0 | registrations and event search are large-scale behavior |
| `Meetup` | 4.89M | $14.11M | community + event coordination monetizes |
| `Viator` | 3.61M | $0 | paid activities / tours category is real |

#### Key comments to keep

- Discovery and booking behavior around experiences is large.
- The app-store revenue numbers here undercount the real businesses, because much of the revenue is probably processed elsewhere.
- This is useful not because `Strava` should become `Eventbrite` or `Viator`, but because it shows **people already use apps to discover and coordinate real-world experiences**.

#### Interpretation for Strava

This strengthens:

- `Strava Escapes`
- `Local Experiences`
- `Race & Event Marketplace`

especially where the story is about:

- discovery
- coordination
- real-world participation

---

## 11. Community / Team Ops

| App | 2025-2026 Downloads | 2025-2026 Revenue | Signal |
|---|---:|---:|---|
| `GroupMe` | 10.02M | $0 | communication layer has scale |
| `Spond` | 2.39M | $0 | team coordination is useful but utility-like |
| `TeamSnap` | 1.62M | $3.80M | team management monetizes, but not explosively |
| `SportsEngine` | 0.99M | $0 | durable but not breakout |
| `Heja` | 0.79M | $0.91M | smaller but monetized |

#### Key comments to keep

- This cluster is stable and real, but it does **not** show breakout consumer excitement.
- It is more a proof of ongoing utility than of a big new market story.

#### Interpretation for Strava

This gives some support to:

- `Club OS`
- community organizer tools
- school / team coordination

But it does **not** look like the strongest flagship expansion wedge.

---

## 12. Nutrition / Calorie Counter

> ⚠️ **Окремий тип експорту.** Nutrition apps присутні тільки у Revenue-файлах, але відсутні у Downloads-файлах ментора. Нижче — revenue-only дані.

| App | Rev 2023-24 | Rev 2024-25 | Rev 2025-26 | YoY |
|---|---:|---:|---:|---:|
| `MyFitnessPal` | $185.5M | $389.6M | $381.8M | -2% (plateau) |
| `AI Calorie Tracker by Yazio` | $32.7M | $98.4M | $130.9M | +33% |
| `Cal AI` | $0 | $21.2M | $57.4M | **+172%** |
| `Lose It!` | $33.6M | $73.4M | $56.3M | -23% |
| `Foodvisor` | $2.9M | $26.8M | $40.5M | +51% |
| `Calorie Counter+` | $14.5M | $35.3M | $36.3M | +3% |
| `MyNetDiary` | $7.0M | $19.1M | $31.4M | +64% |
| `BitePal` | $0 | $2.4M | $23.9M | **+897%** |
| `Noom` | $19.4M | $25.3M | $22.2M | -12% |
| `Cronometer` | $3.9M | $13.6M | $21.8M | +61% |
| `Calo` | $0 | $0.3M | $9.4M | **+2850%** |
| `Fitia` | $1.6M | $5.5M | $9.2M | +66% |
| **КЛАСТЕР TOTAL** | **$301.1M** | **$714.0M** | **$833.2M** | **+17%** |

#### Key comments to keep

- **Найбільший revenue-кластер у всьому датасеті** — у 2.5x більший за Outdoor/Active Travel ($326.6M).
- Revenue зріс на **+137% за 2 роки** ($301M → $833M).
- **AI-хвиля re-disrupting ринок:** Cal AI ($0→$57M за 2 роки), Calo (+2850%), BitePal (+897%) — нові entrants швидко відбирають долю у MyFitnessPal.
- MyFitnessPal плато (-2%) — incumbents вразливі до AI-нативних конкурентів.
- Downloads-дані для цього кластера відсутні в пакеті ментора (revenue-only export).

#### Interpretation for Strava

- **💬 Ментор (19 Apr 2026):** «Я би нутрішн і калорі каунтери не викидав би з шорт ліста, бо по вигрузці там хороший ринок по грошах в апках».
- Strava має calorie burn з activity data — природна adjacency до food tracking.
- Ризик: MyFitnessPal dominant, but AI disruption creates a wedge.
- Verdict: **CONSIDER** — не top shortlist, але не kill.

---

## 13. What These Data Say About The Main Hypotheses

### 1. `Strava Escapes / Active Travel`

**Very strongly supported by data.**

Why:

- `AllTrails`, `komoot`, `Wikiloc`, `Outdooractive` all show real scale
- outdoor utility is monetized
- travel/event discovery apps also show adjacent behavior at scale
- geographic spread is broad enough to support a global story

Best reading:

- this is not a fantasy niche
- this is one of the cleanest external validations for a `Strava` expansion story

### 2. `Coach Marketplace / Guided Training / AI Coach`

**Also strongly supported by data.**

Why:

- `Runna` is exploding
- `TrainingPeaks` monetizes deeply
- users pay for guidance, not only for tracking

Best reading:

- probably one of the strongest monetization-supported consumer adjacencies
- stronger numerically than many softer “coach marketplace” narratives without data

### 3. `Strava Courts / Social Sports`

**Supported as a smaller but fast-growing niche.**

Why:

- `Playtomic` growth is real
- supporting apps exist across padel / tennis / pickleball

Best reading:

- very good non-obvious bet
- probably not the safest main direction
- very strong as mentor discussion candidate

### 4. `Recovery / Longevity`

**Demand exists, but business logic is more complicated.**

Why:

- downloads are growing quickly
- monetization in these data is weak because the category is hardware-led

Best reading:

- strong signal for feature-layer / premium-retention logic
- weaker signal for standalone new market wedge

### 5. `Nutrition / Calorie Counter`

**Largest revenue cluster in the dataset — strongly supported by data, but fit is a question.**

Why:

- `$833.2M` total revenue 2025-26 — the single largest revenue cluster
- AI disruption is happening: `Cal AI` ($0→$57M in 2 years), `Calo` (+2850%), `BitePal` (+897%)
- Mentor explicitly said: keep on shortlist
- Strava has activity-based calorie burn data — natural adjacency

Best reading:

- this is not a weak market — it is the biggest revenue market in this dataset
- the fit question (endurance DNA dilution) is real but the AI angle changes the equation
- best framed as **activity-correlated nutrition / fueling layer**, not generic calorie counter
- **verdict: CONSIDER**, not kill

---

### 6. `Corporate Wellness / Strava for Work`

**These CSV do not validate it well.**

Why:

- the dataset is much richer in consumer mobile comparables than in enterprise wellness platforms
- community/team apps exist, but they do not directly prove B2B wellness demand

Best reading:

- if the team wants to defend `Corporate Wellness`, it needs other sources:
  - `PitchBook`
  - `Crunchbase`
  - `CB Insights`
  - `Owler`
  - enterprise case evidence

---

## 14. Current Ranking Based On These Data

If we rank only by what this paid-tools dataset validates best:

1. **Strava Escapes / Active Travel** — $326.6M · DL 91.7M · YoY +38%
2. **Coaching / Guided Training / AI Coach** — $68.7M · DL 7.5M · YoY +71%
3. **Nutrition / Calorie Counter** — $833.2M · YoY Rev +17% · AI re-disruption
4. **Strava Courts / Social Sports** — $2.9M in-app (GMV >> app-store) · fastest-growing
5. **Race / Event / Local Experiences** — 46.7M DL · $14.1M in-app (off-app GMV massive)
6. **Recovery / Longevity** — demand exists, monetization hardware-led
7. **Corporate Wellness / B2B Work** — цим датасетом не валідується

Important nuance:

- `Nutrition` має найбільший revenue-кластер — але fit питання відкрите (ментор: CONSIDER)
- `Corporate Wellness` may still be strategically smart — but **this specific dataset** does not give it proof
- `Courts` has the fastest growth rate despite small absolute numbers

---

## 14. Recommended Use In The Project

### Use this dataset to say:

- outdoor planning and outdoor discovery are real paid markets
- coaching and guided performance are one of the hottest adjacent spaces
- social sports are smaller but fast-growing and timely
- recovery is real, but more ecosystem- and hardware-driven than simple mobile-subscription-driven

### Do not overclaim from this dataset:

- that corporate wellness is already proven as the best expansion path
- that zero mobile revenue means a product is weak
- that the biggest download category is automatically the best strategic fit for `Strava`

---

## 15. Bottom Line

The lecturer's paid-tools market data most strongly support this conclusion:

**If the team wants the cleanest consumer market validation, the strongest data-backed bets are `Active Travel / Escapes` and `Coaching / Guided Training`, with `Strava Courts` as the best non-obvious niche.**

And one more important line to keep with the slides:

**These data validate where users already show demand and willingness to pay. They do not replace strategic judgment about where Strava has the best right to win.**
