#code book

#grouping variables
Subject: an integer 1-30 representing the individual subject
Activity: The 6 activities measured including: LAYING, SITTING, STANDING, WALKING, WALKING_DOWNSTAIRS, and WALKING_UPSTAIRS 

#measurement variables
measurement variables are captured accross 3 directional axis x,y and z. 
They were caputred with both time and frequency domains.

They are:
Body Acceleration
Gravity Acceleration
Body Acceleration Jerk
Body Gyro
Body Gyro Jerk

Additionally, magnitudes were calculated as follows:
Boddy Acceleration Magnitude
Gravity Acceleration Magnitude
Body Acceleration Jerk Magnitude
Body Gyro Magnitude
Body Gyro Jerk Magnitude

All measurements were normalized within the bounds [-1,1]

For each variable, the mean was calcualated by unique subject/activity combination and the results were saved in "finished tidy data.csv."
More information can be found in README.txt within the UCI HAR Dataset folder.