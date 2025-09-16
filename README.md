# -Rental-House-Price-Prediction-
This project focuses on developing a machine learning model to predict house prices using a variety of property-related features. The dataset is sourced from the Kaggle competition "House Prices – Advanced Regression Techniques". The primary objective is to build and evaluate models that can accurately estimate housing prices based on input features such as location, size, quality, and amenities.

**File Structure**

house_price_prediction.ipynb – Jupyter Notebook containing code for data preprocessing, EDA, feature engineering, model training, and prediction.
submission.csv – Output file with predicted house prices for the test dataset.
gbr.pkl – Pickle file containing the trained GradientBoostingRegressor model.

**Libraries Used**

NumPy – Numerical computations
Pandas – Data manipulation & analysis
Matplotlib, Seaborn – Data visualization
Scikit-learn – Machine learning algorithms & evaluation
XGBoost – Advanced gradient boosting

**Data Loading & Analysis**

Training and test datasets are loaded from CSV files.
Exploratory Data Analysis (EDA) is performed to study data distribution, missing values, and correlations.
Visualizations include histograms, box plots, and heatmaps for insights.

**Data Preprocessing**

Missing values handled via imputation or column removal.
Categorical features encoded using one-hot encoding.
Numerical features standardized for improved model performance.

**Model Selection & Training**

Linear Regression, SVR, SGDRegressor, KNeighborsRegressor

DecisionTreeRegressor, RandomForestRegressor

GradientBoostingRegressor, XGBRegressor, MLPRegressor

Cross-validation used with R² score to compare models.

GradientBoostingRegressor chosen for best performance.

**Model Evaluation & Predictio**n

The selected model was trained on the full training dataset.

Predictions generated for the test dataset.

Final predictions saved in submission.csv (Kaggle format
