# Water_Production_Predictor
Code to create a machine learning model for predicting water production in the City of Ann Arbor, MI.

## SI 670 (Applied Machine Learning) - Kaggle Competition
This notebook is the cleaned version of the code used to create the best performing model for a Kaggle competition. The objective of the competition was to predict the water production for the City of Ann Arbor for the years 2022 and 2023. The provided datasets detail the daily pumped flow into the water distribution system from 2014-2021, as well as additional data, including air temperature and rainfall patterns. 

With this submission, I placed 4th out of 26 teams. In addition to the work in this notebook, I did test out other algorithms and non-stacked models. However, a stacked model with Random Forest regression and XGBoost regression resulted in the lowest MSE. 

## Set Up
### Dependencies
- `Python3.11`
[Installation information can be found here (https://www.python.org/downloads/release/python-3112/)

### Installations
If you do not have xgboost installed, uncomment the pip install in the imports code block. 

*Disclaimer:* I do not own the datasets, though they are publically accessible. 
