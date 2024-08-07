# **Machine Learning Modelling for Airline Delay Time Prediction using R**

This project is published as an R Markdown file, providing a detailed guide for developing a machine learning model to predict airline delay times. The final model is a cubic polynomial regression model, achieving an RMSE of 21.07730 and an R-squared value of 0.9174251. The dataset was split into 75% for training and 25% for testing.

## **Report Sections:**
### **I. Data Wrangling**
1. Missing Values and Formatting
* Identify Missing Values: Detect and report missing data within the dataset.
* Handle Missing Values: Apply techniques to manage and impute missing data.
* Correct Data Format: Ensure all data fields are in appropriate formats for analysis.
2. Data Normalization
* Scaling: Normalize data to bring all features to a similar scale.
* Binning: Categorize continuous variables into discrete bins.
* Indicator Variable: Convert categorical variables into binary indicator variables.
### **II. Explanatory Data Analysis**
* Analyzing Individual Feature Patterns using Visualization: Use visual tools to explore and understand feature distributions and relationships.
* Descriptive Statistical Analysis: Summarize and interpret basic statistical properties of the data.
* Basics of Grouping: Group data based on relevant features to identify patterns.
* Correlation: Analyze the correlation between features to understand their relationships.
* ANOVA (Analysis of Variance): Conduct ANOVA to determine the statistical significance of group differences.
### **III. Model Development**
* Simple Linear Regression: Build and evaluate a simple linear regression model.
* Multiple Linear Regression: Extend to multiple linear regression to include multiple predictors.
* Polynomial Regression: Develop a polynomial regression model to capture non-linear relationships.
* Assessing the Model: Evaluate model performance using appropriate metrics.
### IV. Model Evaluation and Refinement
* Training and Testing Data: Split the data into training and testing sets to evaluate model performance.
* Training a Model: Train the machine learning model on the training data.
* Evaluating a Model: Assess the model on the testing data to determine its predictive power.
### **V. Prediction**
* Use the trained model to make predictions on new, unseen data.

### **Tools and Libraries:**
**Programming Language:** R

**Interactive Programming Tool:** R Studio

**Data Manipulation:** tidyverse, lubridate, tibble, purr

**Data Analysis:** corrplot

**ML Model Evaluation:** tidymodels, broom, Metrics, parsnip

**Data Visualization:** ggplot, knitr

**Report Deployment:** posit Cloud

**Link to Project:** https://posit.cloud/content/8306962

**Video: ** https://drive.google.com/file/d/1p8GxiHQqPRXrF3vjwKHjUUhjQer15Eyy/view
