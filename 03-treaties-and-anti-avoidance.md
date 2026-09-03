# 3 — Tax treaties and anti-avoidance

Covers brief sections 12, 25 and 32.

---

## 3.1 How Australian treaties operate

**International Tax Agreements Act 1953, s 4(2):** Australia's tax treaties **override** the
Income Tax Assessment Acts where they are inconsistent — with a carve-out. **Part IVA of the ITAA
1936 (the general anti-avoidance rule) is not displaced by a treaty.** So a treaty can strip
Australia of a taxing right that domestic law confers, but it cannot protect a scheme that Part
IVA reaches.

Australia has **comprehensive tax treaties with roughly 46 jurisdictions**. Four points matter for
this taxpayer:

| Jurisdiction | Treaty status (September 2026) |
|---|---|
| **UAE** | **None.** CEPA and the Investment Agreement entered into force 1 October 2025 — neither is a tax treaty. No DTA negotiations announced |
| **Hong Kong** | **None.** TIEA only; DTA discussions remain preliminary |
| **Singapore** | In force (1969, amended by protocols and by the MLI; synthesised text published 2021) |
| **Malaysia, Thailand, Switzerland, Malta, Japan, Korea, Indonesia, Philippines, NZ, UK, US** | In force |
| **Portugal** | **Signed 30 November 2023 — not yet in force.** Slovenia (2024), Ukraine (2025) and Croatia (2025) likewise await entry into force |
| **Cayman, Bahamas, Bermuda, Monaco, Andorra, Panama, Georgia, Cyprus, Mauritius, Liechtenstein, Vanuatu** | No comprehensive DTA (several have TIEAs only) |

---

## 3.2 Treaty residence and tie-breakers

Where domestic law makes a person a resident of both states, the treaty's Article 4 tie-breaker
applies a **cascading** test:

1. **Permanent home available** in one state only
2. If both or neither → **centre of vital interests** (personal and economic relations)
3. If unresolved → **habitual abode**
4. If unresolved → **nationality**
5. If still unresolved → **mutual agreement procedure** between competent authorities

### Why this matters more than it first appears

The tie-breaker is **the single most valuable insurance policy available in this whole strategy**,
and it is not available in the UAE or Hong Kong.

Consider the *Quy* scenario replayed with a treaty country. If the ATO argues (as it successfully
did against Quy) that the taxpayer remained an Australian resident under s 6(1), a taxpayer in
Malaysia, Singapore, Malta or Switzerland can respond: *"Even if I am a dual resident under
domestic law, Article 4 makes me a treaty resident of X, and Article 13 then limits Australia's
taxing rights."* A taxpayer in the UAE or Hong Kong **has no such answer** — they must win the
domestic-law argument outright or lose everything.

### The dual-resident wrinkle — and why it does not create a clever alternative

An obvious question: could the taxpayer remain an Australian resident under domestic law (thereby
**never triggering CGT event I1**, since I1 requires you to *stop* being an Australian resident)
while being a treaty resident of, say, Switzerland — and then claim treaty protection on the
disposal?

The mechanics arguably work: CGT event I1 keys off the **domestic** concept of ceasing residency,
so a person who remains a domestic-law resident does not trigger it, while Article 13 might still
allocate the gain exclusively to the other state.

**Do not pursue this.** It fails on three grounds:

1. It requires the taxpayer to be a *genuine* resident of both countries, which is a fragile and
   expensive position to maintain, and it means continuing to file as an Australian resident on
   worldwide income for everything the treaty does not cover.
2. It is exactly the arrangement the **MLI principal purpose test** (§3.5) exists to defeat.
3. It concedes the very thing the strategy needs — an Australian centre of vital interests — while
   claiming its opposite.

**Rated 🔴. Do not rely upon.**

---

## 3.3 Taxing rights over capital gains — the "alienation of property" article

Australian treaties structure the gains article as: real property → source state; business
property of a PE → source state; ships and aircraft → residence state; land-rich shares → source
state; **and then a residual paragraph** for everything else.

**The residual paragraph is where the entire treaty question is decided**, and Australian practice
is not uniform:

| Pattern | Effect on Bitcoin gains | Example |
|---|---|---|
| **"Gains from the alienation of any other property shall be taxable only in the Contracting State of which the alienator is a resident"** | Australia **loses** the right to tax — even a deemed-TAP gain | Reported for the **Australia–Switzerland Convention (2013)** |
| **No residual paragraph at all** (gains not covered fall outside the article) | Australia's domestic law is **unaffected** — the deemed-TAP charge stands | Appears to be the position under the **Australia–Singapore** Agreement, whose Article 10A addresses real property, PE business property and ships/aircraft |
| **A "former resident" preservation clause** — Australia may tax movable-property gains of an individual who was an Australian resident within the preceding *n* years | Australia **keeps** the right for that window, then loses it | Reported in the Australia–Switzerland materials as preserving Australia's right where the individual was an Australian resident at any time in the **4 years** preceding alienation |
| **A "deemed alienation / step-up election"** — where one state taxes a deemed disposal on emigration, the individual may elect to be treated in the other state as having reacquired at market value | The **destination** grants a cost-base step-up | **Australia–UK Article 13**; similar provisions in several modern Australian treaties |

### ⚠️ Verification warning

The Switzerland points above come from **search-retrieved excerpts** of the 2013 Convention and its
Protocol, not from a first-hand reading (see the network limitation noted in the README). The
apparent presence of *both* an exclusive-residence residual paragraph *and* a four-year
former-resident preservation clause is internally coherent — the clause is precisely the carve-out
one would expect from the residual rule — but **the exact text, and whether the four-year window
runs from cessation of residency or from the year of alienation, must be verified against the
instrument before any reliance.** This is question 7 in the lawyer list at §6.4.

---

## 3.4 Can a treaty defeat the deemed-TAP charge? The critical question

If the taxpayer makes the s 104‑165 choice, the Bitcoin becomes deemed taxable Australian property,
and Australian domestic law taxes the eventual disposal (modelled at **$944,600** — see §1.3).
Can a treaty take that right away?

**In principle, yes.** Section 4(2) of the Agreements Act gives the treaty precedence over the
ITAA, so a residual paragraph conferring **exclusive** residence-state taxing rights over "any
other property" would displace the domestic charge. Commentary on Australian departure planning
states this outcome directly: where the destination's DTA gives exclusive taxing rights, "there
will be no Australian CGT liability… even if the election to disregard CGT Event I1 has been made."

**In practice, four conditions must all hold — and each is a point of failure:**

| Condition | Assessment |
|---|---|
| 1. The specific treaty must contain a residual **exclusive**-residence paragraph | 🟠 Treaty-specific. **Not available for the UAE or Hong Kong at all** (no treaty). Apparently absent from the Australia–Singapore Article 10A |
| 2. Any **former-resident preservation clause** must have expired | 🟠 Where one exists (e.g. a 4-year window), the sale must fall outside it — pushing the disposal out to year 5+ |
| 3. The arrangement must survive the **MLI principal purpose test** | 🔴 See §3.5. This is the weak point |
| 4. The arrangement must survive **Part IVA** | 🟠 See §3.6 |

### The risk/reward arithmetic — why this is the wrong trade

| | Cost |
|---|---|
| **Recommended route:** crystallise I1, no election, sell as a foreign resident | **$192,400** |
| **Aggressive route succeeds:** elect, then treaty strips Australia's right | **$0** |
| **Aggressive route fails:** elect, treaty benefit denied (PPT, Part IVA, wrong treaty, or timing) | **$944,600** |

> **Maximum upside: $192,400. Maximum downside: $752,200.**
>
> Break-even requires roughly **80% confidence** in an argument that depends on unverified treaty
> text, an untested application of the MLI PPT to an individual's relocation, and Part IVA. No
> competent adviser signs that off. **Rated 🔴.**

**The recommended route does not need the treaty at all.** By crystallising I1, the Bitcoin
becomes an ordinary non-TAP asset and s 855‑10 disregards the gain under **domestic law**. There is
nothing for the ATO to argue about and nothing for a treaty to do. That is why the absence of an
Australia–UAE DTA — fatal to the aggressive route — is only a secondary weakness for the
recommended one.

---

## 3.5 The MLI principal purpose test

Australia ratified the Multilateral Instrument on 26 September 2018; it entered into force for
Australia on **1 January 2019**. Australia adopted **Article 7** and **only the PPT** (not the
limitation-on-benefits alternative).

> A treaty benefit is **denied** if, having regard to all relevant facts and circumstances, it is
> reasonable to conclude that **obtaining that benefit was one of the principal purposes** of any
> arrangement or transaction that resulted, directly or indirectly, in the benefit — unless
> granting it would accord with the object and purpose of the relevant provisions.

Three features make this dangerous for the aggressive route:

1. **"One of the principal purposes"** is a far lower bar than Part IVA's "dominant purpose".
2. **"Benefit" is read broadly** — a reduction, exemption, **deferral** or refund all count. The
   s 104‑165 choice *is* a deferral, and the treaty argument converts the deferral into an
   exemption.
3. The taxpayer would have made an **irrevocable statutory election** whose only rationale is that
   Australia's taxing right will later be removed by a treaty. That is close to a written
   confession of purpose.

The PPT is largely untested against an individual's genuine relocation, and there is a respectable
argument that a **genuine** move with **genuine** substance is not an "arrangement… to obtain a
benefit". But the *combination* of genuine relocation **plus** a deliberate election that only
makes sense if the treaty applies is materially more exposed than the relocation alone.

**Note the asymmetry that decides the recommendation:** the PPT is essentially irrelevant to the
recommended route, because that route claims **no treaty benefit at all** — it relies purely on
domestic s 855‑10.

---

## 3.6 Part IVA

**Part IVA ITAA 1936** applies where there is (i) a **scheme**, (ii) a **tax benefit** obtained in
connection with it, and (iii) an objective conclusion, on the eight factors in **s 177D(2)**, that
a person entered into the scheme for the **sole or dominant purpose** of obtaining that tax
benefit. The purpose test is **objective** — the taxpayer's stated motives are not decisive, and a
genuine commercial rationale is a factor but not an answer.

### Is a genuine relocation a Part IVA scheme?

**A genuine relocation followed by a genuine sale of personally owned Bitcoin is fundamentally
different from an artificial arrangement designed to manufacture a tax result.** The distinction is
real and defensible:

| Genuine relocation | Artificial arrangement |
|---|---|
| The taxpayer and family **actually live** in the destination for years | Paper residency; family stays; brief visits |
| Real economic and personal disruption: schools, careers, housing, community | No change in how life is actually lived |
| Ownership of the asset is **unchanged** — same person, same coins | Interposed entities, nominees, round-robin transfers |
| The transaction is an **ordinary sale at market price to an unrelated party** | Non-arm's-length or circular dealings |
| The tax outcome follows from the **ordinary operation** of ss 104‑160, 855‑10 and 855‑45 | The outcome depends on artifice |
| **Full disclosure** in Australian and foreign returns | Concealment or misdescription |

**The choice principle** is also relevant: where the law expressly offers alternatives, choosing
the more favourable one is not, without more, a Part IVA scheme. Australian law expressly
contemplates that residency changes (s 104‑160, s 855‑45) and that individuals may elect under
s 104‑165. It is difficult to characterise **not** making an elective concession — which is what
the recommended strategy does — as obtaining a tax benefit.

**Assessment: 🟢 low Part IVA risk for the recommended strategy**, because:
- the "scheme" would be *moving your family to another country and living there for years*, which
  is not the kind of contrivance Part IVA addresses;
- the taxpayer **pays** $192,400 of Australian tax rather than avoiding it;
- there is no counterfactual in which Australia collects the post-departure gain from a genuine
  non-resident, because s 855‑10 says it does not; and
- the **absence** of an election cannot easily be a scheme.

**🟠 Elevated risk** if: the relocation is short and clearly tax-timed; the family does not move;
the taxpayer returns immediately after the sale; or the s 104‑165 election is made and paired with
a treaty claim.

**Sham** is a separate and more serious doctrine: documents that do not reflect the true
arrangement (a lease never occupied, employment never performed, a "resident" never present).
Sham is not tax planning; it is fraud. Nothing in this report contemplates it.

---

## 3.7 Other Australian anti-avoidance regimes

| Regime | Relevance here |
|---|---|
| **CFC rules (Part X ITAA 1936)** | Engaged only if the Bitcoin is held through a **foreign company** controlled by Australian residents. Attributable income can be taxed to the Australian controller. **Recommendation: hold personally. Do not interpose an offshore company** — it triggers a market-value disposal on the way in, loses the 50% discount, and switches on the CFC rules |
| **Transferor trust rules (Div 6AAA ITAA 1936)** | Engaged if an Australian resident transfers property to a non-resident trust. Attributes trust income to the transferor. **Do not use an offshore trust** |
| **Section 99B ITAA 1936** | Taxes a broad range of foreign trust amounts paid to or applied for an Australian resident beneficiary — including **corpus, loans, gifts and the use of trust property**. See **TD 2024/9** and **PCG 2024/3**. Critically relevant to the **return** phase: a returning resident who receives money from any offshore trust structure can be assessed on the full amount. **Another reason to hold personally and remit plain personal savings** |
| **Transfer pricing (Div 815)** | Not relevant — no cross-border dealings between associated enterprises |
| **Foreign resident CGT withholding** | 15% on Australian real property disposals from 1 January 2025, no value threshold. Relevant only to an Australian home sold while non-resident |
| **Foreign resident CGT regime expansion** | Exposure drafts released **10 April 2026** to broaden TARP and reform the principal asset test, with parts applying retrospectively to CGT events from 12 December 2006. Consultation closed 24 April 2026. **On the drafts as described, the expansion targets real-property-related assets, not crypto** — but the direction of travel is toward a wider foreign-resident CGT net, and the status of these bills should be re-checked before executing |

---

## 3.8 Tax planning vs tax evasion — the line this report does not cross

| Legal tax planning (what this strategy is) | Tax evasion (what it is not) |
|---|---|
| **Genuinely** ceasing residency by actually moving | Claiming to have left while living in Australia |
| **Genuinely** becoming resident somewhere else | A mailbox address and a paper lease |
| Declaring the CGT event I1 gain and **paying** ~$192,400 | Failing to lodge the departure-year return |
| Reporting the disposal in the destination country | Hiding the disposal |
| **Genuine** beneficial ownership throughout | Nominees, bearer structures, undisclosed trusts |
| Real acquisition records and a true cost base | Fabricated cost bases |
| Full on-chain transparency; regulated venues | Mixers, obfuscation, unregulated venues |
| Choosing a departure date that falls in a favourable income year | Backdating documents |
| Not making an elective concession the statute offers | Making false statements to the ATO |

The strategy recommended here **increases** the taxpayer's Australian tax in the departure year
(≈$192,400 that would not otherwise be payable then) in exchange for certainty. It depends on the
taxpayer's conduct matching their claims. **If the family does not actually move, the strategy is
not aggressive tax planning — it is a false statement to the Commissioner.**
