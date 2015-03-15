---
title: "PA1_template.md"
author: "ddddd"
date: "Saturday, March 14, 2015"
output:
  html_document:
    fig_caption: yes
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(cache=FALSE)
```


---
title: 'Reproducible Research: Peer Assessment 1'
output:
  html_document:
    fig_caption: yes
    keep_md: yes
---



# Introduction [1]

It is now possible to collect a large amount of data about personal movement using activity monitoring devices such as a Fitbit, Nike Fuelband, or Jawbone Up. These type of devices are part of the “quantified self” movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. But these data remain under-utilized both because the raw data are hard to obtain and there is a lack of statistical methods and software for processing and interpreting the data.


This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.


# Data [1]

The data for this assignment can be downloaded from the course web site:

Dataset: Activity monitoring data [52K]
The variables included in this dataset are:

- steps: Number of steps taking in a 5-minute interval (missing values are coded as NA)

- date: The date on which the measurement was taken in YYYY-MM-DD format

- interval: Identifier for the 5-minute interval in which measurement was taken

The dataset is stored in a comma-separated-value (CSV) file and there are a total of 17,568 observations in this dataset.

# Loading and preprocessing the data
This section shows how to load and process data

### 1.Load the data
```{r 'Loading Data'}
my_data <- read.csv("activity.csv") # Read in data file
```

### 2.Process/transform the data

```{r 'Processing Data'}
# Dates are formatted as YYYY-MM-DD
my_dates <- strptime(my_data$date, "%Y-%m-%d")
my_data$date <- my_dates

# Keep a list of all possible days
my_uniqueDates <- unique(my_dates)
# Keep a list of all possible intervals
my_uniqueIntervals <- unique(my_data$interval)

```


## What is mean total number of steps taken per day?
For this part of the assignment, we ignore the missing values in the dataset.

### 1.Total number of steps taken per day

```{r 'Total number of steps taken per day' }
# Split the data frame by steps
my_stepsSplittedByDay <- split(my_data$steps, my_dates$yday)

# Calculate and show Total number of steps of each day
my_totalStepsByDay <- sapply(my_stepsSplittedByDay, sum, na.rm=TRUE)
head(my_totalStepsByDay) 
```



### 2.Make a histogram of the total number of steps taken each day
```{r 'Histogram of the total number of steps taken each day' }
# Plot an histogram where days are presented in x-axis  
# and the total number of steps by day are presented in the y-axis 

plot(my_uniqueDates, my_totalStepsByDay, main="Histogram of the total number of steps taken each day", 
     xlab="Date (October and November, 2012)", ylab="Total number of steps", type="h", lwd=4, col="red")
```

### 3. Calculate and report the mean and median of the total number of steps taken per day

#### The mean of the total number of steps taken per day are:
```{r 'The mean of the total number of steps taken per day' }
my_meanStepsByDay <- sapply(my_stepsSplittedByDay, mean, na.rm=TRUE)
my_meanDataFrameByDay <- data.frame(date=my_uniqueDates, meanStepsByDay=my_meanStepsByDay, row.names=NULL)
head(my_meanDataFrameByDay)
```

#### The median of the total number of steps taken per day are:
```{r 'The median of the total number of steps taken per day' }
my_medianStepsByDay <- sapply(my_stepsSplittedByDay, median, na.rm=TRUE)
my_medianDataFrameByDay <- data.frame(date=my_uniqueDates, medianStepsByDay=my_medianStepsByDay, row.names=NULL)
head(my_medianDataFrameByDay)
```

## What is the average daily activity pattern?

### 1.Make a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all days (y-axis)


```{r 'time-series graph with The average number of steps taken' }
# x-axis - the 5-minute interval
# y-axis - the average number of steps taken, averaged across all days

# Splitting data by intervals
my_stepsSplittedByinterval <- split(my_data$steps, my_data$interval)

# The average number of steps taken, averaged across all days
my_averageStepsByInterval <- sapply(my_stepsSplittedByinterval, mean, na.rm=TRUE)

# Plotting the time-series graph with The average number of steps taken
plot(my_uniqueIntervals, my_averageStepsByInterval, type="l",
     main="The average number of steps taken, averaged across all days", 
     xlab="The 5-minute interval", ylab="The average number of steps taken", 
     lwd=2, col="red")

# Find the the maximum
my_maxStepsByDaysInterval <- max(my_averageStepsByInterval, na.rm=TRUE)
my_maxIndex <- as.numeric(which(my_averageStepsByInterval == my_maxStepsByDaysInterval))

# Plot the max with a blue line
my_maxInterval <- my_uniqueIntervals[my_maxIndex]
abline(v=my_maxInterval, col="blue", lwd=3)

```


### 2.Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?
```{r 'Interval with maximum steps'}
result <- paste('Interval max is: ' , my_maxInterval)
result
```

 


## Imputing missing values
Note that there are a number of days/intervals where there are missing values (coded as NA). The presence of missing days may introduce bias into some calculations or summaries of the data.

### 1. Calculate and report the total number of missing values in the dataset (i.e. the total number of rows with NAs)

```{r 'Total number of missing values'}
my_na <- is.na(my_data$steps)
my_naCount = paste('There is ' , sum(my_na) ,' NAs.')
my_naCount
```


### 2. Devise a strategy for filling in all of the missing values in the dataset. The strategy does not need to be sophisticated. For example, you could use the mean/median for that day, or the mean for that 5-minute interval, etc.

```{r 'Replacing NAs with mean values'}
# Replace NaN values with 0.  
my_meanStepsByDay[is.nan(my_meanStepsByDay)] <- 0

# Now create a replicated column for mean values and use it to replace columns with NAs values
my_replicatedMeanColumn <- rep(my_meanStepsByDay, length(my_stepsSplittedByinterval) - 1 )


# The steps before replacement
my_Steps <- my_data$steps

# Find any values that are NA in the raw steps data
my_originalStepswithNAs <- is.na(my_Steps)

# Now replace these values with their corresponding mean
my_Steps[my_originalStepswithNAs] <- my_replicatedMeanColumn[my_originalStepswithNAs]
```


### 3. Create a new dataset that is equal to the original dataset but with the missing data filled in.

```{r 'Data with missing values'}
my_newData <- my_data
my_newData$steps <- my_Steps
head(my_newData)


# Splitting the new data frame for steps by day
my_newStepsSplittedByDay <- split(my_newData$steps, my_dates$yday)

# NCalcul of the total number of steps by each day
my_newTotalStepsSplittedByDay <- sapply(my_newStepsSplittedByDay, sum)
```


### 4.Make a histogram of the total number of steps taken each day and Calculate and report the mean and median total number of steps taken per day. Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data on the estimates of the total daily number of steps?

```{r 'Plots of data with and without missing values'}

# Plotting an histogram where days are presented in the x-axis 
# and the total daily number of steps are presented in the y-axis
par(mfcol=c(2,1))

# Plotting the original data without NAs
plot(my_uniqueDates, my_totalStepsByDay, main="Histogram of steps taken each day before imputing NAs", 
     xlab="Date (October and November, 2012)", ylab="Total daily number of steps", type="h", lwd=4, col="red")
# Plot the modified data after imputing NAs
plot(my_uniqueDates, my_newTotalStepsSplittedByDay, main="Histogram of steps taken each day after imputing NAs", 
     xlab="Date (October and November, 2012)", ylab="Total daily number of steps", type="h", lwd=4, col="blue")
```


**************

```{r 'Data with columns of initial mean values and with new mean values' }
my_newMeanStepsByDay <- sapply(my_newStepsSplittedByDay, mean)
my_newMeanDataFrame <- data.frame(date=my_uniqueDates, meanStepsByDay=my_meanStepsByDay, 
newMeanStepsByDay=my_newMeanStepsByDay, row.names=NULL)
my_newMeanDataFrame

```


if we use median values, we have:

**********************

```{r 'Data with columns of initial median values and with new median values'}
my_newMedianStepsByDay <- sapply(my_newStepsSplittedByDay, median)
my_newMedianDataFrame <- data.frame(date=my_uniqueDates, meanStepsByDay=my_medianStepsByDay, 
newMedianStepsByDay=my_newMedianStepsByDay, row.names=NULL)
head(my_newMedianDataFrame)

```



## Are there differences in activity patterns between weekdays and weekends?

We use the dataset with the filled-in missing values for this part.


### 1.Create a new factor variable in the dataset with two levels for weekdays and for weekends indicating whether a given date is a weekday or weekend day.
```{r 'factors of weekdays and weekends'}
# Splitting data by week and weekend days
my_weekDays <- my_dates$wday

# Setting a new column variable to 1 if weekdaus and to 2 if weekend days
my_weekdaysClassification <- rep(0, length(my_weekDays)-1) # 17568 observations overall
my_weekdaysClassification[my_weekDays >= 1 & my_weekDays <= 5] <- 1
my_weekdaysClassification[my_weekDays == 6 | my_weekDays == 0] <- 2

# Setting a new factor variable labelled "Weekdays"" and "Weekends""
my_daysFactor <- factor(my_weekdaysClassification, levels=c(1,2), labels=c("Weekdays", "Weekends"))

# Creatting a column for this factor
my_newData$typeOfDay <- my_daysFactor

# Now split up into two data frames
my_newWeekdaysData <- my_newData[my_newData$typeOfDay == "Weekdays", ]
my_newWeekendsData <- my_newData[my_newData$typeOfDay == "Weekends", ]
```



### 2.Make a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis). See the README file in the GitHub repository to see an example of what this plot should look like using simulated data.

****************

```{r 'Plotting average of steps by interval for weekdays and for weekends' }
# Further split up the Weekdays and Weekends into their own intervals
myDataForWeekdaysSplittedByInterval <- split(my_newWeekdaysData$steps, my_newWeekdaysData$interval)
myDataForWeekendsSplittedByInterval <- split(my_newWeekendsData$steps, my_newWeekendsData$interval)

# Calculus of average steps by interval
myMeanForWeekdaysSplittedByInterval <- sapply(myDataForWeekdaysSplittedByInterval, mean)
myMeanForWeekendsSplittedByInterval <- sapply(myDataForWeekendsSplittedByInterval, mean)

# Plotting average of steps by interval for weekdays 
par(mfcol=c(2,1))
plot(my_uniqueIntervals, myMeanForWeekdaysSplittedByInterval, type="l", main="Average number of steps taken, averaged across all weekday days", xlab="5-minute interval", ylab="Average number of steps taken", lwd=2, col="red")

# Plotting average of steps by interval for weekends
plot(my_uniqueIntervals, myMeanForWeekendsSplittedByInterval, type="l",
main="Average number of steps taken, averaged across all weekends", 
xlab="5-minute interval", ylab="Average number of steps taken", 
lwd=2, col="blue")

```
