# Europe Trip 2026 — Context & Preferences Handoff

> Paste this document into any AI assistant to give it full context on this trip and how Saurabh likes to travel and work. Written 19 Sep 2026, the day before departure.

## Who is travelling

- **Saurabh Maheshwari** (saurabh95maheshwari@gmail.com), travelling as a couple; **friends join for the Poland leg** (group dynamics OK there).
- Indian passport holder, travelling from India. User locale: India (INR, ₹, metric, dd/mm/yyyy).
- **Budget-conscious but activity-heavy**: cheap stays, cheap eats, but willing to pay for standout experiences (cable cars, a Michelin-Green-Star dinner, caves).

## The trip — fixed facts (do not re-plan around these)

- **Dates:** 20 Sep 2026 (Sunday) evening – 7 Oct 2026 (Wednesday). 18 days.
- **Booked flights:** arrive Copenhagen ~19:00 on Sun 20 Sep; fly CPH → Krakow (KRK) morning of Wed 23 Sep; **depart Vienna Wed 7 Oct** (flight time TBC — assumed ~afternoon).
- **Booked stays:** Copenhagen 3 nights (20–23 Sep), Zakopane 2 nights (23–25 Sep), Krakow 2 nights (25–27 Sep). Everything after 27 Sep is unbooked (as of 19 Sep).
- **Core requirement from the start:** "23rd morning leaving for Krakow and go straight to Zakopane, and 25th back to Krakow."

## Route chosen

Copenhagen (3N) → Zakopane (2N, with a **Slovakia day trip on Fri 25 Sep**) → Krakow (2N) → **overnight FlixBus Krakow→Ljubljana Sun 27 Sep** (saves a hotel night; no direct flights exist) → Ljubljana base (5N: Bled, Bohinj, Postojna/Škocjan day trips) → Zagreb (3N: Plitvice + Rastoke day trip) → Vienna (2N) → fly out 7 Oct.

This was picked from an explicit choice: **"Balanced: 1 day Slovakia + 3–4 days Slovenia + 2 days Croatia."** A parallel Claude-generated planner proposed Bratislava (1N) + Piran/coast instead of Croatia; that variant is documented in the webapp as an option but the Croatia shape was the user's pick.

## Dietary requirements

**Vegetarian, dairy & eggs fine** (confirmed by Saurabh directly in conversation). Note: his other planner (Claude file) assumed **strict veg, no egg** — if he says "no egg," egg hides in dumpling dough, breading, custard, Danish pastries. Phrase card (in webapp): "Jestem wegetarianinem" (PL), "Jeg er vegetar" (DK), "Ich bin Vegetarier/in" (AT); no-egg: "bez jajek" (PL), "brez jajc" (SI), "ohne Ei" (AT/DE), "uden æg" (DK).

## What "a good plan" means to him (style preferences)

1. **Detailed day-by-day itineraries** with day trips, day plans, places to eat, must-visits.
2. **Traveller vibe:** hidden gems, waterfalls, offbeat finds — not just the top-10 list. Party/nightlife per city included.
3. **Hikes** ranked with effort/entry fees; relaxed café/walking-tour days to balance.
4. **Public transport ONLY** — no taxis required (Bolt in Krakow optional). Every leg must be a real bus/train/metro with times and prices.
5. **Live checks:** verify transport, opening days and restaurant status against travel blogs, Reddit, Google-review content and official operator pages (2024–2026 sources). Flag anything unverified.
6. **Country-wise coverage filter** — what's covered vs what's skipped and why.
7. **Output: self-contained HTML** (his format reference is his Vietnam trip planner — day cards, accordion food sections, sticky nav). He also likes INR (₹) alongside EUR.
8. **Apps:** wants country-specific app recommendations (transit, buses, hikes, food) — verified current.

## Privacy rules (explicit user requirement)

**"Sensitive information should not go anywhere."** Flight details, bookings, insurance, passport/visa numbers must never be sent to external services or embedded in web searches. Research queries use generic city/transport terms only. The planner HTML contains a blank "Your bookings & documents" template for him to fill locally.

## Urgent bookings (as of 19 Sep)

1. Auschwitz-Birkenau timed pass for Sun 27 Sep (visit.auschwitz.org; no on-site sales since Mar 2026; English tours sell out).
2. Krakow→Ljubljana overnight FlixBus N917, Sun 27 Sep (~€45–50).
3. Ljubljana (5N), Zagreb (3N), Vienna (2N) stays.
4. Zagreb→Vienna EC "Croatia" train (07:25→14:07, from €29.90, oebb.at).
5. Plitvice timed ticket (Sun 4 Oct, €23, official webshop).
6. Postojna (~€30) or Škocjan (~€23) cave ticket; Vintgar time slot (~€10–15, vintgar.si).

## Established live-checked facts (2024–26 sources; re-verify day-of)

- Tivoli Copenhagen summer season ends ~20 Sep (Halloween season from 2 Oct); Vogel cable car (Bohinj) **closed 21 Sep–end Nov**; Kasprowy open (129–165 PLN).
- New direct Zakopane↔Poprad cross-border bus since Jan 2026 (4×/day; 07:30 out; A15 back from Starý Smokovec 15:17) — the Slovakia day hinges on it.
- Vienna S-Bahn main line closed Sep 2026–Oct 2027: airport = ÖBB Railjet/REX from Hauptbahnhof (~€5.40, 15–18 min); "CAT" is a bus replacement.
- Denmark's DOT Tickets app retired → **Rejsebillet** app; Copenhagen Card now digital-only via its app. GetByBus rebranded to Traveling.com. Komoot effectively paid for new users; **Mapy.com** is the free hiking map. HappyCow free on Android since Dec 2025.
- No direct KRK→LJU flights; overnight FlixBus is the budget route. Only one direct Zagreb–Vienna train/day.
- Nishta Zagreb closed since 2017 (still listed by old blogs). Gujžina Ljubljana possibly still temporarily closed — verify. Metelkova quiet Sun–Wed without listed events. Kødbyen (CPH) closed Sun–Wed.

## Deliverables so far

1. `europe-trip-planner-sept-oct-2026.html` — v1: full day-by-day plan.
2. `europe-trip-planner-v2-sept-oct-2026.html` — v2: + hidden gems, hikes/waterfalls table, nightlife per city, apps section, interactive country-wise coverage filter.
3. `index.html` + `sw.js` — **iOS webapp** (v2 content): Safari/iPhone/iPad responsive, Add-to-Home-Screen PWA (icon, standalone, dark-mode aware), service worker for offline use once hosted (Netlify Drop / GitHub Pages). Includes Claude-planner merges: Vogel-closure fix, no-egg phrases, extra Copenhagen veg spots (Foodie, Hija de Sanchez, Mother), INR budget line, alternative Bratislava+Piran route box.
4. This file.

## Trip skeleton (summary)

- Day 1 Sun 20 Sep — arrive CPH ~19:00, Nyhavn evening, optional Tivoli (last day of season)
- Day 2 Mon 21 — CPH classics + Nørrebro offbeat (Jægersborggade, Assistens, Superkilen) + CopenHill; Reffen dinner
- Day 3 Tue 22 — Kronborg + Louisiana day trip (or Cisternerne / Malmö rain-swap)
- Day 4 Wed 23 — fly CPH→KRK, SKA1 train + bus/train to Zakopane; Krupówki, Gubałówka
- Day 5 Thu 24 — Morskie Oko (+Wodogrzmoty falls; Rusinowa Polana alternative); Termy evening
- Day 6 Fri 25 — Slovakia: 07:30 cross-border bus → Belianska Cave (€15) → Starý Smokovec → Skalnaté Pleso (€34) → 15:17 back → evening bus to Krakow
- Day 7 Sat 26 — Krakow: Wawel, Old Town, Zakrzówek, Kościuszko Mound sunset, Kazimierz + Bernatek bridge; big Saturday night
- Day 8 Sun 27 — Auschwitz-Birkenau; overnight FlixBus to Ljubljana
- Day 9 Mon 28 — arrive Ljubljana, relaxed old-town day
- Day 10 Tue 29 — Bled + Vintgar (lunch: Public & Vegan Kitchen)
- Day 11 Wed 30 — Bohinj + Mostnica Gorge + Slap Mostnica (+Savica; Vogel closed)
- Day 12 Thu 1 Oct — Postojna + Predjama **or** Škocjan Caves (traveller pick); Kino Šiška night
- Day 13 Fri 2 — Šmarna Gora sunrise or Velika Planina (⚠ cable-car maintenance check) → bus to Zagreb; Swanky Monkey night
- Day 14 Sat 3 — Zagreb: Dolac, Upper Town, Mirogoj / Sljeme / Samobor options
- Day 15 Sun 4 — Rastoke (Slunj stop) + Plitvice circuit
- Day 16 Mon 5 — EC train to Vienna (arr 14:07); Café Sperl; Mayer am Pfarrplatz heuriger (Sturm season)
- Day 17 Tue 6 — Schönbrunn, Belvedere, Zaha Hadid library + Prater; Wrenkh dinner
- Day 18 Wed 7 — Railjet to airport, depart

## Open questions / things he may still change

- Egg or no-egg — confirm which one is final.
- Vienna departure flight time (affects Day 18 buffer).
- Whether he hosts the webapp (needed for true offline on iPhone/iPad).
- Budget confirmed in EUR; INR conversion rate should be updated at travel time.
