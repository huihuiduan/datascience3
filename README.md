# Overview

# The objective of run_analysis.R is to: 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

# The steps include: 

1. Read features and activity_labels and Remove the - ,  ( and ). 
2. Read train and test subject and combine. 
3. Read X_train, X_test, Y_train and Y_test data sets. 
4. Combine X, subject and Y, then combine train and test to the fulldata. 
5. Average for each activity and each subject and write to working directory. 
6. Output the tidy data. 