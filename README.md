# Gold Price prediction Project
* the project is for data science Regression problem to know the price of gold .
* Data Analysis .
* Data Visualization .
* Machine Learning .
* Choosing the best model . 
* Evaluation Matrix .

# Libraries
* pandas  
* matplotlib 
* seaborn 
* sklearn

# Data Visualization
#### price per gold 
![](https://github.com/AhmedKKhalid/Gold-Price/blob/main/Screenshot/1.PNG)
#### Gold distribution
![](https://github.com/AhmedKKhalid/Gold-Price/blob/main/Screenshot/2.PNG) 
#### polynomial regression degree visualization
![](https://github.com/AhmedKKhalid/Gold-Price/blob/main/Screenshot/3.PNG) 
#### Random forest regression score visualization
![](https://github.com/AhmedKKhalid/Gold-Price/blob/main/Screenshot/4.PNG)

# Model Building
* First, there are train data and test data ready to use 
* Second , I scaled the attributes 
* Third, I Used GridSearchCV to define the best model with the best parameters 
* finally, I used the evaluation matrix mean squared error , mean absolute error and root mean squared error

I tried 5 different models 
 * Random Forest 
 * Linear Regression
 * Polynomial Regression
 * Lasso
 * SVM

# Model performance 
 * Random Forest : score = 0.982971439268413
 * SVM : score = 0.8485952226751453
 * Lasso : score = 0.7555987422960722
 * Linear regression : score = 0.768144432350994
 * Polynomail regression : score = 0.9691265938553029


