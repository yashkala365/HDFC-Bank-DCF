# HDFC Bank Discounted Cash Flow (DCF) Valuation Model

An institutional-style equity valuation project that estimates the intrinsic value of HDFC Bank using a complete Discounted Cash Flow (DCF) framework.

The model automatically downloads live financial statements and historical market data from Yahoo Finance, forecasts financial performance, estimates Free Cash Flows (FCF), calculates the Weighted Average Cost of Capital (WACC) using CAPM, discounts future cash flows, estimates Terminal Value, performs Monte Carlo valuation, sensitivity analysis, scenario analysis, and peer comparison to provide a comprehensive valuation framework.

---

# Project Overview

Discounted Cash Flow (DCF) valuation is one of the most widely used valuation techniques in Investment Banking, Equity Research, Private Equity, and Corporate Finance.

This project demonstrates an end-to-end valuation workflow similar to institutional financial models used by investment professionals.

The notebook performs:

- Financial Statement Analysis
- Revenue Forecasting
- Operating Income Forecasting
- Free Cash Flow Projection
- CAPM Cost of Equity
- Weighted Average Cost of Capital (WACC)
- Enterprise Value Calculation
- Terminal Value Estimation
- Sensitivity Analysis
- Monte Carlo DCF Simulation
- Bull / Base / Bear Scenario Analysis
- Peer Valuation Comparison

---

# Features

- Live financial statements from Yahoo Finance
- Historical stock price download
- Automated financial statement cleaning
- Revenue forecasting
- Operating income forecasting
- CapEx modelling
- Depreciation forecasting
- Tax estimation
- Free Cash Flow calculation
- CAPM Cost of Equity
- WACC estimation
- Discounted Cash Flow valuation
- Terminal Value calculation
- Enterprise & Equity Value estimation
- WACC sensitivity analysis
- Monte Carlo DCF simulation
- Bull / Base / Bear scenarios
- Peer valuation dashboard
- Export financial models to CSV

---

# Financial Concepts Covered

- Financial Statement Analysis
- Corporate Valuation
- Discounted Cash Flow (DCF)
- Enterprise Value
- Equity Value
- Free Cash Flow (FCF)
- CAPM
- Cost of Equity
- Cost of Debt
- Weighted Average Cost of Capital (WACC)
- Terminal Value
- Sensitivity Analysis
- Monte Carlo Simulation
- Scenario Analysis
- Comparable Company Analysis
- Relative Valuation

---

# Workflow

```
Download Live Financial Statements
                │
                ▼
Historical Financial Analysis
                │
                ▼
Revenue Forecast
                │
                ▼
Operating Income Forecast
                │
                ▼
CapEx, Depreciation & Tax Forecast
                │
                ▼
Free Cash Flow Projection
                │
                ▼
CAPM Cost of Equity
                │
                ▼
WACC Calculation
                │
                ▼
Discount Future Cash Flows
                │
                ▼
Terminal Value Estimation
                │
                ▼
Enterprise Value
                │
                ▼
Sensitivity Analysis
                │
                ▼
Monte Carlo Simulation
                │
                ▼
Scenario Analysis
                │
                ▼
Peer Valuation
```

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- SciPy
- yFinance
- OpenPyXL
- Google Colab

---

# Model Components

## Financial Statement Collection

Downloads:

- Income Statement
- Balance Sheet
- Cash Flow Statement
- Historical Share Prices

---

## Revenue Forecast

Projects revenue over a five-year forecast period using historical growth rates.

---

## Operating Income Forecast

Estimates operating profit using forecast operating margins.

---

## Free Cash Flow Forecast

Calculates annual Free Cash Flow after considering:

- Operating Income
- Taxes
- Capital Expenditure
- Depreciation

---

## Cost of Capital

Calculates:

- Risk-Free Rate
- Beta
- Market Return
- Cost of Equity (CAPM)
- Cost of Debt
- Weighted Average Cost of Capital (WACC)

---

## Discounted Cash Flow

Discounts projected Free Cash Flows using WACC to estimate Enterprise Value.

---

## Terminal Value

Estimates continuing business value using the Gordon Growth Model.

---

## Sensitivity Analysis

Measures how Enterprise Value changes under different WACC assumptions.

---

## Monte Carlo Valuation

Runs thousands of simulations by varying:

- WACC
- Terminal Growth Rate

to estimate a probability distribution of intrinsic enterprise value.

---

## Scenario Analysis

Evaluates valuation under:

- Bear Case
- Base Case
- Bull Case

using different revenue growth, operating margin, and discount rate assumptions.

---

## Peer Valuation

Compares HDFC Bank with major Indian banking peers using:

- P/E Ratio
- Price-to-Book Ratio
- Return on Equity

---

# Visualizations

The notebook generates:

### Revenue Forecast

Projected revenue over the next five years.

---

### Operating Income Forecast

Operating profit trend across the forecast period.

---

### Free Cash Flow Forecast

Annual projected Free Cash Flow.

---

### Enterprise Value Sensitivity

Shows how valuation changes with different WACC assumptions.

---

### Monte Carlo Distribution

Probability distribution of Enterprise Value based on thousands of simulated valuation scenarios.

---

### Peer Valuation Dashboard

Comparison of valuation multiples and profitability across major Indian banks.

---

# Example Output

| Metric | Description |
|---------|-------------|
| Company | HDFC Bank |
| Forecast Period | 5 Years |
| Valuation Method | Discounted Cash Flow |
| Cost of Equity | CAPM |
| Discount Rate | WACC |
| Enterprise Value | Calculated |
| Equity Value | Calculated |
| Monte Carlo Simulations | 5,000 |
| Scenario Analysis | Bull / Base / Bear |

---

# Installation

Clone the repository

```bash
git clone https://github.com/yashkala365/HDFC-Bank-DCF.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

or open directly in Google Colab.

---

# Skills Demonstrated

- Equity Valuation
- Financial Modelling
- Corporate Finance
- Investment Banking
- Equity Research
- Financial Statement Analysis
- Discounted Cash Flow (DCF)
- Free Cash Flow Modelling
- CAPM
- WACC
- Monte Carlo Simulation
- Scenario Analysis
- Sensitivity Analysis
- Comparable Company Analysis
- Python Programming
- Financial Data Analysis
- Data Visualization

---

# Applications

This project demonstrates practical skills relevant to:

- Investment Banking Analysts
- Equity Research Analysts
- Private Equity Analysts
- Corporate Finance Teams
- Valuation Advisory
- Asset Management
- Financial Consulting
- Quantitative Finance

---

# Key Takeaways

- Built a complete end-to-end Discounted Cash Flow valuation model using live financial statement data.
- Forecasted revenue, operating income, and Free Cash Flow over a five-year projection horizon.
- Estimated Cost of Equity using CAPM and derived WACC for discounting projected cash flows.
- Calculated Enterprise Value and Equity Value using discounted cash flows and terminal value methodology.
- Enhanced valuation robustness through sensitivity analysis, Monte Carlo simulation, and Bull/Base/Bear scenario analysis.
- Benchmarked HDFC Bank against leading Indian banking peers using key valuation and profitability metrics.

---

# Author

**Yash Kala**

CFA Level III Candidate | Aspiring Equity Research & Investment Banking Analyst 
