# PyBer_Analysis
## Overview of the analysis: Explain the purpose of the new analysis.
We have analyzed the Pyber ride share data from January 2019 through May 2019. We were tasked with creating visualizations of the data for Pyber to help improve access to rides services and determine affordability for underserved neighborhoods. 

Our initital analysis found that ride shares were less frequent and more expensive in rural cities compared to suburban cities. Urband cities had the highest freuency and the lowest rates. See the resources folder containing figs 1-3 to see these visualizations. In fig 4 we can see that there are far more drivers in urban areas than in suburban or rural areas. Figures 6 adn 7 are pie charts showing the % of total rides by city type and % of total drivers by city type. It is clear when there are more drivers there are more rides and the average fare is lower. 


## Results:
We have used Python and Pandas to create a summary DataFrame of the ride sharing data by city type. Then, using Pandas and Matplotlib created a multiple-line graph that shows the total weekly fares for each city type. This creates a snapshot that lets us see that Urban city types avaerage approximately $2000 in weekly fares, while rural cities average below $500. It would seem that accessibility or affordability are not achieved in Rural cities.

We have assembled the data provided in a data frame that compares Urban, Suburban, and Rural city types and shows their total rides, total drives, total fare, average fare per ride, and average fare per driver. As you can see comparing rural to suburban and urban city types, total ride, total drives, and total fares are markedly lower in rural cities. Rural cities have fewer than suburban and suburban have markedly fewer than urban. The opposite is true when we consider the averages. Average fare per ride and per driver are significantly higher in rural than in suburban and then there is another jump down to urban average fares per ride and per driver. 

![summary df](https://github.com/DartElina/PyBer_Analysis/blob/7f447a11340da7851c73bc6c447135a77bcc723b/Resources/df%20avg%20by%20type%20and%20by%20driver%20.png)

Next we summed the weekly fares over the course of these 5 months and created a pivot table of that data. Shown below. 

![weekly fare sum](https://github.com/DartElina/PyBer_Analysis/blob/7f447a11340da7851c73bc6c447135a77bcc723b/Resources/weekly%20pivot%20sum.png)

Which allowed us to plot this data and create a visualization that shows how these city tyes are performing in comparison to eachother. 

![multi line graph](https://github.com/DartElina/PyBer_Analysis/blob/7f447a11340da7851c73bc6c447135a77bcc723b/Resources/PyBer_fare_summary.png)

It is possible that rural cities are experiencing inaccessability and unaffordability due to the lack of drivers. However, low driver count could be the result of lower populations and reduced demand in these cities. Further analysis must be done to measure the affect of the number of drivers per capita and it's affect on the number of rides in a city. 


## Summary: It seems that accessibility and affordability are not being achieved in rural cities. 
1. The analysis so far indicates that when there are fewer drivers in a city then fares are more expensive, and less frequent. This is reducing accessibility and affordability in rural cities. 
2. Addititonally, this hurts our sales, because although fares are higher overall revenue is significantly lowered by these high prices since the volume is so low. 
3. Before adding more drivers, however, more analysis must be done to prove that the cause of fewer rides is in fact the lack of drivers, rather than less demand, or some other not measured variable. 
