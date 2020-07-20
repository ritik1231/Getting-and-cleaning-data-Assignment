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
Subject column is numbered sequentially from 1 to 30. Activity column has 6 types as listed below:
```{r echo=FALSE}
data.frame(Types = head(FinalData$activity))
```
The tidy data contains 6 rows (averaged based on activity) and 88 columns (86 variables and activity labels).
```{r echo=FALSE}
data.frame(Columns = names(FinalData))
```
## Variable units
Activity variable is factor type. Subject variable is integer type. All the other variables are numeric type.
