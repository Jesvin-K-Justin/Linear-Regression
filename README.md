# Medical insurance costs prediction using linear regression
A linear regression model to predict medical insurance costs for individuals based on their personal attributes. It is a predictive model that can accurately estimate the insurance charges given a set of features. 
The goal is to create a predictive model that can accurately estimate the insurance charges given a set of features. The dataset provided includes the following variables for several individuals: age, sex, BMI (Body Mass Index), number of children, smoking status, region, and medical insurance charges.

**Tasks Performed**

1. **Data Preprocessing:**
   - Handle missing data through removal or imputation.
   - Encode categorical variables (e.g., sex, smoker, region) using one-hot or label encoding.
   - Scale continuous variables (e.g., age, BMI, children) for better model performance.

2. **Linear Regression Model Development:**
   - Select relevant features (age, sex, BMI, children, smoker, region).
   - Build and train a linear regression model.
   - Check for multicollinearity (e.g., using VIF) and eliminate highly correlated features.

3. **Model Evaluation:**
   - Split the data into training and testing sets (e.g., 80/20 split).
   - Evaluate performance using metrics such as MAE, MSE, RMSE, R², adjusted R², RSS, and explained variance.

4. **Feature Importance Analysis:**
   - Interpret coefficients to determine feature impact.
   - Rank features by importance, focusing on smoking status and BMI.

5. **Visualization:**
   - Create a scatterplot for actual vs. predicted values to assess model performance.

6. **Residual Analysis:**
   - Create a residual plot to check for random error distribution, a key assumption in linear regression.
