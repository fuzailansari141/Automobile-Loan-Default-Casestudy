This dataset consists of 40 features and 121855 records  which is taken from Kaggle.
This notebook creates a model for the "Automobile Loan Default" dataset predict whether a client will default on the vehicle loan payment or not.
This dataset is further cleaned using numpy and pandas and done Feature engineering, visualized using matplotlib and Seaborn. 
As the Dataset is imbalanced SMOTE(Oversampling) is used to balance the data Encoding is done using LabelEncoder and then splitted into features and target with the help of train_test_split then Scaling is done with StandardScaler and Performed Logistic Regression, Random-Forest, XGBoost, AdaBoost, GradientBoosting algorithms from which all Logistic Regression algorithm provides best f1 score Train 81% - Test 79%to build the model.
