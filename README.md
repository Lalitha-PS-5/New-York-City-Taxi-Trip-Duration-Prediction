# New-York-City-Taxi-Trip-Duration-Prediction
![image](https://github.com/Lalitha-PS-5/New-York-City-Taxi-Trip-Duration-Prediction/assets/113533079/0fdf71af-968a-4db7-9ec5-b02868144c6d)
![image](https://github.com/Lalitha-PS-5/New-York-City-Taxi-Trip-Duration-Prediction/assets/113533079/64637c50-36d7-492b-8b43-7ec79d163cc3)
![image](https://github.com/Lalitha-PS-5/New-York-City-Taxi-Trip-Duration-Prediction/assets/113533079/6bc5fcc6-1fd2-4bc1-835f-91638247716b)
![image](https://github.com/Lalitha-PS-5/New-York-City-Taxi-Trip-Duration-Prediction/assets/113533079/d1934bd4-aff6-46d9-8dd6-993e01f34052)
![image](https://github.com/Lalitha-PS-5/New-York-City-Taxi-Trip-Duration-Prediction/assets/113533079/3dc282f9-1bbb-4758-a14a-437b4128573e)
![image](https://github.com/Lalitha-PS-5/New-York-City-Taxi-Trip-Duration-Prediction/assets/113533079/41d46e45-1ded-4b10-a848-fe200be1b994)

A machine learning case study , which predicts the trip duration needed for New York city taxis.
The challenge here is to build a model that predicts the total ride duration of taxi trips in New York City.
## Introduction
The challenge in taxi trips is to ensure the mostly busy customer centric hubs and identify the duration in those hubs that each taxi trip takes given a pick-up and drop-point locations of any given customer. The outcome should be atleast 95% accurate so that the prediction goes well given any geographic location.Therefore, it becomes important to tackle these instances and understand the demand for taxis for different days and scenarios. 
## Data-Science and Machine Learning
With the help of machine learning and deep learning, this problem could be addressed and this would ensure that the demand for the taxis is known beforehand thus, the companies could ensure that there are adequate taxis present in different locations.
## Metric
Since this is a regression problem, we consider metrics that take into account continuous output variables and give their estimates based on the difference between the actual output and predicted output. Below are some metrics that are used for this prediction.
    * Mean Squared Error
## Machine Learning Models
    * Linear Regression Model
    * Gradient Boosting
    * Random Forest
####  Refer my ipython file for all the above model implementations and precdictions post Data Cleansing and EDA.
## Conclusion
Gradient Boosting model(GBM) with hyperparameter tuning's has got best result for our dataeset.
## Summary
The following topics were covered in this tutorial:

* Downloading a real-world dataset from a Kaggle competition.
* Performing data cleansing and prepare the dataset for training.
* Training and interpreting a Linear Regression model using LinearRegressor.
* Training and interpreting a gradient boosting model using XGBoost.
* Training and interpreting a Random Forest model using RandomForest
* Configuring the gradient boosting model and tuning hyperparamters.
* Comparing the model with other types of models like linear Regression and Random Forest.
* Predicting on Testset.
* Saving the model as a .joblib file.
## Future Work
* I used Linear Regression , GBM & Random Forest , future work may include trying the predictions with other models such as Decision Tress, K-Fold and so on..
* Learning & implementing the speedup mechanisms to increase the time taken to run the models with predictions.
