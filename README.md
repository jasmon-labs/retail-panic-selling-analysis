# 📊 Retail Panic Selling Analysis

This project explores how retail investors in India reacted to the Russia–Ukraine conflict in February 2022.  
By combining Google Trends data on panic sentiment with trading volumes of Nifty 50 (large-cap, institutionally heavy) and mid-cap defense stocks like BHEL and BEL (retail heavy), the study aims to reveal the timing and behavioral differences in market reactions.

> 📌 This repository supports the making of my **Research Paper** (June–July 2025).

---

## 📂 Project Structure

- **`/`**
  - `Research-Paper_Stocks-Analysis.ipynb` – Extracts stock data (opening & closing prices, volumes) and saves to CSV.
  - `ResearchPaper-Data2.ipynb` – Generates plots and visualizations (PNG format).

- **`csv-dataframes/`**
  - Contains cleaned & raw data files used in analysis, e.g.:
    - `google_trends.csv`
    - `Ticker_Large-Mid_Cap_Stock_values.csv`

- **`charts/`**
  - Visual charts generated from notebooks:
    - `combined_volume_vs_google_trends.png`
    - `nifty_volume_vs_google_trends.png`
    - `Normalized_Closing_Prices.png`

- **`README.md`**
  - Project overview and setup instructions.

---

## 🧪 Objectives

- Identify whether panic selling by retail investors shows an immediate spike or a lag (T+1/T+2).
- Compare volume and price movement between retail-heavy mid-cap stocks and the large-cap Nifty index.
- Study sectoral patterns of FOMO buying (e.g., defense) during geopolitical shocks.
- Use online sentiment (Google Trends) to explain or anticipate retail behavior.
- Propose and validate the **Lagged Behavioral Response Framework (LBRF)**.

---

## ⚙️ Dependencies

Make sure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `yfinance`

Install using:

```bash
pip install numpy pandas matplotlib seaborn yfinance
