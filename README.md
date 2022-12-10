# Ruoxin Wang Undergraduate Projects
This repository contains two projects: Time Series Project from PSTAT 174 and ESG Data Analysis Project from PSTAT 100.
## PSTAT 174: Time Series Analysis on US Candy Production Data
The purpose of this project was to apply time series analysis techniques from PSTAT 174 to analyze a real- world time series data set “US Candy Production, 1982 - 1999” and predict future data points via forecasting. My questions addressed in this project is whether the candy production in the US has seasonality and how it going to develop in the following years. To analyze this time series data set, I first plot out the raw data and utilize box-cox transformation to stable the variance and differenced data to make it stationary. Then, plotting out the sample ACF and PACF graph allows me to choose candidate models needed to be further fitted, which are SARIMA(1, 1, 1)(0, 1, 1)[12], SARIMA(0, 1, 2)(0, 1, 1)[12], SARIMA(2, 1, 2)(0, 1, 1)[12]. Selecting the best model according to the AICc scores and use diagnostic checking with p-value of three additional tests greater than 0.05 to confirm that the model residual ACF, PACF, normaltiy, independence, fitting AR(0) work well to behave like a white noise. Finally, I forecast and make prediction with a 95% confidence interval for the following years. According to the forecasting result, all the prediction points are inside the 95% confidence interval and show a seasonal pattern with a increasing trend, which can make a further conclusion that US candy production was affected by a seasonal factor and the amount of production would increase in the following years.
## PSTAT 100: Exploring Analysis on Countries' Sustainability with ESG Data
This project mainly investigates the sustainability of countries worldwide through Environment, Social, and Governance aspects and analyze the variation among the principal components of each country. The motive is to find out which country is most sustainable during the COVID-19 pandemic outbreak. According to the Principal Components Analysis, there are no significant changes in the chosen ESG variables during the pandemic. Although the variation of GDP growth is thought to be an influential component, it doesn't affect the result a lot. Hence, a new sustainability score evaluation method is used and Vietnam is considered the most sustainable country in 2019 and 2020.
## PSTAT 131: Exploring Analysis on Countries' Sustainability with ESG Data
Predicting voter behavior is complicated for many reasons despite the tremendous effort in collecting, cleaning, analyzing, and understanding many available datasets. As the midterm elections in the United States is currently being held near the midpoint of the current president’s four-year term of office, it is a good time for us to review the 2020 United States presidential election data! Despite that the 2016 presidential election came as a big surprise to many, Biden’s victory in the 2020 presidential election has been widely predicted (e.g., see the well-known Nate Silver in FiveThirtyEight).

For this final project, we will analyze and visualize the 2020 presidential election dataset. We will primarily work towards building state/county-level red/blue map plots that are commonly shown on media coverage.

In addition, we will combine the Untied States county-level census data with the election data. Our target would then be building and selecting classification models (among many predictive models that we’ve covered in this quarter) to predict the election winner.

