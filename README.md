# NYC Citibike Analysis

## Overview

New York City Citibike data from August 2019 was used in order to determine if Citibikes would be a good fit for Des Moines, Iowa. The NYC data was analyzed to show trends for times of day, days of the week, gender, starting locations, and ending locations. For this analysis, Pandas was used change the 'tripduration' column from an integer to a datetime datatype. Using the converted datatype, visualizations were created to show the length of time the bikes are checkout for all riders and genders, show the number of bike trips for all riders and genders for each hour of each day of the week, show the number of bike trips for each type of user and gender for each day of the week, top starting locations, and August peak hours.

### Link to Tableau Dashboard
[NYC Citibike Analysis](https://public.tableau.com/views/NYCCitibikeAnalysisChallenge_16592974869800/NYCCitibikeAugustAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Results

After analyzing the data for the peak hours in the month of August 2019, results showed that peak hours were consistent from 8AM-10AM and 5PM-7PM throughout the month.

![image](https://user-images.githubusercontent.com/103764279/182046472-73d2abe4-c6b6-4373-a2f5-df99e971feab.png)

When analyzing the checkout times for users, the tripduration for NYC Citibike users peaked at 5 minutes. Most NYC Citibike trips were under 1 hour in length.

![image](https://user-images.githubusercontent.com/103764279/182046634-09f8c193-64ea-4ff8-b9dc-60511f5be14b.png)

When analyzing the checkout times by gender, the graph shows that more males are using NYC Citibikes than females. However, this graph also shows that both male and female peak ride duration is around 5 minutes.

![image](https://user-images.githubusercontent.com/103764279/182046738-e1b245f8-6424-4276-8313-46315b044cae.png)

The top stating locations for NYC Citibike users in August 2019 were Pershing Square, Union Square, and Tribecca Bridge. These locations are popular tourist spots. From this graph, it can be inferred that there are more Citibike users where there are popular tourist attractions and less Citibike users in the more residential and suburb areas of NYC.

![image](https://user-images.githubusercontent.com/103764279/182046873-134ed639-cd7a-4432-a52d-4e1ea9fdc4c1.png)

The data for trips by weekday per hour shows that Thursday between the hours of 5PM and 7PM are the busiest hours where Citibike usage is high.

![image](https://user-images.githubusercontent.com/103764279/182046990-e1129e48-fd8a-4cd5-bffe-319deb0eb496.png)

The data for trips by gender (weekday per hour) shows that males take more Citibike trips compared to females.

![image](https://user-images.githubusercontent.com/103764279/182047059-3bbd88d6-a9ad-4de0-bbea-450cee2c1540.png)

When looking at the data for user trips by gender, this graph shows that there are more male subscribers than female subscribers. This graph also confirms that Thursday is the busiest day with the highest Citibike usage by males.

![image](https://user-images.githubusercontent.com/103764279/182047108-f2ea68e0-011c-4f48-a687-23db8cbf7028.png)

## Summary

Overall, bikeshare services are popular in busy metropolitan areas. Male subscribers were the primary users of Citibikes in New York City during August 2019 where the most usage occurred on Thursdays.

In order to determine if Citibikes is a good fit for Des Moines, Iowa, other visualizions that could be used are:
- **Population Growth.** If population growth for Des Moines is comparable to New York City's, the Citibikes has potential to be a great fit for Des Moines.
- **Traffic Patterns.** Trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours.
- **Weather Data.** If weather data is comparable to New York City or even better, Citibikes in Des Moines, Iowa should be a good fit.
