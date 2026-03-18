# Time Series Analysis of Oil Prices and Their Potential in Forecasting Airline Stocks (DS4002 - Group 14)
This project attempts to use changes in oil prices to predict monthly airline ETF returns beyond what is already captured by the broad SPY stock market. 

## Contents of this Repository


## Software and Platform Selection
Software: 
 - Google Colab
 - Git / GitHub
 - Jupyter Notebook

Add-on Packages: 
 - p

Platform Used:
 - macOS

## Documentation Map

```text
Ds4002-Group14-Project2/
│
├── README.md
│   └── Contains:
│       • Project overview
│       • Research question & motivation
│       • Software & package requirements
│       • Documentation map
│       • Instructions for reproducing results
│
│   
├── DATA/
│    │
│    └── raw_yfinance_daily_data.csv                                 
│               
│
├── SCRIPTS/
│   │
│   ├── Script 01: Load Data.ipynb
│   │   └── Scrapes Reddit posts and comments for:
│   │       USPS, UPS, FedEx, DHL
│   │       • Cleans text data
│   │       • Removes boilerplate/spam
│   │       • Exports:
│   │           - shipping_posts_raw.csv
│   │           - shipping_comments_raw.csv
│   │           - shipping_comments_clean.csv
│   │
│   └── Script 02: Exploratory & Statistical Analysis.ipynb
│       └── Performs exploratory data analysis (EDA) :
│           • Comment counts by company
│           • Sentiment score distributions
│           • Mean sentiment with 95% confidence intervals
│           • Visualizations (histograms, boxplots, stacked bar charts)
│           • Saves plots to /output/figures/
│               
│
└── output/
    │
    ├── 01_normalized_monthly_prices.png
    ├── 02_monthly_returns.png
    ├── 03_correlation_matrix.png
    ├── 04_rolling_correlation_oil_jets.png
    ├── 05_full_model_comparison_rmse.png
    ├── 06_full_model_comparison_directional_accuracy.png
    ├── 07_focused_model_comparison_rmse.png
    ├── 08_focused_model_comparison_directional_accuracy.png
    ├── 09_actual_vs_predicted_best_presentation_model.png
    └── 10_best_rmse_by_model_family.png

```

# Instructions for Reproducing Results

This section provides explicit, step-by-step instructions to reproduce all results from our study. Follow the steps carefully and in order.

---

## 1. Download the Repository

Clone the repository from GitHub:

```bash
git clone https://github.com/simoneminorr/Ds4002-Group14-Project2.git
cd Ds4002-Group14-Project2
```

Or download the ZIP file from GitHub and extract it locally.

---

## 2. Install Required Software

### Python Version
Ensure you are using **Python 3.9 or higher**.

### Install Required Packages

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels vaderSentiment requests tqdm
```

---

## 3. Reproduce Yahoo Finance Analysis (Main Study Results)

Navigate to:

---

### Step 3.1 – Run `***`

T

---

### Step 3.2 – Run `***`

T

---

### Step 3.3 – Run `***`

T

---

## 4. Verify Successful Reproduction

You have successfully reproduced the results if:

- A
---

## Notes

- I


