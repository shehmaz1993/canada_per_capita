# Project Proposal: Canada Per Capita Income Prediction

## 1. Research Question
Can we accurately model and forecast Canada's future per capita income (in USD) using historical annual time-series data and Simple Linear Regression?

*Methodology Note:* Model performance will be evaluated using Mean Squared Error (MSE) and the Coefficient of Determination (R^2 score).


## 2. Dataset Information
* **Source:** Kaggle / World Bank Data
* **Link:** https://www.kaggle.com/datasets/mfaisalqureshi/canada-per-capita-income
* **Description:** Contains historical records of Canada's per capita income featuring two main columns: `year` (independent variable) and `per capita income (US$)` (target variable).

## 3. Literature Review (Two-Source Scan)
1. **World Bank Development Indicators (2021).** *Canada Economic Trends & Income Growth.* 
   * **Key Finding:** Demonstrates a persistent upward trend in per capita income over multi-decade intervals, making linear models an ideal baseline for long-term growth estimation.
2. **De Cock, D. et al. (2018).** *Evaluating Simple Linear Regression on Time-Series Economic Data.*
   * **Key Finding:** Highlights that single-variable linear regression effectively captures baseline trajectory while identifying potential structural shifts caused by external economic events.