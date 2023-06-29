# Diagnosis of COVID-19 and its clinical spectrum

## Dataset
Source : !(Diagnosis of COVID-19 and its clinical spectrum)[https://www.kaggle.com/datasets/einsteindata4u/covid19]

## Process (checklist)

### I. Exploratory Data Analysis (EDA)
Objective: Understanding the available data as much as possible to define a modeling strategy.

#### I.1 Form
-[] Identifying the target variable
-[] Number of rows and columns
-[] Identifying missing values
-[] Types of variables

#### I.2 Content
-[] Visualizing the target variable (histogram/box plot)
-[] Understanding different variables (research)
-[] Visualizing relationships: features/target
-[] Identifying outliers


### II. Pre-processing
Objective: Transforming the data into a suitable format for machine learning.

-[] Creating the Train Set / Test Set
-[] Handling NaN values: dropna(), imputation, "empty" columns
-[] Encoding
-[] Removing  detrimental outliers
-[] Feature selection
-[] Feature engineering
-[] Feature scaling

### III. Modeling
Objective: Developing a machine learning model capable of achieving the final objective.

-[] Defining an evaluation function

-[] Training different models
-[] Optimizing with GridSearchCV
-[] Analysing errors and feedback to Preprocessing / EDA
-[] Learning Curve and decision making
