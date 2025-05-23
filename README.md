# 📊 Stock Analysis of Microsoft, Amazon, and NVIDIA

This project performs a comparative technical and statistical analysis of Microsoft (MSFT), Amazon (AMZN), and NVIDIA (NVDA) stock data over a 180-day period. It was created as part of the Essentials of Data Analysis Practical coursework for B.Sc (H) Mathematics.

## 🔍 Project Objectives
- Compare the volatility and return profiles of three major tech stocks
- Apply technical indicators like Moving Averages and Bollinger Bands
- Analyze daily returns using statistical and visual techniques
- Generate interactive candlestick and density plots using R

## 🛠 Tools & Packages Used
- **R & R Markdown**
- `quantmod` – for financial data retrieval
- `TTR` – for technical indicators
- `plotly` – for interactive visualizations
- `dplyr` – for data manipulation
- `ggplot2` – for custom plots

## 📁 Project Structure
- `stock_analysis.Rmd` – Main R Markdown file containing all analysis
- `stock_analysis.html` – Rendered HTML output of the report
- `README.md` – Project description and overview

## 📈 Key Insights
- **Microsoft (MSFT)**: Most stable with low volatility
- **Amazon (AMZN)**: Moderately volatile with a broad return range
- **NVIDIA (NVDA)**: High volatility, high risk-return profile

## ▶️ How to Run This Project
1. Open `stock_analysis.Rmd` in RStudio
2. Make sure the required packages are installed (see below)
3. Click **Knit** to render the report (HTML or PDF)

### 🔧 Install Required Packages
```r
install.packages(c("quantmod", "TTR", "plotly", "dplyr", "ggplot2"))
