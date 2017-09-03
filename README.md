# UCL-Msc-Thesis
This repository includes the source codes required for my Msc thesis project about the prevalence of hayfever in UK's population. 
## Project description

## Project files
There are two folders, namely codes and datasets.
### Datasets: 
1.	features.csv: a total of 38 search queries with the same period from 5/1/2004 to 25/7/2016 were collected from Google Trend. 
2.	hayfever_ENG.csv: The RCGP data represents the number of doctor consultations reporting hayfever symptoms per 100,000 people in England. The data’s weekly time series are from January 5, 2004 to July 25, 2016. 
3.	pre. csv: The hayfever incidence estimating results from Elastic net were used as external variable put into the ARIMAX model.
### Codes: 
1. ARIMA.ipynb: ARIMA is used to analyse stationarity of series data, ACF and PACF, and gain forecasting results for five testing periods by use of hayfever_ENG.csv.
2. Elastic_net vs OLS.ipynb: Loading the data from features.csv, this file is used to obtain hayfever incidence estimating results by Elastic net, OLS regression and their performance comparison.
3. ARIMAX with Elastic net.ipynb: Inputting the estimating results from Elastic net, namely pre.csv, this file is to create a combined model of ARIMA and Elastic net: ARIMAX.

