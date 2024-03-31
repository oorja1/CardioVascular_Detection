# ML-PROJECT: CARDIOVASCULAR DISEASE PREDICTION

## BY OORJA MAHANA 
### VEER SURENDRA SAI UNIVERSITY OF TECHNOLOGY 2026

## FOCUSED AREA- ALGORITHMS 

## MOTIVATION
Cardiovascular disease (CVD) is the leading cause of death worldwide, accounting for
approximately 17.9 million deaths annually which is about 30% of all global deaths.
Cardiovascular Disease Prediction is one of the most effective measures for Cardiovascular
Disease control. Therefore it is important to analyze the various factors that contribute the most
towards this disease and predict whether a person can have a cardiovascular disease.


## OBJECTIVE
The first objective of this project is to recognize key factors affecting cardiovascular disease and
to develop a model that can accurately predict accident severity.
In this project we will perform exploratory data analysis on the dataset and then predict the
possibility of a person having Cardiovascular disease based on the various parameters
specified in the dataset by applying various classification modelling techniques.


## APPROACH

### DATASET ANALYSIS AND CLEANING:
First to understand the data, we looked at the properties of each column (like
mean, median, standard deviation, number of null values etc.). Since there were
no null values in the dataset, we didn't have to handle it.
 Also there were 6 categorical variables and 5 continuous variables in the dataset.
 
 ### EDA
For categorical variables like gender, smoke, alcohol, glucose etc, we did a
univariate analysis by plotting a countplot and bar chart(w.r.t dependent variable
cardio) to understand how well the dataset is distributed.
For continuous variables like age, height and weight we did a bivariate analysis
by plotting a kernel density estimate (kde) plot which helps us visualize the
distribution of observations in the dataset. Observing the plot we could conclude
that people over 55 years of age are more exposed to cardiovascular disease.

### DATA PREPROCESSING
Detecting Outliers:- From the dataset we observed that there were some records
where the values of column ap_low were greater than the value of column
ap_high. Therefore we eliminated such records.

### DATA TRANSFORMATION
Did feature engineering by creating a new feature BMI from weight and height.
 Normalized the dataset using MinMaxScaler.
 Performed One-Hot Encoding on categorical variables (Gender, Cholesterol and
Glucose).

### APPLIED VARIOUS MACHINELEARNING MODELS:
XGBoost, Adaboost, K Nearest Neighbours, Neural Networks, RandomForest, Logistic Regression, Support Vector Machine.
