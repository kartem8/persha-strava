# Strava, AllTrails, komoot, Wikiloc, Outdooractive — короткі продуктові нотатки

Короткий файл для команди: що це за продукти, у чому їхня основна цінність і як вони заробляють.

## Швидко в 5 рядків

| Продукт | Простими словами | Основна цінність | Як заробляє |
|---|---|---|---|
| `Strava` | Соцмережа для активних людей | Записати активність, показати її іншим, змагатись, тримати мотивацію | Freemium + subscription + data/services |
| `AllTrails` | Додаток, щоб знайти хороший трейл і не загубитися | Discovery + planning + safe navigation on trail | Freemium + paid subscription tiers |
| `komoot` | Додаток, щоб добре спланувати outdoor-маршрут | Detailed route planning + offline navigation | Free entry + map purchases + Premium subscription |
| `Wikiloc` | Додаток, щоб знаходити й проходити маршрути, які виклали інші користувачі | Community trail library + navigation utility | Free entry + Premium subscription |
| `Outdooractive` | Додаток для серйозного outdoor planning з офіційними маршрутами і картами | Professional route planning + trusted tourism/outdoor content | Free Basic + Pro / Pro+ subscriptions + premium partner content |

---

## 1. Strava

### Що це таке

`Strava` — це не просто трекер, а радше соціальний шар навколо спорту.
Людина записує пробіжку, поїздку чи іншу активність, отримує статистику, ділиться результатом, змагається в сегментах, сидить у клубах і повертається через community-мотивацію.

### Простою мовою

**`Strava` = "запиши тренування, покажи його іншим і отримай мотивацію рухатись далі"`**

### Основна продуктова цінність

- activity tracking
- social proof
- competition and motivation
- clubs, challenges, leaderboards
- identity for active people

### Як заробляє

- `freemium`
- `subscription` на advanced features
- `Strava Metro` та інші data/services напрями
- sponsored / partner mechanics

### Що важливо для нашого проєкту

`Strava` сильна там, де є:

- social graph
- habit loop
- identity layer
- велика база activity data

`Strava` слабша там, де треба виграти просто через "краще route planning" або "глибшу outdoor utility".

---

## 2. AllTrails

### Що це таке

`AllTrails` — це додаток, який допомагає вибрати куди піти на природу, перевірити чи маршрут нормальний, і пройти його без зайвого стресу.

### Простою мовою

**`AllTrails` = "знайди хороший маршрут і комфортно пройди його"`**

### Основна продуктова цінність

- trail discovery
- community reviews
- planning before going out
- navigation on trail
- safety and confidence

### Як заробляє

Основна модель зараз:

- `Base` — free
- `Plus` — paid annual subscription
- `Peak` — higher paid annual subscription

Тобто головний monetization engine у них — **апсейл із free у paid membership**.

### Що входить у paid

#### Plus

- offline maps
- trail conditions
- wrong-turn alerts
- 3D preview
- live share
- print maps
- ad-free

#### Peak

Усе з `Plus`, плюс більш advanced planning features:

- community heatmaps
- in-app custom routes
- plant identifier / `Outdoor Lens`

Важливий нюанс: частину фіч із початкового `Peak` пізніше перенесли в `Plus`, тому зараз `Peak` більше про advanced planning layer, а не просто про weather.

### Що важливо для нашого проєкту

`AllTrails` сильний у:

- outdoor exploration
- trail discovery
- planning and safety

Тобто це конкурент не в "соціальності", а в **utility before and during the trip**.

---

## 3. komoot

### Що це таке

`komoot` — це додаток для людей, які хочуть не просто знайти трейл, а нормально спланувати маршрут під конкретну пригоду: хайк, велопоїздку, bikepacking або multi-day trip.

### Простою мовою

**`komoot` = "сплануй outdoor-маршрут як слід"`**

### Основна продуктова цінність

- detailed route planning
- sport-specific routing
- offline navigation
- multi-day route logic
- better context for terrain and trip prep

### Як заробляє

У `komoot` змішана модель:

- free entry
- one-time purchase of maps / regions
- `Premium` subscription

Тобто вони заробляють і на **покупці map access**, і на **підписці для більш серйозного use case**.

### Що входить у paid

#### Maps products

- `Single Region`
- `Region Bundle`
- `World Pack`

Це one-time purchases.

#### Premium

- worldwide maps and navigation
- multi-day routes
- personal collections
- live tracking
- weather on route
- sport-specific maps
- 3D maps
- komoot map on Garmin

### Що важливо для нашого проєкту

`komoot` сильний у:

- route planning
- adventure preparation
- outdoor specificity
- multi-day and off-road scenarios

Тобто це дуже сильний proof, що **люди готові платити за planning layer**, а не тільки за activity tracking.

---

## 4. Wikiloc

### Що це таке

`Wikiloc` — це платформа з великою бібліотекою маршрутів від самих користувачів. Її суть у тому, що ти знаходиш чужий маршрут, дивишся деталі, ідеш або їдеш по ньому і за потреби користуєшся навігацією.

### Простою мовою

**`Wikiloc` = "знайди готовий маршрут від інших людей і йди по ньому"`**

### Основна продуктова цінність

- велика база user-generated trails
- navigation for existing routes
- practical utility for outdoor use
- route search and filtering

### Як заробляє

- free entry
- `Premium` subscription

### Що входить у Premium

За наданим командою списком у `Premium` входять:

- navigate other users' trails
- route planner
- peak identifier with augmented reality
- 3D maps
- search by passing area
- send to your GPS
- live tracking
- weather forecast
- ad-free browsing
- specific-member trail search
- advanced filters
- trail lists
- `1% for the Planet` contribution

### Що важливо для нашого проєкту

`Wikiloc` сильний як доказ того, що:

- user-generated trail library має цінність
- navigation utility продається
- люди готові платити за practical outdoor features, навіть без сильного social graph

---

## 5. Outdooractive

### Що це таке

`Outdooractive` — це платформа для планування outdoor-маршрутів, де сильний акцент не тільки на community, а й на офіційних маршрутах, професійних партнерах і туристичному контенті.

### Простою мовою

**`Outdooractive` = "сплануй outdoor-поїздку на основі професійних маршрутів і карт"`**

### Основна продуктова цінність

- route planning
- trusted outdoor and tourism content
- official topo maps
- navigation and offline use
- stronger "professional" feeling for hiking, cycling, mountaineering and similar use cases

### Як заробляє

- `Basic` — free
- `Pro` — paid subscription
- `Pro+` — higher paid subscription
- premium routes and partner content

### Що входить у paid

#### Pro

- official topo maps
- offline maps and routes
- ad-free access
- partner discounts
- more advanced map layers and planning tools

#### Pro+

Усе з `Pro`, плюс:

- premium partner routes
- accurate weather and meteorological info
- snow depth layer
- Flyover previews
- 3D view

### Що важливо для нашого проєкту

`Outdooractive` сильний як доказ того, що:

- outdoor planning можна будувати навколо trusted professional content
- official maps and route quality є окремою paid value
- це ближче до "outdoor planning platform" або "digital tourism utility", ніж до спортивної соцмережі

---

## Головна різниця між ними

### Strava

Сильна в:

- social graph
- motivation
- performance identity
- community

### AllTrails

Сильний у:

- finding trails
- understanding the route
- safe navigation

### komoot

Сильний у:

- planning the route deeply
- preparing for the trip
- multi-day and sport-specific exploration

### Wikiloc

Сильний у:

- user-generated route discovery
- practical navigation utility
- finding and using ready-made trails

### Outdooractive

Сильний у:

- professional and official route content
- trusted maps
- tourism-grade planning utility
- more serious planning for hiking, mountaineering, cycling

---

## Найкоротша версія для слайду

- `Strava` — **запиши активність і поділись нею**
- `AllTrails` — **знайди маршрут і спокійно пройди його**
- `komoot` — **якісно сплануй outdoor-маршрут**
- `Wikiloc` — **знайди готовий маршрут від інших і користуйся ним**
- `Outdooractive` — **сплануй outdoor-маршрут на основі професійних карт і маршрутів**

---

## Чому це важливо для Strava Escapes

- `AllTrails` доводить, що люди цінують **discovery + trust + on-trail utility**
- `komoot` доводить, що люди готові платити за **planning layer**
- `Strava` сама по собі сильна в **social graph + identity + community**

Отже логіка `Strava Escapes` не в тому, щоб зробити "ще один komoot" або "ще один AllTrails", а в тому, щоб поєднати:

- planning
- destination discovery
- social proof
- community identity
- active travel context

в одному Strava-native продукті.
