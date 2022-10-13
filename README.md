# PyBer-Challenge

## **Overview of the analysis:** 


#### **Software:** Python 3.7.13, Pandas 1.3.5, Matplotlib 3.2.2, Jupyter Notebook 6.4.12

#### Used Python library in Jupyter Notebook and imported the Pandas and Matplotlib modules. The PyBer [city_data.csv](https://github.com/nabernal/PyBer-Challenge/files/9771146/city_data.csv) and [ride_data.csv](https://github.com/nabernal/PyBer-Challenge/files/9771142/ride_data.csv) files were merged into a new data frame called *pyber_data_df*. Data from the original and merged data frames were used to gather the number of rides, drivers, and fare for each city type (urban, suburban, and rural). These totals were then used to calculate the average fare per ride and driver by city type.

#### Three new data frames were created for the second part of the analysis. The first was to list the fare by date for each city type. The second data frame was created from the previous one to locate dates ranging from January 1, 2019, to April 28, 2019. A final data frame was created using the *resample* and *sum* functions. From this, a line graph was created using the object-oriented interface method to display the total fare by city type for the range or dates in 2019. 

## **Results:**
#### In image one we see that following:
1. Rural cities have the least amount of drivers and the lowest total fares. 
2. Rural cities have higher average ride and driver fares compared to suburban and urban cities. 


<img width="560" alt="PyBer_summary_data_frame" src="https://user-images.githubusercontent.com/108249510/195511597-384ec07b-cf29-4bbb-9a81-c249278c42b6.png"> 
Figure 1 



#### Looking more closely at weekly fares from January 1, 2019 to April 28, 2019 we see the following:
1. Regardless of the week, the total fare for Urban cities is greater than suburban and rural cities combined.
2. The highest total fare for urban and suburban city type was made in the week of February 24, 2019.


<img width="289" alt="Weekly_fares_data_frame" src="https://user-images.githubusercontent.com/108249510/195511652-4fcb9709-5518-4768-a954-39b315880546.png">
Figure 2 

#### The graph is a more digestible display of the information drawn from the previous image. The city type that makes the most in fares are urban cities, followed by suburban and rural ones. We can also see that the total fares of each city never overlap with another city type. Another thing that pops out is the months making it easy to track high and low points throught a month.


![PyBer_fare_summary](https://user-images.githubusercontent.com/108249510/195511750-c5b8e01a-9335-4684-89dc-5268a1130196.png)
Figure 3

## **Summary:** 
#### The data shows that rural cities have the lowest total fare. However, their fares per ride are the highest out of the three city types. This is most likely associated with driving longer distances to a rider's drop-off destination compared to urban and suburban cities. Hiring more drivers is highly encouraged as long as there is a high ride demand. First, I recommend collecting data from the application to see how many requests are canceled. This can provide insight into whether there is a demand for more rides. If there is, I recommend increasing drivers in increments to ensure drivers do not suffer financially due to an abundant amount of drivers compared to ride requests. 
