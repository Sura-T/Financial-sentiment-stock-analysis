# Quantitative Financial Analysis Project

## Project Overview

This project focuses on analyzing financial and stock market data using tools like PyNance, TA-Lib, and Python’s data manipulation libraries. The objective is to uncover trends, patterns, and actionable insights by applying technical and quantitative analysis on datasets retrieved from Yahoo Finance (yfinance).

---

## Key Tasks Completed

### **1. Exploratory Data Analysis (EDA)**

#### **Descriptive Statistics**

- **Headline Length Analysis**: Basic statistics for textual lengths (e.g., average and maximum headline length) were calculated to understand textual data distribution.
- **Article Count Per Publisher**: Analyzed the frequency of articles published by different publishers to identify the most active contributors.
- **Publication Trends Over Time**: Analyzed publication dates for patterns such as increased frequency during specific events or timeframes.

#### **Text Analysis (Sentiment Analysis & Topic Modeling)**

- **Sentiment Analysis**: Applied natural language processing to classify headline sentiment into positive, negative, or neutral categories.
- **Keyword and Topic Extraction**: Identified common keywords, phrases, and topics (e.g., “FDA approval” or “price target”) to extract insights from news headlines.

#### **Publisher Analysis**

- Identified publishers contributing the most news and analyzed their reporting style (e.g., financial analysis vs. breaking news).
- Grouped articles by publisher domains to understand organizational contributions.

---

### **2. Quantitative Analysis Using PyNance and TA-Lib**

#### **Data Preparation**

- Loaded and cleaned stock market data from seven separate datasets obtained via yfinance.
- Ensured uniformity across datasets with essential columns like `Open`, `High`, `Low`, `Close`, and `Volume`.
- Organized data in a single Jupyter Notebook for streamlined analysis.

#### **Application of Technical Indicators**

Using **TA-Lib**:

- **Moving Averages (MA)**: Calculated 20-day and 50-day Simple Moving Averages to smooth out price data and identify trends.
- **Relative Strength Index (RSI)**: Evaluated momentum and potential overbought/oversold conditions using a 14-day RSI.
- **MACD (Moving Average Convergence Divergence)**: Analyzed the relationship between short-term and long-term price movements to identify bullish or bearish signals.

#### **Visualization of Indicators**

- Plotted closing prices alongside moving averages to identify crossover points.
- Created RSI charts with overbought and oversold thresholds to highlight significant events.
- Visualized MACD and signal lines to interpret price momentum shifts.

---

### **3. Consolidation of Multiple Datasets**

- Unified analysis for seven financial datasets within a single Jupyter Notebook.
- Leveraged loops and dictionaries to efficiently calculate indicators and create visualizations for each dataset.

---

## Tools and Libraries Used

1. **Python Libraries**:
   - `pandas` for data manipulation and cleaning.
   - `matplotlib` for data visualization.
   - `talib` for technical analysis indicators.
2. **Data Sources**:
   - Data retrieved via `yfinance` API.
3. **Jupyter Notebook**:
   - Centralized platform for development, visualization, and reporting.

---

## Future Work

- **Enhanced Analysis**: Add advanced sentiment analysis and topic modeling using libraries like SpaCy or Transformers.
- **Comparison with Market Events**: Correlate trends with real-world market events for deeper insights.
- **Predictive Modeling**: Incorporate machine learning algorithms to forecast stock price movements based on historical and indicator data.

---

## How to Run the Notebook

1. Install required Python libraries:
   ```bash
   pip install pandas matplotlib yfinance talib
   ```
2. Clone the repository and navigate to the project folder:
   ```bash
   git clone [repository_url]
   cd financial-analysis-project
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the notebook file and execute each cell in sequence to replicate the analysis.

---

## Conclusion

This project showcases the use of EDA and quantitative analysis tools to derive meaningful insights from financial datasets. By leveraging advanced libraries and analytical methods, we aim to assist traders and investors in making data-driven decisions.
This README is going to be edited...
