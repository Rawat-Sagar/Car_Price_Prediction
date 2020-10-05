# Car_Price_Prediction
Machine Learning Project  

![Python](https://img.shields.io/badge/Python-3.7-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML-green)

Car Price Prediction : A Simple Machine Learning project do predict the price of your car if you want to sell it or just want know to the current price.
Live Demo Link:https://car-price-prediction-04.herokuapp.com/

NOTE: Here you may not find the Brand Option , beacuse there were much of it and some were of different names and tags.

## About this Project:

Car Price Prediction web api or other website are used when there is high chances that you are selling your car for the right price.

Here is the some more info about the dataset which I used to do this project:<br>
This dataset contains information about used cars listed on www.cardekho.com.<br>
This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression in Machine Learning.<br>

The columns in the given dataset are as follows:<br>
1.name.<br>
2.year.<br>
3.selling_price.<br>
4.km_driven.<br>
5.fuel.<br>
6.seller_type.<br>
7.transmission.<br>
8.Owner.<br>

While performimg the operations, the dataset contains more Categorical Values so one can use One Hot Encoding or Pandas Dummy Coding.<br>
Algorithm used here is RandomForestRegressor.A random forest is a meta estimator that fits a number of classifying decision trees on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree.<br>

To find the Co-relation between the Dependent features and Independent features , here we use co-relation and visualize using Seaborn :


