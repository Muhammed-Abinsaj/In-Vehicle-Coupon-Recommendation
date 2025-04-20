# In-Vehicle-Coupon-Recommendation Predication

# Stage 1 - Exploratory Data Analysis

Stage 1 is a step that focused on gathering insights from statistical views.

What have done on this stage:

-> Descriptive Analysis

-> Univariate Analysis

-> Multivariate Analysis

-> Business Insight As Business Recommendation



# Stage 2 - Preprocessing Data

Stage 2 is another next step that we did manipulation on data before it is used in order to build the model.

What have done on this stage:

Handle Missing Values
Handle Duplicated Data
Handle Outliers
Feature Transformation
Feature Encoding
Handle Class Imbalance
Feature Selection
Feature Extraction


# Stage 3 - Modeling and Evaluation

Stage 3 is a step where I tested our data train to machine learning model and evaluated it. On this stage I created 7 different preprocessing treatment on datasets. I tested it to 5 different models: logistic regression, decision tree, random forest, XGBoost and CatBoost. The objective of it's action is at the end of this stage I couldn't only know which the better model also the better preprocessing treatment on dataset. As we know, in data science everything is experimental, so I did it to get the better result.

What  have done on this stage:

Preprocessing Data
Splitting Data (Data Train and Data Test)
Feature Engineering
Model Testing
Tuning Hyperparameters and feature selection
Model Selection
Evaluation most impacful/influence to model output using shap library


# RESULT

Based on my project's result, out best model is CatBoost with accuracy score 77% and precision score 77%. Our model performance could increase coupon acceptance rate and B/C ratio by 0.61x (from 1.7x to 2.31x).
