# S&P 500 Valuation vs. Annual Return Analysis

## 1. Problem & User
This project explores how valuation metrics correlate with stock performance, helping investors understand whether "value investing" strategies work in a sample of S&P 500 stocks.

## 2. Data
- **Source**: Yahoo Finance
- **Access date**: 25 April 2026
- **Key fields**: Stock ticker, PE ratio, PB ratio, Dividend Yield, Annual Return

## 3. Methods
- Load and clean the dataset using Pandas
- Generate descriptive statistics to understand variable distributions
- Build a correlation heatmap to examine relationships between metrics
- Create scatter plots of PE, PB, and Dividend Yield against Annual Return
- Export cleaned data and visualizations as separate files

## 4. Key Findings
- PE ratio shows the strongest negative correlation with annual returns; lower PE stocks outperformed in the sample
- PB ratio has almost no clear relationship with returns
- Dividend yield shows only a weak positive correlation with performance
- The results suggest PE ratio is the most useful metric for identifying value opportunities in this dataset

## 5. How to run
1.  Open the Jupyter Notebook `ACC102_Track2_[YourName].ipynb`
2.  Run all cells sequentially to reproduce the analysis
3.  Visualizations and cleaned data will be saved in the same directory

## 6. Product link / Demo
- GitHub Repository: https://github.com/xiaoyubuss/my-acc102-track2/edit/main/README.md
- Demo Video:https://video.xjtlu.edu.cn/Mediasite/Play/cec74128c56a4e36aaabc771ba51e72e1d

## 7. Limitations & next steps
- **Limitations**: Small sample size of only 20 stocks; results may not generalize to the full S&P 500; does not control for sector or market conditions
- **Next steps**: Expand the sample to include more stocks and time periods; add sector and market cap controls; use statistical tests to validate correlations
