# PyBer_Analysis

## Project Overview:

The goal of this project was to use Python skills and knowledge of Pandas, to create a summary DataFrame of the ride-sharing data by city type for a ride sharing company called PyBer. Then, using Pandas and Matplotlib, I was tasked with creating a multiple-line graph that shows the total weekly fares for each city type.

## Resources:

**Data Source & Folders:** [Resources](https://github.com/matthubb17/PyBer_Analysis/tree/main/Resources) & [Analysis](https://github.com/matthubb17/PyBer_Analysis/tree/main/analysis) Folders

**Challenge File:** [Challenge](https://github.com/matthubb17/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

**Software:** Python 3.9.7, Jupyter Notebook

## Results:

Looking at the below summary dataframe we can reasonably see that there is a direct relationship as it pertains to "total rides", "total drivers", and "total fares". In contrast, there is an inverse relationship when looking at "average fare per ride" and the "average fare per driver".

This is not a suprise as it is reasonable to conclude that there is a smaller popluation in rural areas and thus less of a demand for a ride sharing app within those areas. As a result of the lack of demand for ride sharing, there is in turn a smaller amount of drivers within the rural (less populated) areas. In contrast, when looking at the urban areas, there is a very large amount of drivers available along with more total rides being taken.

![Summary DataFrame](https://github.com/matthubb17/PyBer_Analysis/blob/main/Resources/Summary_DataFrame.png)

The below line chart further documents the relationship we see between high demand and more populated areas (Urban) vs. the low demand more spread out and less populated areas (Rural).

![Fare Summary Line Chart](https://github.com/matthubb17/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary:

Based on the results shown in both the images and the text above, I have the below recommendations:

1. Work to try to encourage PyBar app users to schedule more rides in Rural areas. This will help to increase the demand for drivers for PyBer. In addition, this would also help to increase the quantity of rural rides which tend to cost more money as they are typically longer distance rides.
2. Due to the smaller quantity of Rural drivers, create an driver program that incentivises the drivers to take more rides in rural areas. This will help to shift the excess drivers that we see in the urban areas and allow more rides to take place in the rural areas.
3. Lastly, I would recommend PyBer to increase their marketing efforts in both the rural and suburban areas. From the data above it can be deduced that there is a surplus of drivers in the urban areas. By increasing the marketing efforts, PyBer can hope to have more users requesting rides in both the suburban and rural areas in which there is currently less demand.
