# GettingAndCleaningData

## Collection
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

## Data Transformation
Test and training data, subject ids and activity ids are merged into a single data set. The mean and standard deviation are calculated from the merged data set. A new column is added with activity description. And a tidy data set is created with the average of each variable for each activity and subject. 

## Variable Names:
leading t or f is based on time or frequency measurements.
Body = related to body movement
Gravity = acceleration of gravity
Acc = accelerometer measurement
Gyro = gyroscopic measurements
Jerk = sudden movement acceleration
Mag = magnitude of movement
mean and SD are calculated for each subject for each activity for each mean and SD measurements
