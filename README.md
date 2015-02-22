The R script run_analysis.R performs five steps:
1. Merges the training and the test sets to create one data set.

This is done using the rbind() function

2. Extracts only the measurements on the mean and standard deviation for each measurement.

Names are given based on the features.txt file provided by the UCI HAR dataset.

3. Uses descriptive activity names to name the activities in the data set

Descriptive activity names are applied to the dataset based the activity_labels.txt file.

4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.