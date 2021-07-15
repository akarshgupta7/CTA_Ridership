# CTA_Ridership
Download the python notebook and the compressed dataset.
Unzip the dataset to retrieve the CSV file.
Comment out the first cell if not using Google Drive
Change the file path in the second code cell
Packages used: pandas, numpy, matplotlib.pyplot, datetime, sklearn.ensemble, xgboost, joblib, sklearn.metrics, sklearn.model_selection
The whole notebook takes about 40 minutes to run on Google Colab (may take more on a personal computer)
Skip running the code cell below 'Error analysis on training and dev set: Increasing training data by sequentially including past year's data' as it does an exploratory analysis of significance of historical data on predictions for Random Forest and XGBoost Model.
To quickly run the notebook (not performing cross validation), use the random forest model with parameters mentioned on the last bullet point of the summary of ML model. Change the model name accordingly so that .predict() doesn't give any errors.
