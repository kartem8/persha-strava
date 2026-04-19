# 🏁 Brief 06 — Dariia · Race & Event Marketplace

**Напрямок:** Race & Event Marketplace — running/cycling race registration & organizer tools
**Конкуренти (3):** `RunSignup` · `Let's Do This` · `Race Roster`
**Формат здачі:** Google Doc (копія цього шаблону), view-access команді
**Презентація:** 10 хв на синку

---

## 📊 Джерела даних

- 🔑 **Основні дані з платних тулів (Google Sheet):** https://docs.google.com/spreadsheets/d/1PIKeeGtfvTssDGK29I6GFOO4A9u1-eiC/edit?gid=257325420#gid=257325420
- 📑 Синтеза аналітики: [Paid_Tools_Market_Data_Synthesis_19April2026.md](../03_synthesis/Paid_Tools_Market_Data_Synthesis_19April2026.md) — §10 Events / Travel Discovery
- 📊 Strava brainstorm xlsx: [strava_brainstorm.xlsx](../03_synthesis/strava_brainstorm.xlsx)
- 🎓 Genesis framework: [Claude_Ready_Genesis_Lectures_Framework_For_Validation.md](../03_synthesis/Claude_Ready_Genesis_Lectures_Framework_For_Validation.md)
- 🆓 Free tools: **SimilarWeb free (ментор прямо підказав, цього досить!)**, Reddit r/running, Crunchbase

---

## 💬 На що звернути увагу (ментор)

- 🔑 **Золота цитата ментора: «фрішного SimilarWeb вистачить».** Твій головний tool — SimilarWeb free: traffic на runsignup.com, letsdothis.com, raceroster.com + conversion-style signals (visit duration, bounce rate).
- **Organizer-side pricing — ключ.** Аналог до TrainingPeaks coach-side (яким займається Олха П): organizer platform платить, не athlete. Розбери organizer tiers, per-registration fees, add-on services.
- ⚠️ **Ризик merge з Артемом (Brief 05, Eventbrite/GetYourGuide).** Перевір overlap: чи race registration = generic event booking? Якщо competitor pools >70% збігаються → сигнал об'єднати Local Experiences + Race & Event в одну ідею.
- **Cluster sizing:** Events / Travel Discovery = $14.1M in-app cluster (переважно Meetup). Race-specific частка невідома — твій desk research має це прояснити.

---

## ✅ Що здавати — структура Google Doc

```
═══════════════════════════════════════════════════════════
Teardown — Race & Event Marketplace
Автор: Dariia
Конкуренти: RunSignup · Let's Do This · Race Roster
Дата: [дата]
═══════════════════════════════════════════════════════════
```

### ──── КОНКУРЕНТ 1: RunSignup ────

**🎯 A1. Product Offering**
- Ключовий user flow (athlete + **organizer flow окремо**):
- Топ-3 фічі, за які платять (organizer-side):
  1.
  2.
  3.
- Hero use-case:

**💰 A2. Модель монетизації**
- Тип: per-registration fee + SaaS + add-ons (timing, fundraising, merch)
- Pricing (organizer): fee-per-registration %, $ minimum, tiered/volume discounts:
- Athlete-side: service fee per registration (typ. $1-3 + %):
- Revenue: SimilarWeb traffic → estimate. Cross-check Crunchbase. In-app у нашій аналітиці може бути відсутній (web-billing):

**👥 A3. Audience & Geo**
- Основна персона (organizer side: race directors, charity coordinators; athlete side: runners/triathletes):
- Топ-5 країн (очікувано US-heavy):
- Traffic/DAU (SimilarWeb):
- Differentiator — чому organizer обирає RunSignup:

### ──── КОНКУРЕНТ 2: Let's Do This ────
*(та сама структура)*
- Особливість: UK-based, athlete-facing discovery-first (schedule all your races), + registration marketplace
- Перевір чи модель orientована athlete-acquisition vs organizer tools

### ──── КОНКУРЕНТ 3: Race Roster ────
*(та сама структура)*
- Особливість: CAN-based, набула ASICS (2018) — часть ASICS RunKeeper-адjacent ecosystem
- Business model: organizer-platform + timing/data services

---

### 🎯 Ключовий insight для Strava (5-7 речень)

- **Overlap зі Strava:** Strava має leaderboards, post-race activity posting, Segments. Чого немає: registration engine, payment flows, organizer tools.
- **Gap — transaction layer:** чи це transaction layer над Strava content (Segments + Challenges → бронюй участь)?
- **Merge question з Артемом:** Eventbrite як general-event platform overlap-иться? Чи Race & Event виправдано окремою ідеєю?
- **Organizer supply:** чи у Strava Clubs уже є race organizers (supply pool для cold-start)?
- **Вердикт:**
  - [ ] ФІЧА — upgrade Segments / Challenges
  - [ ] EXPANSION — transaction marketplace над Strava community
  - [ ] NEW MARKET
  - [ ] **MERGE** — absorb у Local Experiences (Brief 05)
- **Сигнал по L:** UPGRADE / KEEP / DOWNGRADE / KILL / MERGE

---

## 🎤 Презентація на синку — 10 хв

| Хв | Що показати |
|---|---|
| 0-1 | Напрямок + 3 конкуренти |
| 1-6 | Топ-3 insights (особливо organizer-side economics) |
| 6-8 | Overlap зі Strava Segments + merge-сигнал з Артемом + вердикт |
| 8-10 | Q&A |

---

## ⏱️ Timeline

- **День 1-2** — desk research (🚩 **основний тул: SimilarWeb free** за прямою підказкою ментора)
- **День 3** — ключовий insight + вердикт + merge-аналіз з Артемом (sync 15 хв)
- **День 4** — синк: 10-хв презентація

---

## 🧭 Що саме шукати (чекліст)

- [ ] **SimilarWeb free:** runsignup.com, letsdothis.com, raceroster.com — monthly visits, top countries, sources
- [ ] **Conversion proxy:** visit duration, pages/visit, bounce rate — стандартні SimilarWeb метрики
- [ ] RunSignup organizer pricing breakdown (free tier, premium features, per-registration fee %)
- [ ] **Hidden revenue:** timing services, merchandise, fundraising add-ons — не тільки registration fees
- [ ] Let's Do This athlete-acquisition model — чи це discovery-marketplace з revenue через organizers, чи freemium для runners?
- [ ] Race Roster після ASICS acquisition — як змінилась модель? ASICS public — є filings?
- [ ] **Merge-sync з Артемом (Brief 05):** чи Eventbrite забирає race category (так, частково, але smaller races)? Конкретний overlap %?
- [ ] Скільки Strava Clubs уже мають race organizers — supply-side для можливого Strava marketplace
