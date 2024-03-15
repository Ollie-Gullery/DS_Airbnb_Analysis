# DS_Airbnb_Analysis

Analysis of Kaggle's Airbnb Dataset

**Objective**: Predict the 'popularity' of an Airbnb listing.

*Brief Project Overview*

## Methodology

### EDA
- Performed data analysis with Pandas and NumPy using methods such as: `.info()`, `.describe()`,  `.shape`, `.corr()`, `.isnull().sum()`, etc. to obtain summary statistics.

- Generated Visualizations with `seaborn` & `matplotlib` including correlation heat maps, box plots, scatter plots, etc.

- Generated ideas for Feature Engineering and excecuted ideas using methods such as discretization, imputation, 

### Preprocessing & Transformations

- Utilized sklearn's `make_pipeline` and `make_column_transformers` to prepare data for modelling and ensure there is *no data leakage occurs.*
    - Utilized methods such as ordinalEncoder, OneHotEncoder, StandardScaler to transform the data and prepare it for modelling. 


### Modelling & Evaluations

- Generated model with sklearns Gradient Boosting Regressor, XGBoost, and Ridge Regression

- Used cross validation and hyperparameter optimization with GridSearchCV to obtain optimal hyperparameters. 

- Used `SHAP` to analyze feature importances in the model 
