## About R script
File with R code `run_analysis.R` perform 5 following steps :  

1. Merges the training and the test sets to create one data set.   
  1.1 Read files (tranings tables, testing tables, feature vector, activity labels)    
  1.2 Assign column names   
  1.3 Merge all data in one set   
  
2. Extracts only the measurements on the mean and standard deviation for each measurement   
  2.1 Read column names  
  2.2 Create vector for defining ID, mean and standard deviation   
  2.3 Make nessesary subset from setAllInOne
  
3. Uses descriptive activity names to name the activities in the data set   

4. Appropriately labels the data set with descriptive variable names   

5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject   
  5.1 Make second tidy data set   
  5.2 Write second tidy data set in txt file   

## About variables :
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* `features` contains the correct names for the `x_data` dataset, which are applied to the column names stored in
