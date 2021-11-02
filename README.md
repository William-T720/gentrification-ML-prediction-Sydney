# gentrification-ML-prediction-Sydney
This repository contains the .r and .python script files used to build several tree-based ML models to predict gentrification within Sydney from 2016-2021.

The initial data cleaning (step 1) was performed in R. Cleaning for census data was performed in Excel, while cleaning for non-census data was performed in 
step 1.a) (housing market variables) and 1.b) (all other non-census variables). The combined, cleaned predictor dataset is created in step 1.c)

The ML modelling (step 2) was performed in Python. Each Python script in step 2. contains a separate model. The models and their contents are:
- 2.a) Linear Regression: Basic Model, Visualisation
- 2.b) Random Forest: Basic Model, Tuned Model, Visualisation
- 2.c) Extreme Gradient Boosting: Basic Model, Tuned Model, Visualisation
- 2.d) Gradient Boosted Machine: Basic Model, Tuned Model, Visualisation, Model Explanation using SHAPley

The validation process (step 3) was performed in R. The two validation tests were performed using Housing Prices (3.a) and Development Approvals (3.b).
