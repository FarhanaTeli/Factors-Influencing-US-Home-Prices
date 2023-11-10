# US Housing Trends Analyzer and Influence Explorer

**Objective:**

The project aims to build a data science model to predict U.S. home prices based on key economic factors over the last 20 years.

**Steps**

1. **Data Collection:**

Utilized the S&P Case-Schiller Home Price Index as a proxy for home prices, sourced from the Federal Reserve Economic Data (FRED) website.

2. **Key Factors:**

Gathered publicly available data on factors influencing home prices nationally, including Per Capita GDP, Consumer Price Index (CPI), Construction Material Costs, Median Income, Subsidies, and Population Demographics, etc.

3. **Data Cleaning and Processing:**

Cleaned and processed the data, addressing missing values, converting date formats, and handling outliers.

4. **Exploratory Data Analysis (EDA):**

Conducted EDA to understand the distribution of variables, identify correlations, and visualize trends over time.

5. **Model Selection:**

Explored various regression models, including Linear Regression, ElasticNet, Random Forest, Gradient Boosting, Support Vector Regression (SVR), and XGBoost.

6. **Model Training and Evaluation:**

Trained each model using a subset of the data, evaluated performance using metrics such as Mean Squared Error (MSE) and R-squared.

7. **Feature Importance:**

Analyzed feature importance for models like Random Forest, XGBoost, and Gradient Boosting to understand the factors influencing home prices.

8. **Model Comparison:**

Compared models based on MSE, R-squared, and other relevant metrics to identify the model with the best predictive accuracy and explanatory power.

9. **Conclusion:**

Identified Random Forest and XGBoost as strong contenders for the best model, considering their low MSE and high R-squared values.

10. **Overall Implication:**

The project contributes to understanding the key factors influencing U.S. home prices and provides a foundation for building robust predictive models in the real estate domain.

# Data Availability

**The following variables are chosen for the study-**

1. Unemployment Rate
2. Employment Rate
3. Per Capita GDP
4. Real Median Household Income
5. Construction Prices
6. CPI
7. Interest Rates
8. Number of new houses supplied
9. Working Population
10. Urban Population
11. Percentage of population above 65
12. Housing subsidies
13. Number of Households

As a proxy to the home prices, S&P CASE-SHILLER Index is used.

Most of the data is downloaded from [https://fred.stlouisfed.org/].

**Following sources were used to gather data:**

CASE-SCHILLER Home Price Index - https://fred.stlouisfed.org/series/CSUSHPISA

Interest rates - https://fred.stlouisfed.org/series/FEDFUNDS

Unemployment rate - https://fred.stlouisfed.org/series/UNRATE

Working Population - https://fred.stlouisfed.org/series/LFWA64TTUSM647S

Employment rate - https://fred.stlouisfed.org/series/LREM64TTUSM156S

Consumer price index (CPI) - https://fred.stlouisfed.org/series/CPIAUCSL

Real Median Household Income - https://fred.stlouisfed.org/series/MEHOINUSA672N

Per Capita GDP - https://fred.stlouisfed.org/series/A939RX0Q048SBEA

Construction price index - https://fred.stlouisfed.org/series/WPUSI012011

percent urban population - https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS?end=2021&locations=US&start=2001

Housing Subsidies (Federal) - https://fred.stlouisfed.org/series/L312051A027NBEA

Total households - https://fred.stlouisfed.org/series/TTLHH
