First imported the required classes and modules
Then stored the given data appropriately
Segregarted the data into numerical and categorical columns
Used features like PipeLine and ColumnTransformer
Done some Feature Engineering: filled missing values using SimpleImputer
                               scaled the values using RobustScaler
each for numerical as well as categorical columns and applied it to the training and test data
used another PipeLine for implementing Logistic Regression
used function predict_proba to find out the probabilities each for xyz_vaccine and seasonal_vaccine
combined them into a data frame and converted it into a csv file.
