# Car_Price_Prediction
Machine Learning Project: Regression Problem.

![Python](https://img.shields.io/badge/Python-3.7-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML-green)

Car Price Prediction : A Simple Machine Learning project do predict the price of your car if you want to sell it or just want know to the current price.
Live Demo Link:https://car-price-prediction-04.herokuapp.com/

NOTE: Here you may not find the Brand Option , because there were much of it and some were of different names and tags.

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

To find the Co-relation between the Dependent features and Independent features , here we use co-relation and visualize using Seaborn :<br>
<img src="https://github.com/Rawat-Sagar/Car_Price_Prediction/blob/main/seaborn_heatmap_car_price_prediction.png"><br>

I also use RandomsearchCV for Hyperparameter Tunning purpose :
Randomized search on hyper parameters.<br>
RandomizedSearchCV implements a “fit” and a “score” method. It also implements “predict”, “predict_proba”, “decision_function”, “transform” and “inverse_transform” if they are implemented in the estimator used.<br>
The parameters of the estimator used to apply these methods are optimized by cross-validated search over parameter settings.<br>

Here I also look for Important Features Graph which look like this:<br>
<img src="https://github.com/Rawat-Sagar/Car_Price_Prediction/blob/main/important_feature.jpg"><br>

Atlast I use sklearn metrics to check the Mean Squre Error , Mean Absolute Error , Root Mean Squared Error:<br>
MAE Score:0.9377161202185811.<br>
MSE Score: 4.109102939568499.<br>
RMSE: 2.027092237558148.<br>

## How to run the project?

1. Install all the libraries mentioned in the [requirements.txt](https://github.com/Rawat-Sagar/Car_Price_Prediction/blob/main/requirements.txt) file.
2. Clone this repository in your local system.
3. Open the command prompt from your project directory and run the command `python app.py`.
4. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
5. That's it , now you can start your predictions.





