# UCL-Msc-Thesis
This repository includes the source codes required for my Msc thesis project about the prevalence of hayfever in UK's population. 
## Project description

## Codes files:
1. ARIMA.ipynb: ARIMA is used to analyse stationarity of series data, ACF and PACF, and gain forecasting results for five testing periods by use of hayfever_ENG.csv which are actual hayfever weekly incidence rates from 5/1/2004 to 25/7/2016 reported by UK's GP.
2. Elastic_net vs OLS.ipynb: Loading the data from features.csv which includes 38 search queries with the same period from 5/1/2004 to 25/7/2016 collected from Google Trend, this file is used to obtain hayfever incidence estimating results by Elastic net, OLS regression and their performance comparison.
3. ARIMAX with Elastic net.ipynb: Inputting the estimating results from Elastic net, namely pre.csv, this file is to create a combined model of ARIMA and Elastic net: ARIMAX.

