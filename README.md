# Diagnosis of COVID-19 and its clinical spectrum

The project involves performing exploratory data analysis (EDA) to comprehensively examine the data, including identifying the target variable, assessing the size and shape of the dataset, handling missing values, and categorizing the types of variables.

The project involves delving into the content of the dataset, visualizing the target variable using histograms or box plots, exploring the relationships between different variables, and identifying any outliers.

Finally, the project culminates in modeling, where different machine learning models are trained and evaluated. This includes defining an evaluation function, optimizing the models using techniques like GridSearchCV, analyzing errors, and iterating back to the pre-processing and EDA stages if necessary. Learning curves are also considered to aid in decision-making throughout the project.


## Dataset
Source : 
[Diagnosis of COVID-19 and its clinical spectrum](https://www.kaggle.com/datasets/einsteindata4u/covid19)

## Process (checklist)

### I. Exploratory Data Analysis (EDA)
Objective: Understanding the available data as much as possible to define a modeling strategy.

#### I.1 Form
- [x] Identifying the target variable
- [x] Number of rows and columns
- [x] Identifying missing values
- [x] Types of variables

#### I.2 Content
- [x] Visualizing the target variable (histogram/box plot)
- [x] Understanding different variables (research)
- [x] Visualizing relationships: features/target
- [ ] Identifying outliers


### II. Pre-processing
Objective: Transforming the data into a suitable format for machine learning.

- [ ] Creating the Train Set / Test Set
- [ ] Handling NaN values: dropna(), imputation, "empty" columns
- [ ] Encoding
- [ ] Removing  detrimental outliers
- [ ] Feature selection
- [ ] Feature engineering
- [ ] Feature scaling

### III. Modeling
Objective: Developing a machine learning model capable of achieving the final objective.

- [ ] Defining an evaluation function
- [ ] Training different models
- [ ] Optimizing with GridSearchCV
- [ ] Analysing errors and feedback to Preprocessing / EDA
- [ ] Learning Curve and decision making
