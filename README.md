# Retail-Finance-Analysis-ACC102
Python-based financial analysis of 10 A-share retail listed companies in 2024, completed for ACC102 Track2 Mini Assignment (XJTLU)

## 1. Project Overview
- **Analytical Problem**: Evaluate the solvency and profitability of 10 A-share retail listed companies through 3 core financial indicators: debt-asset ratio, gross profit ratio, and net profit ratio.
- **Target User**: Entry-level investors and financial analysis interns who need a simplified, data-driven reference for retail industry investment.
- **Core Objective**: Identify the retail enterprise with the strongest comprehensive financial performance and provide actionable investment insights.

## 2. Data Source
- **Source**: Eastmoney.com (China's leading financial information platform)
- **Access Date**: 10 April 2026
- **Dataset Details**: 10 A-share retail listed companies, 3 key 2024 annual financial indicators, 10 rows × 4 columns of structured data

## 3. Python Tools & Analytical Workflow
- **Core Libraries**: pandas (data loading/cleaning), numpy (numerical calculation), matplotlib & seaborn (data visualization)
- **Full Workflow**:
  1. Raw data loading & format verification
  2. Data cleaning (missing value removal, duplicate data elimination, abnormal value filtering)
  3. Descriptive statistical analysis (industry average calculation)
  4. Multi-dimensional data visualization (bar charts, correlation heatmaps, dual-axis comparison charts)
  5. Insight generation & conclusion output

## 4. Key Business Insights
1. **Industry Solvency Level**: The average debt-asset ratio of the A-share retail industry in 2024 is **61.42%**, with **Wangfujing** achieving the lowest ratio, representing the strongest short-term solvency and operational stability.
2. **Profitability Leadership**: **Wangfujing** ranks first in both gross profit ratio (38.27%) and net profit ratio (5.18%) among the 10 companies, demonstrating excellent cost control and profitability.
3. **Indicator Correlation**: There is a significant positive correlation between gross profit ratio and net profit ratio in the retail industry, meaning companies with higher gross margins generally achieve higher net profit margins.

## 5. Repository File Structure
- `retail_finance_2024_raw.csv`: Original raw financial data
- `retail_finance_2024_cleaned.csv`: Cleaned, standardized dataset for analysis
- `retail_analysis.ipynb`: Complete Jupyter Notebook with full analytical code and running results
- `Gross_Profit_Ratio_Bar.png`: Bar chart of gross profit ratio for all companies
- `Financial_Indicators_Correlation.png`: Heatmap of correlation between the 3 financial indicators
- `Debt_Asset_Net_Profit_Subplot.png`: Dual-axis comparison chart of debt-asset ratio and net profit ratio

## 6. Author Information
- **Student Name**: Sitong Kong
- **GitHub Username**: @VesperKong
- **Module**: ACC102 Financial Accounting (Semester 2, 2025-2026, Xi'an Jiaotong-Liverpool University)
