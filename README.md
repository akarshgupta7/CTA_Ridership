# CTA_Ridership
1. Download the python notebook and the compressed dataset.<br />
2. Unzip the dataset to retrieve the CSV file.<br />
3. Comment out the first cell if not using Google Drive.<br />
4. Change the file path in the second code cell.<br />
5. Packages used: pandas, numpy, matplotlib.pyplot, datetime, sklearn.ensemble, xgboost, joblib, sklearn.metrics, sklearn.model_selection<br />
6. The whole notebook takes about 40 minutes to run on Google Colab (may take more on a personal computer)<br />
7. Skip running the code cell below 'Error analysis on training and dev set: Increasing training data by sequentially including past year's data' section as it does an exploratory analysis of significance of historical data on predictions for Random Forest and XGBoost Model.<br />
8. To quickly run the notebook (not performing cross validation), use the random forest model with parameters mentioned on the last bullet point of the summary of ML model. Change the model name accordingly so that .predict() doesn't give any errors.<br />
9. The code saves the best model found by grid search cross validation. The file size is about 250MB. Comment the code cell below 'Cross validation' section if there is no need to save the model. 
