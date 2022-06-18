# A_Countrys_Secret_to_Happiness

# Introduction
Machine Learning Model for trying to answer the age-old question of - what exactly makes us happy?
The World Happiness Report may be a point of interest survey of the state of worldwide bliss. The primary report was distributed in 2012, the second in 2013, the third in 2015, and the fourth within the 2016 Upgrade. The World Joy 2017, which positions 155 nations by their bliss levels, was discharged at the Joined together Countries at an occasion celebrating Universal Day of Joy on Walk 20th.
The report proceeds to pick up worldwide acknowledgment as governments, organizations and respectful society progressively utilize joy pointers to educate their policy-making choices. Driving specialists over areas – financial matters, brain research, overview investigation, national insights, wellbeing, open approach and more – depict how estimations of well-being can be used effectively to evaluate the advance of countries. 
The reports survey the state of bliss within the world nowadays and appear how the modern science of bliss clarifies individual and national varieties in bliss.

# There are six measurements taken per country for guaging the World Happiness Index. They consist of:

1. GDP per Capita - Gross Domestic Product per capita for the countries

2. Family - Satisfaction Rank of Family

3. Life Expectancy - Avg. expected years to live

4. Freedom - Perception of freedom quantified

5. Generosity - Numerical value estimated based on the perception of Generosity experienced by poll takers in their country.

6. Trust/Government Corruption - A quantification of the people's perceived trust in their governments.

7. Dystopia Score - Score based on comparison to hypothetically the saddest country in the world.

8. Dystopia Residual - Rank of any country in a particular year.

# Problem Statement    
1. **Part A** - Analyze and understand which factors affect the Happiness Index Score of countries
2. **Part B** - Analyze and understand the relationship between Terror Attacks and Happiness Index
3. **Part C** - Create a Model to predict the Happiness Index of a Country
4. **Part D** - To see how much Health contributes to the Happiness Index? With the current pandemic at hand, predicting COVID-19 Cases in the coming days for countries.

# Conclusions
The data factors being used for calculating the Happiness Index of the countries is not holistic and inclusive. There are other factors to also be considered. GDP per capita seems to be a skewed figure itself and the limitations that GDP poses is highly likely to bias the happiness score.

We did not find much correlation between no. of terror attacks and happiness index of a country. However, we believe we need to consider more factors & influences pertaining to terrorism for us to properly see the relationship.

For COVID-19 forecasts, we performed univariate analysis on the historical data, which made me realize that historical data alone might not be sufficient for the prediction. But certainly, this is one of the main predictors and it can be used with other set of predictors to create a more powerful model.

# Scope of Improvements:
1. Figure out another way to calculate Happiness Index of a country which includes more holistic and inclusive factors

Based on the observations, we believe that factors apart from 6 selected need to be considered in order to make accurate happiness index scoring. A possible improvement would be to research on an alternative way to calculate the index without using GDP per capita as a score

2. To move into using NLP & Decision Trees for analyzing Terrorism Data

Most of the factors in the Terrorism Dataset were text based. Hence, using NLP here will be best for us to understand the influences of the predictor on the response. To improve model prediction, we believe models pertaining to Decision Trees will help.

3. To move into Multivariate Analysis

We forecasted COVID-19 cases using only past data – however, we are aware that historical data alone is not enough to make accurate forecasts. There are many other external factors – the intention here is to more or less look at the trend and observe how this trend will move in the future.
