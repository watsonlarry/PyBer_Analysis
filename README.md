# PyBer Ride Share Analysis

## Overview

Working as an employee for the ride-share app company PyBer, we are tasked with analyzing data from the first four months of 2019. Specifically we are to analyze ride-share data based on city type (urban, suburban, and rural). During the course of the analysis, we will create a data frame summary and a multiple line-graph before presenting our conclusions.

### Results

![table](https://github.com/watsonlarry/PyBer_Analysis/blob/main/Resources/Screen%20Shot%202020-11-02%20at%2011.28.46%20AM.png)

Based on city type we can see where the rideshare app is both is more affordable and more frequently used--and there does seem to be a correlation between the two. Moving linearly from rural to suburban to urban city types we see a steady rise in divers and fares and a decline in average fare per ride and driver. What does this mean? In urban, high-density cities there are more riders/drivers and the fares are less costly for riders.  Whether the higher demand in urban areas is because of the inherent lower average fare cost, or the higher demand encourages fares to be driven to lower prices cannot be inferred from this data. What can be observed is that the ride-share app is used more in urban cities and is more lucrative from a total fares perspective. As far as Rural cities are concerned, just invert the observations made about urban cities: there are fewer rides and the rides are more expensive. Suburban cities find themselves between the extremes presented by the other two city types. 

![lineplot](https://github.com/watsonlarry/PyBer_Analysis/blob/main/Resources/Screen%20Shot%202020-11-02%20at%2011.26.00%20AM.png)

Looking at the data plotted on a line-graph presenting fares over time (weeks), we see that the city types share a lot of the same peaks and valleys. All three city types see a peak in the third week of Feb, they all start out with lower fares in Dec-Jan. So while the city types differ in the number of fares, they seem to follow similar rider demand patterns--which could help when it comes to predicting rider demand in the future.

### Summary

Following the analysis, I've formed the following suggestions to address the observations made:
  - Make a push to sign-up more drivers in the rural and suburban city types. The flush of available cars may lower the price of fares and make the service more appealing as a transnportation option--driving up the number of fares.
  - Since the demand is already apparent in Urban cities, maintaining and expanding that demand is key, that means that means appealing to drivers and making sure that they have the tools to collect enough fares to meet their needs, since average fare cost is lower.
  - By plotting expected high and low demand dates based on our collected data we can provide that information to drivers so they can plan to meet demand at opportune times.
