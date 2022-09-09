# bikesharing

## Overview
This project is to analyze the bike sharing business in NYC. We are looking at the data in August 2019 and breaking down into following analysis:
- Overview of the bike sharing audience
- Checkout time by gender
- Rides by weekday for each hour and each gender
- Popular Rides Location
- Repair and Utilization

### Purpose
The purpose of the analysis is to understand the composition of the customer, and their behavior related to the bike sharing business, the popularity in the potential city and potential repair and maintenance cost, so that we can determine whether the bike sharing business in Des Moines is a solid business proposal.

## Results
[link to whole story](https://public.tableau.com/app/profile/lucy.yuan/viz/NYC_Citi_Bikes_16527401066240/NYCCitiBikeAnalysis?publish=yes)

### Overview of the bike sharing audience
[link to dashboard](https://public.tableau.com/views/NYC_Citi_Bikes_16527401066240/Customer?:language=en-US&:display_count=n&:origin=viz_share_link)
<br> As showcased in the visulizations above, there're total 2,344,224 customers experienced the bike sharing business, with 81% of the rides are by subscribers and 65% of the rides were from Male users.

### Checkout Time by Gender
[link to dashboard](https://public.tableau.com/views/NYC_Citi_Bikes_16527401066240/Checkouttime?:language=en-US&:display_count=n&:origin=viz_share_link)
<br>Most of the rides are within 5-6mins and descrease quickly after 6mins. No rides exceed 60mins. Again, Male riders account for the most rides.

### Rides by Weekday for Each Hour and Each Gender
[link to dashboard](https://public.tableau.com/views/NYC_Citi_Bikes_16527401066240/WeekdayTrips?:language=en-US&:display_count=n&:origin=viz_share_link)
<br>More rides happen during the weekday than weekend. Among weekday, the peak time that the rides would happen is during rush hours, such as 7-9am or 5-7pm. During Weekend, more rides tend to happen in the afternoon than in the morning. Obviously Male and subscribers account for most of the rides. 
<br>From the graph below, we can also tell the fact that most of the rides happened during 7-9am and 5-7pm in August 2019.

[link to dashboard](https://public.tableau.com/views/NYC_Citi_Bikes_16527401066240/AugustPeakHours?:language=en-US&:display_count=n&:origin=viz_share_link)

### Popular Rides Location
[link to dashboard](https://public.tableau.com/shared/448QXTBMM?:display_count=n&:origin=viz_share_link)
<br> The top starting and ending locations are all located in Manhattan of NYC, especially Lower Manhattan.

### Repair and Utilization
[link to dashboard](https://public.tableau.com/shared/44T7Y924J?:display_count=n&:origin=viz_share_link)
<br>This is the reference info regarding the Bike ID which have got the most rides and the most trip duration time. We can further determine the threshold by which we should put the bikes into maintenance for longer utilization.

## Summary
<br> Overall, the audience base is wide enough to support the bike sharing business in Des Moines, especially during August and summer time. Male riders outweigh the female riders. Seems like subscribers tend to use the ride sharing more. The most popular time is during rush hours and weekend afternoon. Given the population, city tends to have more frequent bike ride needs.

### Further Analysis
- Total Bikes involved into the rides
<br> Furthermore, if we want to analyze the maintenance cost, we will need to look into the total quantity of the bikes. By dragging the bike ID into text, we can tell that there're total 13,983 bikes used in the rides. By looking into the numbers of rides, we can tell 12,281 bikes are used in less than 300 trips, which account for 88% of the total bikes. If we set a threshold, saying maintenance will take place for those who have served more than 300 trips, then only 12% of the bikes that will incur maintenance fee.

- Birth year related to the trips
<br> We can also anlayze the correlation between the birth year and the trip counts. By adding Birth year into Columns, and trip counts into Rows, we can find that customers who were born in year 1969 tend to use the bikes the most. Beside the peak value, the younger the customers are, the more they tend to use the bike sharing, until the birth year 1990. This fun result can be used to help come up with the promotion campaign.  
