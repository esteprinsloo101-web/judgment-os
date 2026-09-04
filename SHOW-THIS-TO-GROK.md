# SHOW THIS FILE TO GROK

You are looking at **Judgment OS**, Este Prinsloo's South African household decision app.
Este wants you to *see the app*, then improve or operate it. Read this whole file before changing anything.

## Open these first

- Live app: https://esteprinsloo101-web.github.io/judgment-os/
- Source (the whole app is ONE file): https://raw.githubusercontent.com/esteprinsloo101-web/judgment-os/main/index.html
- Repo: https://github.com/esteprinsloo101-web/judgment-os
- GitHub user: esteprinsloo101-web
- X: @EP19880205
- Timezone: Africa/Johannesburg

If the live Pages URL still looks like a beige Georgia 3-tab stub titled "household decision desk", that is a **CDN cache of an old file**. The real app is the 30KB dark `index.html` on `main` (commit `92552e4`, Pages deploy run 7 succeeded 4 Sep 2026 09:03 SAST). Hard-refresh or read the raw file.

## What the product is

Not a news site. Not a flood map (that is AEGIS Floodwatch). Not RandRadar groceries.

Judgment OS collects intelligence across economic, social, environmental, finances, risks, safety, government and world events, then turns it into a **same-day household call**: HOLD / BUY / SAVE / WAIT / FILL.

It must help ordinary people:
- budget and see the squeeze (visuals, not essays)
- save money (fuel-fill maths, envelope bars, shop-split only if already passing the door)
- make better life decisions
- get deals and safety for **where they are standing now**, not only where they live

Example of the original brief: when diesel is about to rise, tell people to fill. As of 4 Sep 2026 the September hike is **already on the pump**, so the call flipped to HOLD extra litres and watch the next DMPR cycle on **7 Oct 2026**.

Este is often in Stellenbosch / Cape Town / Western Cape. IP may also show Fraserburg, Northern Cape (inland prices). Locator must follow the GPS pin that day.

## App map (bottom nav)

Single-file HTML + inline CSS/JS. Fonts: Sora + Fraunces. Leaflet map from unpkg. Dark theme `#07090d` / lime `#d4ff4a` / mint `#3ee0a4`.

1. **Today** — HOLD stamp, fuel pulse bars, KPI chips, today's board, "if you move now"
2. **Near me** — GPS + Leaflet. Deals filtered by current city + time of day. Coastal vs inland fuel zone from the pin.
3. **Money** — donut + envelopes (income, rent, food, fuel, utilities, kids, debt) in localStorage. Fuel-fill calculator. Save cards.
4. **Intel** — filter chips + cards with section, DO line, depth paragraph, source
5. **Calls** — private decision journal in localStorage
6. **Bots** — shop desk showing automations (humans only paste)
7. **Pay** — Paystack tiers

Defaults on Money tab (editable): take-home R28,000 · rent R8,500 · food R6,200 · fuel R2,800 · electricity+data R1,900 · school R2,200 · debt R1,500.

## Paystack only (never Payoneer, never Stripe, never bank numbers)

| Desk | Price | URL | Status |
|---|---|---|---|
| Street brief | R0 | live site | shipped |
| Household | R89 | https://paystack.com/pay/judgment-os-desk | LIVE page |
| Command | R249 | https://paystack.com/pay/judgment-os-command | linked in app, page may 404 |
| Family | R489 | https://paystack.com/pay/judgment-os-family | 404 as of 4 Sep 2026 |

Until Command/Family exist in the Paystack dashboard, send buyers to the R89 slug only.
Paystack connection on Este's Grok account is Composio, default alias `za-test` (TEST mode). Test card: `4084 0840 8408 4081` / `08/27` / `408`.
Flip live + KYC when real rand should settle T+1/T+2 to a SA bank.

## Snapshot baked into the app (4 Sep 2026)

- Petrol 95 inland R26.92 / coastal R26.05 (▲ R1.34 from 2 Sep)
- Diesel 0.05% wholesale inland R29.11 / coastal R28.24 (▲ R2.94)
- Diesel 0.005% inland R30.05 (▲ R3.15)
- 50 L inland diesel fill ≈ R1,456
- Slate levy 83.28c/l (adding, not cushioning)
- Next official DMPR cycle: 7 October 2026. Mid-month CEF tracking ~14 Sep onward.
- USD/ZAR ~16.01 · SARB repo 7.00% · prime 10.50% · CPI ~4.3% Jul · next MPC 23 Sep
- Eskom +8.76% from 1 Apr · municipal +9.01% from 1 Jul · Homelight 60A ~343.61c/kWh
- Cape Town 4 Sep: 11–14°C, SE wind 40–56 km/h
- Grocery windows to 6 Sep: Shoprite whole chicken R49.99/kg; Checkers pork chops R58.99/kg; Fair Cape milk 2L R29.99; PnP jumbo eggs 18s R24.99

Cities in the locator table: Cape Town, Stellenbosch, Somerset West, Bellville, Paarl, Durban, Gqeberha (coastal); Johannesburg, Pretoria, Bloemfontein, Kimberley (inland). **Fraserburg / Karoo is missing — add inland fallback when GPS is in Northern Cape.**

## Bots that already run the shop (draft only, do not post or email-send)

- Judgment OS morning desk — 07:00 SAST — task `65dc2f9f-cf95-4223-8743-17cfe1924690`
- Judgment OS marketing desk — 07:10 SAST — task `3aad0fc2-56e1-4839-8cfd-4d63379c7b8f`
- Evening sales still on generic 19:00 self-serve pack — task `e6ec264c-f95b-43f7-8d19-38e8bc48282c` (mentions this product; a dedicated 19:10 Judgment OS sales bot may still be missing)

Do not invent revenue. Do not publish bank account numbers. Do not use Stripe. Este has a day job — bots draft, she pastes after work.

## How to change the app

1. Edit `index.html` only (keep it self-contained so Pages cannot 404 assets).
2. Keep `.github/workflows/pages.yml` and `.nojekyll`.
3. Commit to `main`. Pages source is GitHub Actions.
4. Never split CSS/JS into `/assets` unless you also commit those files.
5. Update the snapshot numbers from official DMPR/CEF/SARB/SAWS — do not invent prices.

## Honest limits

- Curated snapshot, not a live government API
- Not financial, legal or medical advice
- Paystack may still be test-mode
- Flood / GLOF maps belong on AEGIS Floodwatch, not here

## What Este asked for (do not drop these)

- Full attractive app worth paying for, lots of visuals, not walls of text
- In-depth intelligence, not simple Q&A
- Locator for where you ARE during that time
- Budget planning + save money + better life decisions
- Whole business managed by bots including marketing and sales
- Paystack (updated from Payoneer)

## First message Este can paste into a new Grok chat

```
This file is the handoff for Judgment OS.
Live: https://esteprinsloo101-web.github.io/judgment-os/
Source: https://raw.githubusercontent.com/esteprinsloo101-web/judgment-os/main/index.html
Repo: https://github.com/esteprinsloo101-web/judgment-os
Read SHOW-THIS-TO-GROK.md in that repo, then open the raw index.html.
Do not rebuild from the old beige stub. Improve the dark 7-tab desk already on main.
Paystack R89 only is live: https://paystack.com/pay/judgment-os-desk
```
