# Comparative Market Risk Analysis of American Defense Stocks

This repository contains an empirical financial time series analysis comparing the market risk profiles of two major American defense contractors: **Northrop Grumman (NOC)** and **L3Harris Technologies (LHX)**. The study utilizes Vector Autoregressive (VAR) modeling in R to evaluate joint dynamics and risk transmission.

---

## 📄 Repository Structure

* `Comparative market risk analysis of two American defense stocks.pdf`: Seminar paper detailing the methodology, empirical results, and risk assessment.
* `Financial_Time_Series_VAR.Rmd`: R Markdown file containing the complete econometric pipeline (data loading, VAR specification, diagnostic checks, and risk analysis).
* `NorthrupGrumman.csv`: Historical stock market data for Northrop Grumman.
* `L3harris.csv`: Historical stock market data for L3Harris Technologies.

---

## 🛠️ Requirements & R Packages

To reproduce the analysis, open `Financial_Time_Series_VAR.Rmd` in RStudio and ensure the following packages are installed:

```R
install.packages(c("vars", "tseries", "urca", "forecast", "tidyverse", "ggplot2", "xts"))
