# R.E.A.L Real Estate LLC
## What Zipcodes in the United States Offer the Most Attractive Returns?

### Organizational Overview
R.E.A.L real estate company is looking to purchase properties in the United States to return profit. The company wants to know which five zipcodes offer the most attractive returns on their investment within periods of two, three, and four years. This research aims to use several time series models to determine these zipcodes.

### Data
The dataset used for this research is from Zillow Research. The features it includes are:

RegionID, RegionName, City, State, Metro, CountyName, SizeRank as well as dates corresponding to the values of each feature in wide format. 
There are 14723 entries from 0 to 14722. The dates are from April, 1996 to April, 2018. It catalogues the median price of United States zipcodes monthly from the 1996 to 2018. 

### Models 
- Random Walk
- Autoregression (AR)
- Moving Average (MA)
- Autogression Integrated Moving Average (ARIMA)
- Seasonal Autogression Integrated Moving Average (SARIMA)

The research will look at the median prices of each zipcode and forecast prices for 2019, 2020, and 2021. This will be done through multiple iterations of time series modeling. 

### Results 
The best zipcodes by measure of return on invesment in percentages are:

- 30032
    - 2019-12-01 198.00152208172042
    - 2020-05-01 202.68729983655916
    - 2021-05-01 199.01100346021502

- 94601
    - 2019-05-01 197.66874486525552
    - 2020-05-01 195.76325657356733
    - 2021-05-01 198.0860745673722

- 94804
    - 2019-05-01 158.63288678752645
    - 2020-05-01 162.77930431501056
    - 2021-05-01 158.3325668874207

- 85305
    - 2019-05-01 159.4691462080645
    - 2020-05-01 158.19675713064515
    - 2021-05-01 156.9243680532258

- 85008
    - 2019-05-01 136.63685165484878
    - 2020-01-01 137.2413246089677
    - 2021-05-01 135.64692322210635

### For Future Analyses 
It would be worthwhile to look at a larger dataset thaty catalogues median price from a farther point back in time. This could show seasonality and cyclical trends that cannot be seen by looking at a 22 year window. Also, by not including datapoints from 1996 to 20013, the model has less data to try to forecast further into the future accurately. By having data from the last 50 years for example, other instances of housing crashes may be observed, which could help mitigate the effects of the 2007/08 housing bubble burst on this dataset. On the other hand, we can adjust the granularity of the dataset to only observe between 3 month periods coinciding with the seasons to see if there are differences in price based on geography and climate. We may be able to hypothesize that prices are lower in the Northeast during the winter months due to the encroaching cold. Lastly, it would be interesting to see the relationship between stockmarket performance and the housing market. These two time series have been observed to follow each other.

Things for R.E.A.L real estate to consider:

Timeframe: What is the ideal amount of time for the company to hold property?
Budget: Is there a maximum amount the company is willing to pay for property?
Risk Aversion: Can the company tolerate higher highs and lower troughs in favor of higher possible returns?


