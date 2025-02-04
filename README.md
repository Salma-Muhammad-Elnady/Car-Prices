# **Car Prices Regression Project**
#### The project aims to predict the price of a car based on a set of features such as insurance risk rating, car company, fuel type, aspiration, number of doors, body style, drive wheel type, engine location, dimensions (wheelbase, length, width, height), weight, engine type, cylinder count, engine size, fuel system, engine specifications (bore ratio, stroke, compression ratio, horsepower, peak RPM), and mileage (city and highway).
![dataset-cover](https://github.com/user-attachments/assets/954511f7-5e6d-45e3-bbf3-888cae512df5)

## Project Aims 

### 1. Data Import:
+ Download the car price dataset from Kaggle.
+ Import and clean the data by handling any missing or incorrect values. 

### 2. Data Analysis:
* Explore data and analyze different features.
* Create visualizations to highlight the relationships between different features and car prices.

### 3. Model Building:
* Try different algorithms like: Linear Regression, polynomial Regression, Ridge Regression, Lasso Regression, Random forest, Decision tree.   
* Train the model using the data and evaluate its performance using metrics like: R2-Score, MSE, RMSE, MAE, MAPE.
 
### 4. Model Improvement:
* Improve the model using techniques like cross-validation and feature engineering.
* Compare different models and select the one that provides the best accuracy.


# Data Set 
__________________________________________________________
The dataset for this project can be found [Here](https://www.kaggle.com/datasets/imgowthamg/car-price/data) 

# Results 
___________________________________________________________
Below is a brief description of the results of the models used 

| Evaloution |Linear Regression | polynomial Regression | Ride Regression | Lasso Regression | Decision tree Regression | Random forest Regression |
|----------|----------|----------|----------|----------|----------|----------|
| R2-Score Train | 0.88  | 1.0 | 0.98 | 0.96 | 0.95 | 0.97 |
| R2-Score Test | 0.92  | -121.8 | 0.88 | 0.89| 0.82 | 0.92 |
| MSE Train | 6860822.9 | 2.3478533609988427e-19 | 682751.4 | 1961903.2 | 2472760.6 | 1218577.2 | 
| MSE Test | 6205818.5 | 10478812451.9 | 9482245.7 | 9014785.9 | 14945566.3 | 6727369.4 | 
| RMSE Train | 2619.3 | 4.845465262489086e-10 | 826.2 | 1400.6 | 1572.5 | 1103.8 | 
| RMSE Test | 2491.1 | 102366.07 | 592.8 | 3079.3 | 3002.4 | 3865.9 | 2593.7 | 
| MAE Train | 1937.5 | 3.198925785510233e-10 | 592.8 | 1032.3 | 1188.0 | 763.4 |
| MAE Test | 1836.9 | 43309.27 | 2215.3 | 2183.7 | 2100.5 | 1507.9 |
| MAPE Train | 15.9% | 0.00000000000274% | 5.35% | 9.16% | 9.37% | 5.67% | 
| MAPE Test | 14.3% | 294.74% | 19.59% | 17.78% | 13.96% | 10.18% |

# Summary : 
__________________________________________________________________
* ### Linear Regression and Random Forest models :
show the best performance on test data, with Random Forest having a slight edge in terms of error metrics.

* ### Polynomial Regression :
 suffers from severe overfitting.

 * ### Ridge and Lasso Regression :
provide a good balance between bias and variance.

* ### Decision Tree :
shows signs of overfitting but still performs reasonably well.  

 

     



 


 
