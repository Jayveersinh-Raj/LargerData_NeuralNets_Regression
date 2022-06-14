This notebook contains Neural Networks Regression on larger data sets (taken from kaggle) in TensorFlow
Main Highlights:
Preprocessing (without normalization):
1. Reading from CSV using pandas (as pd)
2. One-Hot encoding using pd.get_dummies(name_of_the_variable_you_stored_from_csv_read) # It will directly encode non numeric data
3. Using Sklearn to split the train and test data (20% test, 80% train)

-> Building model, evaluating, saving the fit and plotting the loss curve

Preprocessing (with normalization)
1. Reading from the CSV
2. Using tranformer with MinMaxScalar(normalization) and OneHotEncoding (using Sklearn)
3. Using Sklearn to split the test and train data (0.2 for test i.e. 20% and 80% to train)

-> Model
