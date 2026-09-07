<div align="center">

# 🚲 Easy Velo — A Bike-Subscription Business Plan

### Financial Toolbox — Group Assignment · MSc International Business Management & Finance

<p>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Rennes%20School%20of%20Business-002B5C?style=for-the-badge" alt="RSB"/>
</p>

<p>
  <img src="https://img.shields.io/badge/model-P%26L%20%C2%B7%20BS%20%C2%B7%20WACC%20%C2%B7%20Break--even-blue?style=flat-square" alt="model scope"/>
  <img src="https://img.shields.io/badge/status-completed-brightgreen?style=flat-square" alt="completed"/>
  <img src="https://img.shields.io/badge/net%20margin-28.2%25-orange?style=flat-square" alt="28.2% net margin"/>
</p>

**Can a bike-subscription service actually turn a profit in Rennes — and how many subscribers does it need before it does?**
Financial modeling · P&L forecasting · Balance sheet structuring · Cost of Capital (WACC) · Break-even analysis

</div>

---

## 📌 TL;DR

| Question | Answer |
|---|---|
| Is the idea profitable in year 1? | ✅ Yes — **€15,497** net profit / year on **€54,880** in sales (28.2% net margin) |
| How many subscribers to break even? | 🚲 **152 active subscriptions/month** (≈ €3,884 in monthly revenue) |
| How is it financed? | 71% equity (savings + angel loan) / 29% debt, **WACC = 3.94%** |
| What's the biggest cost driver? | Not maintenance — it's **rent + marketing + admin** (2,200€/mo, 3× the COGS) |

---

## 📂 Table of Contents
1. [The idea](#-the-idea)
2. [Key assumptions](#-key-assumptions)
3. [Financial model & results](#-financial-model--results)
4. [Visuals](#️-visuals)
5. [Conclusion](#-conclusion)
6. [Repo contents](#-repo-contents)
7. [Stack](#️-stack)
8. [A note on AI usage](#-a-note-on-ai-usage-in-this-repo)

---

## 💡 The idea

**Easy Velo** is a second-hand bike subscription service for Rennes, France — the same model as [Swapfiets](https://swapfiets.fr/): instead of buying a bike, customers pay a flat monthly fee and Easy Velo handles maintenance and replacement.

> Group Assignment brief (30% of the course grade): *build a simple business plan and show whether it can make money*, covering the business idea, value proposition, revenue plan, a one-year P&L, two justified financial ratios, a SWOT, a sustainability angle, and a closing pitch. See [`Assignment_Brief.docx`](Assignment_Brief.docx).

## 🧮 Key assumptions

| Item | Assumption | Source |
|---|---|---|
| Fleet | 350 second-hand bikes @ €300/unit | [Decathlon listing](https://www.decathlon.fr/) |
| Utilization | 80% of fleet in active subscriptions (280 bikes) | Benchmarked against a reference case study (~67% utilization) and adjusted upward for the Rennes market |
| Pricing | €15.5/month subscription + €10 one-time onboarding fee | [Swapfiets pricing](https://swapfiets.fr/) |
| Maintenance | 5% of active bikes need service/month, €6/bike average cost | — |
| Staffing | 1 part-time mechanic (€570/mo) + 1 part-time admin (€500/mo) | French minimum wage reference |
| Fixed costs | Store rent €1,200/mo, marketing €500/mo, app maintenance €200/mo | Rennes commercial listing |
| Financing | €11,000 private/angel loan + €26,900 savings (equity) + €80,000 bank loan for the initial fleet | — |
| Cost of capital | Cost of equity 3.46% (10Y French OAT bond) · Cost of debt 6% (average bank rate) · Tax 15% | — |

## 📊 Financial model & results

<table>
<tr><th>Statement</th><th>Key figures</th></tr>
<tr>
<td><b>P&L (monthly → yearly)</b></td>
<td>Total Sales <b>€7,140 → €54,880</b> · COGS €854 → €10,248 · Gross Profit <b>€6,286</b> (88.0% margin) → €44,632 · OpEx €2,200 → €26,400 · Net Profit <b>€3,473 → €15,497</b> (28.2% net margin)</td>
</tr>
<tr>
<td><b>Balance Sheet (opening)</b></td>
<td>Net Fixed Assets €87,900 (bikes €84,000 + tools/furniture €3,900) · Net Current Assets €30,000 (working capital) · Bank Loan €80,000 · <b>Net Assets / Equity €37,900</b></td>
</tr>
<tr>
<td><b>Cost of Capital</b></td>
<td>Weight of Debt 29.0% · Weight of Equity 71.0% · <b>WACC = 3.94%</b></td>
</tr>
<tr>
<td><b>Break-even (Year 1)</b></td>
<td>Contribution margin €19.5/subscription (price €25.5 − variable cost €6) on fixed costs of €2,970/month → <b>152 subscriptions</b> (€3,884/month) to break even</td>
</tr>
</table>

## 🖼️ Visuals

<table>
<tr>
<td width="50%"><img src="figures/pnl_bridge_chart.png" alt="Monthly P&L bridge"/><p align="center"><sub>Monthly P&L bridge — from sales to net profit</sub></p></td>
<td width="50%"><img src="figures/breakeven_chart.png" alt="Break-even chart"/><p align="center"><sub>Break-even point at 152 active subscriptions</sub></p></td>
</tr>
</table>

## ✅ Conclusion

The model **supports the idea's viability**: at the planned 80% fleet utilization (280 active subscriptions), Easy Velo sits comfortably above its 152-subscription break-even point, generating a healthy 28.2% net margin in year 1. The financing mix (mostly equity + a small angel loan, plus a separate bank loan for the fleet itself) keeps the **WACC low at 3.94%**, which is favorable given the business isn't capital-structure sensitive at this stage — the real risk lever is **utilization**, not financing cost: every point of occupancy below the 80% assumption moves the business meaningfully closer to its break-even line.

<details>
<summary>⚠️ Limitations (self-critique)</summary>

- Utilization (80%) is the single most sensitive assumption in the whole model and is benchmarked against one reference case study, not Rennes-specific market data.
- The model is a **year-1 snapshot** — no multi-year growth, churn, or fleet-replacement cycle is modeled.
- Marketing spend (€500/mo) is assumed constant regardless of the customer-acquisition results it needs to deliver (152+ subscriptions).
- The €80,000 bank loan is not folded into the WACC calculation (which only weights the €11,000 angel loan against equity) — a fuller model would size WACC against total financing, not just the working-capital piece.

</details>

## 📁 Repo contents

| File | Description |
|---|---|
| [`EasyVelo_Financial_Model_LDELOT.xlsx`](EasyVelo_Financial_Model_LDELOT.xlsx) | Full financial model — 5 sheets: Assumptions, P&L, Balance Sheet, Cost of Capital, Break Even |
| [`Assignment_Brief.docx`](Assignment_Brief.docx) | Official assignment brief (objective, required slide contents, grading weight) |
| `figures/` | P&L bridge and break-even charts (rendered from the model's figures) |

## 🛠️ Stack

<p>
<img src="https://img.shields.io/badge/Microsoft%20Excel-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/Financial%20Modeling-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/WACC-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/Break--Even%20Analysis-blue?style=flat-square"/>
</p>

## 🤖 A note on AI usage in this repo

The **business idea, financial model, and assumptions are the group's own work**, submitted for the Financial Toolbox course.

**Claude (Anthropic)** was used *afterwards*, and only for one thing: organizing the local project files and publishing this repository to GitHub in a clean, structured way (including rendering the two charts in `figures/` directly from the model's own numbers).

---

<div align="center">

**Author:** [Ludovic Delot](https://github.com/ludodelot) — MSc International Business Management & Finance, Rennes School of Business

</div>
