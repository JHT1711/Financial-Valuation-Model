# 3-Statement Financial Model with DCF Valuation

A fully integrated financial model built in Excel featuring Income Statement, Balance Sheet, Cash Flow Statement, DCF Valuation, Financial Ratios, and Scenario Analysis.

## Project Overview

This model demonstrates:
- **3-Statement Integration** — Income Statement, Balance Sheet, and Cash Flow are fully linked
- **DCF Valuation** — Calculates Enterprise Value and Equity Value
- **Scenario Analysis** — Switch between Base, Bull, and Bear cases with one input
- **Financial Ratios** — Profitability, Liquidity, Leverage, and Return metrics

## Features

| Feature | Description |
|---------|-------------|
| Dynamic Assumptions | All inputs in one place for easy modification |
| Scenario Switcher | Type 1, 2, or 3 to toggle Base/Bull/Bear cases |
| 5-Year Projections | Revenue, costs, and cash flows projected over 5 years |
| DCF Valuation | Free Cash Flow, Terminal Value, and Present Value calculations |
| Auto-Balancing | Balance Sheet automatically balances with Cash as plug |

## Model Structure
```
Financial_Model.xlsx
├── Assumptions      → All user inputs and scenario selector
├── Income Statement → Revenue, COGS, Operating Income, Net Income
├── Balance Sheet    → Assets, Liabilities, Equity (auto-balancing)
├── Cash Flow        → Operating, Investing, Financing activities
├── DCF Valuation    → FCF, WACC discounting, Terminal Value
├── Ratios           → Profitability, Liquidity, Leverage, Returns
└── Scenarios        → Side-by-side comparison of all scenarios
```

## Scenario Assumptions

| Assumption | Base Case | Bull Case | Bear Case |
|------------|-----------|-----------|-----------|
| Revenue Growth | 10% | 15% | 5% |
| COGS (% of Revenue) | 60% | 55% | 65% |
| Operating Expenses | 20% | 18% | 23% |
| Discount Rate (WACC) | 10% | 8% | 12% |
| Terminal Growth | 3% | 4% | 2% |

## Sample Valuation Output

| Metric | Base Case | Bull Case | Bear Case |
|--------|-----------|-----------|-----------|
| Enterprise Value | $2,498M | $6,366M | $1,533M |
| Equity Value | $3,109M | ~$6,900M | ~$1,600M |

## How to Use

1. Open `output/Financial_Model.xlsx` in Excel
2. Go to **Assumptions** sheet
3. Change **F2** to:
   - `1` = Base Case
   - `2` = Bull Case
   - `3` = Bear Case
4. Entire model updates automatically
5. View results in **DCF Valuation** and **Scenarios** sheets

## Skills Demonstrated

- **Financial Modeling** — 3-statement integration
- **Valuation** — DCF, WACC, Terminal Value
- **Excel** — Formulas, IF statements, cell references
- **Scenario Analysis** — Sensitivity to assumptions
- **Financial Ratios** — Profitability, leverage, returns

## Author

**Jaikhush Thakkar**  
Double Major in Applied Statistics & Economics | Penn State University  
[GitHub](https://github.com/JHT1711) • [LinkedIn](https://www.linkedin.com/in/jaikhush-thakkar/)

---

*Disclaimer: This model is for educational purposes only and does not constitute financial advice.*
