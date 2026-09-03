# Optimal International Tax-Residency Strategy for an Australian Bitcoin Holder

**Research project — international tax law analysis across two jurisdictions and a change of residency.**

Research date: **3 September 2026**. Australian law analysed as at the **2026–27 income year**.

---

## ⚠️ Status of this document

This is a **tax-law research exercise**, not tax advice, and not a substitute for a formal
opinion or a private binding ruling. It was produced by an AI research agent. Every material
conclusion below needs to be verified by an Australian international-tax specialist and by
local counsel in the destination country before a single dollar moves.

**A material limitation you must know about.** The research environment's network policy
blocked direct access to `ato.gov.au`, `legislation.gov.au` and AustLII. Statutory text,
ATO rulings and treaty text were therefore obtained through **search-engine-retrieved
excerpts of those same primary sources** rather than by reading the instruments end to end.
Provision numbers, operative rules and quoted language are cited to the primary instrument
throughout, but **the full text of no statute or treaty was read first-hand**. Three
conclusions in particular rest on excerpts that must be checked against the instrument
itself before reliance:

1. the residual paragraph of the "alienation of property" article in any specific Australian DTA
   (§3 of this report);
2. the precise interaction of ITAA 1997 s 104‑165(3) with s 855‑45 on re-entry
   (ATO ID 2009/148 — §1.5); and
3. the current status of the 2026 exposure drafts strengthening the foreign-resident CGT
   regime (§1.9).

Nothing here recommends concealment, sham transactions, nominee ownership, false residency
declarations, fabricated cost bases, undisclosed accounts, or mixers. The strategy analysed
is a **genuine relocation, genuinely reported**.

---

## The headline answer

> **Cease Australian residency properly, let CGT event I1 crystallise (do *not* make the
> s 104‑165 choice), time the departure to the first days of an Australian income year, and
> relocate the whole family to the United Arab Emirates.**

Modelled Australian tax on the existing AUD $1m embedded gain: **≈ $192,400** (≈19.2% of the
gain), paid once, in the year of departure. Every subsequent dollar of Bitcoin appreciation —
$1.8m in the base fact pattern — is then **outside the Australian CGT net permanently**, and
outside the UAE net entirely. Returning to Australia in year 8 creates **no retrospective
liability**.

The single most important finding is a negative one:

> **The "elect to disregard CGT event I1" option — the one that looks like the tax-efficient
> choice — is the worst outcome available.** It converts a $192,400 liability into a modelled
> **$944,600** liability, and it is worse than never leaving Australia at all.

See [§4](04-modelling-and-numbers.md) for the arithmetic and [§1.3](01-australia-departure-and-return.md)
for why.

---

## Contents

| File | Covers | Brief-spec sections |
|---|---|---|
| [01 — Australian departure & return CGT](01-australia-departure-and-return.md) | Residency tests and case law; CGT event I1; the s 104‑165 choice; TAP; selling as a foreign resident; returning to Australia; crypto transaction mechanics; parcel selection; loss harvesting; family structures; BTC-backed loans; reporting | 1, 2, 3, 4, 5, 15, 16, 17, 18, 19, 24, 26 |
| [02 — Jurisdiction screening](02-jurisdiction-screening.md) | Screening criteria; 40+ jurisdictions; deep dives on UAE, Singapore, Hong Kong, Malaysia, Thailand; recent law changes; banking and liquidation; weighted ranking | 6, 7, 8, 9, 10, 11, 27, 28 |
| [03 — Treaties & anti-avoidance](03-treaties-and-anti-avoidance.md) | DTA architecture; tie-breakers; alienation-of-property articles; the treaty-override question; MLI principal purpose test; Part IVA; sham; CFC and foreign-trust rules; avoidance vs evasion | 12, 25, 32 |
| [04 — Modelling & numbers](04-modelling-and-numbers.md) | Do-nothing base case; departure tax at 7 asset values; 4 price-appreciation scenarios; loss-harvesting model; the three headline comparison tables | 20, 21, 22, and Tables 1–3 |
| [05 — Recommended strategy & timeline](05-recommended-strategy-and-timeline.md) | Permanent vs 5-year vs 10-year relocation; the return strategy (options A–G); T‑12 months to return chronology | 13, 14, 29 |
| [06 — Risk, failure modes & questions](06-risk-failure-modes-and-questions.md) | Certainty ratings; substance/residency risk with strong and weak cases; 10 failure modes with probability, impact and mitigation; 20 questions for a tax lawyer; red flags; confidence scores | 23, 24, 30, 33 (part) |
| [07 — Sources](07-sources.md) | Primary and secondary source list, by jurisdiction | 31 |

---

## Executive summary (1,000 words)

**The question.** Can an Australian resident with an existing embedded Bitcoin capital gain
genuinely cease Australian tax residency, resolve the departure CGT position, become resident
somewhere that does not tax the disposal, sell while non-resident, and return to Australia in
5–10 years without Australia taxing the gain retrospectively?

**The answer is yes — but not for the reason most people assume, and the obvious route is a trap.**

**Australia has no temporary non-residence rule.** Unlike the UK (FA 2013 Sch 45 Pt 4, which
claws back gains realised during an absence of five years or less), Australia has *no*
time-based clawback. Once you genuinely cease residency, gains on non-taxable-Australian-property
assets realised while you are a foreign resident are disregarded by ITAA 1997 s 855‑10, full
stop, and you can come home the next year. This is the load-bearing feature of the whole
strategy. Australia's only defences are (a) the residency test itself and (b) Part IVA.

**But you cannot leave for free.** ITAA 1997 s 104‑160 triggers CGT event I1 the moment you
stop being an Australian resident: a deemed disposal at market value of every CGT asset that
is not taxable Australian property. Bitcoin is a CGT asset and is not TAP, so it is caught.
On the fact pattern — $1.2m market value, $200k cost base — the deemed gain is $1m, halved by
the 50% discount to $500k of net capital gain.

**The central decision is whether to make the s 104‑165 choice, and the answer is no.** That
choice lets you disregard the I1 gain. In exchange, s 104‑165(3) deems every affected asset to
be **taxable Australian property** until you either dispose of it or become an Australian
resident again. It is a **deferral, not an exemption**, it is **irrevocable**, and it is
**all-or-nothing across every asset**. Two consequences make it destructive here:

- *If you sell while non-resident*, the Bitcoin is still deemed TAP, so s 855‑10 does not
  disregard the gain. Australia taxes the **entire** gain from the original $200k cost base —
  and Subdiv 115‑B (ss 115‑105, 115‑115) apportions the CGT discount down to the resident
  share of the holding period, while foreign-resident rates start at 30% from the first dollar
  with no tax-free threshold. Modelled: **$944,600**, against $192,400 for crystallising.
  It is worse than never leaving.
- *If you return still holding the asset*, ATO ID 2009/148 confirms the s 855‑45 market-value
  cost-base reset **does not apply**, because the asset was TAP immediately before you resumed
  residency. The original $200k cost base survives and Australia eventually taxes everything.

Crystallising I1 instead does the opposite: you pay once, and the cost base resets to $1.2m.
From that moment the Bitcoin is an ordinary non-TAP asset held by a foreign resident, and
every subsequent gain is disregarded under s 855‑10.

**Coming home is safe.** ITAA 1997 s 855‑45 deems a returning resident to have acquired each
non-TAP asset at market value on the day residency resumes, and restarts the discount clock.
So Australia taxes only post-return growth. Sale proceeds sitting offshore are capital, not
income; remitting them to Australia is not a taxable event, though Div 775 can produce a small
forex gain or loss on currency movement after residency resumes. The one absolute condition is
that you did **not** make the s 104‑165 choice.

**Residency is where this succeeds or fails, and Australian family ties are the killer.**
There are no bright lines — TR 2023/1 says so expressly, and the Board of Taxation's proposed
183-day test has still not been legislated. *Quy* [2025] ARTA 174 is the cautionary case on
these exact facts: an Australian citizen working in Dubai, in Australia under two months a
year, was held to be an Australian resident throughout — because his wife and daughters stayed
in Perth, the family home remained available to him, and his UAE presence rested on a
sponsored work permit tied to his Australian employer. *Harding* [2019] FCAFC 29 is the
taxpayer win, and the difference is instructive: Harding's move was permanent in character.
**The spouse and child must relocate. This is not optional.**

**Where to go.** Screening 40+ jurisdictions against 15 criteria, the UAE ranks first
(weighted 8.45/10): no personal income tax at all, no capital gains tax, no wealth or estate
tax, no exit tax, several self-sponsored Golden Visa routes (capital-free on the skilled-professional
route; ~AUD 250k–450k of equity on the mortgaged-property route since February 2026), clear
statutory tax-residency criteria (Cabinet Decision 85/2022; Ministerial Decision 27/2023),
and deep VARA-regulated crypto liquidation infrastructure. Its one real weakness is that
**Australia and the UAE have no double tax agreement**, so there is no treaty tie-breaker to
fall back on if the ATO disputes residency — which is precisely what went wrong in *Quy*.
Runners-up: Malta (7.90), Singapore and Malaysia (7.85 each), Switzerland (7.75).

Several famous "0% crypto countries" do not survive contact with the law. **Cyprus** imposed
an 8% flat crypto tax from 1 January 2026. **New Zealand** taxes crypto disposals as ordinary
income at up to 39%. **Portugal**'s 365-day exemption is real but carries a crypto exit tax
and a denial rule for out-of-network counterparties, and the Australia–Portugal treaty signed
in 2023 is still not in force. **The UK's** new four-year FIG regime is useless for crypto,
because HMRC treats crypto as situated where its beneficial owner resides — so a UK resident's
crypto gains are UK gains and cannot be foreign.

**What it costs to be wrong.** If the ATO succeeds in arguing residency never ceased, the
modelled exposure is roughly **$1.13m–$1.30m** — $654,800 of CGT on the $3m sale, plus seven
years of foreign salary assessed as a resident, plus shortfall penalties of 25–75% and interest.
That is the number that should drive the substance decisions, not the $192,400.

**Bottom line: pay the $192,400, move the family properly, keep contemporaneous evidence, and
do not touch the s 104‑165 choice.**

---

*Prepared 3 September 2026. Not legal or tax advice.*
