# GROK BOT BRIEF — Judgment OS

Paste this file into a Grok chat, or give Grok these two URLs:

1. This brief: https://raw.githubusercontent.com/esteprinsloo101-web/judgment-os/main/GROK-BOT-BRIEF.md
2. The app source (open this to *see* the app): https://raw.githubusercontent.com/esteprinsloo101-web/judgment-os/main/index.html

Live site: https://esteprinsloo101-web.github.io/judgment-os/
Repo: https://github.com/esteprinsloo101-web/judgment-os

If Pages still shows the old 3-tab stub, trust **index.html on main** (about 30 KB). That is the real app. Open the raw HTML in a browser to demo it offline.

---

## Who and what

Operator: Este Prinsloo, South Africa (Stellenbosch / Western Cape / often travelling). Day job. X @EP19880205. GitHub `esteprinsloo101-web`.

**Judgment OS** is a household command desk. It collects public intelligence (economic, social, environmental, finances, risks, safety, government, world events) and turns it into one same-day call: FILL / WAIT / BUY / HOLD / SAVE. It is not a flood map (that is AEGIS Floodwatch) and not a grocery-only board (that is RandRadar).

Promise: help ordinary people budget, save money, and make better life decisions. Visual-first. Short lines. No essays.

## What the shipped app contains

Single file: `index.html` (CSS + JS inlined). GitHub Pages. No build step. Leaflet map from CDN. Journal + budget numbers live in `localStorage` on the phone.

Bottom nav:

| Tab | id | What it does |
|---|---|---|
| Today | `today` | Act-now stamp (HOLD/BUY/SAVE), fuel pulse bars, KPI tiles, today board |
| Near me | `locate` | GPS locator. Deals follow **where you are now**, not home town. Coastal vs inland fuel. Leaflet map |
| Money | `money` | Envelope budget donut, fuel-fill maths, electricity shock, save hints |
| Intel | `intel` | Filterable cards: economic / social / environmental / finances / risks / safety / government / world |
| Calls | `journal` | Private decision journal |
| Bots | `bots` | Business desk: morning intel, marketing, sales |
| Pay | `pay` | Paystack tiers |

Title in source: `Judgment OS — see it. call it. keep the rand.`
H1: `See the shock. Make the call. Keep the rand.`

## Payments — Paystack ZAR only

- Working checkout: https://paystack.com/pay/judgment-os-desk — **R89 Household**
- Linked but pages were 404 on 4 Sep 2026: `judgment-os-command` (R249), `judgment-os-family` (R489)
- Until those slugs exist, send buyers to the R89 page
- Test card (test mode): `4084 0840 8408 4081` / `08/27` / `408`
- Never Payoneer on this product. Never Stripe. Never print bank account numbers
- Same rail style as AEGIS Floodwatch Science Desk (also Paystack R89)

## Snapshot baked into the app (4 Sep 2026)

- Petrol 95 inland **R26.92** / coastal **R26.05** (▲ R1.34 from 2 Sep)
- Diesel 0.05% wholesale inland **R29.11** / coastal **R28.24** (▲ R2.94)
- Diesel 0.005% inland **R30.05**
- Next official DMPR cycle: **7 October 2026**
- Slate levy 83.28c/l — adding to the pump, not cushioning
- USD/ZAR ~15.98–16.01 · SARB repo **7.00%** · prime **10.50%** · CPI **4.3%** (Jul)
- Next MPC: 23 Sep 2026
- Eskom +8.76% from 1 Apr · municipal +9.01% from 1 Jul
- Act-now: **do not panic-fill** (hike already live). Buy Cape grocery window (chicken / milk / prawns) before **6 Sep** if you are already in that store

## Bots that run the shop (draft only — no post, no email-send)

- Judgment OS morning desk — 07:00 Africa/Johannesburg
- Judgment OS marketing desk — 07:10 SAST (X + WhatsApp + IG drafts)
- Evening sales pack — 19:00 / 19:10 SAST
- Paid rail in bot copy: Paystack R89 only. Never invent a sale. Unknown cash = R0

## Rules for any Grok that edits this product

1. Keep it one self-contained `index.html` so Pages cannot 404 assets
2. Locator must use GPS *now-location*, not only home (Stellenbosch / Fraserburg / Cape Town can all be the pin)
3. Visuals over paragraphs. One DO per intel card
4. Do not invent official fuel or grocery prices. If DMPR/CEF has gazetted a number, use that
5. Do not mix in AEGIS flood maps, RandRadar flights, MONTHFILE, Jories, Eco Rehab, or Verdict retainers
6. Not financial, legal or medical advice
7. Este has a day job. Bots draft. Humans paste after work. Do not spend ads unless she asks
8. If you change copy, keep Afrikaans-friendly plain English

## What Este may ask you to do next

- Refresh the board after 7 Oct fuel cycle
- Create missing Paystack Command R249 and Family R489 pages, then point the Pay tab at live slugs only
- Flip Paystack from test to live after KYC
- Deepen budget (goals, sinking funds) without turning it into a bank app
- Add more cities/deals on the locator without fake prices

## Sibling products (do not merge)

- AEGIS Floodwatch: https://esteprinsloo101-web.github.io/aegis-floodwatch/
- RandRadar: https://esteprinsloo101-web.github.io/randradar/

Prototype for Este Prinsloo. Public data stays under its own licences.
