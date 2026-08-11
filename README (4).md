# Microsoft Corporation — Activision Blizzard Acquisition
## M&A Accretion/Dilution & Strategic Analysis

## 📄 Project Overview

This project is a full investment-banking-style analysis of Microsoft's acquisition of Activision Blizzard — built to answer one specific question: **was the deal financially justified, and what level of annual synergies was required for it to become EPS accretive?** Rather than a generic case study, the model is built around this thesis and quantifies the answer directly, using Microsoft's *final* (not preliminary) purchase price allocation and real, sourced financial data throughout.

Key techniques used:

- Purchase price allocation using Microsoft's final (post-measurement-period) 10-K disclosure
- Segment-specific tax-rate accretion/dilution bridge, preserving each company's real historical effective tax rate
- Synergy breakeven analysis, solved directly against Microsoft's standalone EPS
- Five-year linked pro forma income statement, balance sheet, and cash flow statement
- A liquidity-rebuild analysis in place of a conventional (and here, inapplicable) debt-paydown narrative

---

## 🏗️ Project Structure

| File | Description |
|------|-------------|
| **Sam_Felix_MSFT_ATVI_MA_Model.xlsx** | Complete linked model: transaction terms, purchase price allocation, standalone historicals, sources & uses, accretion/dilution bridge, synergy breakeven with sensitivity tables, five-year pro forma income statement, balance sheet, and cash flow (11 tabs, fully formula-linked, balance-checked to $0) |
| **MSFT_ATVI_Full_Report.pdf** | Full written report — transaction overview through final recommendation, with every figure tagged [SOURCED], [ASSUMPTION], [MODEL-DERIVED], or [INTERPRETATION] |
| **MSFT_ATVI_Executive_Summary.pdf** | One-page summary with the four headline findings |
| **MSFT_ATVI_Deck.pptx** | 9-slide presentation deck covering the transaction, financing, accretion/dilution, synergy breakeven, five-year EPS path, liquidity rebuild, strategic rationale, and final verdict |

*(Source data: Microsoft's FY2025 Form 10-K (final Activision purchase price allocation), Microsoft's FY2023 Form 10-K and earnings release, Activision Blizzard's FY2022 Q4 earnings release exhibit — all publicly available via [SEC EDGAR](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000789019&type=10-K).)*

---

## 🔍 Key Findings

- **Base deal economics are dilutive.** With zero synergies, the transaction dilutes Microsoft's EPS by approximately **4.07%** in Year 1 — driven by foregone interest income on deployed cash and new intangible-asset amortization, not by operational weakness at either company.
- **The EPS-neutral synergy hurdle is exceptionally large.** Reaching 0% accretion/dilution requires approximately **$3.637 billion** of annual pre-tax synergies — equal to roughly **48.31%** of Activision's entire FY2022 revenue. This is a model-derived breakeven point, not a figure Microsoft has guided to.
- **The five-year EPS path improves steadily and turns accretive**, moving from -3.10% in Year 1 to +2.33% by Year 5 as synergies ramp and intangible amortization steps down — a scenario outcome under the model's own assumptions, not a prediction of realized results.
- **Microsoft's cash-generation capacity could absorb the deal quickly.** Under the model's forecast assumptions, cumulative post-close cash generation would rebuild the $61.8 billion of liquidity deployed in approximately **2.40 years**, without a debt-paydown story, asset sales, or an interruption to dividends and buybacks.
- **The deal is more defensible as a long-duration strategic investment than as a traditional cost-synergy transaction** — the EPS-accretion lens is a real and useful discipline, but it isn't by itself sufficient to judge whether the deal made strategic sense; that depends on revenue synergies and ecosystem value the model isn't built to price.

---

## 🛠️ Tools & Techniques Used

- Microsoft Excel (linked three-statement modeling, segment-specific tax bridging, sensitivity tables, formula-driven interpolation)
- Purchase price allocation and accretion/dilution analysis
- Financial statement analysis across two standalone companies and one combined pro forma entity
- Scenario modeling with explicit, disclosed assumptions distinguished from sourced figures throughout
- Professional report and presentation development

---

## 🚀 How to Use

- Download the `.xlsx` to review the full model — every input is color-coded (blue = sourced/hardcoded, black = formula, green = cross-sheet link), with sources cited directly next to each figure.
- The workbook includes a permanent balance check (Total Assets − Total Liabilities & Equity = $0) and a Year-1 reconciliation check confirming the five-year forecast ties back exactly to the base-case bridge.
- Read the full report for the complete narrative, or the one-page executive summary for a quick read.
- This project is intended as a portfolio showcase for roles in:
  - Corporate Finance / FP&A
  - Investment Banking / M&A
  - Financial Analyst (broadly)

---

## ✍️ Author

Sam Felix
LinkedIn: [Sam Felix](https://www.linkedin.com/in/sam-felix-644b492b2/)
Email: 2samfelix@gmail.com

---

## 📢 Disclaimer

This project is for educational and personal portfolio purposes only. All historical financial data is sourced from Microsoft Corporation's and Activision Blizzard, Inc.'s official public filings (SEC EDGAR) and press releases. The author makes no claim of affiliation with either company. Growth, margin, tax-transition, and cash-flow assumptions beyond reported historicals are the author's own model assumptions, clearly disclosed as such throughout the workbook and report. Not investment advice.
