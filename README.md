# data1030_financial_forecasting
## Files relating to term project for Data 1030

- Data folder:
  - Contains all datasets used in the project - includes financial and weather data imported from the external sources as well as engineered feature matrices and target variable.
- Figures folder:
  - Contains all plots generated during the training and analysis of the models considered in this project. 
  - Figures are labeled with the prefix "HPT_" if they are one of the models found via hyperparameter tuning 
  (the only model not fitting this description is a reference random forest used for comparison against the main RF)
  - Figures describing feature importance are included
- Results folder:
  - Contains saved models and their predictions of the target variable (predictions are stored for both the target delta values, and for the original stock price values of which
  the delta values describe the daily change) 
- Report folder:
  - Contains project report (due to report word limit, there is some information given in the models.ipynb notebook that is not in the report)
- src folder:
  - Contains notebooks detailing the EDA completed for the original dataset and the training and analysis of the models used in executing the regression task
  
