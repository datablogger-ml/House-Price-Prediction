# House-Price-Prediction
Predicting the price of Houses using different features. Using multiple feature selection techniques to choose the best model

#### -- Project Status: Active

## Project Intro/Objective
The purpose of this project is to get familiar with Regression Analysis which is a very helpful prediction method in univariate and multivariate analysis.

### Methods Used
* Regression Analysis - Linear, Polynomial, Ridge, Lasso, Elastic Net
* Machine Learning
* Feature - Selection Techniques
* Data Visualization

### Technologies
* Python
* sklearn
* Pandas, jupyter
* matplotlib

## Project Description

### Data

The real estate markets, like those in Sydney and Melbourne, present an interesting opportunity for data analysts to analyze and predict where property prices are moving towards. Prediction of property prices is becoming increasingly important and beneficial. Property prices are a good indicator of both the overall market condition and the economic health of a country.

* Total Columns = 18
* Total Rows = 21613

<a href='https://raw.githubusercontent.com/datablogger-ml/House-Price-Prediction/main/kc_house_data.csv'>Download Link</a>

### Methods

#### 1. Regression 

In statistical modeling, regression analysis is a set of statistical processes for estimating the relationships between a dependent variable and one or more independent variables :

* <strong>Simple Linear Regression</strong> - A simple liner regression is a linear model which concerns two-dimensional sample points with one independent /input/feature variable and one dependent/output/target variable and finds a linear function that,as accurately as possible, predicts the dependent variable values as a funcition of the independent variable.
It is common to make the additional stipulation that the ordinary least squares (OLS) method should be used: the accuracy of each predicted value is measured by its squared residual (vertical distance between the point of the data set and the fitted line), and the goal is to make the sum of these squared deviations as small as possible. 
<img src = 'https://raw.githubusercontent.com/datablogger-ml/House-Price-Prediction/main/1920px-Linear_regression.svg.png' width = 400 height = 300>

Equation for Simple Linear Regression : h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> + &theta;<sub>1</sub>x

* <strong>Multiple Linear Regression</strong> - Multiple linear regression (MLR), also known simply as multiple regression, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. The goal of multiple linear regression (MLR) is to model the linear relationship between the explanatory (independent) variables and response (dependent) variable.
In essence, multiple regression is the extension of ordinary least-squares (OLS) regression that involves more than one explanatory variable (n independent variables).

Equation for Multiple Linear Regression : h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> + &theta;<sub>1</sub>x<sub>1</sub> + &theta;<sub>2</sub>x<sub>2</sub> + ...&theta;<sub>n</sub>x<sub>n</sub>

* <strong>Polynomial</strong> -
* <strong>Lasso(L1 Regularization)</strong> - 
* <strong>Ridge(L2 Regularization)</strong> - 
* <strong>Elastic Net</strong> - 


#### 2. Feature Selection Techniques

* <strong>Correlation</strong> - 
* <strong>Reccursive Feature Elimination(RFE)</strong>
* <strong>Lasso Feature selection</strong>

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](https://raw.githubusercontent.com/datablogger-ml/House-Price-Prediction/main/kc_house_data.csv) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)
