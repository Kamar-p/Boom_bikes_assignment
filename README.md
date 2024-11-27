# Boom Bikes Sharing Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to ongoin Covid-19 pandaemic. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes?
- How well those variables describe the bike demands?
- We are required to model the demand for shared bikes with the available independent variables. It will be used by the business to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.



## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
- We have used day.csv as dataframe

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The top 3 features contributing significantly towards explaining the demand of shared bikes are-

	Top 3 Significant Features Contributing to Shared Bike Demand:

1.Temperature (temp) with a coefficient of 04201:
Interpretation: The positive coefficient for temperature indicates a strong, positive relationship with bike demand. As the temperature increases, the demand for shared bikes increases. This suggests that warmer weather encourages more people to rent bikes, likely because people are more willing to bike when the weather is favorable.

Suggestion: The business should consider increasing marketing and promotions during warmer months when demand is likely to peak.

2.Weather Situation:Light Snow/Rain(weathersit_Light) with a coefficient of -0.2742:
Interpretation: The negative coefficient for light snow, rain, or misty weather (represented by weathersit = 3) shows that adverse weather conditions reduce bike demand. People are less likely to rent bikes during rainy, snowy, or misty weather due to discomfort or potential safety concerns.

Suggestion: During periods of light snow, rain, or mist, the business could offer targeted promotions or introduce flexible rental policies, such as longer rental times for the same price, to encourage users to rent bikes despite the weather.

3.Year (yr) with a coefficient of 0.2373:
Interpretation: The positive coefficient for the year variable indicates that bike demand has increased significantly in 2019 compared to 2018.

Suggestion: The business should continue to capitalize on this upward trend by increasing brand awareness campaigns


## Acknowledgements
- This project was based on Linear Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.


## Contact
- <a href="https://github.com/Kamar-p/">Kamarudheen P</a>


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
