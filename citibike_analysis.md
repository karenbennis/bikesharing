# Citi Bike: Recommendations for Implementation in Des Moines based on NYC data
The following Tableau story "NYC vs DM Recommendations" seeks to identify similarities between NYC and Des Moines for the purpose of making a recommendation to implement the bikesharing service *Citi Bike* in Des Moines.

The story can be viewed using the following link:

["NYC vs DM Recommendations" Tableau Story]("https://public.tableau.com/profile/karen.bennis#!/vizhome/BikesharingNYCandDesMoines/NYCvsDMRecommendations")

The analysis provided here is meant to give more context to the Tableau story. The working hypothesis is that Citi Bike could operate a similar business model in Des Moines to that of NYC (albeit at a smaller scale) if demographics and climate are established to be similar.

## NYC Citi Bike Customer Profile
To begin, it is important to understand who the Citi Bike customer is. The first consideration was to investigate the type of customer (either Subscriber or Customer), gender, and age.

Use this page to explore the data. The data on this dashboard can be filtered by selecting any values (or any combination of values) in the visualizations.

An exploration of this data shows that the majority of NYC Citi Bike customers are subscribers who are male and between 24 - 50 years of age.

On this introductory page, the direction of the analysis is established, informing the audience that recommendations for Citi Bike in Des Moines will be based on investigation as it pertains to demography (age and gender), climate/weather, and cultural fit.

## NYC Citi Bike Usage
The second story point aims to further drill into the NYC Citi Bike operation by examining customer usage behaviours based on the 13,983 Citi Bike bikes which exist.

Use this page to explore the data. The data on this dashboard can be filtered by selecting any value (or any combination of values) in the visualizations.

Overall, average trip duration decreases slightly as age increases; however, it is important to note that the Citi Bike trip fare includes a 30-minute ride, and additional fees are charged for exceeding that time limit (https://www.citibikenyc.com/). If a similar pricing model were to implemented in Des Moines, it might be inferred that similar trends would be observed.

Generally, regardless of the customer type or gender, the peak hours are generally from 7 am to 7 pm.

The implication of this data is that it could be expected that similar observations would be observed in Des Moines if the similarities across demographics and climate are confirmed.

## Demographics Comparison
The third story point aims to do a deeper dive into the demographics of NYC and Des Moines. Using a data layer showing age median by census tract in each city's respective map, it is shown that the distribution of age across the respective cities is similar.

Under each map, demographic data is shown. Importantly, gender distribution is very similar between the two cities, with the percetage of males slightly higher in Des Moines by comparison with NYC. Ultimately, the difference is small; however, this difference, as small as it is, would likely result in more customers proportionally in Des Moines, since males make up most of the business.

The population of NYC is 38.9 times that of Des Moines, and the population density in NYC is 10 times that of Des Moines.

Implications of these observations are that any implementation of Citi Bike in Des Moines would have to be nearly 40 times smaller than that of NYC, provided that the weather in Des Moines is similar enough to that of NYC, since biking is an outdoor activity.

## Temperature Comparison
The fourth story point focuses on temperature. Data from https://www.ncdc.noaa.gov/ was used to show average high and low temperatures by month for each city. The axes were both set to display similarly, so an easy comparison could be made.

From this data, it is clear that NYC is a bit milder in the winter by comparison with Des Moines. Throughout the rest of the year, temperatures seem to be quite comparable. While Des Moines is cooler, it follows that on very cold days, less revenue would be generated (on the basis that many people would not want to ride a bike in extreme conditions); however, these average lows do not seem so low that it could be concluded that nobody would use a bike for approximately 30 minutes or less.

## Daylight and Precipitation Comparison
The fifth story point focuses on daylight hours and precipitation (rain and snow). Data from https://www.ncdc.noaa.gov/ was used to show daylight and precipitation by month. Daylight is compared between the two cities in the first plot; and in the second plot precipitation is compared.

From this data, it is clear that the data are very similar across all measures between the 2 cities. NYC appears to get a bit more rain, which would seem to be a bigger deterant for bikeriding by comparison with temperature.

Crucially, daylight hours are nearly identical. This supports the expectation that peak hours would be expected to be similar, since most bikeriding occurs during daylight hours.

## Overall Recommendation
The final story point aims to assess whether or not it actually makes sense to implement Citi Bike in Des Moines.

Throughout the analysis, it has been established that the demographics and weather are similar enough to generate the same interest in Des Moines for a similar customer profile.

The key question to consider is how many bikes to implement. Looking only at ratio of persons per bike in NYC, Citi Bike would implement 359 bikes.

Looking into Des Moines offerings, it is clear there is a lot of outdoor activity, particularly bike trails to explore, even in downtown Des Moines. Based on the Des Moines tourism website (https://www.catchdesmoines.com/) there are outdoor activities throughout the year. 

Interestingly, outdoor trails are not promoted on the tourism site for winter activities.

Since the tourism site showed so many images of people biking, it seemed logical to check if a bikesharing service already exists there, and indeed, it does. According to the Des Moines BCycle website (https://desmoines.bcycle.com/), there are 120 bikes across 20 different stations.

Based on the existance of a competitor service which operates under the same terms (i.e. 30 minutes per fare), it follows that it might be too agressive for Citi Bike to launch in Des Moines with 359 bikes. It might be recommended then to apply a more conservative approach by launching with fewer bikes, perhaps 240 to accommodate for the existing Des Moines BCycle bikes.

## Recommendations for further analysis
While the analysis presented here is compelling enough to infer that bikesharing has a place in Des Moines, it is important to gain insights about the competition that exists.

When this analysis began, it was based on the premise that Des Moines did not already have bikesharing. Since the service indeed exists, it is imparative that market analysis be completed robustly to avoid saturating the market.

Des Moines has a very small population, so the placement of bike stations and the number of bikes is key to a successful implementation.

At this time, there is enough good reason to continue with the analysis with the working hypothesis that a Citi Bike implementation in Des Moines will be successful if the market is not saturated.