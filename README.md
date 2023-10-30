# House Pricing Advance Regression Assignment

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

* Which variables are significant in predicting the price of a house, and

* How well those variables describe the price of a house. 


## Table of Contents
- [House Pricing Advance Regression Assignment](#house-pricing-advance-regression-assignment)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Following steps are performed,

* EDA
  * Data Cleanup
  * Data Visualization
  * Data Transformation / Prepartion

* Model Training
  * Model Training using correlated variables
    * Performed Linear, Ridge and Lasso
    * Residual and Scores analysis 
  * Model Training using all the categorical variables.
    * Performed Linear, Ridge and Lasso
    * Residual and Scores analysis
* Exercise Summary
* Questions

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Built two models, one with less but correlated variables (55 independent variables) and another model with 156 variables.

The smaller model gaves the R2 score of 0.88 compared to big one which gave 0.91 on train dataset.

The residual analysis for both models show that the errors are normally distributed (with slighly longer tail on left side) and the models are homoscedastic. 

In summary, the Lasso algorithm is performing better for both the models.

I have chosen the smaller model for further analysis given it's more robust and generalisable given way lesser no. of variabels would impact the target variable.

## Technologies Used

- Python 3.10.9
- Jupyterlab 3.6.3
- pandas 1.5.3
- seaborn 0.12.2
- scikit-learn 1.3.0
- statsmodels 0.14.0
- numpy 1.23.5
- matplotlib 3.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

I referred [Investopedia](https://investopedia.com), Wikipedia, GeekForGeeks, AnalyticsVidya, StackExchange to learn and write the answers to subjective questions.


## Contact
Created by [Jatan Porecha](https://github.com/porechajp)

