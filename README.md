# Routing_with_xgboost
### dataset.csv
Model training data from Neshan company
### imputed data.ipynb
Data after nulls are handled
### imputed data.ipynb
Notebook to handle nulls. This notebook takes the original data and the output is the data that nulls are handled
### network.gpickle
Street graph based on Neshan company data
### model.ipynb
The main part that take imputed_data.ipynb and makes the model, then takes the test_cases.csv file and predicts the time and the closest route between the src and dest. Finally, it outputs the test_cases_finall.csv file. It also outputs the model0001.h file for later use


