# Analysis

### Initial Exploration

* Included the dataset and performed linear regression to check the performance of the model. The performance is low but I believe adding more features will increase the performance of the model. 

### Linear Regression

* Earlier with a single feature Linear Regression accuracy was calculated at 0.02197. After adding 3 features which are  'Stay_In_Current_City_Years','Occupation' and 'Marital_Status' Linear Regression the performace of the model has increased.


[Linear Regression Notebook](https://github.com/44-599-Machine-Learning-F22/project-machine-learning-f22-nayanjr/blob/main/linear_regression.ipynb)

### Classification

1. Random Forest accuracy is achieved at 67.81

2. Decision Tree Classifier accuracy:  67.81

3. SVM accuracy:  61.87

[Classification Notebook](https://github.com/44-599-Machine-Learning-F22/project-machine-learning-f22-nayanjr/blob/main/classification.ipynb)

### Limitations

* The initial dataset had a lot noise So, before applying dataset modeling, I translated the data to integer values using LabelEncoder.  I have worked on removing null values and have created a derived feature which will divide the purchase amount to two classes.