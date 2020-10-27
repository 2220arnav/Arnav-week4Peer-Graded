Tidy data set description
The variables in the tidy data
Tidy data contains 180 rows and 68 columns. Each row has averaged variables for each subject and each activity.

Only all the variables estimated from mean and standard deviation in the tidy set were kept.
mean(): Mean value
std(): Standard deviation
The data were averaged based on subject and activity group.
Subject column is numbered sequentially from 1 to 30. Activity column has 6 types as listed below.

WALKING
WALKING_UPSTAIRS
WALKING_DOWNSTAIRS
SITTING
STANDING
LAYING
The tidy data contains 6 rows (averaged based on activity) and 68 columns (66 variables and activity labels).
1."activitylabel"
2."subject"
3."tBodyAcc-mean()-X"
4."tBodyAcc-mean()-Y"
5."tBodyAcc-mean()-Z"
6."tBodyAcc-std()-X"
7."tBodyAcc-std()-Y"
8."tBodyAcc-std()-Z"
9."tGravityAcc-mean()-X"
10."tGravityAcc-mean()-Y"
11."tGravityAcc-mean()-Z"
12."tGravityAcc-std()-X"
13."tGravityAcc-std()-Y"
14."tGravityAcc-std()-Z"
15."tBodyAccJerk-mean()-X"
16."tBodyAccJerk-mean()-Y"
17."tBodyAccJerk-mean()-Z"
18."tBodyAccJerk-std()-X"
19."tBodyAccJerk-std()-Y"
20."tBodyAccJerk-std()-Z"
21."tBodyGyro-mean()-X"
22."tBodyGyro-mean()-Y"
23."tBodyGyro-mean()-Z"
24."tBodyGyro-std()-X"
25."tBodyGyro-std()-Y"
26."tBodyGyro-std()-Z"
27."tBodyGyroJerk-mean()-X"
28."tBodyGyroJerk-mean()-Y"
29."tBodyGyroJerk-mean()-Z"
30."tBodyGyroJerk-std()-X"
31."tBodyGyroJerk-std()-Y"
32."tBodyGyroJerk-std()-Z"
33."tBodyAccMag-mean()"
34."tBodyAccMag-std()"
35."tGravityAccMag-mean()"
36."tGravityAccMag-std()"
37."tBodyAccJerkMag-mean()"
39."tBodyAccJerkMag-std()"
40."tBodyGyroMag-mean()"
41."tBodyGyroMag-std()"
42."tBodyGyroJerkMag-mean()"
43."tBodyGyroJerkMag-std()"
44."fBodyAcc-mean()-X"
45."fBodyAcc-mean()-Y"
46."fBodyAcc-mean()-Z"
47."fBodyAcc-std()-X"
48."fBodyAcc-std()-Y"
49."fBodyAcc-std()-Z"
50"fBodyAccJerk-mean()-X"
51."fBodyAccJerk-mean()-Y"
52."fBodyAccJerk-mean()-Z"
53."fBodyAccJerk-std()-X"
54."fBodyAccJerk-std()-Y"
55."fBodyAccJerk-std()-Z"
56."fBodyGyro-mean()-X"
57."fBodyGyro-mean()-Y"
58."fBodyGyro-mean()-Z"
59."fBodyGyro-std()-X"
60."fBodyGyro-std()-Y"
61."fBodyGyro-std()-Z"
62."fBodyAccMag-mean()"
63."fBodyAccMag-std()"
64."fBodyBodyAccJerkMag-mean()"
66."fBodyBodyAccJerkMag-std()"
67."fBodyBodyGyroMag-mean()"
68."fBodyBodyGyroMag-std()"
69."fBodyBodyGyroJerkMag-mean()"
70."fBodyBodyGyroJerkMag-std()"
variable units
Activity variable is factor type. Subject variable is integer type. All the other variables are numeric type.
