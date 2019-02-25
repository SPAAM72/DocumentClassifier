# DocumentClassifier


Requirements :-

~ Sklearn
~ python 2

Problem 1
1. First build a model that classifies the two document types – whether it is employment letter or amendment letter 
Approach 

Step1-

divide the data on the basis of thier name using shutil 

step2

Import the data in python using loadfiles method of sklearn

step3

vectorize the documents ie create a sparse matrix of the documents loaded in Step2

Step3

Perform a tf-idf transform of the sparse matrix.

step4
Split the dataset into training and testing using train_test_split

Step4
Train gradientboostingclassifier on training data

step 5 
Test the data and print accuracy

