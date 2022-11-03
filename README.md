# Ford-GoBike-Data-Exploration-Project

## Dataset
> **The dataset contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset consist of over 183,000 observations and 16 attributes. The dataset can be found at https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv**

## Summary of Findings
> **In the exploration, I used duration of rides as my main variable of interest. It was found that the distribution of the duration of rides is fairly normal under the log transformation with the peak around 500 seconds I also noticed that all the rides were taken in the month of February. 99.99% of the rides ended in the same month of February, while 0.01% ended in the month of March. Furthermore, most of the rides were taken and ended on working days (Monday, Tuesday, Wednesday, Thursday, Friday), with Thursday being the most popular day. The highest number of rides were taken from the 8th to 9th hour and the 17th and 18th hour of the day. `90.53%` of the riders are Subscribers and `9.47%` are Customers. I determined the ages of the riders from their birth year and did the histogram of it. No definite insights could be drawn from the distribution of the ages, I then decided to create age groups from the data. It turned out that most of the riders are in the Middle Adult age group. That is, 30 to 42 years old.
> When I explored the duration of rides with respect to the weekdays, it was seen that the median duration of rides increases gradually through the working days of the week. It experienced a swift rise on Saturdays. Also, the median duration of rides decrease from midnight to 4:00 am, then it increases till the 18th hour before it falls again. Finally, I checked if these patterns are dependent on whether a rider or user type is a Customer or Subscriber. I used median as the estimator rather than mean beacause the dataset consists of outliers.**


## Key Insights for Presentation:
> **For the presentation, I focused on the factors determining the duration of rides. I started by introducing the distribution of the duration of rides, and user type. I went forth to present the relationship of the duration of rides with weekdays and hours of the day. Finally, I presented the result of investigating the pattern above as per use type.**
