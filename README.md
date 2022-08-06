# Project 1: Standardized Test Analysis

Project 1 done by - **Anand Ramchandani**

## Executive Summary  

## Problem Statement  
The College Board (SAT), in partnership with ACT Inc. wishes to explore if median household income, college enrollment rates, state population and test participation rates have any relationship with each state's ACT and SAT performance. We are a team of analysts hired to analyse the provided data, use supporting data from other sources  and present our findings to the college boards.

## Sub Problem that will be the focus of this work  
 To collect and analyse data from external sources for median household income and population for each state and to determine if any relationship can be found with each state's ACT and SAT performance and their participation rates

## Data Dictionary

|FEATURE|TYPE|DATASET|DESCRIPTION|
|---|---|---|---|
|state|object|mean_sat_act_inc_pop|US states excluding District of Columbia, Virgin Islands and Puerto Rico| 
|income_mean|float64|mean_sat_act_inc_pop| Mean Household Income by State over 2017 to 2019| 
|pop_mean|float64|mean_sat_act_inc_pop| Mean Population by State over 2017 to 2019| 
|participation_act_mean|float64|mean_sat_act_inc_pop| Mean ACT Participation Rates by State over 2017 to 2019| 
|composite_act_mean|float64|mean_sat_act_inc_pop| Mean Composite ACT Scores by State over 2017 to 2019|
|english_act_mean|float64|mean_sat_act_inc_pop| Mean English ACT Scores by State over 2017 to 2019| 
|math_act_mean|float64|mean_sat_act_inc_pop| Mean Math ACT Scores by State over 2017 to 2019| 
|reading_act_mean|float64|mean_sat_act_inc_pop| Mean Reading ACT Scores by State over 2017 to 2019| 
|science_act_mean|float64|mean_sat_act_inc_pop| Mean Science ACT Scores by State over 2017 to 2019| 
|participation_sat_mean|float64|mean_sat_act_inc_pop| Mean SAT Participation Rates by State over 2017 to 2019| 
|ebrw_sat_mean|float64|mean_sat_act_inc_pop| Mean EBRW SAT Scores by State over 2017 to 2019| 
|math_sat_mean|float64|mean_sat_act_inc_pop| Mean Math SAT Scores by State over 2017 to 2019|
|total_sat_mean |float64|mean_sat_act_inc_pop| Mean Total SAT Scores by State over 2017 to 2019|

## How the analysis was done
We were given datasets for ACT and SAT from 2017 to 2019. These datasets were analysed, cleaned and compiled in order to see what data was pertinent to solving the problem statement and to determine what other external datasets would be required.
We collected external datasets from US government census websites for Median Household Income and Population. These datasets were cleaned and merged with the datasets we have already in order to prepare for Exploratory Data Analysis and Data Visualisation.

Since we were given raw data for years 2017 to 2019, we merged the datasets and found the mean of the 3 years in order to find any broad trendlines that occured over that time period. Using such data visualisation tools as scatterplots, bargraphs, boxplots, correlation heatmaps we analysed the data to find any correlations between Median Household Income, Population with participation rates in the SAT and ACT as well how each states perform in these standardised tests

## Shortcomings

- We only worked with 3 years worth of data, which is quite a short amount of time so the data could also be impacted by a large number of other variables, for example how the economy is doing, unemployment figures, other major events like a pandemic or a poltical upheaval
- We are only given particpation percentage rates, which is useful in comparing data for bigger and smaller states, it would still be more informative to be given the absolute number of students that are taking the ACT and SAT


## Conclusions

**How does population affect participation rates in the SAT/ACT tests?**  

- As the population increases, we see a slight correlation that SAT participation rates increase and ACT participation decreases
- More states participate in taking the ACT rather than the SAT
- More states have 100% participation in ACT than SAT. It can be presumed a perfect partcipation rate may imply participation in these states are mandatory

**How does population affect SAT/ACT test peformance?**  

- As the population increases, we see a slight correlation that SAT scores decrease and ACT scores increase
- The trends we see are all comparable amongst Total/Composite, Math and English/EBRW scores

**How does median household income affect participation rates in the SAT/ACT tests?**  

- As household income increases, we see a correlation that SAT participation rates increase and ACT participation strongly decreases
- As household income increases, we see a correlation that SAT scores slightly decrease but ACT scores strongly increase

**How does median household income affect SAT/ACT test peformance?**  

- As the income increases, we see a slight correlation that SAT scores decrease and but quite a strong correlation that ACT scores increase
- The trends we see are all comparable amongst Total/Composite, Math and English/EBRW scores

## Recommendations

- Take a longer timeframe than 3 years, I would recommend at least a decade to decide on any meaningful correlation or trends. This is done to avoid any short-term major events that could skew the data
- If the SAT and ACT tests were free of charge, this would most likely increase participation in these tests and we could find a more clearer picture on how population and median household income actually affects the performance of students taking SAT and/or ACT
- This would also enable more students to apply for college and expand the reach of the SAT and ACT Board to enrich the lives of Americans

