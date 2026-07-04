# The Orion Enterprise Blueprint
### Foundational Reference Document — Orion Industrial Technologies B.V.

--

## 1. Company Snapshot

Orion Industrial Technologies B.V. is headquartered in Amsterdam and designs advanced industrial automation systems, semiconductor manufacturing equipment, robotics, smart factory technology, renewable energy equipment, and industrial AI software. It's privately held, with a 22% minority stake owned by Blackstone Growth since 2021 — a structure that matters later, because it's why Orion behaves like a company preparing for an eventual IPO, complete with investor-grade reporting discipline.

The business runs at **€6.2 billion in FY2025 revenue**, employs roughly **22,000 people across 27 countries**, and operates through **17 legal entities**. It reports on a calendar fiscal year and is mid-migration from legacy SAP ECC to SAP S/4HANA.

Five business units make up the portfolio:

- **Semiconductor Equipment** — the largest, at ~38% of revenue
- **Industrial Robotics & Automation** — ~27%
- **Renewable Energy Systems** — ~19%
- **Industrial AI Software** — ~10%
- **Aftermarket Services & Support** — ~6%

Customers span semiconductor fabs, automotive OEMs and tier-1 suppliers, logistics and warehouse automation, renewable energy developers, and pharmaceutical manufacturers.

---

## 2. Regional & Legal Entity Footprint

Orion's 17 entities cluster into four regions:

- **EMEA** — the Netherlands (Group HQ), Germany, France, UK, Nordics, Iberia. This is where the manufacturing footprint is heaviest.
- **Americas** — US (Delaware), Canada, Brazil, Mexico. The US entity also carries the largest commercial organisation outside the Netherlands.
- **APAC** — Singapore (regional HQ), Japan, Korea, China, India, Taiwan. China combines manufacturing and sales; India houses the Finance Operations shared centre.
- **Poland** — a single entity dedicated entirely to the Shared Service Centre.

Intercompany trading between these entities is material and deliberately messy — shared manufacturing component cross-charges, R&D cost-sharing agreements, and management fee recharges all flow between them, which creates intercompany reconciliation complexity across entities.

---

## 3. Group Finance Organisation

Finance runs roughly **650 people** globally under Group CFO **Marieke van der Berg** (ex-Philips, ex-ASML, joined 2022, and the executive sponsor of Project Meridian).

Reporting into her:

- **Corporate Finance (100)** — led by Group Controller Thomas Reijnders. Covers Controllership, External Reporting, Technical Accounting, Consolidation.
- **FP&A (90)** — led by Priya Nair. Covers Group, Regional, and Business Unit FP&A.
- **Finance Transformation (40)** — led by David Okonkwo. Covers Process Excellence, Automation, Data Analytics, and ERP Transformation.
- **Shared Service Centre, Poland (180)** — led by Katarzyna Wiśniewska. Handles AP, AR, GL, Fixed Assets, and Master Data.
- **Finance Operations, India (120)** — led by Arjun Mehta. Handles Reporting Support, Reconciliations, Product Costing Support, Data Quality, and Analytics.
- **Treasury (25)** under Sophie Laurent, **Tax (30)** under Henrik Larsson, **Internal Audit (20)** under Fatima Al-Rashid, and **Business Finance Partners (45)** embedded across the five BUs.

Regional CFOs sit dotted-line into the Group CFO: Jan de Vries (EMEA), Rachel Kim (Americas), Wei Zhang (APAC).

---

## 4. Project Meridian — Why Any of This Exists

In Q1 2024, Orion's Board approved a **€120 million Finance Transformation Programme**, internally branded **Project Meridian**, to modernise finance operations, cut the close from nine days to five, standardise processes across all 17 entities, complete the SAP S/4HANA migration, and push automation and self-service analytics across the function.

The programme runs 2024–2027 in four phases, which map directly onto the four Phases of this portfolio:

- **Phase 1, Stabilise (2024)** → close transformation, reconciliation automation, reporting automation
- **Phase 2, Standardise & Digitise (2025)** → FP&A modernisation, pricing analytics, customer profitability
- **Phase 3, Decision Support (2025–2026)** → treasury, capital allocation, M&A
- **Phase 4, Strategise (2026–2027)** → equity story, investor narrative, capital strategy

---

## 5. The Financial Story — Including the Bad Year

The financials include operational volatility to reflect real-world performance dynamics.. Here's the real shape:

Revenue grew from €5.27B (FY2023) to €5.78B (FY2024) to €6.2B (FY2025). But **FY2024 was a bad year underneath the surface** — reported EBITDA margin actually *fell* to 16.2%, dragged down by an €85M restructuring charge and €63M of supply chain disruption costs (expedited freight, chip shortage cover-buys). Strip those out and adjusted EBITDA margin was a flat 18.8% — still a stall, not the growth story leadership wanted. FY2025 shows real recovery, adjusted EBITDA margin reaching 20.0%, though FX translation (a strengthening EUR against USD and BRL) shaved €28M off the reported number.

This dip is not incidental — **it's a key driver behind the approval of Project Meridian.** The CFO used the gap between reported and adjusted EBITDA in 2024 as the burning-platform argument to the Board. It introduces reporting inconsistencies across business units: Orion's five business units currently use **four different working definitions of "adjusted EBITDA,"** contributing to reporting inconsistencies across finance and business units.

Net debt ticked up temporarily in FY2024 (restructuring cash costs) before falling to €890M in FY2025 — a deleveraging trend that becomes relevant when Workstream 8 asks whether Orion can afford to build another factory.

---

## 6. The Close Process, As It Actually Runs Today

The close currently takes **nine business days**, against a Board-mandated target of five. It unfolds roughly like this:

Days 1–2 are sub-ledger close — AP/AR cutoff and intercompany billing cutoff, run out of SSC Poland. Days 2–3 handle fixed asset roll-forward, inventory close, and payroll accruals across SSC Poland and FinOps India. By days 3–4, each of the 17 entities closes its own GL independently — there's no synchronised close calendar across entities, which is itself part of the problem. Days 4–6 are consolidation, where Corporate Finance layers manual adjustments on top of the SAP consolidation Phase's output, because the Phase's output alone isn't trusted. Days 6–7 cover balance sheet reconciliation and substantiation — 18 reconciliation packs per entity, using inconsistent templates. Days 7–8 are spent assembling the management reporting pack, which currently means stitching together 42 separate Excel files. The cycle closes on days 8–9 with review, final adjustments, and sign-off at the Close Steering Committee.

**The baseline numbers measured against:**

| Metric | Current State |
|---|---|
| Close duration | 9 business days |
| Manual journal entries per month | ~1,200 group-wide |
| Reconciliation packs per cycle | 18 per entity (306 total) |
| Standalone Excel reporting files | 42 |
| Finance FTE-days consumed in close | ~410/month |
| Entities with late postings requiring reopening | ~9% per cycle |
| Restatements in past 12 months | 6 (2 material enough for Audit Committee) |

---

## 7. Governance, Briefly

A **Close Steering Committee** meets monthly, chaired by the CFO, to review close performance and sign off on consolidated results. A Board-level **Audit Committee** meets quarterly, reviewing restatements and control deficiencies alongside the external auditor (a Big 4 firm, deliberately unnamed).

Orion isn't SOX-listed given its private status, but the Board has mandated SOX-equivalent rigor ahead of a possible future IPO — journal entries follow an approval hierarchy (below €10k needs one reviewer; €10k–€100k needs Controller sign-off; above €100k needs Group Controller sign-off; above €1M triggers CFO notification), and Group materiality sits at €12M, with individual reconciling items investigated above €50k at entity level and €100k at Group level.

---

## 8. The Pain Points Register

This is the register that justifies almost everything built herein. Each item below is tagged to the workstream it feeds.

**Feeds Workstream 1 (Close):**
- 37% of journal entries are still manual Excel uploads into SAP, with no automated interface — a direct driver of both error risk and close delay.
- AP postings from three APAC entities routinely arrive after cutoff, because local statutory filing deadlines conflict with the Group close calendar. This is the actual root cause of the Day 1–2 bottleneck.

**Feeds Workstream 2 (Balance Sheet Reconciliation):**
- Intercompany reconciliation rules differ by region: EMEA nets monthly, APAC nets quarterly, Americas doesn't net at all — mismatches routinely persist one to two quarters before resolution.
- SSC Poland's legacy cost centre mapping doesn't fully align with SAP HQ's master data structure — an estimated 6% of cost centres are mismapped, distorting cost allocation.
- FX revaluation calculated in SAP doesn't tie to Treasury's own exposure system, leaving a persistent €2–4M unexplained variance every cycle that gets manually bridged.
- Fixed asset sub-ledgers and GL balances diverge in four entities due to manual depreciation adjustments.

**Feeds Workstream 3 (Management Reporting):**
- Four different working definitions of "Adjusted EBITDA" exist across the five business units.
- FP&A, Corporate Finance, and BU Finance each maintain separate actuals extracts with different as-of dates — there's no single source of truth.

**Feeds Workstream 4 (FP&A Transformation):**
- Orion still runs a single annual budget cycle with no rolling forecast — the budget is set in November and effectively goes stale by Q2, forcing constant off-cycle re-forecasting that FP&A does manually, entity by entity.
- Forecast accuracy isn't tracked in any structured way. Regional FP&A teams each define "forecast accuracy" differently, so there's no consistent basis for the Board to judge whether a region is over- or under-forecasting.
- Budget-vs-actual variance commentary is written manually into PowerPoint each month by five separate BU FP&A teams, with no shared driver-based model underneath so variance explanations are narrative, not quantified.

**Feeds Workstream 5 (Pricing Analytics):**
- There's no group-wide, product-level margin visibility. Pricing decisions are made locally by regional commercial teams, with Finance seeing the P&L impact only after the fact.
- Discounting authority is decentralised down to account managers in several regions, with no systematic tracking of discount depth against customer profitability, a pattern flagged internally but never quantified.
- List prices for the same product can differ by more than 15% across regions with no documented rationale tied to cost-to-serve or local market elasticity.

**Feeds Workstream 6 (Customer Profitability):**
- Roughly 2,800 duplicate or near-duplicate customer records exist across Salesforce and SAP, a legacy of historical M&A activity and absent MDM governance.

**Cuts across multiple workstreams:**
- About 4% of active vendor records were flagged in the last audit for incomplete banking or tax data — an AP control gap relevant to both Workstream 1 and Workstream 2.

---

## 9. How the Systems Actually Talk to Each Other

Understanding where data physically moves — and where it breaks — is the real diagnostic foundation for Workstreams 1 and 2.
Customer data flows nightly from Salesforce into SAP via partial field mapping, which is exactly where the 2,800 duplicate records originate. Each of the 17 entity ledgers in SAP feeds into the Group Consolidation Phase, but Corporate Finance doesn't trust that output on its own — hence the manual Excel adjustments layered on top every cycle. Treasury's FX and cash system feeds SAP monthly, but the two systems' FX revaluation figures don't reconcile, producing that recurring €2–4M gap. Concur feeds AP via batch upload; Workday feeds payroll accruals into the GL monthly, with timing mismatches flagged in two of the last four cycles. SSC Poland's local cost centre mapping table feeds into SAP HQ's master data, with the 6% mismatch already noted. And FinOps India produces those 18 reconciliation packs per entity in manual Excel templates with no standard format, which Corporate Finance then reviews one by one before the Group Consolidation output is finally extracted — manually — into the 42 separate files that make up the management reporting pack.
Several finance teams maintain parallel Excel-based ‘shadow models’ for reporting and forecasting due to perceived limitations in SAP and SAC outputs.
**The diagnostic takeaway:** the close isn't slow because of one bottleneck. It's slow because of five uncoordinated manual bridges between systems that were never designed to talk to each other natively. That finding, quantified, is what the Workstream 1 current-state assessment needs to land on.

---

## 10. Chart of Accounts — Detail to Feel Real

The account structure follows standard SAP numeric ranges — assets in the 100000s–300000s, liabilities in the 400000s–500000s, equity in the 600000s, revenue in the 700000s, cost of goods sold in the 800000s (low range), operating expenses in the 800000s (high range), and non-operating items in the 900000s.

Revenue and cost accounts are segmented by business unit, product line, and region. For example, Semiconductor Equipment revenue splits into separate EMEA, Americas, and APAC accounts (700100/700110/700120), and its cost of goods sold splits into direct materials, direct labour, manufacturing overhead, scrap and rework, and warranty provision (800210 through 800250). Renewable Energy Systems revenue is not yet consistently segmented by region, creating reporting granularity gaps. A deliberate gap the Board has already flagged as a reporting granularity request, and a natural thread for a future Workstream.

Intercompany transactions are tracked in dedicated account ranges for receivables, payables, and eliminations: receivables and payables by counterparty entity (295000s and 495000s), plus dedicated elimination accounts for intercompany revenue and cost (799000 and 899000).

Cost centres follow a `[Region]-[BU]-[Function]-[sequence]` convention, e.g. `EMEA-SEMI-MFG-1042`. Profit centres align to the intersection of Business Unit and Region.

---

## 11. Standing Narrative Rules

A few rules keep 18 months of Workstreams consistent:
- Every figure, name, and structure in this document is locked. Changes get logged at the top of this file, not made silently.
- Every workstream should trace back to Project Meridian explicitly — it's the reason the work exists.
- Recurring characters should reappear where plausible: Okonkwo commissions Workstream 1, van der Berg is the audience for the Workstream 11 Investor Day deck, and so on.
- Financial data introduced in later workstreams must stay arithmetically consistent with Section 5.
- Anything new introduced in an workstream — a person, an entity, a number — gets folded back into this document as a logged revision, not left orphaned in one project's files.

---
