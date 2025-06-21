# Analysis of Trader Behavior and Market Sentiment

This repository contains the full analysis for the Junior Data Scientist assignment. The project explores the relationship between trader performance on the Hyperliquid platform and the crypto market's Fear & Greed sentiment index.

## 📂 Repository Contents

-   `Trader_Behavior_Analysis.ipynb`: The complete Jupyter Notebook containing all the Python code for data loading, cleaning, analysis, and visualization.
-   `Trader_Behavior_Analysis_Report.pdf`: A detailed PDF report summarizing the project's methodology, key findings, and actionable insights.

## ✨ Key Findings

1.  **Profitability Paradox:** The largest average profits were recorded during periods of "Fear," while the typical trader achieved more consistent gains during "Greed."
2.  **Behavioral Pattern:** Trader activity is highest during "Extreme Fear" and systematically decreases as the market becomes more greedy, indicating a widespread "buy the dip" strategy.
3.  **Profile of a Top Trader:** The most successful traders are defined by their immense trading volume, not necessarily the highest win rate.

## 🚀 How to Run the Notebook

To replicate the analysis, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/[Your-GitHub-Username]/trader-behavior-analysis.git
    cd trader-behavior-analysis
    ```

2.  **Set up a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    # .\venv\Scripts\activate  # On Windows
    ```

3.  **Install the required libraries:**
    *The notebook uses pandas, numpy, matplotlib, and seaborn.*
    ```bash
    pip install pandas numpy matplotlib seaborn jupyterlab
    ```

4.  **Launch Jupyter Lab and open the notebook:**
    ```bash
    jupyter lab
    ```
    Then, open the `Trader_Behavior_Analysis.ipynb` file and run the cells.
