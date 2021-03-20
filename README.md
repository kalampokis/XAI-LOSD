# XAI-LOSD
XAI on linked data from the Scottish government data portal (http://statistics.gov.scot). Code from a paper submitted to EGOV2021 conference.

In our case, the 2011 Data Zones are employed as the geographical unit of analysis for the case study. Data zones are the core geography for dissemination of results from Scottish Neighborhood Statistics. They are designed to have roughly standard popula-tions of 500 to 1,000 household residents. There are 6,976 2011 Data Zones.

The topic that will be explored is the mean house prices in the 2011 Data Zones in the year 2017. The average mean house price in 2017 across the 6,976 data zones is £168,285, while the median mean house price is £148,375. The problem that will be explored is the prediction of the probability the mean house price of a data zone is higher than the average price (£168,285). Moreover, what are the factors that contrib-ute towards this prediction in each data zone.

eXtreme Gradient Boosting (XGBoost) is used to create the predictive model and SHapley Additive exPlanation (SHAP) framework to explain the predictive model. 
