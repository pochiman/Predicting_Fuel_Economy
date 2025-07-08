# Predicting Fuel Economy

## The Situation
You've just been hired as a Product Data Scientist for Consumer Reports Magazine, a trusted source for information on consumer products and services.

## The Assignment
Fuel economy is a major factor in the cost of owning a car, so they are studying the automobile characteristics that impact fuel economy for an upcoming article. 
You've been asked to build a regression model to predict fuel economy based on characteristics like the car's weight, model year, acceleration, and more.

## The Objectives
1. Prepare and explore the data
2. Split the data and build a multiple regression model
3. Evaluate model test performance and interpret the model
4. Challenge: Build a ridge regression model and compare the results

## The Data Set

#### Automotive Fuel Economy
This dataset contains the fuel economy in miles per gallon (mpg) for 398 cars sold in the US in the 1970s and 1980s. The data includes vehicle characteristics including horsepower, acceleration, country of origin, and more.

#### Recommended Analysis
1. What is the overall trend in fuel economy over time?
2. Which automobile characteristic is most correlated to fuel economy?
3. Is there a difference in fuel economy by the origin of the car produced? If so, is there an underlying difference in the types of cars manufactured in each?

#### Objective 1: Prepare and Explore the Data
Your first objective is to prepare the data for modelling, explore the target ('mpg') and other features in the dataset, and fix any issues you encounter.

* Read in the auto-mpg.csv dataset, and check datatypes and columns for missing or unusual values.
* Convert 'origin' to a categorical feature.
* Calculate summary statistics for each of the numeric columns in the dataset including min, max and mean, then build a histogram of the target variable ('mpg').
* Explore relationships between the features and the 'mpg' column, and use scatterplots and build a correlation heatmap. Which column is most strongly correlated with 'mpg'?

#### Objective 2: Split the data and build a multiple regression model
Your second objective is to split the data into training and test data, then fit a multiple regression model using the validation scheme of your choice. Perform feature engineering and variable selection, and check whether any assumptions are violated.

* Split the data into train and test, then set up a validation scheme of your choice.
* Fit a baseline regression model using the feature with the strongest correlation to the target ('mpg').
* Fit a multiple regression model. Perform any feature selection and feature engineering necessary, fixing any violated assumptions along the way.

#### Objective 3: Evaluate model test performance and interpret the model.
Score your model on the test data set, use your model to predict a new batch of cars, and interpret your model results.

* Score your final model on the test set, calculating both R2 and MAE. If your test R2 is less than 8, revisit the modelling process.
* Interpret your model. What impact does a one-year increase in model year have on the predicted mileage?
* BONUS: Repeat the modelling process using ridge regression. How much better was the ridge model than traditional regression, if at all?

#### [Project Link]()