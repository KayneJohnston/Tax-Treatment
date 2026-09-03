# 4 — Quantitative modelling

Covers brief sections 20, 21, 22, and the three required deliverable tables.

> **These are illustrative calculations, not legal conclusions.** They apply 2026–27 Australian
> rates to a stylised fact pattern and ignore Medicare levy surcharge, HELP repayments, offsets,
> state duties, foreign professional fees and relocation costs. Real numbers require a modelled
> return prepared by a registered tax agent.

---

## 4.1 Rates used

**Australian residents, 2026–27** (the second bracket fell from 16% to 15% under the *Treasury
Laws Amendment (More Cost of Living Relief) Act 2025*):

| Taxable income | Rate |
|---|---|
| $0 – $18,200 | Nil |
| $18,201 – $45,000 | 15% |
| $45,001 – $135,000 | 30% |
| $135,001 – $190,000 | 37% |
| $190,001 + | 45% |

Plus **Medicare levy 2%**. A part-year resident's tax-free threshold is **$13,464 + $395 per month
of residency**; the Medicare levy is exempt for the foreign-resident portion of the year.

**Foreign residents, 2026–27:**

| Taxable income | Rate |
|---|---|
| $0 – $135,000 | **30%** |
| $135,001 – $190,000 | 37% |
| $190,001 + | 45% |

**No tax-free threshold. No Medicare levy.**

---

## 4.2 The "do nothing" base case (§22)

**Remain an Australian resident. Sell all Bitcoin at $1.2m. Claim the 50% discount. Pay Australian
tax.** This is the benchmark every international strategy must beat.

```
Market value                                        $1,200,000
Cost base                                          ($  200,000)
Gross capital gain                                  $1,000,000
Less 50% CGT discount (held > 12 months)           ($  500,000)
Net capital gain                                    $  500,000

Salary                                              $  150,000
Total taxable income                                $  650,000

Tax on $650,000:
  $26,800 @ 15%                                     $    4,020
  $90,000 @ 30%                                     $   27,000
  $55,000 @ 37%                                     $   20,350
  $460,000 @ 45%                                    $  207,000
                                                    ----------
                                                    $  258,370
  Medicare levy 2%                                  $   13,000
                                                    ----------
Total tax                                           $  271,370
Less tax on salary alone ($150,000)                ($   39,570)
                                                    ==========
TAX ATTRIBUTABLE TO THE BITCOIN GAIN                $  231,800
```

**Effective rate on the $1m gain: 23.18%. Net cash retained: $968,200.**

Two observations that matter:

- 23.18% is not a punitive rate. The 50% discount plus a single-year realisation makes Australia's
  headline 47% top rate behave like a ~23% capital gains tax. **Any international strategy must
  beat 23.18%, net of relocation costs, professional fees and lifestyle disruption — not beat 47%.**
- If Bitcoin appreciates, the comparison changes decisively, because the do-nothing case taxes the
  *whole* future gain while the departure case taxes only the gain to the departure date. That is
  what §4.4 measures.

---

## 4.3 Departure tax at different Bitcoin values (§20)

Cost base held constant at $200,000. Both timing variants shown, because the choice of departure
date is worth tens of thousands of dollars.

| BTC value at departure | Unrealised gain | Net capital gain (after 50%) | **(i) Depart late in year** (on top of $150k salary) | **(ii) Depart early July** (employment ended 30 June) | Saving from timing | Effective rate on gain, variant (ii) |
|---|---|---|---|---|---|---|
| $500,000 | $300,000 | $150,000 | $67,300 | **$37,500** | $29,800 | **12.5%** |
| $1,000,000 | $800,000 | $400,000 | $184,800 | **$147,200** | $37,600 | **18.4%** |
| **$1,200,000** | **$1,000,000** | **$500,000** | **$231,800** | **$192,400** | **$39,400** | **19.2%** |
| $2,000,000 | $1,800,000 | $900,000 | $419,800 | **$373,100** | $46,700 | **20.7%** |
| $3,000,000 | $2,800,000 | $1,400,000 | $654,800 | **$598,900** | $55,900 | **21.4%** |
| $5,000,000 | $4,800,000 | $2,400,000 | $1,124,800 | **$1,050,600** | $74,200 | **21.9%** |
| $10,000,000 | $9,800,000 | $4,900,000 | $2,299,800 | **$2,179,900** | $119,900 | **22.2%** |

**Read the last column.** The effective rate on a discounted long-held gain converges to about
**22.6%**, and never exceeds it. This is the number to hold in mind: Australia is not a
high-CGT jurisdiction for a patient individual investor, and the *marginal* value of leaving is
bounded by roughly 23% of the gain accrued to the departure date — plus 100% of everything after.

**The strategic implication is important and under-appreciated:** the departure strategy is not
primarily about escaping tax on the **existing** $1m gain (you cannot — CGT event I1 taxes it on
the way out). **It is about escaping tax on all future appreciation.** The bigger the expected
future gain, the more the strategy is worth; if Bitcoin goes nowhere, it is not worth doing.

---

## 4.4 Bitcoin price appreciation scenarios (§21)

Departure value **$1.2m**, cost base **$200k**, sale in **year 7** while resident in a 0%
jurisdiction, acquisition 6 years before departure.

| | **Scenario A** sale $1.2m | **Scenario B** sale $2m | **Scenario C** sale $5m | **Scenario D** sale $10m |
|---|---|---|---|---|
| **Route 1 — Australian resident throughout; sell in year 7** | $231,800 | $419,800 | $1,124,800 | $2,299,800 |
| **Route 2 — Depart, crystallise I1, sell abroad (RECOMMENDED)** | **$192,400** | **$192,400** | **$192,400** | **$192,400** |
| — Australian tax at departure | $192,400 | $192,400 | $192,400 | $192,400 |
| — Australian tax on sale | $0 | $0 | $0 | $0 |
| — Destination tax (UAE / SG / HK / MY / CH / PT) | $0 | $0 | $0 | $0 |
| — Tax on return to Australia | $0 | $0 | $0 | $0 |
| **Route 3 — Depart, ELECT to disregard I1, sell abroad, no treaty relief** | **$321,500** | **$598,400** | **$1,636,800** | **$3,367,500** |
| **Route 4 — Depart, elect, treaty relief succeeds** 🔴 | $0 | $0 | $0 | $0 |
| | | | | |
| **Route 2 advantage over Route 1 (staying home)** | $39,400 | $227,400 | $932,400 | $2,107,400 |
| **Route 3 penalty vs Route 1 (worse than never leaving)** | ($89,700) | ($178,600) | ($512,000) | ($1,067,700) |

### Three conclusions from this table

1. **Route 2 is flat.** Once the I1 gain is crystallised, the Australian liability is **fixed at
   $192,400 forever**, regardless of whether Bitcoin goes to $2m or $10m. That certainty is the
   product being purchased.

2. **Route 3 is worse than never leaving Australia, in every single scenario.** Electing to
   disregard I1 and then selling as a foreign resident costs between $89,700 and $1,067,700 *more*
   than simply staying home and paying Australian CGT. The election destroys value because it
   surrenders the 50% discount (down to ~23%) *and* the tax-free threshold *and* the graduated
   rates, while surrendering none of Australia's taxing rights.

3. **Route 4 is worth less than it costs.** Its advantage over Route 2 is $192,400 in every
   scenario. Its downside if the treaty argument fails is Route 3 — up to $3.37m. See §3.4.

### Destination-country sale tax, by candidate (Route 2, no election)

| Destination | Scenario A ($1.2m) | B ($2m) | C ($5m) | D ($10m) |
|---|---|---|---|---|
| **UAE, Cayman, Bahamas, Monaco, Vanuatu** | $0 | $0 | $0 | $0 |
| **Singapore, Hong Kong, Malaysia** (investment, not trading) | $0 | $0 | $0 | $0 |
| **Switzerland** (private wealth mgmt) | $0 + wealth tax | $0 + wealth tax | $0 + wealth tax | $0 + wealth tax |
| **Portugal** (held ≥365 days) | $0 | $0 | $0 | $0 |
| **Cyprus** (8% from 2026) | $80,000 | $144,000 | $384,000 | $784,000 |
| **New Zealand** (up to 39% as income) | $390,000 | $702,000 | $1,872,000 | $3,822,000 |

⚠️ **A trap worth naming.** The destination computes its own gain on **its own** cost base — normally
the original acquisition cost — **not** the Australian $1.2m step-up from CGT event I1. So in a
jurisdiction that *does* tax the gain, the taxpayer is taxed twice on the pre-departure slice
unless the treaty contains a **deemed-alienation step-up election** (as the Australia–UK Article 13
does). The NZ and Cyprus figures above are computed from the original $200,000 cost base for
exactly this reason. In a 0% jurisdiction the point is moot — which is another reason to choose a
0% destination rather than a merely low-tax one.

Swiss wealth tax, for scale: at ~0.1–1% per annum on the full holding value, a $3m position costs
roughly **$3,000–$30,000 per year**, or **$21,000–$210,000** over a seven-year stay.

---

## 4.5 Table 1 — Country comparison

| Country | Personal CGT on Bitcoin | Crypto-specific tax rule | Tax residency requirement | Foreign income treatment | Wealth tax | Exit tax | Australia treaty | Australian return implications | Banking / crypto rails | **Score** |
|---|---|---|---|---|---|---|---|---|---|---|
| **UAE** | **0%** | None (no PIT law); 9% CT only if a *business* > AED 1m turnover | 183d; or 90d + permit + permanent home/business; or centre of interests | N/A | No | No | **None** | Clean; s 855‑45 reset applies | VARA-licensed; AED rails; heavy SoF | **8.45** |
| **Malta** | **0%** foreign-source (non-dom) | Long-term store of value = capital | Residence programme + presence; €15k min tax under GRP/TRP | Foreign gains outside the net even if remitted | No | No | **Yes (1985)** | Clean | 🔴 Weak crypto banking | **7.90** |
| **Singapore** | **0%** | IRAS e-Tax Guide; badges of trade | 183d + EP / ONE Pass / GIP (SGD 10m) | No CGT at all | No | No | **Yes (1969, MLI)** | Clean | 🟢 Best in class (MAS) | **7.85** |
| **Malaysia** | **0%** for individuals | No individual crypto CGT; LHDN treats trading as business income | **182d** | Exempt to 31 Dec 2036, conditional on foreign tax | No | No | **Yes** | Clean | 🟡 SC-registered DAX; thin for $3m | **7.85** |
| **Switzerland** | **0%** private wealth mgmt | FTA Circular 36 (5 cumulative criteria; **no borrowed capital**) | Permit (quota) or lump-sum forfait | Swiss-source taxed | **Yes 0.1–1%/yr** | No | **Yes (2013)** | Clean; best treaty text | 🟢 Sygnum, AMINA, Bitcoin Suisse | **7.75** |
| **Cayman Islands** | **0%** | No direct taxation | CI$1m investment | N/A | No | No | None | Clean | 🟡 CIMA VASP; limited banking | **7.40** |
| **Bahamas** | **0%** | None | US$1m investment; 90d/yr intent | N/A | No | No | None | Clean | 🟡 | **7.35** |
| **Monaco** | **0%** | None | €500k deposit + housing | N/A | No | No | None | Clean | 🟡 | **7.30** |
| **Hong Kong** | **0%** | IRD **DIPN 39**; badges of trade | Employment / Top Talent / CIES (HKD 30m) | Territorial | No | No | **None (TIEA)** | Clean | 🟢 SFC VATPs; ZA Bank | **7.20** |
| **Georgia** | **0%** | 2019 MoF Decision N-201 (not statute) | 183d; HNWI route | Territorial in practice | No | No | None | Clean | 🟡 | **6.95** |
| **Portugal** | **0%** if held ≥365d | CIRS art. 10; denial rule for out-of-network counterparties | 183d or habitual residence | Worldwide | No (AIMI on property) | **Yes — crypto exit tax** | **Signed 2023, not in force** | Portuguese exit tax if still holding | 🟡 | **6.95** |
| **Thailand** | 0% with LTR; else taxed on remittance | Por 161/162 (2023); 2025 relaxation **not enacted** | 180d | Remittance basis | No | No | **Yes** | Clean | 🟡 | **6.90** |
| **Panama** | **0%** (territorial) | None | Friendly Nations visa | Territorial | No | No | None | Clean | 🟡 | **6.85** |
| **Mauritius** | **0%** if capital; 10–15% if revenue | None | RBI (USD 375k property) | Territorial-ish | No | No | None (TIEA) | Clean | 🟡 | **6.70** |
| **New Zealand** ⚠️ | **10.5–39% as ordinary income** | IRD presumes acquisition for disposal | 183d / permanent place of abode | Worldwide | No | No | Yes | Clean | 🟢 | **6.50** ⚠️ fails the gate |
| **Cyprus** ⚠️ | **8% flat from 1 Jan 2026** | New art. 20E crypto regime | 60-day rule | Non-dom exemptions | No | No | **None** | Clean | 🟡 | **6.25** ⚠️ |
| **Andorra** ⚠️ | **10%** | Integrated into PIT | 183d | Worldwide | No | No | None | Clean | 🟡 | **5.95** ⚠️ |
| **UK** ⚠️ | Full CGT; **FIG cannot apply to crypto** (HMRC situs rule) | Crypto situated where beneficial owner resides | SRT | FIG 4 years (not for crypto) | No | **Temporary non-residence clawback** | Yes | Clean | 🟢 | **~5.5** ⚠️ |
| **Italy / Spain / Japan / Korea** ⚠️ | 19–55% | Various | 183d | Worldwide | Some | Some | Yes | Clean | Varies | **4.9–5.6** ⚠️ |

---

## 4.6 Table 2 — Australian tax outcomes by strategy

Base fact pattern: departure value $1.2m, cost base $200k, sale at $3m in year 7.

| # | Strategy | Australian tax at departure | Australian tax on sale | Australian tax on return | **Total Australian tax** | Certainty |
|---|---|---|---|---|---|---|
| 1 | **Stay Australian resident + sell now** (at $1.2m) | n/a | $231,800 | n/a | **$231,800** | 🟢 |
| 1b | *Stay Australian resident + sell in year 7 at $3m* | n/a | $654,800 | n/a | **$654,800** | 🟢 |
| 2 | **Leave + crystallise I1** (late-year departure) | $231,800 | $0 | $0 | **$231,800** | 🟢 |
| 2b | **Leave + crystallise I1** (early-July departure) ⭐ | **$192,400** | **$0** | **$0** | **$192,400** | 🟢 |
| 3 | **Leave + disregard I1** (liability preserved, not extinguished) | $0 | *deferred in full* | *deferred in full* | **see 4–6** | 🟢 (that it defers) |
| 4 | Leave + disregard + **sell after 1 year** | $0 | ≈$695,000 | $0 | **≈$695,000** | 🟢 |
| 5 | Leave + disregard + **sell after 5 years** | $0 | ≈$891,700 | $0 | **≈$891,700** | 🟢 |
| 6 | Leave + disregard + **sell after 10 years** | $0 | ≈$999,100 | $0 | **≈$999,100** | 🟢 |
| 7 | **Leave + crystallise + sell (yr 7) + return to Australia (yr 8)** ⭐ | $192,400 | $0 | **$0** | **$192,400** | 🟢 |
| 8 | **Leave + crystallise + sell (yr 7) + remain overseas** | $192,400 | $0 | n/a | **$192,400** | 🟢 |
| 9 | Leave + disregard + treaty relief succeeds 🔴 | $0 | $0 | $0 | **$0** | 🔴 |
| 10 | Leave + disregard + **return still holding the BTC** | $0 | — | **Full gain from $200k base; s 855‑45 switched off (ATO ID 2009/148)** | **Worst case** | 🟠 |

**Rows 7 and 8 are identical.** Returning to Australia adds **nothing** to the Australian tax bill,
provided the s 104‑165 choice was not made and the sale happened while genuinely non-resident.
**This is the direct answer to the brief's central question.**

---

## 4.7 Table 3 — Total tax on the $1m gain, by strategy

Comparing at year 7, with Bitcoin at $3m (so a total economic gain of $2.8m from the $200k base).

| Strategy | Australian tax | Destination tax | **Total tax** | **Net cash retained** | vs. staying resident and selling in yr 7 |
|---|---|---|---|---|---|
| **Do nothing — sell today at $1.2m as a resident** | $231,800 | — | **$231,800** | $968,200 | *n/a — different transaction* |
| **Stay resident, sell at $3m in year 7** | $654,800 | — | **$654,800** | $2,345,200 | **baseline** |
| **⭐ Depart + crystallise I1 + sell in UAE at $3m** | $192,400 | $0 | **$192,400** | **$2,807,600** | **+$462,400** |
| Depart + crystallise + sell in Singapore / HK / Malaysia / Portugal | $192,400 | $0 | **$192,400** | $2,807,600 | +$462,400 |
| Depart + crystallise + sell in Switzerland | $192,400 | ~$21k–210k wealth tax | **$213k–$402k** | $2,598k–$2,787k | +$252k–$441k |
| Depart + crystallise + sell in Cyprus | $192,400 | $224,000 | **$416,400** | $2,583,600 | +$238,400 |
| Depart + crystallise + sell in New Zealand | $192,400 | $1,092,000 | **$1,284,400** | $1,715,600 | **−$629,600** |
| **Depart + DISREGARD I1 + sell at $3m (no treaty)** 🔴 | $944,600 | $0 | **$944,600** | $2,055,400 | **−$289,800** |
| Depart + disregard + treaty relief succeeds 🔴 | $0 | $0 | **$0** | $3,000,000 | +$654,800 |

**The three numbers that decide everything:**

```
Recommended route (crystallise, UAE)          $  192,400
Never leave Australia                         $  654,800   (+$462,400)
Elect to disregard, treaty fails              $  944,600   (+$752,200)
```

---

## 4.8 Capital loss harvesting model (§18)

Losses are applied to the **gross** gain before the 50% discount (s 102‑5 method statement).
Modelled on an optimised early-July departure.

| Capital losses | Net gain after losses | Net capital gain | Australian tax | Tax saved | **Value per $1 of loss** |
|---|---|---|---|---|---|
| $0 | $1,000,000 | $500,000 | $192,400 | — | — |
| $50,000 | $950,000 | $475,000 | $181,100 | $11,300 | **22.6c** |
| $100,000 | $900,000 | $450,000 | $169,800 | $22,600 | **22.6c** |
| $200,000 | $800,000 | $400,000 | $147,200 | $45,200 | **22.6c** |
| $500,000 | $500,000 | $250,000 | $79,450 | $112,950 | **22.6c** |

> **A capital loss offset against a discounted gain is worth roughly half what people expect.**
> Apply losses to non-discounted gains first where any exist. Do not manufacture losses through
> wash sales (TA 2008/7 and Part IVA).

---

## 4.9 Sensitivity: what if Bitcoin falls before departure?

The I1 gain is measured at the market value on the cessation date. A lower Bitcoin price at
departure means a materially lower departure tax — and the taxpayer keeps the same upside
afterwards, because post-departure gains are outside the Australian net either way.

| BTC value at departure | Departure tax (optimised) | Australian tax if BTC later recovers to $3m and is sold abroad |
|---|---|---|
| $600,000 | ≈$56,900 | $0 |
| $900,000 | ≈$124,600 | $0 |
| $1,200,000 | ≈$192,400 | $0 |
| $1,800,000 | ≈$327,900 | $0 |
| $2,400,000 | ≈$463,400 | $0 |

This is a genuine, lawful consideration — the taxpayer chooses when to emigrate, and the tax
follows the market value on that date. **But do not let it drive the decision.** Deliberately
delaying a family relocation to wait for a drawdown means (a) holding a concentrated position for
tax reasons, which is an investment error, and (b) creating a documentary record that the move was
tax-timed, which is the last thing you want if residency is ever challenged. Treat a low price at
the planned departure date as a windfall, not as a target.
