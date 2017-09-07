# UCL-Msc-Thesis
This repository includes the source codes required for my Msc thesis project about the prevalence of hayfever in UK's population. 
## Project description
This project intends to reveal the prevalence of hayfever in UK’ population by estimating whether hayfever incidence rates can be detected and estimated using weekly online search queries from Google Trend. Four supervised learning models are implemented, namely ARIMA, OLS, Elastic net regression and ARIMAX with Elastic net. The results of ARIMAX with Elastic net achieves the best estimating performance with an average RMSE of 3.04 which is 25.3% and 71.3% lower than RMSE of Elastic net (4.07) and ARIMA (10.60) respectively, compared with RCGP hayfever data. The results imply that search query information can improve autoregressive inference, proving the success of this project to estimate the hayfever prevalence among UK’s population using search queries.

## Codes files:
1. ARIMA.ipynb: ARIMA is used to analyse stationarity of series data, ACF and PACF, and gain forecasting results for five testing periods by use of hayfever_ENG.csv which are actual hayfever weekly incidence rates from 5/1/2004 to 25/7/2016 reported by UK's GP.
2. Elastic_net vs OLS.ipynb: Loading the feature data which includes 38 search queries with the same period from 5/1/2004 to 25/7/2016 collected from Google Trend, this file is used to obtain hayfever incidence estimating results by Elastic net, OLS regression and their performance comparison.
3. ARIMAX with Elastic net.ipynb: Inputting the estimating results from Elastic net, this file is to create a combined model of ARIMA and Elastic net: ARIMAX.
