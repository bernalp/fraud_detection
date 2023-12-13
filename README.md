# Online Payment Fraud Detection

** this is still draft repositories, I working on code at other workspaces.

### Last progress on other workbook
- reading Data and Understanding the Structure
- exploring Data and Transaction Types
- visualizing Transaction Type Distribution
- calculate correlation on numeric columns with 'isFraud' column
- extracting features and target variable for machine learning
- try machine learning model using DecisionTreeClassifier
- try another model using OneHotEncoder
- perform one-hot encoding on the 'type' column
- concatenate the encoded 'type' column with other numerical columns
- split the encoded data into training and testing sets
- initialize and train the Decision Tree Classifier with the encoded training data
- perform one-hot encoding on the 'type' column in the test set
- concatenate the encoded 'type' column with other numerical columns in the test set
- use the trained model to make predictions on the encoded test data
- check the number of samples in predicted_values and ytest
- reshape y to a 1D array
- retrain the model with the updated y
- make predictions on the encoded test data
- reshape ytest to a 1D array
- calculate the accuracy score
- Try classify whether a transaction is a fraud or not by feeding about a transaction into the model
- Try classify transaction with different features
- Try classify transaction with different features value
- evaluate on test data
- evaluate confusion matrix
