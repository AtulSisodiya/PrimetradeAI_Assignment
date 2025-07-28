# Trader Sentiment Analysis on Hyperliquid Data

This project explores the relationship between trader behavior on the **Hyperliquid** platform and broader **Bitcoin market sentiment** using the **Fear & Greed Index**. The objective is to uncover hidden behavioral patterns and derive **actionable trading strategies** based on real market signals.

---

## Key Findings

- **Fear is a Catalyst for Opportunity**  
  Periods of **Extreme Fear** consistently show the highest **trading volume** and **average profitability**. This suggests that **volatility**, not optimism, offers the most rewarding opportunities.

- **Divergence as a Predictive Signal**  
  The strongest insights emerge when **sentiment and net volume diverge**:
  
  - **Bearish Divergence **: High sentiment (Greed) + negative net volume → often precedes **market tops**.
  - **Bullish Divergence **: Low sentiment (Fear) + positive net volume → often signals **market bottoms**.

- **Actionable Strategy**  
  Use sentiment as a **volatility gauge** and divergence as a **confirmation signal**.  
  ➤ Example: **Buy only when Extreme Fear is confirmed by positive net volume (accumulation).**

---

## Project Structure
├── needed/
│ ├── fear_greed_index.csv # Market sentiment data
│ └── historical_data.csv # Hyperliquid platform trading data
├── outputs/
│ ├── TraderBehaviour.png # Visualization: Trader behavior by sentiment
│ └── DivergenceAnalysis.png # Visualization: Sentiment vs. net volume divergence
├── notebook_1.ipynb # Main analysis notebook (Colab-ready)
├── ds_report.pdf # Final project summary report
└── readme.md 


---

## Getting Started

### Run in Google Colab

1. **Open the Notebook**  
   Upload and open `notebook_1.ipynb` in [Google Colab](https://colab.research.google.com/).

2. **Upload Required Data**  
   Upload the CSV files from the `needed/` directory into your Colab environment.

3. **Execute the Analysis**  
   Run the notebook cells in order. It will handle dependencies, process data, and generate visualizations automatically.

---

## Dependencies

Make sure the following Python libraries are installed (automatically handled in Colab):

- `pandas`
- `matplotlib`
- `seaborn`
- `gdown`

---

## Visualizations

- **Trader Behavior by Sentiment**  
  Shows how volume, PnL, and net volume vary by Fear & Greed classification.

- **Divergence Analysis**  
  Plots net volume vs. sentiment to identify **bullish** and **bearish** divergence zones.

---

## 📄 Report

For a deeper dive into the methodology and results, see the [📘 `ds_report.pdf`](./ds_report.pdf) included in the repository.

---

