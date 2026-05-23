<div align="center">

# Crop Yield Prediction Using Polynomial Regression

### End-to-End Machine Learning Regression Project Using Polynomial Features, Data Preprocessing, Visualization, and Scikit-learn

</div>

---

# Project Overview

This project demonstrates the implementation of **Polynomial Regression** on an agricultural crop yield dataset to predict crop production trends using environmental and agricultural factors.

The project was developed step by step to understand how machine learning handles non-linear relationships between input features and crop yield production.

Unlike simple linear regression, this project explores curved relationships between agricultural factors and crop productivity through Polynomial Feature Transformation.

The notebook contains complete preprocessing, visualization, feature engineering, model training, prediction, evaluation, and graphical analysis using Python libraries and Scikit-learn.

---

# Problem Statement

Can machine learning predict agricultural crop yield using environmental and farming-related features?

This project attempts to predict:

- Crop Yield (`hg/ha_yield`)

using important agricultural factors such as:
- Area
- Crop Item
- Rainfall
- Pesticides Usage
- Temperature
- Year

The goal is to analyze how these features influence crop production patterns and how Polynomial Regression captures non-linear trends in the dataset.

---

# Dataset Workflow

The dataset contains agricultural production information along with environmental conditions affecting crop yield.

The workflow was designed to simulate a real-world machine learning regression pipeline including:
- preprocessing
- encoding
- normalization
- feature transformation
- polynomial feature generation
- regression analysis
- visualization

---

# Project Workflow

## Step 1: Import Libraries

Required Python libraries were imported for:
- data handling
- preprocessing
- visualization
- machine learning implementation

Libraries used:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Step 2: Load Dataset

The agricultural crop yield dataset was loaded and explored using Pandas to inspect:
- dataset structure
- feature types
- numerical columns
- categorical columns

---

## Step 3: Data Preprocessing & Exploratory Data Analysis (EDA)

The dataset was explored carefully to understand feature relationships and data quality.

EDA included:
- dataset inspection
- feature analysis
- heatmap visualization
- distribution understanding

The dataset contained:
- no missing values
- structured agricultural records
- environmental and production-related features

Heatmaps were used to visually analyze feature relationships and dataset structure.

---

## Step 4: Encoding of Dataset

Categorical columns such as:
- Area
- Item

were converted into numerical format using:

LabelEncoder()

Encoding allowed machine learning algorithms to process categorical agricultural information.

---

## Step 5: Normalization

Feature scaling was performed using:

MinMaxScaler()

to normalize feature ranges and improve Polynomial Regression performance.

Normalization transformed features into a consistent scale suitable for machine learning processing.

---

## Step 6: Check Linearity of Data

A pairplot was created to visually inspect:

feature relationships
trends
patterns
linearity and non-linearity of data

This step helped identify that several relationships in the dataset were non-linear, making Polynomial Regression more suitable than simple linear regression.

---

## Step 7: Check Correlation

Correlation heatmaps were generated to analyze:

strong feature relationships
weak relationships
positive correlations
negative correlations

This helped understand how agricultural and environmental factors influence crop yield.

---

## Step 8: Splitting of Data into Training & Testing

The dataset was divided into:

Training dataset
Testing dataset

to evaluate model performance on unseen agricultural data.

---

## Step 9: Converting Input Features into Polynomial Form

Input features were transformed into Polynomial Features using:

PolynomialFeatures()

This step allowed the model to capture:

curves
complex patterns
non-linear relationships

between environmental factors and crop yield production.

---

## Step 10: Apply Model

Polynomial Regression was implemented using:

LinearRegression()

on transformed polynomial features.

The model learned complex agricultural patterns from environmental and farming-related data.

---

## Step 11: Prediction & Accuracy Evaluation

The trained model generated crop yield predictions using testing data.

Model performance was evaluated using:

prediction analysis
accuracy metrics
regression evaluation

This helped analyze how effectively the model predicts agricultural production trends.

---

## Step 12: Visualization

Multiple visualizations were created to understand:

actual vs predicted values
polynomial curve behavior
feature relationships with crop yield
non-linear trends in agricultural data

Subplots were created for different features to visually inspect how each agricultural factor influences crop production.

The visualizations helped demonstrate how Polynomial Regression captures curved relationships more effectively than linear models.

---

## Technologies Used
---
Technology	                         Purpose
Python	                             Programming Language
Pandas	                             Data Handling
NumPy	                               Numerical Operations
Matplotlib	                         Data Visualization
Seaborn	                             Heatmaps & Pairplots
Scikit-learn	                       Machine Learning & Preprocessing

---

## Project Output

The project successfully:

implemented Polynomial Regression
transformed features into polynomial form
analyzed agricultural patterns
normalized data using MinMaxScaler
encoded categorical agricultural features
generated predictions
visualized polynomial relationships
explored non-linear crop production trends
---

## Learning Objective

This project was developed to strengthen understanding of:

Polynomial Regression
non-linear machine learning models
feature transformation
polynomial feature engineering
normalization techniques
encoding categorical data
regression visualization
agricultural data analysis
real-world machine learning workflows

---

The repository combines preprocessing, feature engineering, regression modeling, evaluation, and visualization into a complete end-to-end machine learning project workflow.

<div align="center">
Repository Includes

EDA • Heatmaps • Pairplots • Label Encoding • MinMaxScaler • Polynomial Features • Regression Modeling • Prediction Analysis • Visualization • Agricultural Data Analysis

</div>
