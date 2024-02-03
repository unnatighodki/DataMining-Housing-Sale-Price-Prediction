# Introduction
The project aims to estimate the housing sale prices with the highest accuracy by identifying the best model using data mining and machine learning algorithms. It could help potential buyers, sellers, investors, insurance agencies, bankers, and real estate marketers understand the housing market conditions, enabling them to plan for their "dream" houses. 

<img width="309" alt="image" src="https://github.com/unnatighodki/DataMining-Housing-Sale-Price-Prediction/assets/37828502/f772f065-1135-447c-ba1a-262396da5531">

## Data Description
   - contains data on residential homes in Ames, Iowa.
   - 79 features (predictors/independent variables)
        - 36 numerical
        - 43 categorical
   
### ***Insights***

   - **Best Model** - Random Forest
   - **R2** - 88%
   - **Mean Absolute Error** - 18047.66
   - **Best Features**
        1. Overall quality of the house
        2. Ground living area
        3. 1st floor square feet
        4. 2nd floor square feet


## Regression - Predictive Analysis

***The project consists of various steps***

### Data Collection & Processing

   - Conversion of Date variables to numerical columns
   - Missing Values removal and imputation
   - Dimension Reduction using Pearson's coefficient and Carmmer's rule
   - Removal of uncorrelated variables from Target to avoid the unwanted variance
   - Target Encoding for converting categorical columns into numerical columns to feed in the models

### Data Exploration & Visualization
 
   - Bar Chart for combining categories
   - Histogram for identifying the skewed numerical variables

<img width="261" alt="image" src="https://github.com/unnatighodki/DataMining-Housing-Sale-Price-Prediction/assets/37828502/970a760f-c4bd-4fc8-951f-9cfe3a74ef98"> <img width="309" alt="image" src="https://github.com/unnatighodki/DataMining-Housing-Sale-Price-Prediction/assets/37828502/3a366b2b-a5fb-4e35-954d-31cd7d51f5de">



### Model Exploration & Selection
 
  - Data Preparation
  - Data Standardization
  - Data Splitting

### Implementation of Selected Model and Exploration

   - Linear Regression
   - Random Forest
   - Regularized Linear Regression Model – Lasso
   - Regularized Linear Regression Model – Ridge
   - Regularized Linear Regression Model – Bayesian
   - Decision Trees

### Performance Evaluation & Interpretation

   - Identification of the best features by Random Forest
   - Comparison of various models by evaluation metrics such as R2 score and RMSE
