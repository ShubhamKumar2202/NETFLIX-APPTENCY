<img width="438" alt="image" src="https://user-images.githubusercontent.com/88205480/177112704-cb3dd34a-2a83-4203-ac64-726f50bf00f6.png">

# NETFLIX-APPTENCY
 The test set. it consists of everything in train.csv except target.
 Test set csv - https://www.kaggle.com/competitions/netflix-appetency/data?select=test.csv
 The training set. it consists of an id column, the customers features, and a target column: target.
 Train set csv - https://www.kaggle.com/competitions/netflix-appetency/data?select=train.csv
 A sample submission file in the correct format target=1 means that the customer subscribes to Netflix
 Sample_submission - https://www.kaggle.com/competitions/netflix-appetency/data?select=sample_submission.csv


steps:-
1) IMPORTS

- NUMPY
- PANDAS
- SEABORN
- MATPLOTLIB.PYPLOT
- DATETIME
- SKLEARN.PREPROCESSING
- CATBOOST
- XGBOOST
- LIGHTgbm
- sklearn.preprocesing(LabelEncoder)
- sklearn.model_selection(cross_val_score, Kfold, RepeatedStratifiedKFold, StratifiedKFold, cross_val_predict)
- sklearn.model_selection(train_test_split, GridSearchCV)
- sklearn.metrics(roc_auc_score)


2 IMPORT AND READ THE DATASET
- TRAIN.CSV - the training set. it consists of an id column, the customers features, and a target column: target.
- TEST.CSV  - the test set. it consists of everything in train.csv except targe.

NOTE:- USED ---->  (%config Completer.use_jedi = False ) MAGIC COMMAND.
			- Once you have enabled and run the %config Completer.use_jedi = False magic command, 
			  you can trigger the code autocompletion by pressing the tab button after the "." character.


3. ANALYSIS
- HEAD()
- SHAPE()
- DESCRIBE()
----> FIND MISSING DATA:-
- get_mising- function made to find missing data
- A histplot to show the distribution of missing data
- A histplot to show the distribution of missing data  in  Missing_df
	- To get columns with more than 25% missing values.
- Drop them from test and train set.

- Print categorical features of datatype object.
- Print numerical features of datatype object.
- Plot a pichart to show the percentage of numeric and categorical features.
- Fill with median(Numerical Features).
- Fill with mode(Categorical Features).

- Find columns that contain date objects.
- Apply datetime format.
- Show datetime features.
- Get each part of datetime using pandas DatetimeIndex.

- Drop from train/test.
- Update Categorical_Features list.

- Create a copy of datasets.
	- For train and test.
- Get the number of unique values for each feature.
- Categorical Features Sorted by cardinality.
