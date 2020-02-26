# Cost-of-Living-Index-Analysis-over-2010-2019

https://www.numbeo.com/cost-of-living/rankings.jsp?title=2019

I would like to take this data set using some manual wrangling of years 2010-2020. I would remove cities without a full data set. I would group cities by countries. I would want to see how much other cities and groups changed over the last ten years in respect to NYC for each of the offered indices. This would be interesting because there is a lot of talk about how much rent has increased and I am interested in how much cities across the US and in other regions have changed in comparison.  

Some challenges 
There will be some missing data (maybe not every index is done for every city)
Not every city will be included in each year 
The city column is a little messy for looking at other groupings 
US cities have the state but international cities do not 
There will have to be another column added for country level aggregations 
There is no immediate way to group by different types of regions such as Africa/North America/Asia etc. 


Some questions to look into 

Countries with the highest/lowest mean of each index 
Countries with the highest/lowest change of each index over the years 
Countries with the highest disparity of cost index 
Rankers over the years 
(optional) Same as above but for US states 
Use the api from here to allow for additional geo-coded regions (Continent, North/South)
