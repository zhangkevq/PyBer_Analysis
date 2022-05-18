# PyBer_Analysis
  In this Python project, I will seek to use Pandas to compare the summaries of ride-sharing data by city type and creating a graph which summarizes the differences in total fares for each city type. We will investigate the general trends and differences between these city-types data on a single graph. The three different city types we are looking to investigate are **Urban**, **Suburban**, and **Rural**.
  
### Ride-Sharing Summary DataFrame
  The first summary of data we need is the ride-sharing summary DataFrame by city type. <br>  
![Pyber Summary DataFrame](https://github.com/zhangkevq/PyBer_Analysis/blob/main/Resources/pyber_summary_df.png) <br>  
  
  This is just the first few rows of the data, but the data is grouped by city types **Rural**, **Suburban**, and **Rural** and various relevant statistics associated with ride-sharing. The data shows that Urban ride-sharing is a figure or two higher than Rural or Suburban usage, which is where most of the ride-sharing money comes from. The average fares are also lowest in urban areas.

### Multiple-Line Chart of Total Fares for Each City Type
  We would like to get a chart that shows the fares of Ride-Shares in each city type from the beginning of Jan 2019 to the end of April 2019. <br>  
![total_fare_by_city_type](https://github.com/zhangkevq/PyBer_Analysis/blob/main/Resources/total_fare_by_city_type.png) <br>  


## References drawn from the data
  According to this data, we can make these three recommendations for Ride-Sharing business:
  1) Urban cities make more money than the other city types even with lower average fare and Rural cities make less money even with higher average fare, therefore it would be good to focus mainly on urban services for increasing revenue.
  2) To increase the number of riders in rural and suburban areas, it might be good to find a way to bring down the average fare.
  3) It would be wise to account for distance when considering average ride costs between urban, rural, and suburban city types. Urban riders might have shorter distances than rural or suburban.
