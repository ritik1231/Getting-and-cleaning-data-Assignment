---
output:
  word_document: default
  html_document: default
---
title: "Codebook"
output: word_document
---
# Tidy Data Set Description
## The variables in the tidy data
Tidy data contains 180 rows and 68 columns. Each row has averaged variables for each subject and each activity.
## Only all the variables estimated from mean and standard deviation in the tidy set were kept.
-mean(): mean value  
-std(): standard deviation  
## The data were averaged based on subject and activity group.
-Subject column is numbered sequentially from 1 to 30. Activity column has 6 types as listed below:  
1             LAYING
2            SITTING
3           STANDING
4            WALKING
5 WALKING_DOWNSTAIRS
6   WALKING_UPSTAIRS

-The tidy data contains 6 rows (averaged based on activity) and 88 columns (86 variables and activity labels).  
1                                             subject
2                                            activity
3                      TimeBodyAccelerometer.mean...X
4                      TimeBodyAccelerometer.mean...Y
5                      TimeBodyAccelerometer.mean...Z
6                   TimeGravityAccelerometer.mean...X
7                   TimeGravityAccelerometer.mean...Y
8                   TimeGravityAccelerometer.mean...Z
9                  TimeBodyAccelerometerJerk.mean...X
10                 TimeBodyAccelerometerJerk.mean...Y
11                 TimeBodyAccelerometerJerk.mean...Z
12                         TimeBodyGyroscope.mean...X
13                         TimeBodyGyroscope.mean...Y
14                         TimeBodyGyroscope.mean...Z
15                     TimeBodyGyroscopeJerk.mean...X
16                     TimeBodyGyroscopeJerk.mean...Y
17                     TimeBodyGyroscopeJerk.mean...Z
18              TimeBodyAccelerometerMagnitude.mean..
19           TimeGravityAccelerometerMagnitude.mean..
20          TimeBodyAccelerometerJerkMagnitude.mean..
21                  TimeBodyGyroscopeMagnitude.mean..
22              TimeBodyGyroscopeJerkMagnitude.mean..
23                FrequencyBodyAccelerometer.mean...X
24                FrequencyBodyAccelerometer.mean...Y
25                FrequencyBodyAccelerometer.mean...Z
26            FrequencyBodyAccelerometer.meanFreq...X
27            FrequencyBodyAccelerometer.meanFreq...Y
28            FrequencyBodyAccelerometer.meanFreq...Z
29            FrequencyBodyAccelerometerJerk.mean...X
30            FrequencyBodyAccelerometerJerk.mean...Y
31            FrequencyBodyAccelerometerJerk.mean...Z
32        FrequencyBodyAccelerometerJerk.meanFreq...X
33        FrequencyBodyAccelerometerJerk.meanFreq...Y
34        FrequencyBodyAccelerometerJerk.meanFreq...Z
35                    FrequencyBodyGyroscope.mean...X
36                    FrequencyBodyGyroscope.mean...Y
37                    FrequencyBodyGyroscope.mean...Z
38                FrequencyBodyGyroscope.meanFreq...X
39                FrequencyBodyGyroscope.meanFreq...Y
40                FrequencyBodyGyroscope.meanFreq...Z
41         FrequencyBodyAccelerometerMagnitude.mean..
42     FrequencyBodyAccelerometerMagnitude.meanFreq..
43     FrequencyBodyAccelerometerJerkMagnitude.mean..
44 FrequencyBodyAccelerometerJerkMagnitude.meanFreq..
45             FrequencyBodyGyroscopeMagnitude.mean..
46         FrequencyBodyGyroscopeMagnitude.meanFreq..
47         FrequencyBodyGyroscopeJerkMagnitude.mean..
48     FrequencyBodyGyroscopeJerkMagnitude.meanFreq..
49           Angle.TimeBodyAccelerometerMean.Gravity.
50  Angle.TimeBodyAccelerometerJerkMean..GravityMean.
51           Angle.TimeBodyGyroscopeMean.GravityMean.
52       Angle.TimeBodyGyroscopeJerkMean.GravityMean.
53                               Angle.X.GravityMean.
54                               Angle.Y.GravityMean.
55                               Angle.Z.GravityMean.
56                      TimeBodyAccelerometer.std...X
57                      TimeBodyAccelerometer.std...Y
58                      TimeBodyAccelerometer.std...Z
59                   TimeGravityAccelerometer.std...X
60                   TimeGravityAccelerometer.std...Y
61                   TimeGravityAccelerometer.std...Z
62                  TimeBodyAccelerometerJerk.std...X
63                  TimeBodyAccelerometerJerk.std...Y
64                  TimeBodyAccelerometerJerk.std...Z
65                          TimeBodyGyroscope.std...X
66                          TimeBodyGyroscope.std...Y
67                          TimeBodyGyroscope.std...Z
68                      TimeBodyGyroscopeJerk.std...X
69                      TimeBodyGyroscopeJerk.std...Y
70                      TimeBodyGyroscopeJerk.std...Z
71               TimeBodyAccelerometerMagnitude.std..
72            TimeGravityAccelerometerMagnitude.std..
73           TimeBodyAccelerometerJerkMagnitude.std..
74                   TimeBodyGyroscopeMagnitude.std..
75               TimeBodyGyroscopeJerkMagnitude.std..
76                 FrequencyBodyAccelerometer.std...X
77                 FrequencyBodyAccelerometer.std...Y
78                 FrequencyBodyAccelerometer.std...Z
79             FrequencyBodyAccelerometerJerk.std...X
80             FrequencyBodyAccelerometerJerk.std...Y
81             FrequencyBodyAccelerometerJerk.std...Z
82                     FrequencyBodyGyroscope.std...X
83                     FrequencyBodyGyroscope.std...Y
84                     FrequencyBodyGyroscope.std...Z
85          FrequencyBodyAccelerometerMagnitude.std..
86      FrequencyBodyAccelerometerJerkMagnitude.std..
87              FrequencyBodyGyroscopeMagnitude.std..
88          FrequencyBodyGyroscopeJerkMagnitude.std..
## Variable units
Activity variable is factor type. Subject variable is integer type. All the other variables are numeric type.
