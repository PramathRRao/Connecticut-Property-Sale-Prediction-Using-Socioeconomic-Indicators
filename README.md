# Connecticut-Property-Sale-Prediction-Using-Socioeconomic-Indicators

Overview:
This project analyzes real estate sale prices in Connecticut from 2001 to 2022 using socioeconomic factors like crime rates, school availability, healthcare access, and economic metrics. The study integrates and processes multiple datasets, performs exploratory data analysis (EDA), and builds predictive models using Random Forest and XGBoost regressors. The goal is to provide stakeholders—homebuyers, policymakers, and investors—with insights into factors influencing property value.

Requirements

Prerequisites:

1. Python Environment:
   - Jupyter Notebook or any Python IDE with support for data science libraries

2. Python Version:
   - Python 3.8 or higher

3. Libraries to Install:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
   - xgboost
   - plotly (optional for advanced visualizations)

To install these libraries, use:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost plotly

4. Dataset:
   The dataset is included in the `dataset.zip` file. It includes:
   - Real estate sales data (2001–2022)
   - Crime data per 100,000 population
   - Public school count by town
   - Healthcare facility distribution
   - Economic indicators like wages and employment statistics

   Steps:
   i. Extract `dataset.zip`.
   ii. Place the extracted datasets in the `/dataset` folder.
   iii. Update file paths in the notebook or source code if needed.

5. Steps to Run the Project:

i. Open Jupyter Notebook or preferred IDE.

ii. Navigate to the `src/` directory and open the notebook or Python scripts:
   - `data_preprocessing.py` for data cleaning and merging
   - `model_training.py` for model development and evaluation
   - `visualizations.ipynb` (optional) for generating EDA and geospatial plots

iii. Run preprocessing to clean and merge datasets.

iv. Train and evaluate models:
   - Random Forest Regressor
   - XGBoost Regressor

v. View model metrics:
   - R² Score
   - RMSE (Root Mean Squared Error)
   - Residual plots
   - Feature importance graphs

Outputs:
The model generates sale price predictions, visual insights into crime, school, and healthcare influence on real estate prices, and detailed performance comparisons. The best-performing model was Random Forest, with an R² of ~0.95 for sale price prediction.
