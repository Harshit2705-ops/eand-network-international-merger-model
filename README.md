# e& / Network International: Merger Consequences and EPS Accretion/Dilution Model

An Excel merger model that tests one question: **if e& (Emirates Telecommunications Group, ADX: EAND) bought Network International, would its earnings per share go up or down?**

Everything is formula-driven. Change one input on the Assumptions tab and every other tab updates.

> **Illustrative only.** This is a hypothetical deal built for learning and portfolio purposes. Network International is owned by Brookfield and is not for sale. e& has not proposed this deal. Target figures are my own estimates. This is not investment advice.

**Currency:** AED million unless stated (USD/AED peg 3.6725)
**Prepared by:** Harshit Maheshwari, November 2026

---

## The deal idea

- **Acquirer:** e&, a listed UAE telecom and technology group. Inputs use e& FY2025 reported figures (share price, shares, net income, EPS).
- **Target:** Network International, a UAE payments processor.
- **Why it could make sense:** e& gets an owned payments backbone for its e& money and fintech push.
- **Funding mix:** 40% cash on hand, 40% new debt, 20% new e& shares.

## What is in the workbook

| Tab | What it does |
|---|---|
| Cover | Deal summary, how to use the model, sources, disclaimer |
| Assumptions | All inputs: acquirer data, target estimates, deal terms, purchase price allocation, synergies. Blue = input, yellow = key lever |
| Sources & Uses + PPA | Where the money comes from and goes, new shares issued, goodwill and intangibles, implied deal multiples |
| Accretion-Dilution | Pro forma net income bridge, pro forma share count, GAAP and cash EPS, breakeven synergies |
| Sensitivity | Two grids: synergies vs % stock, and purchase price vs % stock |

## Base case results

| Item | Result |
|---|---|
| Offer equity value | AED 12,120m (about USD 3.3bn) |
| Enterprise value | AED 13,222m |
| EV / EBITDA paid | 16.4x |
| P/E paid (offer value / target net income) | 36.6x |
| e& own P/E | 13.1x |
| Total uses (price + fees) | AED 12,300m |
| New debt raised | AED 4,848m |
| New e& shares issued | 116.5m |
| Goodwill / amortizable intangibles | AED 5,952m / AED 3,968m |
| Standalone EPS | AED 1.584 |
| Pro forma EPS (GAAP) | AED 1.530, **3.5% dilutive** |
| Pro forma EPS (cash, amortization added back) | AED 1.571, **0.9% dilutive** |
| Pre-tax synergies needed for GAAP breakeven | about AED 906m, vs AED 200m assumed |

## Main takeaways

- **The deal is dilutive in the base case.** e& pays about 37x earnings for a target, while its own shares trade at about 13x. That gap drives the result.
- **Synergies do not fix it.** Breakeven needs about 4.5x the synergies assumed. That is unrealistic for a payments business joining a telecom group.
- **Much of the damage is accounting.** Intangible amortization is the biggest drag. On a cash EPS basis dilution shrinks to under 1%.
- **Using less stock helps.** e& shares are cheap relative to earnings, so paying in stock gives away more earnings than the debt costs. The 0% stock column is the least dilutive in the grid.
- **Price matters more than funding mix.** With no stock, moving the offer from USD 2.76bn to USD 4.0bn takes dilution from about -1.8% to about -4.4%. Moving stock from 0% to 40% at the base price only costs about 1 percentage point.

## How the model works

1. **Sources & Uses:** total uses (equity price + fees) are split into cash, new debt and new stock using the % inputs. A check cell proves sources equal uses.
2. **Purchase price allocation:** the excess of price over target book equity is split into amortizable intangibles (40%, over 10 years) and goodwill (not amortized).
3. **Net income bridge:** e& net income + target net income + after-tax synergies - after-tax interest on new debt - after-tax lost interest on cash - after-tax amortization.
4. **EPS:** pro forma net income divided by (existing shares + new shares). Compared with standalone EPS on a GAAP and a cash basis.
5. **Sensitivity:** each grid cell recomputes the full deal for that combination.

## How to use it

1. Open `eand_network_merger_model.xlsx`.
2. Go to **Assumptions**. Change blue cells (inputs) or yellow cells (key levers such as price, funding mix, synergies).
3. Read the result on **Accretion-Dilution**, then stress test it on **Sensitivity**.

## Limits

- Target figures (revenue, EBITDA, net income, net debt, book equity) are estimates anchored to Network International's last public financials and its 2024 take-private value. Replace them with better data if you have it.
- One modelled year only, with 75% of synergies realized. No multi-year projection, no integration costs, no revenue synergies.
- Flat 9% UAE tax rate. Debt cost (5%) and cash yield (4%) are assumptions.
- Real deals add more: break fees, refinancing of target debt, FX, regulatory approvals.

## Sources

- e& FY2025 results / ADX (EAND): price, shares, net income, EPS
- e& USD 5.95bn Vodafone-stake sale (Jul 2026): deal firepower
- Network International FY2022 results: revenue USD 438.4m, +42% net profit
- Brookfield take-private of Network International: GBP 2.2bn / USD 2.76bn, 400p, 64% premium

## Skills shown

Merger modelling, sources and uses, purchase price allocation, EPS accretion/dilution, breakeven analysis, sensitivity analysis, linked Excel formulas.

---

*Learning and portfolio project. Not investment advice.*
