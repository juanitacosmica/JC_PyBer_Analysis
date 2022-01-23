# JC_PyBer_Analysis
Module 5, intro to Matplotlib!

# Overview of the analysis:

The project tasks the data analyst to create a summary DataFrame of the ride-sharing data per city type, using Pandas and Matplotlib, multiple-line graph that shows the total weekly fares for each city type. This report will summarize how the data differs per city type and how those differences can be used by decision-makers at PyBer.

# Resources:
 
 **Data source** All data used in this analysis is in the [Resources](https://github.com/juanitacosmica/JC_PyBer_Analysis/tree/main/Resources) folder and the image files in the [analysis] (https://github.com/juanitacosmica/JC_PyBer_Analysis/tree/main/analysis) folder.

 **Software** Python 3.7, Anaconda 4.11.0, Jupyter Notebook, Matplotlib and Pandas.

# Results:

After performing the analysis of the Pyber ride sharing data to evaluate the rides and fare rates per city type (Urban, Suburban and Rural) the following were the results  so it contributes to understand what services can be improved, an overview of the whole data is as follows:

![Data Summary](/analysis/old_district_summary.png)

From the above, it is seen how the average of ride fare is roughly 10$ more in the rural cities when comparing it to the urban rides, where there is more availibity of drivers. Overall, from a total of 2,375 rides, 5% occurs in Rural cities, 26% in Suburban areas and 68% in the Urban areas. Furthermore, the average fare per driver is close to 38$ more. This can be easier seen in the following pie-chart:

![% of Total Rides per City Type](/analysis/Fig6.png)

Also, and seeing the distribution of % of Total Drivers per City Type, the most activity is definitely occuring in the Urban cities, with lower fares per ride and per driver, which makes it more affordable and convenient.

![% of Total Rides per City Type](/analysis/Fig7.png)

With all this being said, it is remarkable to note how between Jan and Apr from 2019, there are not major changes in the rides activity, in other words, Urban, Suburban and Rural, remained within the same ranges; which in a long term, makes it easier for the company to predict the behavior and stablish strategies to increase the revenue, or tackle any concerns.

![Total Fare by City Type](/analysis/PyBer_fare_summary.png)

# Summary:

In accordance to the data analyzed, the following three options seem to be avaialble to the CEO of PyBer, focusing in the Rural cities where the fare (per ride and per driver) is higher, and yet the amount of rides is way less compared to the total in Urban and Suburban cities:

    1. To perform a survey in the Rural cities, to evaluate if the demand is high enough, to be worth adding drivers.

    2. Using the results form above, it will be also possible to decide if dicreasing the Fare in the Rural cities, which will increase the users as the service, becomes more affordable.

    3. To study the expenses of the service (car maintenance, gas, etc.) as Rural distances tend to be longer rides, and to see room for improvements (what type of cars are being used?, type of gas, amongst many others).