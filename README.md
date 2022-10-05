# Regression-Predicting-Calories-Burnt
## About the Project
This is a machine learning regression project to predict the amount of calories burnt.
## Prerequisities
In this project, I have used the following libraries and dependencies:
* Numpy
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn
* Metrics
* XGBRegressor 

## The Dataset
There are two datasets used in this library. The datasets are both from kaggle and are public [here](/datasets/fmendes/fmendesdat263xdemos).
The first dataset,calories.csv, contains information about the calories burnt per user. It has the following two columns:
* User_ID
* Calories

The other dataset, exercise.csv contains other descriptive features and has the following columns:
* User_ID
* Gender
* Age
* Height
* Weight
* Duration
* Heart_Rate	
* Body_Temp

The two datasets are combined into one dataset called calories_data. The calories data has the following columns:
* User_ID
* Gender
* Age
* Height	
* Weight
* Duration	
* Heart_Rate
* Body_Temp
* Calories

The following columns are the features used in this project:
* Gender
* Age
* Height	
* Weight
* Duration	
* Heart_Rate
* Body_Temp

The following column is used in this project as the target:
* Calories



## Roadmap
The aim of the project is to predict the calories burnt based on the features in the dataset.
I split the features from the target.
The dataset was split into training and testing data in the proportion of 80% to 20% respectively.
I modelled the data with an XGBoost Regressor and evaluated the results with the mean absolute error framework.

## Results and Discussion
