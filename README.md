# data-602-assignment-6
model evaluation
    
    objective:

creating Modelling pipelines which can be used by Logistic Regression Model to perform predictions wheather a person has diabetes or not.
Comapre prepared Model with added regularization methods and various solvers
Evalutaing the models using a metric.
 procedure:
 for which we imported the necessary libraries and loaded the given csv file and noticed that there are  768 rows in the dataset.
There are 9 columns in the dataset.
there are many non-null values and we can also observe that there are only int and float data types.
There are no null values in the dataset. The data also have numerics like integer and float values so there is no purpose of preprocessing of data as the data is good.
then we checked the correlation between the columns and it is noted that there is very less or no correlation between the data variables.
then created a pipeline for scalar and modelling and one for modelling alone.
the data is there after splitted into test and train.
there are 614 training samples. there are 154 test samples.
then we have performed logestic regression choosing accuracy as the metric and found that the accuracy of the model is 79.8.
later,Using 10 fold Grid search cross validation and saga as a solver where the accuracy noted to be 76.37
the above step is followed by 10 fold Grid search cross validation where the accuracy seemed to be 76.53 
conclusion:
the accuracy of the model was noticed to be 79.8 and after performing the logestic regression with grid search cross-validation itis 76.53 using liblinear solver and 76.37 using saga solver
It can be concluded that the hyper parameter tuning doesn't improve the model.the accuracy of the model itself is higher.After performing the logestic regression with grid search cross-validation using both solvers it is noticed the the difference between accuracy of both models is almost the same.
