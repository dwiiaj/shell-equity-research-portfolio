# Shell plc (SHEL) Equity Research & Valuation Portfolio

Independent equity research and valuation work on Shell plc, built as part of my transition into asset management. I'm an MSc Data Analytics for Economics and Finance student (University of Glasgow), and this repo documents my process of applying fundamental valuation and quantitative analysis to a real, complex energy company — from first principles, using primary source data.

## Why Shell?

Shell sits at the center of some of the most interesting tensions in equity analysis right now: capital allocation between legacy oil & gas cash flows and energy transition investment, sensitivity to volatile commodity prices, and a valuation gap between intrinsic worth and market pricing that's worth interrogating rather than assuming away. I picked one company and am going deep, building the kind of multi-angle view (fundamental, quantitative, risk) that an equity or portfolio analyst would actually produce.

## Projects

### 01 — DCF Valuation & Investment Memo ✅ Complete
A full discounted cash flow model built from Shell's 2025 Annual Report and 20-F filing (not third-party aggregator data).

- Historical financials, 2020–2025
- 5-year forecast, 2026–2030
- WACC via CAPM (~7.22%)
- Terminal value and intrinsic value per share: **$59.59** vs. ~$91 market price → **SELL**, ~35% implied downside
- Sensitivity analysis (WACC × terminal growth heatmap)
- Waterfall chart of value bridge components
- Written investment memo summarizing thesis, methodology, and risks

[View notebook](./01-dcf-valuation/shell_dcf_model.ipynb) · [Investment memo](./01-dcf-valuation/investment_memo.docx)

### 02 — Equity Research Report 🔜 In Progress
Broader qualitative + quantitative research report: industry positioning, competitive landscape, catalysts, and risk factors.

### 03 — Portfolio Tracker & Risk Dashboard 🔜 Planned
Tracking Shell alongside sector peers with risk metrics (volatility, beta, drawdown).

### 04 — Return Forecasting (ARIMA/GARCH) 🔜 Planned
Time-series modeling of Shell's return and volatility behavior.

## Approach

- **Primary sources only**: all figures sourced directly from Shell's annual report and SEC 20-F filing, not data aggregators.
- **Built from scratch**: every model, chart, and calculation is my own — designed to be re-run and audited (see execution notes below).
- **Tools**: Python (pandas, matplotlib), Jupyter Notebook, Excel.

## Note on running the notebook

Cells depend on variables defined earlier in the notebook — use **Restart & Run All** rather than running cells individually.

---
📫Built by (https://www.linkedin.com/in/dwiajengratri/)
